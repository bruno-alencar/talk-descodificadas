# Git init

login: teste12313
senha: s31`3131

## O que é git?
 *"Git é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas"*
 [Tableless](https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/)


Criado por [Linus Torvalds](https://pt.wikipedia.org/wiki/Linus_Torvalds) por necessidade em seu projeto do Kernel do Linux.

## Login
Criar uma conta no github
https://github.com/join

## Download do Git Desktop
Para utilizar o github usando no computador
https://desktop.github.com

## git init 
Comando utilizado para iniciar um projeto git
> `git init`

## git clone < LINK>
Comando para baixar o repositório do git
> `git clone git@github.com:bruno-alencar/talk-git-init.git`

## git remote add < NOME > < LINK >
Quando estamos referenciando uma origem de código de um projecto já existente na máquina
> `git remote add origin git@github.com:bruno-alencar/talk-git-init.git`

## git add < ARQUIVO >
Podemos adicionar nossos arquivos a serem comitados separadamente ou não
> `git add README.md`

ou para adicionar todos os arquivos:
> `git add .` / `git add *`

## git commit -m ""
Commits são utilizados para "gravar" um comentário para as modificações que foram feitas
> `git commit -m "First commit"`

## git branch
Criamos novas ramificações quando estamos em outra funcionalidade

![Branch](./branch.jpg "Branch example")

### listar todas as branches
> `git branch`

### criar nova branch 
> `git branch bruno`

### excluir branch
> `git branch -d bruno`

### renomear
> `git branch -m bruno brunoalencar`

## git checkout < BRANCH-NAME >
Para navegar/trocar as branches

> `git checkout bruno`

> `git checkout master`

## git push
Enviar os arquivos commitados (registrados) para o seu repositório remoto
git push origin < BRANCH-NAME >

> `git push origin dev`
