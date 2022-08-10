# Exercício cadastrar Novos Usuários no Banco de Dados - NodeJS

### Instale as depêndencias:
1. `npm install`
2. `npm install express mustache-express dotenv`


### Instale os types
3. `npm install --save-dev @types/express @types/mustache-express @types/node`

### Crie um arquivo dotenv com as informações do seu banco:
- PORT=3000
- MYSQL_DB=teste
- MYSQL_USER=root
- MYSQL_PASSWORD=
- MYSQL_PORT=3306


### Instale o nodemon, mysql e sequelize

4. `npm install -g nodemon typescript ts-node`
5. `npm install mysql2`
6. `npm install sequelize`

Em package.json crie o seu script para rodar o projeto

7. "start-dev": "nodemon -e ts,json,mustache server.ts"

inicie o projeto com o comando que você criou no script (start-dev)

