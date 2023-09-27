# Fase1
Aplicação em Java com integração com Banco de Dados (Creche para animais domésticos) - BAN2

Aplicação composta por 5 tabelas (Clientes, Animais, Planos, Funcionários e Reservas);
Todas as tabelas possuem o CRUD e além disso, há também uma classe para geração de relatórios.

Em relação aos relatórios é possível gerar:
1) Reservas por Funcionário (todas as reservas feitas por um determinado funcionário)
2) Reservas por Animal Selecionado (todas o histórico de reservas de um determinado Animal)
3) Animais por Plano (todos os Animais cadastrados em um determinado Plano)

Para executar a aplicação:

1) Copiar o pacote com os fontes para um diretório local
2) Abrir na IDE desejada (para o desenvolvimento do trabalho foi utilizado o NetBeans)
3) Abrir o pgAdmin e aplicar o banco Creche
4) Dentro do fonte, alterar o usuário e senha de conexão do banco
5) Dentro da classe GerarRelatorios, alterar os diretórios onde os arquivos serão gerados, caso desejar (está padronizado para C:\temp)
6) Executar a aplicação e selecionar a opção que desejar, conforme menu.
