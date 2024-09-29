
# Git Useful commands
## Converting any folder to git repo
    git init .

## Commiting a change to git repo
    git add -A
    git commit -m "My first commit"

## Pushing to a repo
    git push 

## Generating a patch
    git add -A
    git diff --staged > mygit_patch.patch

## Reverting or undoing a commit
    git revert <first-7-hex-digits-of-commit>

## Applying a patch
    git apply mygit_patch.patch
