# NLW3happy-server
<h1 align="center">
<img alt="happy" src="https://github.com/AndreVTavares/NLW3-happy/blob/main/happy.png?raw=true" width="450px">
</h1>


## Tecnologias

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [TypeORM](https://typeorm.io/#/)
- [SQLite](https://www.sqlite.org/index.html)
- [Insomia](https://insomnia.rest/)
- [Beekeeper Studio](https://www.beekeeperstudio.io/) 

## Instalação - Backend

### Instalação de dependências

Para executar o projeto é necessário ter o Node e o NPM ou Yarn instalados para realizar a instalação das dependências.

```
# na pasta raiz do seu projeto instale as dependencias:

$ yarn install

# se estiver usando npm

$ npm install

```

### Realização das Migrations e incializando o server

```
# primeiramente é realizado as migrations e depois a inicialização do servidor

$ yarn typeorm migration:run
$ yarn dev

# se estiver usando npm

$ npm run typeorm migration:run
$ npm run dev

```
