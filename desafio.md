//Aula 04/02 - 
Após copiado a pasta src.

0- modificar arquivos que copiamos
  0.1 apagar os seguintes arquivos
  "Task.js" dentro de Models (não precisa apagar a pasta, iremos usar ela depois)
  "TaskController.js" dentro de Controllers (não precisa apagar a pasta, iremos usar ela depois)
  pasta "database"

  0.2 - No arquivo de rotas, apagar todas as rotas, exceto a rota '/' que deve retornar função para retornar uma mensagem qualquer.

1- comando "npm init -y" para inciar npm na pasta, (aparece "package.json")

2- instale os modulos express e cors "npm i express cors", 
(a pasta "node_modules" e "package-lock.json" aparecem depois de ter algum módulo instalado)

3- .gitignore para ignorar node_modules

4- instale nodemon como dev_dependencies "npm i -D nodemon"

5- No arquivo "package.json" dentro do parametro "scripts", insira a linha "start": "nodemon ./src/index.js" 

6- ao dar start, se der erro de algum modulo faltando que tinha copiado antes, 
instale com "npm i <nome-do-modulo>"

7- se inciado servidor, ao digitar  http://localhost:3000 deve aparecer a mensagem q vc colocou no passo 0.2

 