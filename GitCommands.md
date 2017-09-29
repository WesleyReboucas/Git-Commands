					
					----| Comandos Git |----
	
	
---------> Configuração 
 

--> Configurar o nome da sua conta :

		git config --global user.name "SEU_USUARIO"

--> Configurar o email da sua conta:

		git config --global user.email "SEU_EMAIL"

--> Configurar o editor padrão da sua conta

		git config --global core.editor "NOME_EDITOR"

--> Verificar todas as configurações:

		git config  --list

--> Alterar repositório remoto:

		git remote set-url origin URL_REPOSITÓRIO

---------> Inicializando um repositorio

--> Criar uma pasta :
	
		mkdir SUA_PASTA

--> Entrar na pasta:

		cd SUA_PASTA

--> Iniciar o git nessa pasta:

		git init

--> Iniciar o repositório remoto:

		git remote add URL_REPOSITORIO 


---------> Branch

--> Criar um novo branch:
		
		git checkout -b branch NOME_BRANCH

--> Identificar quais as Branch existentes e saber em qual você estar:
		
		git branch 

--> Navegar entre as Branch:
		
		git checkout NOME_BRANCH

--> Apagar uma branch:
		
		git branch -D NOME_BRANCH

--> Unir branch:

*Merge = Ele junta commit's criados em outras branch's, criando um novo commmit
		na branch master. Deixando assim tudo linear. Estando na master, digite:

			git merge NOME_BRANCH		

*Rebase = Ele junta commit's criados em outras branch's, movendo o commit da 
		branch criada para a branch master.
		
--> Realizar um pull request - Estando na master, faça um merge e depois realize o pull request:
		
		git request-pull NOME_BRANCH URL master
