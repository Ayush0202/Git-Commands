# Git Commands #

### Initializing a Git Repositry ###
```
$ git init
```
<br>

### Checking Status of Files ###
```
$ git status
```
<br>

### Add Files to Staging Area ###
```
$ git add .
```
<br>

### Commiting Changes ###
```
$ git commit -m "Some Message"
```
<br>

### Removing Changes from Stage ###
```
$ git restore --staged file.txt
```
<br>

### Viewing Overall History ###
```
$ git log
```
<br>

### Removing Commit from History of Project ###
```
$ git reset COMMIT_HASHCODE
```
<br>

### Stashing Changes ### 
Saving modified changes but not commiting them
```
$ git stash
```
<br>

### Getting Stashed Changes back to Staging Area ###
```
$ git stash pop
```
<br>

### Cleaning Stash ###
```
$ git stash clear
```
<br>

### Connecting Remote Repositry to Local Repositry ###
```
$ git remote add origin URL
```
<br>

### Pushing Local Changes to Remote Repositry ###
```
$ git push origin main
```
<br>

### Making a New Branch ###
```
$ git branch NAME
```
<br>

### Switching to a Branch ###
```
$ git checkout NAME
```
<br>

### Merging Branch to Main ###
```
$ git merge NAME
```
<br>

### Adding Upstream to Local ###
```
$ git remote add upstream FORKED_PROJECT_URL
```
<br>

### Making Forked Project even with Main Project ###
```
$ git fetch --all --prune

$ git checkout main

$ git reset --hard upstream/main

$ git push origin main
```

OR

```
$ git pull upstream main

$ git push origin main  
```
<br>