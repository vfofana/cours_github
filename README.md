# Cours GitHub Ada

Premier fichier ajouté à Git.

Deuxième commit du cours pour apprendre la commande `git pull`.

Premier commit dans la branche `premiere_branche`

Apprendre à faire une pull request

Modification pour le rebase
Modification pour le rebase numero 2

Commit squash 1
Commit squash 2
Commit squash 3
1er commit dans la branche pycharm

### Description: Git add

The git add command stages changes (modified, new, or deleted files) to be committed in Git. It moves files from the working directory to the staging area, preparing them for a commit.

`git add <file-name>` : Stages a single file for commit.

`git add <file1> <file2>` :  Stages multiple specified files.

`git add .` : Stages all changed and new files in the current directory and subdirectories.


### Description: Git branch

`git branch` : List all local branches

`git branch -a` : List all local & remote branches

`git branch <branch-name>` : Create a new branch

`git branch -d <branch-name> ` : Delete a branch (Use -D to force delete)


### Description: Git commit

Saves staged changes to the repository's history.

`git commit -m "Your commit message"` : Commit staged files with a message:

`git commit` : Commit with a detailed message (Opens a text editor to write a detailed commit message)

`git commit --amend` : Amend the last commit (Modifies the last commit message or includes additional changes)

### Description: Git push

Sends committed changes to a remote repository.

`git push origin <branch-name>` : Push the current branch to remote:

`git push --all origin` : Push all branches

`git push --set-upstream origin <branch-name>` : Push and set upstream (track remote branch)

### Description: Git pull

Fetches and merges changes from a remote repository.

`git pull origin <branch-name>` : Pull changes from the remote branch

`git fetch origin` : Fetch latest changes without merging (Useful when you want to review changes before merging)

Description: Combines changes from different branches.

`git merge <branch-name>` : Merge another branch into the current branch

`git merge --abort` : Abort a conflicted merge (If a merge conflict occurs and you want to cancel it)

### Description: Git checkout 

Switches between branches or restores files.

`git checkout <branch-name>` : Switch to another branch (In newer Git versions, use git switch <branch-name> instead)

`git checkout -b <new-branch-name>` : Create and switch to a new branc

`git checkout -- <file-name>` : Restore a file to the last committed state

### Description: Git stash 

Temporarily saves changes without committing them.

``git stash`` : Stash changes (Saves changes and reverts working directory to the last commit)

``git stash list`` : List all stashed changes

``git stash apply`` : Apply the last stashed changes

``git stash pop`` : Apply and remove the last stash

``git stash clear`` : Clear all stashes
