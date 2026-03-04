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
