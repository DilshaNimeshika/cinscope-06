## this is for version controlling
## Step 01 : Create a repository github.com
## step 02 : create a folder in local machine
## step 03 : open the project folder in vs code
## step 04 : open the terminal in the vs code(bash/cmd/git bash)
## step 05 : check the git version
```bash
git -v
```
## step 06 : Initialize a git repo using 
```bash
git init
```
## step 07 : check the git status
```bash
git status
```
## step 08 : add files to the git using
```bash
git add .
```

## step 09 : commit the changes with the meaningful commit message
```bash
git commit -m "initial project commit "
```

## step 10 : check if there's any remote urls
```bash
git remote -v
```
## step 11 : add remote
```bash
git remote add origin git@github.com:<remote-url>
```

## step 12 : check if the remote url configured without issue
```bash
git remote -v
```

## step 13 : make sure the default branch is your main branch
```bash
git branch -M main
```

## step 14 : push the local commits to the remote/cloud branch
```bash
git push -u origin main
```

## step 15 : check if the changes are there in the remote

-----

## step 16 : do a file change

## step 17 : check the file change in vs code

## step 18 : check file change in the terminal using
```bash
git status
```

## step 19 : Repeat step 8

## step 20 : proper commit message
```bash
git commit -m "update the steps in documentation"
``

## step 21 : push the changes to existing branch
```bash
git push
```

## step 22 : create a new branch called "dev" from "main" branch
```bash
git checkout -b dev
```

## step 23 : publish the branch to remote "origin dev"
```bash
git push -u origin dev
```

## step 24 : Repeat step 8

## step 25 : Create a pull request from github and merge it to main


```bash
# Navigate between branches
git checkout main 
git checkout dev

# Check the changes/status between local and remote
git fetch

# Checkout to main branch
git checkout main

# Pull the changes to local from remote
git pull

git checkout

# Stash changes temporary
git stash

# Apply Stashed changes back
git stash apply

#Merge changes in dev branch to main

git checkout main

git merge dev

git status

git push


```










