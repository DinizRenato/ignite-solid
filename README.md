## Desafio 01 - Introdução ao SOLID

### Teste do Model
- [x] Should be able to create an user with all props

### Testes do repositório
- [x] Should be able to create new users
- [x] Should be able to list all users
- [x] Should be able to find user by ID
- [x] Should be able to find user by e-mail address
- [x] Should be able to turn an user as admin

### Testes de useCases
- [x] Should be able to create new users
- [x] Should not be able to create new users when email is already taken
- [x] Should be able to turn an user as admin
- [x] Should be able to turn an user as admin
- [x] Should be able to get user profile by ID
- [x] Should not be able to show profile of a non existing user
- [x] Should be able to list all users
- [x] Should not be able to a non admin user get list of all users
- [x] Should not be able to a non existing user get list of all users

### Testes das Rotas
- [x] [POST] /users
- [x] [PATCH] /users/:user_id/admin
- [x] [GET] /users/:user_id
- [x] [GET] /users

### Documentação com SWAGGER
- [x] [POST] /users
- [x] [PATCH] /users/:user_id/admin
- [x] [GET] /users/:user_id
- [x] [GET] /users

