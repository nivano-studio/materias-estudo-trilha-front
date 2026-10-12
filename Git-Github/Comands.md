Comando de setup do Git
git config --global user.name "Jose
git config --global user.email "jr3303361587@hotmail.com"

Comandos essenciasa
git init <- Cria repositorio na pasta

git status <- Alterações feitas

git add . <- Preparar para commit

git add arquivo.txt <- preparar para commit somente desse arquivo

git commit -m "msg" <- Salvar e manda as alterações

git push <- Mandar todo o projeto

git pull <- Baixar todo projeto do repositor
git clone <url.> Copia um repositorio

git log <- Historico de Alterações

git checkout 1d0acf4f9b46d8a5ae3e8630e6dda003f87b152d <- consegue visualizar versões passadas
git checkout main <- voltar para versão atual

git checkout -b "test" < Mudando a branch (pode ser feito alterações sem prejudicar a main)

git merge test <- trazer alterações feitas em outra branch

Usar o git bash para commits no terminal

git remote add origin https://github.com <- Cria coneção com algum repositorio do Git

Como alterar do main para o master:

1. Renomeia a sua branch local de 'master' para 'main'

git branch -M main

2. Envia os arquivos para a branch 'main' no GitHub

git push -u origin main



Criando primeira coneção com o repositorio:

git init

git remote add origin url-projeto

git romote -v

git push --set-upstream origin master <- adicionando a branch master no repositorio

git push
