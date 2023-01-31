# **Git Paper**
* O objetivo é criar um paper para exercitar os comandos e funcionalidades do git.
* Será criada a estrutura do paper, branches para cada tópico do paper e merge ao final para se obter o paper completo.

## **Como foi feito:**

notas: 
**Foi usado o VSCODE para editar os textos**  
**Foi usado o terminal do VSCODE**  
**Os comandos devem rodar dentro da pasta**  

1 - Criar uma pasta  


2 - Criar arquivos README.md e git_paper.md (md = MarkDown)


3 - Criar um repositório no github 



4 - Inicialização, primeiro commit e link github:

*git init*  
*git add .*  
*git commit -m "commit inicial"*  
*git remote add origin https://github.com/frbassan/git_paper.git*  
*git push -u origin master*  



5 - Criação do branch **introdução**, commit, push no branch, merge (branch+master) e push no master

*git checkout -b "introdução"*  
*code git_paper.md //aqui vai abrir o git_paper.md no vscode, editar o arquivo*  
*git add git_paper.md*  
*git commit -m "texto da introdução adicionado"*  
*git push -u origin introdução*  
*git checkout "master"*  
*git merge "introdução"*  
*git push*  



6 - criação do branch **desenvolvimento**, commit, push no branch, merge (branch+master) e push no master

*git checkout -b "desenvolvimento"*  
*code git_paper.md //aqui vai abrir o git_paper.md no vscode, editar o arquivo*  
*git add git_paper.md*  
*git commit -m "texto do desenvolvimento adicionado"*  
*git push -u origin desenvolvimento*  
*git checkout "master"*  
*git merge "desenvolvimento"*  
*git push*  



7 - criação do branch **conclusão**, commit, push no branch, merge (branch+master) e push no master  

*git checkout -b "conclusão"*  
*code git_paper.md //aqui vai abrir o git_paper.md no vscode, editar o arquivo*  
*git add git_paper.md*  
*git commit -m "texto do conclusão adicionado"*  
*git push -u origin conclusão*  
*git checkout "master"*  
*git merge "conclusão"*  
*git push*  
