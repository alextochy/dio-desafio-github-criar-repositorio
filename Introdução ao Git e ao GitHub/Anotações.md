# Comandos Git Bash

- cd + *** (tab) : mudar diretório e usando tab pra autocomplete.

- git init : Para inicializar o repositório git de dentro do diretório
- git init {directory} : Para inicializar o repositório git de fora do diretório

- g : Para clonar o projeto do repositório remoto

- git status (-s -v): mostra o estado atual do diretório de trabalho do Git e do Staging Area

- git add {file name} : Para adicionar o arquivo para o próximo commit (iniciar o rastreamento do arquivo pelo git/iniciar controle de verão local)
- git add (. ou -A) : Para adicionar todos os arquivos do diretório atual para o próximo commit (iniciar o rastreamento desses arquivos pelo git/iniciar controle de verão local)

- git commit : Para comitar (confirmar, enviar e guardar) alterações à area de Stage(repositório local)
- git commit -m "{comment for the commit}" - Para comitar alterações com comentário do commmit.
- -git commit -a -m --allow-empty-message : para comitar sem comentário (não recomendado)

- git push : enviar o conteúdo do repositório local para um repositório remoto. 
- git push -u origin main : transferir commits do repositório local a um repositório remoto.
	- Para enviar um novo projeto para o repositório remoto:
		- cd {project directory}
		- git init
		- git add .
		- git commit -m "{comment for commit}"
		- git remote add origin {repository url}
		- git push -u origin main

	- Para enviar um repositório existente
		- git remote add origin {repository url}
		- git branch -M main
		- git push -u origin main


- [Diferença entre git pull e git fetch](https://stackoverflow.com/questions/292357/what-is-the-difference-between-git-pull-and-git-fetch)

** Como usar VIM?
:i - inserir 
:wq - salvar e sair