# git-tutorial
repository for git tutorial

## git remove remote folder
1. remove folder and commit
2. push to remote folder


## switch to remote branch
- git checkout --track origin/daves_branch

## branching
git checkout -b "iss1" 5773  
git checkout -d "iss1"  

## git fetch
git fetch --all
git checkout origin/homeuse
git branch -b "iss1"
git checkout "homeuse"
git merge  "iss1"

## add origin
git remote add origin git://github.com/ling910520/file-monitoring
git push - u origin master

## resync with sources:
git fetch  
git reset --hard origin/master

## tracked newly created remote branch

git checkout --track origin/test1

##  Changing the Last Commit:
git commit --amend --no-edit

## git rebase
git rebase master
git rebase --continue

## git delete remote branch
git push -d origin test1

## git push branch to origin
- git push origin testfa
- git push --set-upstream origin testing-file

## view merge conflict
- git status

## clone without create a new folder
- git clone <repo_url> .

## reset url origin
- git remote set-url origin https://github.com/USERNAME/REPOSITORY.git

## Please commit your changes or stash them before you switch branches.
git reset --hard


## Checkout

git checkout --orphan latest_branch

Add all the files

git add -A

Commit the changes

git commit -am "commit message"

Delete the branch

git branch -D master

Rename the current branch to master

git branch -m master

Finally, force update your repository

git push -f origin master

PS: this will not keep your old commit history a
