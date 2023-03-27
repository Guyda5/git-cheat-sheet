Git Cheat Sheet
This cheat sheet provides a quick reference guide for common Git commands.

Basic Commands
git init: Initialize a new Git repository
git add <file>: Add a file to the staging area
git add .: Add all files to the staging area
git commit -m "commit message": Commit changes to the local repository with a message
git status: Show the status of the repository
git log: Show the commit history
git clone <url>: Clone a repository from a remote server
Branching Commands
git branch: List all local branches
git branch <branch name>: Create a new branch
git checkout <branch name>: Switch to a different branch
git merge <branch name>: Merge a branch into the current branch
git branch -d <branch name>: Delete a branch
Remote Commands
git remote add <name> <url>: Add a new remote repository
git push <remote> <branch>: Push changes to a remote repository
git pull <remote> <branch>: Pull changes from a remote repository
git fetch <remote>: Fetch changes from a remote repository
Undoing Changes
git reset <file>: Unstage a file
git reset --hard: Discard all changes in the working directory and the staging area
git revert <commit>: Revert a commit
git checkout <file>: Discard changes in a file
Miscellaneous Commands
git diff: Show the differences between the working directory and the staging area
git tag <tag name>: Create a new tag for a commit
git blame <file>: Show who made changes to a file and when they were made
git stash: Save changes to a temporary area so you can switch branches without committing
Feel free to use this cheat sheet as a quick reference guide for your Git commands. If you have any suggestions or corrections, please feel free to submit a pull request or issue.
