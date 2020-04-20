# Git Basics
## Working Directory
* Area where all of our files and directories and changes are living all the time

## Staging Area
* Files and directories that we explictly add to the staging area

## Git Repository
* Where all our snapshots are stored

# Git Intermediate
## Adding multiple files of a certain type
* git add *.<filetype>

## Add all files in directory (including hidden)
* git add -A

## Removing files
* git reset HEAD <file>

## Ignoring files
* create .gitignore file
* add file names to ignore, 1 per line

# Git Branches
## Listing all branches
* git branch

## Adding a branch
* git checkout -b <branch_name>

## Changing branches
* git checkout <branch_name>

## Merging a branch
* git merge <branch_name>
* need to be working in the branch you want to other branch to be merged into

## Removing a branch
* git branch -d <branch_name>


         /--0--\
        /       \       
0------0----0----0