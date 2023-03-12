# Git-demo
Going through git essentials commands and adding a file with a summary of each of them .Well it seems funny right .Hell YEAH, LET'S D THIS 

## The first command mostly used locally will be below this header
***
**To initialise the repository** use git init 
eg : git init 
This will allow git to be able to track change in this repo.

To add files to git allowing tracking, use the command git add with one of the following argument.
1. [ ] Argument A
git add <filename>
eg : git add myfile1.txt
this will instruct  git to add the file to the local staging area  
1. [ ] Argument B
ed : git add . 
Here the dot (.) means all files that were created and not tracked should be added to the local staging area for tracking.

To commit or move the changes to your staging area, use git commit. While using git commit you would have to use a comment to allow easy tracking of your changes 
ed : git commit -m "message to commit"
The above line would commit all changes to the branch with the message "message to commit".

to create a branch use git checkout -b <branchname>
eg: git checkout -b myfeature/GHOST-123456

to display the list of branches use git branch 
eg : git branch

to switch between branches , use git checkout 
eg : git checkout <branchname>
git checkout mynewbranch

to check the difference between branches use git diff <branchname>
eg: git diff myfeature/GHOST-123456

to delete a branch use git branch -d <branchname>
eg : git branch -d myfeature/GHOST-123456

