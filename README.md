Restful com NodeJs e MongoDB
========================

Para iniciar é necessário instalar usando o gerenciador de pacotes npm:
-------------------------

- Mongodb instalado ou crie uma conta no http://mlab.com
- NodeJs
- ExpressJs - npm install express --save
- Body-Parser - npm install body-parser --save
- ValidatorJS - npm install validator --save
- Mongoose - npm install mongoose --save

Para se criar um novo package.json deve-se rodar o comando: npm init.
No nosso caso o pacote já está criado.

-------------------------

Esta é uma Api Restful exemplo utilizando as tecnologias NodeJs com MongoDB.

Inicialmente é preciso instalar os pacotes, node_modules, pelo gerenciador npm usando o comando: npm install.

Para rodar a aplicação deve-se usar o comando: node app.js.

A partir daí a aplicação estará rodando no http://localhost:5000.

Para que se possa rodar a aplicação de maneira que o servidor 'escute' as alterações e atualize automaticamente
sem que seja necessário sair (CTRL C) e entrar novamente (node app.js) pode-se instalar o nodemon.

Para isto use o comando: npm install -g nodemon.

A partir daí pode-se user o comando: nodemon app.js.

-------------------------

O chrome disponibiliza uma aplicação chamada 'Postman' (getpostman.com).
Nela você pode testar as suas requisições GET, POST, PUT, DELETE e outras.

Obrigado!

Daniel Bueno



