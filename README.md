# Git Cheat Sheet

## **Basic Commands**
| Command                           | Description                                      |
|-----------------------------------|--------------------------------------------------|
| `git init`                        | Initialize a new Git repository.                |
| `git clone <url>`                 | Clone a repository from a URL.                  |
| `git status`                      | Show the working tree status.                   |
| `git add <file>`                  | Add file(s) to the staging area.                |
| `git add .`                       | Add all changes to the staging area.            |
| `git commit -m "message"`         | Commit changes with a message.                  |
| `git push origin <branch>`        | Push changes to the remote repository.          |
| `git pull origin <branch>`        | Pull the latest changes from the remote branch. |
| `git branch`                      | List all branches.                              |
| `git branch <name>`               | Create a new branch.                            |
| `git checkout <branch>`           | Switch to a specific branch.                    |
| `git checkout -b <branch>`        | Create and switch to a new branch.              |
| `git merge <branch>`              | Merge a branch into the current branch.         |

---

## **Undoing Changes**
| Command                                | Description                                      |
|----------------------------------------|--------------------------------------------------|
| `git reset --soft HEAD~1`              | Undo last commit, keep changes in staging.      |
| `git reset --mixed HEAD~1`             | Undo last commit, keep changes in working dir.  |
| `git reset --hard HEAD~1`              | Undo last commit, delete all changes.           |
| `git checkout -- <file>`               | Discard changes in a file.                      |
| `git revert <commit>`                  | Create a new commit to undo a previous one.     |

---

## **Working with Remotes**
| Command                                | Description                                      |
|----------------------------------------|--------------------------------------------------|
| `git remote -v`                        | Show remote URLs.                               |
| `git remote add origin <url>`          | Add a remote repository.                        |
| `git push -u origin <branch>`          | Push branch and set upstream.                   |
| `git fetch`                            | Download changes without merging.               |

---

## **Viewing History**
| Command                                | Description                                      |
|----------------------------------------|--------------------------------------------------|
| `git log`                              | View commit history.                            |
| `git log --oneline`                    | View a compact commit history.                  |
| `git diff`                             | Show changes between commits or working state.  |
| `git show <commit>`                    | Show details of a specific commit.              |

---

## **Stashing Changes**
| Command                                | Description                                      |
|----------------------------------------|--------------------------------------------------|
| `git stash`                            | Save changes without committing.                |
| `git stash list`                       | List all stashed changes.                       |
| `git stash apply`                      | Apply stashed changes without removing them.    |
| `git stash pop`                        | Apply and remove stashed changes.               |

---

## **Tagging**
| Command                                | Description                                      |
|----------------------------------------|--------------------------------------------------|
| `git tag <tagname>`                    | Create a new tag.                               |
| `git tag`                              | List all tags.                                  |
| `git push origin <tagname>`            | Push a tag to the remote repository.            |
| `git push origin --tags`               | Push all tags to the remote repository.         |

---
