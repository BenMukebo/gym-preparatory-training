# General recap

## grid_css_recap

## Git Commands

- Branches:

```bash
$ git branch # list all local branches
$ git branch -a # list all local and remote branches
$ git branch <branch_name> # create new branch
$ git swich <branch_name> # switch to branch git-command
$ git checkout -b <branch_name> # create and switch to branch
$ git checkout <branch_name> # switch to branch
```

- Add & Commit
  
```bash
$ git add <file_name> # add file to staging area
$ git add . # only add all file from current directory to staging area
$ git add -A # add all files to staging area
$ git commit -m "commit message" # commit staged files
$ git commit -a -m "commit message" # add and commit all files but it never work for new files OR
- git commit -am "commit message" 
```

- Undo Add & Commit

```bash
$ git reset HEAD~ # undo last commit but keep changes OR 
$ git reset HEAD~2
$ git revert HEAD # Create a new commit that undoes all of the changes made in the most recent commit
$ git revert <commit_hash> # Create a new commit that undoes all of the changes made in <commit_hash>, then apply it to the current branch.
```