# GIThelp
a list of all of my help documents for git!

handy tutorial:        http://vallandingham.me/Quick_Git.html

make a fork:           https://help.github.com/articles/fork-a-repo/
keep fork up-to-date:  https://help.github.com/articles/syncing-a-fork/
pull request:          https://help.github.com/articles/using-pull-requests/

generating ssh key:    https://help.github.com/articles/generating-ssh-keys/
help making pushes:    http://guides.railsgirls.com/github/
general commands:      https://na1.salesforce.com/help/pdfs/en/salesforce_git_developer_cheatsheet.pdf



##########################################################################
IF HTTP error on push:

go into .git/config file and change remote 'origin' from:

url=https://MichaelDrogalis@github.com/derekerdmann/lunch_call.git 

to:

url=ssh://git@github.com/derekerdmann/lunch_call.git

It works!
Do not forget the "git" before the "@".

###########################################################################
