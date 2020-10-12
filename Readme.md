# Git

##### Esse é um resumo que estou criando com minhas palavras sobre Git e resolvi postar para que possa ajudar outras pessoas. Sintam-se avontade para ajudar com novos / melhores comandos.
###### Agradeço a todos

##### This is a summary I'm creating with my words about Git and I've decided to post so that I can help others. Feel free to help with new / better commands.
###### I thank you all

…or create a new repository on the command line

echo "# teste" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/WesleyReboucas/teste.git
git push -u origin main
                

…or push an existing repository from the command line

git remote add origin https://github.com/WesleyReboucas/teste.git
git branch -M main
git push -u origin main

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
