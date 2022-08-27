
Nesse dataset temos uma base em Excel para demonstrar a vendas de uma empresa fictícia, demonstrando os valores Realizados x Orçados. Porém a base está bem desestruturada, com os Anos em colunas separadas, colunas de Diferença entre o Realizado e o Planejado, células vazias e linha de Total.

![image](https://user-images.githubusercontent.com/65839541/187006452-c1400573-d0e7-418c-9813-7d0f5a437cce.png)

Aqui não promovi os cabeçalhos, pois não tenho nenhuma linha que consiga promover. Então trabalhei referenciando as posições das colunas, e através das posições das colunas, eu descubro qual o Ano e também qual o KPI, se é Realizado ou Planejado. Com isso consigo preencher o Ano utilizando Applymap e trazer o KPI para posteriormente transformar de linha para coluna.

O resultado final ficou assim:

![image](https://user-images.githubusercontent.com/65839541/187006881-34753284-5971-47ad-9227-e40af22217cb.png)
