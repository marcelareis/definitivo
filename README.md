# SistWebZen2

Comandos de instalação descritos nesta documentação é compatível para Sistema Operacional Windows.

Comunicações importantes:
- Para o efetivo funcionamento do sistema como pré-requisito é necessário ter o NodeJs em sua máquina.
- Como banco de dados foi utilizado o postgres associado ao knex, utilizando a porta 3000 ((verificar antes se a porta esta desocupada).
- A Aplicação esta em duas pastas separadas denominadas: 1)Backend e 2)Front end.

Segue abaixo alguns passos importantes e necessários:

1. É necessário instalar o knex de forma global, para isso, acesse o cmd(prompt) de sua máquina e insira o comando: npm i -g knex

2. Será necessário criar um banco de dados pelo postgres. Para isso através do cmd(prompt de comando) acessar a pasta backend e insira o comando: create database partscatalog.

3. Antes de acessar as aplicações as dependências devem ser instaladas. Para isso:  Acessar a pasta Backend através do prompt e digitar: npm i. Após acessar a pasta Frontend, também através do cmd, digitar: npm i

4. Comandos para rodar o sistema em Frontend. Através do cmd(prompt de comando) digite: npm run serve, acessando a porta 8080 (verificar antes se a porta esta desocupada)

5. Comandos para rodar o sistema em Backebd. Através do cmd(prompt de comando) digite: npm start

6. Abrir o Browser com o endereço http://localhost:8080, para acessar toda aplicação e utilizar o sistema.
