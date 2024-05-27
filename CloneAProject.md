# Clone and push codes to a remote repository

1. Clone the repository to your local machine using "git clone" command.

```
$ git clone https://github.com/PrathicaShettyM/Git_Tutorials.git
```

2. check the status of workspace area using "git status" command. This commands lets us know the tracked al well as untracked files

```
$ git status
```

3. Add the untracked files to the staging area using "git add command". If we want to add all files to the staging area then use "add ."

```
$ git add .
```

4. If we want to add only one file then use

```
$ git add file1
```
5. Change the branch to "main" branch
```
$ git branch -M main
```
6. Add the code to remote repository and replace the link with "origin" keyword
```
$ git remote add origin https://github.com/PrathicaShettyM/Git_Tutorials.git
```
7. push the code files to the remote repository
```
$ git push -u origin
```






