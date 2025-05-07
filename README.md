# Demo 2

Run below command to initaite new repo :
git init

git add .

Since this repo is created and not with any reference, we can't do git push

We create a repo on github UI and then create a remote connection:
git remote add origin sshlink

To check the current remote status use below command:
git remote -v

to see all the branched present :
git branch 

To create a new branch :
git checkout -b feature-readme-instructions

To move to a particular branch :
git checkout feature-readme-instructions

To set upstream :
git push -u origin feature-readme-instructions

To get changes made to local environment :
git pull -u origin main

to delete the branch :
git branch -d feature-readme-instructions

TO get the branch commited id:
git log

To revert the branch :
git reset committedid
