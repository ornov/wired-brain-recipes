### git config
Global setting
*git config --global --list*

Local setting
*git config --list*

### Initialize 
*git init*

### Status
*git status*
*git status -s* short version\

## Log
*git log*
*git log -<count of commit>*
*git log --oneline*
*git log --stat*
*git log --patch*

### Add
*git add <filename>*
*git add .*  All files

## Remove
*git rm <filename>* remove from everywhere
*git rm --cached <filename>* to keep in the working dir

## Rename
*git mv <current_filename> <new_filename>*

### Commit
*git commit -m "<COMMIT_MSG>"*
*git commit -a -m "<COMMIT_MSG>"* to add and commit

### Checkout 
*git checkout -- <file>...* to discard changes in the working directory

### Remote Origin Add
*git remote add origin <URL>*

###  Origin Push
*git push -u origin master*
*git push origin master*

### Diff
*git diff*
*git diff --staged*
*git diff --staged --no-renames*

### Branch
*git checkout -b new_branch* checkout to a new branch
*git checkout <branch_name>* checkout to an existing branch

### Branch Merge
*git merge <branch_name>* merge <branch_name> to master

##Reset
*git reset --soft* Repo to Index
*git reset --mixed* Repo to Working Dir
*git reset --hard* Repo to Trash
