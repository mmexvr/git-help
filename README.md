#  Git commands

### tldr

- `git init`
- `git fetch`
- `git branch`
- `git checkout -b new_branch_name`
- `git checkout branch_name`
- `git add .` or `git add file_name`
- `git commit`
- `git push`

## Guide

### Start a git repository
1. run `git init` to create a 

### Fetch latest
1. Fetch the latest from the current repository by running `git fetch`
2. If you want to clean up old branch that have been merged and deleted `git fetch --prune`

### Create a new branch
1. Look at what branch you are on with `git branch` command
2. Checkout a new branch based on the one you are on `git checkout -b new_branch_name`. `-b` flags stands for branch

### Checkout from origin/local
1. To checkout out a already existing branch you run the command `git checkout branch_name`, that will automatically set up-stream for a branch if the branch exist on orgin

### Commit
1. First you have to stage all files for commit but running either `git add .` for all fiels or `git add file_name`
2. Run `git status` to see all the staged changes
3. When everything looks good, you can run the command `git commit `

### Push
1. `git push --set-upstream branch_name`
