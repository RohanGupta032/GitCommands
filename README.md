# GitCommands

This document for git commands is self learing from Intuit Project which may be used differently in other project.

First you need to create a new repository in github.
After that copy the path of the project that needs to be cloned.
Create  a local folder to clone the project. Open git bash from the folder location . Git bash command line is best.
First command :- git init :-It will initialize git.

Setting of origin and remote is imporatnt.
it remote add upstream git@github.intuit.com:SBG-Plugins/qbdt-payroll-ews-ui.git
git remote add origin https://github.com/RohanGupta032/Java8.git (origin isthe forked local project)

We can check the above origin and upstream by below comamands.
git remote -v  : - we can check Same repository stored in internet.

git fetch upstream  :- The git fetch command to SEE downloads commits, files, and refs from a remote repository into your local repo.
git pull upstream branch-name :- It does more than fetch and downloads the changes.


git branch :-to check the available branches. Also this can be used to create the branch.
git checkout :- to switch to the branch.

git push origin branch-name
git push -f  origin branch name :- to force commit.
git pull --rebase origin behind-apigw
git add -:- will add the file to the staging area/index.
git status:-see what is there in staging area ,need to check the existing status before pulling latest files from server
git commit -m “” :- Go ahead and commit , it will put into local repository.
git push :- push from local repository to remote repository.
Git pull 
git rm - -cached  
git clone :- to download .
git branch -v
git pull upstream behind-apigw
git stash 
git stash pop
git remote show origin
git remote show upstream
git pull upstream ibp2-plugins-migration
git push origin
git push —set-upstream origin behind-apigw
git reset -hard
git rebase upstream/master :-to Update master
git remote -v 
git fetch origin
git remote rm upstream

Git branch -d branch name .

git reset --hard HEAD^ 

Intuit github origin and upstream examples

Upstream : git@github.intuit.com:SBG-Plugins/qbdt-payroll-ews-ui.git
Origin:-       git@github.intuit.com:rgupta25/qbdt-payroll-ews-ui.git


