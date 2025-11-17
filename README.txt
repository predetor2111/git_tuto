git init - powers your folder to be managed by git , and initialize new empty repo. It also create .git folder that has all the relevant logic to manage version of your project.


working area - there can be bunch of files that cannot be handled by git, bunch of untracked files

staging area - what all files are going to be part of the next version that we will create

repository area - this area actually contains  the details of all the previous registered versions. and the files in this area, git already manages them and knows their versions history 

git add <file> - add files from working area to staging area

git rm --cached <file> - remove files fro  working area to staging area

git commit - i -> (write comment) -> esc -> :wq 

git log - list down all the commits to the repository

git restore <file> - remove all file changes from the working area.

git restore --staged <file> - bring back file from staging to working area then do git restore
