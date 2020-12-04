## Introduction:
### Git Helps you manage your code by keeping track of your changes when you commit... and lets you rollback changes if you messed up!

#### First Download This Git Manager 
https://git-scm.com/download/

# Basics
```sh
# run this command from the folder u want to upload (required only once)
git init

# To add all the files we are about to commit !!.... (u can remove files in a text file that will pop up now)
git add .

# To commit all the files(u are commiting that your code is proper!! be sure ..it might hurt someone!)
git commit -m "edited this readme"
```
#### Now if You Want Manually ignore certain files ... like compiled .exe files
reference: https://labs.consol.de/development/git/2017/02/22/gitignore.html

#### Create a file with name .gitignore
```
*.exe
.gitignore
```

## You’ve now got a local git repository. You can use git locally, like that, if you want. 
## But if you want the thing to have a home on github, do the following.

##### Go to github.
##### Log in to your account.
##### Click the new repository button in the top-right. 
##### You’ll have an option there to initialize the repository with a README file, but I don’t.
##### Click the “Create repository” button.

```sh
#add(select) ur origin folder (this will select easy_github repo for me...yay!)
git remote add origin https://github.com/rayanfer32/easy_github

#push(upload) ur code !!! DONE
git push
```
# Modifying:
```sh
# if u want to download and modify existing repo then do this,
# origin will locate ur existing repo...
git remote add origin https://github.com/rayanfer32/programming

#do the basics again!! you will get used to it!!
`Basics`

#run this to finally push ur changes
git push

#git push -u origin master   #use this to specify git branch if u do so

#if u get this error
fatal: refusing to merge unrelated histories

#first clone(download) ur repo to ur computer
git clone https://github.com/rayanfer32/programming

#then do <modifying>
```

# Extras 
#### Show current remote location
```
git remote show origin
git remote show master
```
#### Removing a remote (i.e: repo in github)   
```
git remote remove origin
git remote remove master
```

# If You ever get struck somewhere,check this out!
## I learned the stuff from here!

https://kbroman.org/github_tutorial/pages/init.html

git pull --help

https://github.community/t5/How-to-use-Git-and-GitHub/How-to-deal-with-quot-refusing-to-merge-unrelated-histories-quot/td-p/12619

# Always remember to pull(sync) with the remote repo from the github before modifying it!!
