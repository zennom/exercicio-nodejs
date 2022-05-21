# Exercício cadastrar Novos Usuários no Banco de Dados - NodeJS

### Instale as depêndencias:
`npm init`
`npm install express mustache-express dotenv`

## Instale os types
`npm install --save-dev @types/express @types/mustache-express @types/node`


## Crie um arquivo dotenv com as informações do seu banco:
PORT=3000
MYSQL_DB=teste
MYSQL_USER=root
MYSQL_PASSWORD=
MYSQL_PORT=3306


## Instale o nodemon, mysql e sequelize

`npm install -g nodemon typescript ts-node`
`npm install mysql2`
`npm install sequelize`

Em package.json crie o seu script para rodar o projeto

"start-dev": "nodemon -e ts,json,mustache server.ts"

inicie o projeto com o comando que você criou no script (start-dev)

