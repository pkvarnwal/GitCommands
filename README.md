### List of Git commands

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
