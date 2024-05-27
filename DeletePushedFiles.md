# Delete accidentally pushed files to the remote repository:
This can be achieved using -

1. Open the bash CLI in the directory
2. Type the following command along with required file name(like here the `File.md` file)
```
$ git rm --cached File.md
```
3. Now commit and push the files to the remote repository
```
$ git push
```

# To remove files from the Staging area after `git add .` :
```
$ git restore File.md
```