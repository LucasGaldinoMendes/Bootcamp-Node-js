## Bootcamp Node.js

# Indice

- [Sobre](#-sobre)
- [delivery-api](#-delivery-api)
- [petshop-api](#-petshop-api)
- [petshop-api-v2](#-petshop-api-v2)
- [livraria-api](#-livraria-api)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como baixar o projeto](#-como-baixar-o-projeto)

## 🔖&nbsp; Sobre

O projeto **Bootcamp-Node-js** é um repositório dos trabalhos avaliativos do **Bootcamp Desenvolvedor Node.js**. Cada projeto contém seu respectivo enunciado.

---

## 🍔&nbsp; Delivery api

O projeto **Delivery api** é uma API para controlar pedidos de um delivery de comida.

---

## 🐶&nbsp; Petshop api

O projeto **Petshop api** é uma API para gerenciar cadastros de um petshop.

---

## 🐕&nbsp; Petshop api v2

O projeto **Petshop api v2** é uma outra versão do Petshop API. Nela, a API é refatorada para utilizar o Sequelize e são incluídas novas funcionalidades como controle de serviços e uma estrutura para blog, salvando título, conteúdo e comentários no MongoDB.

---

## 📚&nbsp; Livraria api

O projeto **Livraria api** é uma API para controlar cadastros de uma livraria. Nela está incluso controle de clientes,
livros, autores e vendas. Também é possível adicionar informações dos livros e avaliações dos mesmos.

---

## 🚀 Tecnologias utilizadas

Os projeto foram desenvolvidos utilizando as seguintes tecnologias

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [MongoDB](https://www.mongodb.com/)
- [Sequelize](https://sequelize.org/)
---

## 🗂 Como baixar o projeto

```bash

    # Clonar o repositório
    $ git clone https://github.com/LucasGaldinoMendes/Bootcamp-Node-js

    # Entrar no diretório
    $ cd Bootcamp-Node-js
  
    #Entrar no projeto que quer acessar, por exemplo a delivery-api
    $ cd delivery-api
  
    # Instalar as dependências
    $ npm install

    #Configurar a base de dados
    Caso o projeto utilize uma base de dados, é necessário criar a base de dados 
    com o script bd.sql e configurar a uri de conexão em repositories/db.js. 
    No caso de base de dados NoSQL a conexão deve ser configurada em 
    respositories/mongo.db.js (para essa base de dados não há script, é necessário cria-lá).  
    
    # Iniciar o projeto
    $ node index.js
```

---

