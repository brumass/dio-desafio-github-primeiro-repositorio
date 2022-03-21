# Repositório do Desafio Git/GitHub 

_Participação no Philips Fullstack Developer | You Are You_



## Comandos básicos do git 



> **_git init_ ** - Iniciar git
>
> Inicializa o repositório git dentro da pasta
>
> 
>
> **_git add_**  - iniciar versionamento (mover arquivos)
>
> Tira os arquivos do Tracked (o git nao sabia da existencia do arquivo) e adiciona os arquivos no staged e se prepara para um commit
>
> 
>
> **_git commit_** - Criar commit
>
> Carrega dados como autor,  data e mensagem. Cria um snapshot (foto) no repositório local para ser empurrado para o repositorio remoto.
>
> 



 ## Instruções



1. Criei diretório no  /c

   

   > **mkdir** desafio-repositorio



2. Entrei no diretório e **iniciei o git**

   

   > **cd** desafio-repositorio
   >
   > **git init**



3. Adicionei um arquivo no diretório desafio-repositorio

   

   > arquivo do primeiro repositorio.md



4. Comitei todos os arquivos do diretório

   

   > **git  add ***
   >
   > **git commit** -m "commit inicial do meu repositorio"



[ _**git status** para saber como está o status dos arquivos_ ]



5.  Criei repositório no github

   

   **Diretório:**  dio-desafio-github-primeiro-repositorio

   **Status:** público

   **Descrição:**  Desafio de projeto Git/GitHub bootcamp Dio Phillips

   

   No gitbash realizei o apontamento do diretório criado no github com o repositorio local:

   _origin ( é apenas apelido do link poder ser qualquer nome)_

   

   > **git remote add origin**n https://github.com/brumass/dio-desafio-github-primeiro-repositorio.git



Para listar os reposítórios cadastrados pode realizar o comando:

>  git remote -v



6. Empurrei meus arquivos para o repositório remoto

   > git **push** originn master



_Pode ser que peça senha e email (logar no github)_



>  Caso seja a primeira vez utilizando o git será necessário configurar  email e senha (indicado utilizar o mesmo do github)
>
> 
>
> **git config --global user.email** _"colocar email aqui_"
>
> **git config --global user.name** _"colocar nickname aqui"_
>
> 
>
> Inserindo o comando **unset** irá deletar o que foi cadastrado podendo assim cadastrar um _novo email e senha_.
>
> 
>
> git config --global **--unset** user.email
>
> git config --global **--unset** user.name



