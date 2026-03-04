# Learning git
this reposity is used for learning to use git and github

learning to make change, stage change and commit

testing branch!

# Basic git commands

`git clone <ssh/url>` -> clone a reposity into your local machine.  
`git status` -> tell which files have been modified, add, or deleted since the last commit.  
`git branch` -> create, list, delete, or switch branch.  
`git log` -> show commit log.  
`git diff` -> show difference between current state of your file and the last commit.  
`git add .` -> stages changes for commit.  
`git commit -m "your message"` -> for commit your change with message.  
`git push` -> sends your committed changes to a remote repository stored on GitHub.  
!try not to push into main branch!  
`git pull` -> fetch changes from a remote repository and merges into your local branch.  
`git checkout <branch-name>` -> change branch to that branch-name.  
`git switch -c <branch-name>` -> create and change into that branch-name.  
`git commit -a -m "your message"` -> auto stages all change and make a commit.  
`git push origin <branch-name>` -> push change into remote repository.  
`git checkout main` -> change branch to main.  
`git merge <branch-name>` -> merge local branch into local main if need change for remote reposity use `git push`.  
`git push origin -d <branch-name>` -> delete branch from remote repository.  
`git branch -d <branch-name>` -> delete branch from local machine.  
  
## Workflow
when you wanna change something first you make a new branch.  
`git branch <new_branch>` to create a branch or `git switch -c <new_branch>` to create and switch into new branch.  
when you finish changing anything use  
`git commit -a -m "your message"` to auto stages change and commit  
but if you make new files and git don't know about it you must manually stage it by using  
`git add .`  
after commit your change use  
`git push origin <branch-name>` to push a new branch into browser.  
then checkout to main and merge branch by use  
`git merge <branch-name>` to merge a branch with main locally.  
then push to update remote repository  
`git push`  
then you need to delete closed branch from remote repository by  
`git push origin -d <branch-name>`  
then delete closed branch from your local machine by  
`git branch -d <branch-name>`  
then your workflow is finished
