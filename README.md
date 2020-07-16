# helpful-commands
Just a place to store useful bash / git / etc. commands

### Bash

##### Awesome terminal command line costumization tool:
`http://bashrcgenerator.com/`

##### See all active ports on linux machine
`sudo ss -tulwn | grep LISTEN`

##### Kill a running port on linux machine
`sudo fuser -k 8000/tcp`

##### Edit bashrc for constant commands and shell variables
`nano ~/.bashrc `

----

### Git

##### new local branch
`git checkout -b <branch_name>`

##### Add local branch to remote
`git push -u origin <branch_name>`

##### Push local changes to remote
`git push`

##### Push FORCE local changes to remote
`git push -f`

##### Reset and delete non-staged files
`git reset --hard`

##### Reset but keep non-staged files
`git reset --soft`

##### Log of local references
`git reflog`

##### Squash together n commits
`git rebase -i HEAD~<n-1>`

##### Rebase to current master
`git rebase origin/master`

##### Stash unstaged changes
`git stash save`

##### Recover stashed changes
`git stash apply`

##### Clear stash
`git stash drop`

##### Rename branch
`git branch -m <old_name> <new_name>`

----
#### Docker

##### List running docker containers
`docker ps`

##### Follow docker container log
`docker logs --follow <container_name>`

----
#### MongoDB

##### Connection
`mongo --username <username> --password <password> --authenticationDatabase admin`

##### Allow querries on slave db
`rs.slaveOk()`

----
### SSH
##### Connect so ssh server
`ssh <username>@<machine>`
