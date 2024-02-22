# projeto-api-dados-historicos-IPCA

Este projeto foi realizado como parte do curso da DevMedia e tem como objetivo fornecer um serviço para consultar o histórico de inflação do IPCA (Índice Nacional de Preços ao Consumidor Amplo) e calcular reajustes com base nesses dados.

## Instalação
Para executar este projeto, é necessário ter o Node.js instalado. Em seguida, siga os passos abaixo:
1- Clone este repositório
2- Instale as dependencias do projeto: npm install express
3- Para iniciar o servidor e executar o projeto: node index.js
4- O servidor será iniciado na porta 8080. Você pode acessar as rotas do projeto usando um navegador ou uma ferramenta de API como o Postman.

## Rotas

### GET /historicoIPCA
Retorna todo o histórico de inflação.

### GET /historicoIPCA/:id
Retorna um item específico do histórico de inflação com base no ID fornecido.

### GET /historicoIPCA/calculo?valor=valor&mesInicial=mesInicial&anoInicial=anoInicial&mesFinal=mesFinal&anoFinal=anoFinal
Calcula o reajuste com base nos parâmetros fornecidos. Os parâmetros devem ser números válidos. Se algum parâmetro for inválido, a API retornará um erro 400.

## Contribuindo
Sinta-se à vontade para contribuir com melhorias para este projeto! Basta enviar um pull request com suas alterações.





