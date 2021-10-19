# Gerenciador de Biblioteca 🤓📚


# **Requisitos:**

**Rotas da aplicação:**

**[POST]** /obras : A rota deverá receber titulo, editora, foto, e autores dentro do corpo da requisição. Ao cadastrar um novo projeto, ele deverá ser armazenado dentro de um objeto no seguinte formato: 
```{ id: 1, titulo: ‘Harry Potter’, editora: ‘Rocco’,foto: ‘https://i.imgur.com/UH3IPXw.jpg’, autores: [“JK Rowling”, “…”]};```

**[POST]** /upload-obras: está rota deverá receber um **arquivo csv contendo os mesmos parâmetros da rota anterior** mas podendo ser salvo em massa no banco de dados  

**[GET]** /obras/ : A rota deverá listar todas as obras cadastradas

**[GET]** /file-obras/ : A rota retornar um arquivo contendo todos as obras, **deverá ser possível filtrar pela data de criação**

**[PUT]** /obras/:id: : A rota deverá atualizar as informações de titulo, editora, foto e autores da obra com o id presente nos parâmetros da rota

**[DELETE]** /obras/:id: : A rota deverá deletar a obra com o id presente nos parâmetros da rota

## Ferramentas utilizadas

[x] Python 3.9

[x] Pycharm

[x] Django

## Aplicação publicada

**Basta clicar no link para acessar a solução** 😉

[x] - [Heroku](https://biblioteca-rhsm.herokuapp.com/) em construção...⚒⚙
