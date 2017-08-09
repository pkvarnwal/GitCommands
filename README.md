### List of Git commands

* git status : To check status
* git add . : To add all files
* git add File : To add specific file
* git commit -m "Desc" : To commit added files
* git push origin branch : To push branch on github
* git pull origin branch : To pull branch from github
* git log --pretty=oneline : Show all branch commits and its message.
* git config credential.helper store : To store username and password for specific git project
* Recover from git reset --hard HEAD : 
+	i. git fsck --lost-found
+	ii. cd .git/lost-found/
+	iii. recover form here 

* git checkout -b <branchname> : Create a new branch and switch to it
* git checkout <branchname> : Switch to a specific branch
* git push --all origin : Push all branches to your remote repository.
* git diff : To show changes in all files.
* git diff --base <fileName> : To show changes in specific file
