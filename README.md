This repo is made from the terminal of my computer.

Assumes a folder is to be converted into a git repo. 

. is assumed to be the root folder of the soon-to-be repo

Here are the commands needed.


`git init` <- this creates a local repo in the folder

add,.commit like normal

*If you try to push now, you'll see that the repo have no upstream branch*


test the `gh` command, you might need to authenticate (it was easy! :) )

`gh repo create NAMEOFTHEREPO --public --source=. --remote=upstream`

You should get verification that the repo is created


Lastly we need to push our commits from before. In order to do that we need to set our upstream

`git push --set-upstream upstream master`


Now you have a repo, created from the terminal
