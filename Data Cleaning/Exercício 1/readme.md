![image](https://user-images.githubusercontent.com/65839541/131933870-c4e99a2a-9819-43fa-93b3-504105ca4df4.png)

  O Exercício consistia em fazer o tratamento de uma base muito desestruturada, pois as informações que deveriam estar em colunas, como o Segment e o Ship Mode estão no cabeçalho, e o Segment ainda possui vazios, dificultando sua identificação.
  A solução que pensei foi gerar uma tabela temporária somente com o cabeçalho e a primeira linha da tabela, para gerar as combinações possíveis de Segment e Ship Mode.
