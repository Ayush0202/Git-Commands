# Git Commands #

#### Initializing a Git Repositry ####
```
$ git init
```

#### Checking Status of Files ####
```
$ git status
```

#### Add Files to Staging Area ####
```
$ git add .
```

#### Commiting Changes ####
```
$ git commit -m "Some Message"
```

#### Removing Changes from Stage ###
```
$ git restore --staged file.txt
```

#### Viewing Overall History ###
```
$ git log
```

#### Removing Commit from History of Project ###
```
$ git reset COMMIT_HASHCODE
```

#### Stashing Changes ### 
Saving modified changes but not commiting them
```
$ git stash
```

#### Getting Stashed Changes back to Staging Area ###
```
$ git stash pop
```

#### Cleaning Stash ###
```
$ git stash clear
```

#### Connecting Remote Repositry to Local Repositry ###
```
$ git remote add origin URL
```

#### Pushing Local Changes to Remote Repositry ###
```
$ git push origin main
```

#### Making a New Branch ###
```
$ git branch NAME
```

#### Switching to a Branch ###
```
$ git checkout NAME
```

#### Merging Branch to Main ###
```
$ git merge NAME
```

#### Adding Upstream to Local ###
```
$ git remote add upstream FORKED_PROJECT_URL
```

#### Making Forked Project even with Main Project ###
```
$ git fetch --all --prune

$ git checkout main

$ git reset --hard upstream/main

$ git push origin main
```

#### OR

```
$ git pull upstream main

$ git push origin main  
```