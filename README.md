**Name:** Agata  
**Surname:** Zając   
**Date:** April 7, 2025  
**Field of study:** Bioinformatics


## **Useful Git commands:**


### **1. git config --list**
- displays all the git configuration settings currently in effect for our system, user, and repository


### **2. git init**
- creates a new git repository in current directory


### **3. git add**
- adds a change in the working directory to the staging area
- for example: 'git add README.md'


### **4. git commit**
- saves changes to the local repository
- for example: 'git commit -m "first commit"'
- '-m' flag in git stands for "message" and is used to provide a commit message directly in the command line


### **5. git branch -M main**
- renames the current branch to main
- if the branch was originally named master, this command renames it to main
- '-M' flag forces the rename, even if the branch name already exists.


### **6. git remote add origin <repository-url>**
- connects the local git repository to a remote repository on GitHub
- origin is just a name for the remote repository


### **7. git push**
- pushes commits from the local repository to the remote repository (GitHub)
- for example: 'git push -u origin main'
- '-u' flag sets origin main as the default upstream branch so in the future we can just type git push


### **8. git pull**
- fetches changes from the remote repository and merges them into the local branch
- for example: 'git pull origin main'
- it ensures that the local copy is up to date before we add more commits

