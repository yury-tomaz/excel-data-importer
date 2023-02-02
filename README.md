# Excel Data Importer

Esse projeto é uma API que permite importar dados de uma tabela em formato de planilha Excel para um banco de dados MySQL, utilizando o [sequelize](https://sequelize.org/) como ORM. A API foi desenvolvida usando Node.js com Typescript.

## Instalação

Para instalar as dependências do projeto, execute o seguinte comando na raiz do projeto:

npm install


## Configuração

Antes de iniciar a API, você precisa configurar as informações do seu banco de dados MySQL em um arquivo `.env` na raiz do projeto. O arquivo deve conter as seguintes variáveis:

DB_HOST=<host do banco de dados>
DB_PORT=<porta do banco de dados>
DB_USER=<nome de usuário do banco de dados>
DB_PASS=<senha do banco de dados>
DB_NAME=<nome do banco de dados>


## Execução

Para iniciar a API, execute o seguinte comando na raiz do projeto:

npm start

A API estará disponível na URL `http://localhost:3000`.