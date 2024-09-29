
# Git Useful commands
---
# Installing Git on Ubuntu
    sudo apt install git

# How to clone a repo
    git clone <git@github.com/someone/repo-name.git>

# Basic commands
## Converting any folder to git repo
    git init .

## Track your changes
Changes are not tracked by git by default
To add your changes

    git add -A

This will track newly created, modified and deleted files
You can do this multiple times before a commit

**NOTE**:**CAUTION**!!!,<br/> To **remove** a **file** from directory permanently

    git rm "filename"

## To check the status of your files

    git status

If everything is good,no leftover changes, no untracked files , 
everything should be in green.

## Commiting a change to git repo
To check which developer has made the change, git requires you 
to commit your changes.

    git commit -m "My first commit"

## To check commit history
To check the lore of git commit history 

    git log

## Reverting or undoing a commit
    git revert <first-7-hex-digits-of-commit>

## Pushing to a repo
    git push 

## Generating a patch
    git add -A
    git diff --staged > mygit_patch.patch

## Applying a patch
    git apply mygit_patch.patch



# Advanced Commands

