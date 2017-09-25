					
					----| Comandos Git |----
	
	
---------> Configuração


--> Configurar o nome da sua conta :

		git config --global user.name "(seuUsuario)"

--> Configurar o email da sua conta:

		git config --global user.email "(seuemail@seuemail.com)"

--> Configurar o editor padrão da sua conta

		git config --global core.editor "(nomedoEditor)"

--> Verificar todas as configurações:

		git config  --list


---------> Inicializando um repositorio

--> Criar uma pasta :
	
		mkdir (sua-pasta)

--> Entrar na pasta:

		cd (sua-pasta)

--> Iniciar o git nessa pasta:

		git init


---------> Branch

--> Criar um novo branch:
		
		git checkout -b branch (nomedaBranch)

--> Identificar quais as Branch existentes e saber em qual você estar:
		
		git branch 

--> Navegar entre as Branch:
		
		git checkout (nomedaBranch)

--> Apagar uma branch:
		
		git branch -D (nomeBranch)

--> Unir branch:

*Merge = Ele junta commit's criados em outras branch's, criando um novo commmit
		na branch master. Deixando assim tudo linear.

		

*Rebase = Ele junta commit's criados em outras branch's, movendo o commit da 
		branch criada para a branch master.
		# Git
