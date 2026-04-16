<!-- first check git is installed  -->

git --version

<!-- Then create folders

Then create User profile -->

git config --global user.name "Sachin"
git config --global user.email "sachin@gmail.com"

<!-- Then change the master to main  -->

git branch -m master main

git branch

git status

<!-- Then create repo using  -->

git init

<!-- Then Add file  -->

git add Hello.js

git add.

<!-- Then commit changes -->

git commit -m "Files Added"


<!-- Go back to previous commit -->

git checkout code

<!-- Go back to main branch agian -->

git checkout main


<!-- Create Repositiories on github -->

git remote add origin repo link

<!-- Push local repo to github -->

git push -u origin main

<!-- Create new branch -->

git branch name

<!-- To change branch  -->

git checkout branch-name

<!-- Create and jump to new branch -->

git branch -b branch-name


<!-- Create branch with specified branch -->

git branch branch-name source-branch

This is from dev 1


This is from the dev 2


To resolve merge conflicts we need to go to main branch and pull the code to local repo

Then we need go to our branch

Then merge main to your branch

resolve the code and add and commit and push