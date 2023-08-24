### List of Git commands

* Git installer : Download the Git installer for Mac/Linux/Windows and follow the prompts to install Git
* git --version: Open a terminal and verify the installation was successful by typing git --version
  + $ git --version
git version 2.9.2
* git config --global user.name "Prinsu Kumar":
* * git config --global user.email "pkvarnwal@gmail.com" Configure your Git username and email using the following commands, replacing Prinsu's name with your own. These details will be associated with any commits that you create:
  * git clone https://github.com/pkvarnwal/GitCommands.git: Copy the repo link and paste it on your terminal with git clone repo, then press enter.
  * git init: To initialise the repo. 
* git status : To check status
* git add . : To add all files
* git add FilePath : To add specific file
* git commit -m "Desc" : To commit added files
* git push origin branch : To push branch on github
* git pull origin branch : To pull branch from github
* git log --pretty=oneline : Show all branch commits and its message.
* git config credential.helper store : To store username and password for specific git project
* Recover from git reset --hard HEAD : 
+	i. git fsck --lost-found
+	ii. cd .git/lost-found/
+	iii. recover form here 

* git checkout -b branchname : Create a new branch and switch to it
* git checkout branchname : Switch to a specific branch
* git push --all origin : Push all branches to your remote repository.
* git diff : To show changes in all files.
* git diff --base <fileName> : To show changes in specific file
* git push --tags origin : Push all tags to remote repository.
* git info : Show information about repo.
### rm all files
* git rm -r --cached .
### add all files as per new .gitignore
* git add .
### now, commit for new .gitignore to apply
* git commit -m ".gitignore is now working"

### Git push rejected
* git fetch
* git rebase dev
* git push origin dev

### Ignore files that have already been committed to a Git repository
* git rm -r --cached .
* git add .
* git commit -m ".gitigonre is now working"

### To count number of commits
* git count conflict commit

### To install git extras command in mac
* brew install git-extras
