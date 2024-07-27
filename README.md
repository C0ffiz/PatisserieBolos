# PatisserieBolos

Website in NodeJs, Handlebars and Sequelize

## Description

A CRUD for saving clients and editing homepage photos and text

## Getting Started

### Dependencies

NodeJs
Handlebars

### Installing

//Configuração Banco de Dados

//Dados do banco estão na pasta db, no arquivo conn.js para autenticação do banco

//Comandos:

    create database node_mvc;
    use node_mvc;

    //rode o index.js para criar as tabelas

    //popular o banco
    insert into promos(id,produto,preco,img,createdAt,updatedAt) values(1,"produto1",1,"combo1.jpg",now(),now());
    insert into promos(id,produto,preco,img,createdAt,updatedAt) values(2,"produto2",2,"combo1.jpg",now(),now());
    insert into promos(id,produto,preco,img,createdAt,updatedAt) values(3,"produto3",3,"combo1.jpg",now(),now());
    insert into promos(id,produto,preco,img,createdAt,updatedAt) values(4,"produto4",4,"combo1.jpg",now(),now());

    insert into sobres(sobretxt,img,createdAt,updatedAt) values("O nome completo é Izabella Tavares. A data de nascimento é 1997. É natural de Goiânia-Goiás. A formação profissional é na área de administração. É empreendedora e confeiteira por amor. Abandonou a profissão de administração para viver o sonho da Confeitaria.","nada",now(),now());

### Executing program

* How to run the program
* Step-by-step bullets
```
node index.js
```


## Authors

Contributors names and contact info

ex. [Coffee](github.com/C0ffiz)
