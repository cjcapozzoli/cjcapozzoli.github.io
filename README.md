# Making a Personal Website using Github Readme

## Steps:
Make # cjcapozzoli.github.io (must match username)
When you make a new repository on github, it will make you set the origin as that repository using git init.
need index.html
Go to Settings, Code and Automation, Pages, and select "Deploy from a branch", then select a branch.


## Making changes:
in the terminal:

$ cd \<directory to local files>

use . for all new files, or just put \<filename> for a specific file
$ git add . 

when you're ready to put all the changes to a version:
$ git commit -m "\<name of commit- anything>"

to release this version to the world:
$ git push origin main
where main is the branch we are on for now, and origin is the source we are releasing to
or 
$ git push

you will need to put your github username, and **personal token** for the password

check the website!!!

## notes:
Switching users:

$ git config --global user.name "cjcapozzoli"
$ git config --global user.email "\<youremail\@email.com>"
When pushing, you will be asked for your person token.
