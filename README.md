# Comandos-do-git-
## Eu esqueci quase todos então fiz esse repositório listando eles.🦥

$ git config  user.email “email”

$ git config user.name “usuariodogit”

Depois siga os comandos abaixo, mas assista os vídeos para entender o porque de cada um e porque podem acontecer erros nesse período.

Iniciar o processo

$ git init

Mostra os arquivos que ainda não estão no repositorio

$ git status

Adiciona os arquivos para irem ao repositório

$ git add .

Nomeia esse upload, cada commit tem um nome.

$ git branch -M main

envia dados para a raiz do projeto (principal).

Envia dados para a raiz do projeto(principal) 

$ git commit -m “Exemplo – exercícios sobre operadores aritmeticos”

Informa para qual repositório vai esses arquivos, o link abaixo você vai copiar do github

$ git remote add origin https://github.com/seunome/nomerepositorio.git

Agora precisamos enviar os arquivos o comando é:

$ git push origin master

Na primeira vez ele irá pedir seu usuário e senha que cadastrou no git.

Em caso de erro nessa etapa, use antes o comando abaixo:

git pull origin master –allow-unrelated-histories (só em caso de erro)

Em seguida use esse novamente

$ git push origin master

OBS.: TODO O PROCESSO ACIMA ESTÁ NOS VÍDEOS, NÃO DEIXE DE ASSISTIR, MOSTRO COMO SUBIR, ATUALIZAR REPOSITÓTIO E CRIAR OUTRO REPOSITÓRIO PARA ARMAZENAR SITE. USE ESSES COMANDOS ACIMA APENAS DEPOIS DE ENTENDER O PORQUÊ DE CADA UM DELES, OU PARA RELEMBRAR.
