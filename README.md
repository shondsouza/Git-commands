# Git Commands

## Setup and Configuration
 ``` - git config --global user.name "Your Name" ``` 
  Set the username for Git globally.
- ```git config --global user.email "you@example.com"```  
  Set the email for Git globally.
- `git config --list`  
  View all Git configuration settings.
- `git config --global color.ui auto`  
  Enable color highlighting in the Git command-line interface.

## Starting a New Repository
- `git init`  
  Initialize a new Git repository.
- `git clone <repository-url>`  
  Clone an existing repository from a URL.

## Basic Snapshotting
- `git add <file>`  
  Stage a file for commit.
- `git add .`  
  Stage all changes in the current directory for commit.
- `git commit -m "commit message"`  
  Commit staged changes with a message.
- `git commit --amend`  
  Amend the previous commit.

## Branching and Merging
- `git branch`  
  List all branches in the repository.
- `git branch <branch-name>`  
  Create a new branch.
- `git checkout <branch-name>`  
  Switch to a specific branch.
- `git checkout -b <branch-name>`  
  Create and switch to a new branch.
- `git merge <branch-name>`  
  Merge a branch into the current branch.
- `git branch -d <branch-name>`  
  Delete a branch locally.

## Stashing
- `git stash`  
  Temporarily save changes not ready to be committed.
- `git stash pop`  
  Reapply stashed changes and remove them from the stash.
- `git stash apply`  
  Reapply stashed changes without removing them from the stash.
- `git stash list`  
  List all stashed changes.
- `git stash drop`  
  Remove a specific stash.

## Remote Repositories
- `git remote add <name> <url>`  
  Add a remote repository.
- `git remote -v`  
  View remote repositories.
- `git fetch <remote>`  
  Fetch updates from a remote repository.
- `git pull <remote> <branch>`  
  Fetch and merge updates from a remote branch.
- `git push <remote> <branch>`  
  Push changes to a remote branch.
- `git push -u <remote> <branch>`  
  Push changes and set the upstream branch for future pushes.

## Viewing History
- `git log`  
  Show commit history.
- `git log --oneline`  
  Show a compact commit history.
- `git log --graph --oneline --all`  
  Show a graphical representation of the commit history.
- `git show <commit>`  
  Show details of a specific commit.

## Inspecting Changes
- `git status`  
  Show the working tree status.
- `git diff`  
  Show changes not staged for commit.
- `git diff --staged`  
  Show changes staged for commit.

## Undoing Changes
- `git reset <file>`  
  Unstage a file.
- `git reset --hard`  
  Reset working directory and staging area to the last commit.
- `git reset --soft HEAD~1`  
  Undo the last commit but keep changes staged.
- `git revert <commit>`  
  Create a new commit to undo changes from a specific commit.

## Tagging
- `git tag`  
  List all tags.
- `git tag <tag-name>`  
  Create a new tag.
- `git tag -a <tag-name> -m "message"`  
  Create an annotated tag.
- `git push <remote> <tag-name>`  
  Push a specific tag to a remote repository.

## Collaborating
- `git pull`  
  Fetch and integrate changes from a remote repository.
- `git push`  
  Push changes to a remote repository.
- `git fetch`  
  Download changes from a remote repository without merging.

## Advanced Operations
- `git rebase <branch>`  
  Reapply commits on top of another branch.
- `git cherry-pick <commit>`  
  Apply changes from a specific commit.
- `git bisect`  
  Start a binary search to find the commit that introduced a bug.

## Cleaning Up
- `git clean -f`  
  Remove untracked files.
- `git clean -fd`  
  Remove untracked files and directories.
