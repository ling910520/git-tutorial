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

