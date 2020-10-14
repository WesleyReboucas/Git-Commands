#### ---------------------------------------------------------| Git Commands |-------------------------------------------------------
		
-> Configuração 

		git config --global user.name "SEU_USUARIO"

		git config --global user.email "SEU_EMAIL"

		git config --global core.editor "NOME_EDITOR"

- Verificar configurações:

		git config  --list

- Alterar repositório remoto:

		git remote set-url origin URL_REPOSITÓRIO

-> Inicializando um repositorio

		git init 
    
   		git add . (Caso tenha conteúdo na pasta)  
		
		git commit -m "SEU_COMMIT"   
    
   		git branch -M main    
    
   		git remote add origin https://github.com/SEU_USUÁRIO/SEU_REPOSITÓRIO.git  
    
   		git push -u origin main
    

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
