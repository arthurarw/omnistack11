# Semana OmniStack 11 - [Link](https://rocketseat.com.br/week/aulas/11.0)

#### EN:
Hello, I decided to learn a little about Node JS, React JS and React Native, so I decided to sign up for the week OmniStack 11. My experience and my area in programming is specifically PHP.

I hope you make good use of the repository.

To install, enter the backend and frontend folder and enter the following code in the terminal:
```
npm install
```

The database used in the project is MySQL and to configure the database, just edit the following file:
```
backend/knexfile-example.js
```
And edit the filename to ```knexfile.js```

In lines 9, 10 and 11, you can find the lines for editing:
```
user: 'YOUR_USER_DB',
password: 'YOUR_PASS_DB',
database: 'YOUR_DB'
```

After configuring the database, you need to run the migrations.
To run the migrations use this code on the terminal in the backend folder:
```
knex migrate:latest
```

After having done all the settings above, just go to the backend folder and run the following command in the terminal:
```
npm start
```
After starting the backend, go to the frontend folder and run the following command in the terminal:
```
npm start
```

After that, your project will be working correctly, just access the link: ```http://localhost:3000```
Thanks and sorry for any programming and grammar errors. Remembering that the project is not yet finalized.

##### [LinkedIn](https://www.linkedin.com/in/261656165/)


#### PT-BR:
Olá, eu resolvi aprender um pouco sobre Node JS, React JS e React Native, então resolvi me inscrever na semana OmniStack 11. Minha experiência e minha área na programação é especificamente o PHP.

Espero que vocês façam bom proveito do repositório.

Para instalar, entrar na pasta backend e frontend e digitar o seguinte código no terminal:
```
npm install
```

O banco de dados utilizado no projeto é MySQL e para fazer a configuração do banco de dados, basta editar o seguinte arquivo:
```
backend/knexfile-example.js
```
Na linha 9, 10 e 11, se encontra as linhas para fazer a edição:
```
user: 'YOUR_USER_DB',
password: 'YOUR_PASS_DB',
database: 'YOUR_DB'
```
Após editar, altere o nome do arquivo para ```knexfile.js```

Após ter configurado o banco de dados, você precisa rodar as migrations.
Para rodar as migrations utilize este código no terminal na pasta backend:
```
knex migrate:latest
```

Após ter feito todas as configurações acima, basta ir na pasta backend e rodar o seguinte comando no terminal:
```
npm start
```
Após ter inicializado o backend, vá na pasta frontend e rode o seguinte comando no terminal:
```
npm start
```
Após isso, seu projeto estara funcionando corretamente, basta acessar o link:
```http://localhost:3000```
Obrigado e desculpa por qualquer erro de programação e de gramática. Lembrando que o projeto ainda não esta finalizado.

##### [LinkedIn](https://www.linkedin.com/in/261656165/)