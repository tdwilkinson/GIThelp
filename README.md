# GIThelp
a list of all of my help documents for git!
-handy tutorial:        http://vallandingham.me/Quick_Git.html

Set up git repository from local computer by typing this in a terminal:
>>> git clone 'https://github.com/tdwilkinson/stellar-analysis.git'

You have to make a fork before you can suggest a change to someone's code:
-make a fork:           https://help.github.com/articles/fork-a-repo/
-keep fork up-to-date:  https://help.github.com/articles/syncing-a-fork/

Make commits often, then push code when things work out.
Make sure local files are up-to-date with online files:
>>> git pull
-pull request help:          https://help.github.com/articles/using-pull-requests/

After making edits to local file, add it to files to be pushed, add commit comments, and push to online files:
>>> git add stellar_analysis.py
>>> git commit -m 'added some stuffs'
>>> git push

When using git from a new computer, you have to authenticate it:
-generating ssh key:    https://help.github.com/articles/generating-ssh-keys/
##########################################################################
IF HTTP error on push:

go into .git/config file and change remote 'origin' from:
url=https://MichaelDrogalis@github.com/derekerdmann/lunch_call.git 

to:
url=ssh://git@github.com/derekerdmann/lunch_call.git
It works!  Do not forget the "git" before the "@".

###########################################################################
