# GIThelp
a list of all of my help documents for git!

handy tutorial:        http://vallandingham.me/Quick_Git.html

you have to make a fork before you can suggest a change to someone's code:
make a fork:           https://help.github.com/articles/fork-a-repo/

keep fork up-to-date:  https://help.github.com/articles/syncing-a-fork/

pull request:          https://help.github.com/articles/using-pull-requests/

when using git from a new computer, you have to authenticate it:
generating ssh key:    https://help.github.com/articles/generating-ssh-keys/

make commits often, then push code when things work out

##########################################################################
IF HTTP error on push:

go into .git/config file and change remote 'origin' from:
url=https://MichaelDrogalis@github.com/derekerdmann/lunch_call.git 

to:
url=ssh://git@github.com/derekerdmann/lunch_call.git
It works!  Do not forget the "git" before the "@".

###########################################################################
