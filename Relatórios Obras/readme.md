
Esse relatório em Excel mostra um detalhado de serviços de Obra. O relatório em Excel em si a primeira vista aparenta estar bastante desestruturado , mas o exercício era extrair do montante de informação, 6 colunas: Data, Nível, Subnível, Credor, Nº Documento e o Valor do Documento. Deixei destacado para melhor entendimento:

![image](https://user-images.githubusercontent.com/65839541/187007211-ddd9d24b-43f4-4d0c-9b93-8db960b9ed3b.png)

A ideia então foi para o Nível, onde na coluna A contivesse a string "Nível", trazer o valor da linha ao lado, o da Coluna B. Para o Subnível, ao verificar na Coluna A que se atendia uma máscara que identifica o código do Subnível, trazer o valor da linha ao lado, o da Coluna B. Por fim, após esse tratamento, trago os registros onde somente possuem a data preenchida, limpando todo o "lixo" do dataset.

O resultado final ficou assim:

![image](https://user-images.githubusercontent.com/65839541/187007338-96136468-eb2d-473b-808d-b5717393e961.png)


