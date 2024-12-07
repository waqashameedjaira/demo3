# demo3


- step1: created a repo on hithub account
- step2: created a same name folder in local in your pc.
- step3: create my file in that folder for versioning.
    -   eg: 'echo' # git-demo-again" >> README.md'
- step4: initialize git in your local folder
    -   eg: 'get init'
- step: to checkthe status (untracked - 'red'/track file - 'green') of your github repo
    eg: 'git status'
- step6: to move file from untrack files to trank files
    -eg: 'git add .' OR 'git add -A'(add all files into tracking)
    -eg: 'git add <file-name> (add only specific file to tracking)
    -eg: 'git add *.csv' (add only specific files)
    -let suppose you want to move file from tracking to untracking again (ticket wapis krdo)
        - 'git rm --cached <file>

- step7: to move file ready to push we do commit (send to airport) 
    eg: 'git commit -m' "any meaningful comment"

- step8: to rename the branch from "master" to "main"
    eg: "git branch -M main"
- step9: to set the origin for your local repo for github repo (traveling destination)
    eg: 'git remote add orgin https://github.com/waqashameedjaira/demo3.git'
- step10: to push file from local to github repo (in flight from KHI to ISL)
    eg: 'git push -u origin main'

## second time

- git add .
- git commit -m "any message"
- git push


adding new thing

## Branching

- step01: to check on which branch you're 
    - eg: 'git branch'
- step02: to move and create new branch
    -eg: 'git checkout -b task/development-branch'
    -if branch already exist eg: 'git checkout <branch-name>'

## upstreaming remote & local branch

task/development-branch
	-branching code push

pull request to balance
	main & task/development-branch
	NOTE: pull request always balance git remote branches

Now if we want to balance lOCAL main & task/development-branch
	- git chechout main
	- git pull (to take the code from git MAIN branch)