# ImersaoFullCycle

Instalar o Nest 

```
npm install -g @nestjs/cli
```

Criar o projeto
```
npx @nestjs/cli new nestjs-api
```

Para criar um resource
```
nest g resource
```
Ele já irá criar toda a estrutura CRUD, basta somente colocar a lógica

Instalar o ORM Sequelize e Mysql
```
npm install --save sequelize sequelize-typescript mysql2
npm install --save-dev @types/sequelize
```