
O desafio era consolidar as Vendas dentro de um Arquivo em Excel que estava separado por Abas, além de estar bem desestruturado, com células mescladas, meses em colunas, nome do Ano somente no nome da Aba, KPI nas linhas ao invés de colunas, conforme print abaixo:

![image](https://user-images.githubusercontent.com/65839541/186801571-cf83c342-f019-4c28-8194-b7088b1d3f26.png)

Como nativamente o Qlik não tem alguma forma dinâmica para tratar abas, existe um Script que conecta o Excel em um Driver ODBC, fazendo com que as Abas do Excel fossem tabelas em um banco, sendo possível listar então os nomes das Abas e fazer um tratamento para verificar o nome da Aba e com um loop iterar por todas as Abas.

O resultado final ficou assim:

![image](https://user-images.githubusercontent.com/65839541/186801721-9a6b6626-f11b-42c1-b216-effdfb6f78dc.png)


