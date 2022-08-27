
Nesse Exercício, a ideia era com uma base em Excel das partidas de futebol do Brasil, extrair quem era o time mandante, o time visitante, o placar de gols do time mandante e do time visitante, além do resultado do time, se ele venceu, perdeu ou houve empate.

A base originalmente veio assim:

![image](https://user-images.githubusercontent.com/65839541/187005296-4d3bb380-8573-42ac-8da7-e2fb7b51560d.png)

Para isso primeiramente criei 2 colunas, uma contendo o nome do time mandante e outra do time visitante. Depois utilizei o Crosstable para que eu pudesse gerar 2 registros para cada partida, 1 registro seria para o time visitante, e outro para o mandante. Após essa etapa, criei 2 colunas extras, uma para os gols do time mandante e outra do time visitante. Depois verifico qual o lado do time, e trago a coluna correspondente que indica os gols que o time fez, e também o resultado da partida.

O resultado estruturado ficou assim:

![image](https://user-images.githubusercontent.com/65839541/187005549-e75eea96-79e4-4736-afc3-80ac549ac39a.png)


