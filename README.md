# **Git Paper**
* O objetivo é criar um paper para exercitar os comandos e funcionalidades do git.
* Será criada a estrutura do paper, branches para cada tópico do paper e merge ao final para se obter o paper completo.

## **Como foi feito:**
1 - criar uma pasta;
2 - criar arquivos README.md e git_paper.md
3 - criar um repositório no github
4 - seguir os comandos abaixo 

## **Comandos usados, deve estar dentro da pasta criada conforme citado acima, foi usando o terminal do VScode:**

### **inicialização, primeiro commit e link github:**

*git init*
*git add .*
*git commit -m "commit inicial"*
*git remote add origin https://github.com/frbassan/git_paper.git*
*git push -u origin master*


### **criação do branch **introdução**, commit, push no branch, merge (branch+master) e push no master**

*git checkout -b "introdução"*
*code git_paper.md //aqui vai abrir o git_paper.md no vscode, editar o arquivo*
*git add git_paper.md*
*git commit -m "texto da introdução adicionado"*
*git push -u origin introdução*
*git checkout "master"*
*git merge "introdução"*
*git push*


### **criação do branch **desenvolvimento**, commit, push no branch, merge (branch+master) e push no master**

*git checkout -b "desenvolvimento"*
*code git_paper.md //aqui vai abrir o git_paper.md no vscode, editar o arquivo*
*git add git_paper.md*
*git commit -m "texto do desenvolvimento adicionado"*
*git push -u origin desenvolvimento*
*git checkout "master"*
*git merge "desenvolvimento"*
*git push*


### **criação do branch **conclusão**, commit, push no branch, merge (branch+master) e push no master**

*git checkout -b "conclusão"*
*code git_paper.md //aqui vai abrir o git_paper.md no vscode, editar o arquivo*
*git add git_paper.md*
*git commit -m "texto do conclusão adicionado"*
*git push -u origin conclusão*
*git checkout "master"*
*git merge "conclusão"*
*git push*
