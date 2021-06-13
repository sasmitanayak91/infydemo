```
git config --global user.email "<emailid>"
git config global user.name "<usrname>"
ssh-keygen -t rsa -b 4096 -C "<emailid>"
```

then give the default options and key will be stored in your local path
copy that key and add that ssh key in github site settings
this ssh key helps to connect your local machine to interact with your github server


`git remote -v` -> To check Remote repository

`git clone <ssh url from github repo>`  -> To clone from remote repo to local server

`git status` -> to know the status of files

`git add *` -> to add the workspace items into idex area

`git commit` -> to push the indexed items to local server

`git reset <filename>` -> To move back indexed items to workspace

`git push <repo> <branch>` -> To move the committed items from local server to remote server

`git pull` -> to move committed items froms remote to local server

