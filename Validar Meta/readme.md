Nesse Exercício uma base em Excel possui uma coluna dizendo qual a Meta em % a ser realizada, e outra Coluna mostrando o % realizado. A ideia é gerar uma coluna final, dizendo ser a meta foi batida ou não, retornando TRUE ou FALSE.
A dificuldade é que a coluna meta é uma coluna textual, contendo os caracteres de maior, menor ou igual.

A base é assim:

![image](https://user-images.githubusercontent.com/65839541/187008222-7dc64302-edca-44af-8df8-dc45b68cd19f.png)

A ideia foi então criar uma nova coluna que extraísse os sinais de maior, menor e igual para depois criar uma coluna testando os valores. Precisei fazer uma formatação forçada pois o Qlik estava misturando texto e número na coluna contendo a Meta.
Após criar a nova coluna extraindo os sinais da operação, utilizei a função Pick e Match para gerar o teste baseado no valor que foi extraído dos sinais:

![image](https://user-images.githubusercontent.com/65839541/187008384-e2cabf93-9d4f-4ad9-83f0-b8cedd79f85d.png)

O resultado final ficou assim:

![image](https://user-images.githubusercontent.com/65839541/187008443-c984a243-9fb1-4c8f-b91a-5cc28691f993.png)



