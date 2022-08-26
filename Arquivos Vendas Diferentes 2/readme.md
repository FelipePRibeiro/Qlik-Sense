
Nesse caso temos um arquivo de vendas desestruturado em Excel, onde a data da Venda está em uma linha solta acima das linhas onde seriam os cabeçalhos, as regiões nas colunas, o ID do vendedor no mesmo campo do nome e linhas de Totais:

![image](https://user-images.githubusercontent.com/65839541/186802010-8f9407b3-cd50-4da2-a99d-f30b028bf721.png)

Nesse caso, eu promovi os cabeçalhos, criei uma coluna extra para puxar as Datas, e no caso da primeira linha que foi excluída por causa da promoção do cabeçalho e que continha a data do primeiro vendendor, puxei novamente com a função Applymap.

Após o tratamento, consegui estruturar deixando assim:

![image](https://user-images.githubusercontent.com/65839541/186802090-a40f76bf-bffd-4352-8604-836b39d6540d.png)
