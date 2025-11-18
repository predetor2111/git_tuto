git init - powers your folder to be managed by git , and initialize new empty repo. It also create .git folder that has all the relevant logic to manage version of your project.

working area - there can be bunch of files that cannot be handled by git, bunch of untracked files

staging area - what all files are going to be part of the next version that we will create

repository area - this area actually contains the details of all the previous registered versions. and the files in this area, git already manages them and knows their versions history

git add <file> - add files from working area to staging area

git rm --cached <file> - remove files from staging area and bring back to untracked files i.e.working area

git commit - i -> (write comment) -> esc -> :wq

git log - list down all the commits to the repository.

git restore <file> - remove all file changes from the working area / LAST COMMIT it gives.

git restore --staged <file> - it removes file changes from staging area to the working area. this works only if the changes are in staging area

Diff between git rm and git restore
ans: if you want to move whole file back to the untracked files, then we do git rm, otherwise if we just want the changes to be moved in working area or staging area then we do git restore

git commit -m "your commit message" - if we dont want vim editor to opened

git remote - list down all the connection names

Remote connections - it helps you to link two git repositories for uploading and downloading changes from each other

git remote add <name of remote conn> <link of the remote> - add a new remote connection

git remote rm <name of the remote> - this command deletes the remote connection

git remote rename <oldname> <newname> -
note : the name of the remote connection is always used to establish communication between the repository

git push <name of the connection> <name of the branch> - push the changes from local to remote

git pull origin master - download latest changes from the branch of the mentioned remote in your local machine

git add <file1> <file2> <file3>

git add .
