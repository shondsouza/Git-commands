# Git Commands

_A list of my commonly used Git commands_

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git init` | Initialize a local Git repository |
| `git clone <repository-url>` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | Check the status of your working directory |
| `git add <file>` | Add a specific file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes with a message |
| `git commit --amend` | Amend the previous commit |
| `git rm -r <file>` | Remove a file or folder |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch <branch-name>` | Create a new branch |
| `git branch -d <branch-name>` | Delete a branch |
| `git checkout -b <branch-name>` | Create a new branch and switch to it |
| `git checkout <branch-name>` | Switch to a specific branch |
| `git merge <branch-name>` | Merge a branch into the current branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash pop` | Apply the latest stash and remove it from the stash |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin <branch-name>` | Push a branch to your remote repository |
| `git push -u origin <branch-name>` | Push changes and set upstream branch |
| `git pull` | Fetch and merge updates from the remote repository |
| `git pull origin <branch-name>` | Pull changes from a specific remote branch |
| `git remote add origin <repository-url>` | Add a remote repository |
| `git remote -v` | View remote repository details |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View commit history |
| `git log --oneline` | View a simplified commit history |
| `git log --graph` | View a visual graph of the commit history |
| `git diff` | Show unstaged changes in the working directory |
| `git diff <source-branch> <target-branch>` | Compare changes between branches |
