# Initialise git in the folder and push the code to a remote repository

1. Create a folder and open the git bash inside the folder and type -
```
$ git init
```
- We can check the status of the tracked and untracked files using
```
$ git status
```
2. Add files to the staging area using -
```
$ git add .
```
3. Add a commit message
```
$ git commit -m "commit message"
```
4. Change the branch (optional)
```
$ git branch -M main
```
5. Replace the remote repository link with `origin` keyword 
```
$ git remote add origin https://github.com/PrathicaShettyM/Git_Tutorials.git 
```
6. Now push the codes to the remote repository
```
$ git push -u origin
```
