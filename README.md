# Construindo sexy APIs usando arquitetura serverless

Construindo uma API para Gestão de Produtos utilizando Node.js, aplicando conceitos de Arquitetura Serverless com Node.js. [^1]



Ferramentas:

- Azure Function Core Tools



Dependências:

- mongodb




### Rota de entrada para o serviço na nuvem Azure da Microsof:
![rota-de-entrada-azure-cloud](./public/images/rota-de-entrada-azure-cloud.png)



### Resultado da requisição na rota GET 'products', com o retorno feito pelo serviço da Azure e do banco de dados MongoDB:
![imagem-da-rota-products](./public/images/imagem-da-rota-products.png)



### Resultado da requisição na rota GET 'products/{id}', sendo retornada pelo serviço da Azure e do banco de dados MongoDB:
![imagem-da-rota-products-id](./public/images/imagem-da-rota-products-id.png)



### Resultado da requisição na rota POST 'products' sendo retornada pelo serviço da Azure e da inserção do novo documento no banco de dados MongoDB:
![imagem-da-rota-post-products](./public/images/imagem-da-rota-post-products.png)


### Resultado da requisição na rota PUT 'products' sendo retornada pelo serviço da Azure, junto com a atualização do documento no banco de dados MongoDB:
![imagem-da-rota-put-products](./public/images/imagem-da-rota-put-products.png)



### Resultado Final do projeto :





[^1] Orientação do professor Igor Halfeld da Digital Innovation One.

