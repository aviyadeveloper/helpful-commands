# helpful-commands
Just a place to store useful bash / git / etc. commands

#### Bash

###### See all active ports on linux machine
`sudo ss -tulwn | grep LISTEN`

###### Kill a running port on linux machine
`sudo fuser -k 8000/tcp`

#### Git

###### Squash together n commits
`git rebase -i HEAD~<n-1>`
  
###### Stash unstaged changes
`git stash .`

###### Recover stashed changes
`git stash apply`

###### Clear stash
`git stash drop`
