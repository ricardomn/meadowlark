# Meadowlark
The Meadowlark Travel Website with NodeJS and Express

# NODE - Instalando através de NVM

O legal do NVM é que você pode instalar várias versões do Node e ficar alternando entre elas, mas antes de instalar o NVM precisamos de alguns pacotes de dependências que já estão no repositório de sua distribuição Debian Based.

Para instalar o NVM, primeiro devemos executar os seguintes comandos:

sudo apt-get update
sudo apt-get install build-essential libssl-dev

# Instalando o NVM

curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.2/install.sh | bash

Para visualizar as versões disponíveis, fazemos:

nvm ls-remote

A partir da versão mais recente, deve-se executar o comando:

nvm install v6.11.2

No nosso caso, utilizamos a versão acima.



# Express
Um Framework web rápido, flexível e minimalista para Node.js

Para instalar o Express no Linux:

npm install --save express

# Engine HTML - express3-handlebars

Para instalar fazemos:

npm install --save express3-handlebars


# Instalando Mocha para Test page

npm install --save-dev mocha

Depois fazemos,

mkdir public/vendor

cp node_modules/mocha/mocha.js public/vendor
cp node_modules/mocha/mocha.css public/vendor

# Para utilizar a funcionalidade de Assert

npm install --save-dev chai
cp node_modules/chai/chai.js public/vendor

