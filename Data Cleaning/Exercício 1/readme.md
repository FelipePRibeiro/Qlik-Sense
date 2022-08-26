![image](https://user-images.githubusercontent.com/65839541/131933870-c4e99a2a-9819-43fa-93b3-504105ca4df4.png)

  O Exercício consistia em fazer o tratamento de uma base muito desestruturada, pois as informações que deveriam estar em colunas, como o Segment e o Ship Mode estão no cabeçalho, e o Segment ainda possui vazios, dificultando sua identificação.
  A solução que encontrei foi fazer um Crosstable para pegar o Segment e o Ship Mode, e utilizando a posição da coluna, usar ela como referência para identificar posteriormente qual era o Ship Mode e o Segment para tal coluna.
