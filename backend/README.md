<html>
<h1 align="center">
            <img src="./assets/logo.svg" alt="Be The Hero" width="100px" height="100px">
            <img src="./assets/nodeJS.png" alt="Be The Hero" width="100px" height="100px">
            <img src="./assets/sqlite.png" alt="Be The Hero" width="150px" height="75px">
    <p align="center"><strong>BE THE HERO</strong></p>
    <p align="center">API RESTFUL com nodeJS</P>
</h1>

## Conteúdo
* [Sobre o Projeto](#sobre-o-projeto)
* [Feito Com](#sobre-o-projeto)
* [Dependências Necessárias](#dependências-necessárias)
* [Como executar](#como-executar)
* [Bibliotecas Utilizadas](#bibliotecas-utilizadas)

## Sobre o projeto
Trata-se de uma **API RESTFUL** desenvolvida em nodeJS responsável pela interação com um banco de dados SQLite, que armazena dados referentes às informações necessárias para a realização das ações de <strong style="color: #31BE2E">POST</strong>, <strong style="color: #AB77F0">GET</strong> e <strong style="color: #B81531">DELETE</strong> de dados.

## Feito com
* [NodeJS](https://nodejs.org/en/)
* [SQLite](https://www.sqlite.org/index.html)

## Dependências Necessárias
Para rodar o projeto você precisa ter instalado na sua máquina o [node](https://nodejs.org/en/download/) e o [yarn](https://yarnpkg.com/) .

## Como executar
Após o clone desse repositório e o download das [dependências necessárias](#dependências-Necessárias), dentro no diretório /backend execute: `yarn install`  para instalação das dependêcias, e em seguida `yarn start` para rodar a aplicação.

**Atenção:** Por padrão, a aplicação é executada em http://localhost:3333 . Se necessário, é possível trocar a porta de execução em ./backend/src/server.js e alterar o valor de `const port` .

**Atenção:** Caso tenha problemas para rodar `yarn start` em um SO Linux, tente `sudo yarn start` . 


## Bibliotecas Utilizadas

* [nodemon](https://nodemon.io/)
* [express](https://expressjs.com/)
* [cors](https://developer.mozilla.org/pt-PT/docs/Web/HTTP/CORS)
* [celebrate](https://www.npmjs.com/package/celebrate)
* [jest](https://jestjs.io/)
* [cross-env](https://www.npmjs.com/package/cross-env)
* [supertest](https://github.com/visionmedia/supertest)
* [knex](http://knexjs.org/)
* [sqlite3](https://www.sqlite.org/index.html)
