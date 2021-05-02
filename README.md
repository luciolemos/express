# Hey! 👤

[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/luciolemos)](https://github.com/luciolemos)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucio-lemos-a550441a1/)](https://www.linkedin.com/in/lucio-lemos-a550441a1/)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/lucciolemos)](https://twitter.com/lucciolemos)
[![Youtube Badge](https://img.shields.io/badge/-YouTube-ff0000?style=flat-square&labelColor=ff0000&logo=youtube&logoColor=white&link=https://studio.youtube.com/channel/UCrNM1nr2nw0lSqMD10m6rLw)](#)

## EXPRESS_PROJECT 📌: 
### 1. Parar o processo rodando na porta 3000:
#### ✔️ Você pode encontrar o PID de um processo escutando em uma porta com o comando:
    luciolemos@dev:~/nextlevelweek/restful$ sudo netstat -nlp | grep :3000
    [sudo] senha para luciolemos:     
    tcp6       0      0 :::3000                 :::*                    OUÇA       11020/node 

#### ✔️ O ID do processo é o número antes do nome do processo na sexta coluna, que você pode passar para o killcomando:
    luciolemos@dev:~/nextlevelweek/restful$ kill 11020
#### ✔️ Fazer como previsto em [Gerador](http://expressjs.com/en/starter/generator.html)
#### ✔️ O arquivo README.md não faz parte da estrutura de arquivos do projeto.

### 2. Criando uma aplicação com a ferramenta `express-generator` para criar rapidamente o esqueleto de um aplicativo.
    luciolemos@dev:~/nextlevelweek$ ls -l
    total 16
    drwxrwxr-x  8 luciolemos luciolemos 4096 abr 27 17:29 podcastr
    drwxrwxr-x 10 luciolemos luciolemos 4096 abr 20 07:14 podcastrnext
    drwxrwxr-x  5 luciolemos luciolemos 4096 mai  1 17:00 react_project
    drwxrwxr-x  6 luciolemos luciolemos 4096 abr 24 13:53 restful
### ✔️ Criando o diretório onde será gerado o projeto: 
    luciolemos@dev:~/nextlevelweek$ mkdir express_project
### ✔️ Listando arquivos e diretórios
    luciolemos@dev:~/nextlevelweek$ ls -l
    total 20
    drwxrwxr-x  2 luciolemos luciolemos 4096 mai  1 19:08 express_project
    drwxrwxr-x  8 luciolemos luciolemos 4096 abr 27 17:29 podcastr
    drwxrwxr-x 10 luciolemos luciolemos 4096 abr 20 07:14 podcastrnext
    drwxrwxr-x  5 luciolemos luciolemos 4096 mai  1 17:00 react_project
    drwxrwxr-x  6 luciolemos luciolemos 4096 abr 24 13:53 restfu
### ✔️ Navegando até a raiz do projeto:
    luciolemos@dev:~/nextlevelweek$ cd express_project
### ✔️ Listando arquivos e diretórios
    luciolemos@dev:~/nextlevelweek/express_project$ ls -l
    total 0
### ✔️ Gerando o projeto com o comando 'npx express-generator`:
    luciolemos@dev:~/nextlevelweek/express_project$ npx express-generator

    warning: the default view engine will not be jade in future releases
    warning: use `--view=jade' or `--help' for additional options


    create : public/
    create : public/javascripts/
    create : public/images/
    create : public/stylesheets/
    create : public/stylesheets/style.css
    create : routes/
    create : routes/index.js
    create : routes/users.js
    create : views/
    create : views/error.jade
    create : views/index.jade
    create : views/layout.jade
    create : app.js
    create : package.json
    create : bin/
    create : bin/www

    install dependencies:
        $ npm install

    run the app:
        $ DEBUG=express-project:* npm start
### ✔️ Instalando as dependências do projeto
    luciolemos@dev:~/nextlevelweek/express_project$ npm install
### ✔️ Startando o servidor 
    luciolemos@dev:~/nextlevelweek/express_project$ DEBUG=express-project:* npm start
