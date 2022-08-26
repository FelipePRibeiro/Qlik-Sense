![image](https://user-images.githubusercontent.com/65839541/131934096-061a13d8-cd68-48cb-b54d-8fd7764e86cc.png)

A ideia é utilizar a função SubField para quebrar cada ocorrência do Pipe na coluna Category, para transformar em linhas. Porém isso faz com que os valores da coluna Amount também se repitam por cada linha da coluna Category. Então com a função Peek, eu crio um ID sequencial para cada Order ID, o que me permite saber quantas ocorrências tem dentro de cada Order ID, para passar como parâmetro novamente para a função Subfield para quebrar a coluna Amount e distribuir corretamente os valores.

![image](https://user-images.githubusercontent.com/65839541/186795438-94260cd7-d37b-4da5-b257-131d53bc67a3.png)

O resultado final ficou assim:

![image](https://user-images.githubusercontent.com/65839541/186795738-44d71c05-1922-4e62-914e-4593222d7175.png)

