# Git Commands

| Command                                                           | Description                                  |
| ----------------------------------------------------------------- | -------------------------------------------- |
| `git init`                                                        | _Initialize a local Git repository_          |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | _Create a local copy of a remote repository_ |

## Snapshots

| Command                            | Description                                         |
| ---------------------------------- | --------------------------------------------------- |
| `git status`                       | _Check status_                                      |
| `git add [file-name.txt]`          | _Add a file to the staging area_                    |
| `git add -A`                       | _Add all new and changed files to the staging area_ |
| `git commit -m "[commit message]"` | _Commit changes_                                    |
| `git rm -r [file-name.txt]`        | _Remove a file (or folder)_                         |

## Branching & Merging

| Command                                              | Description                                                |
| ---------------------------------------------------- | ---------------------------------------------------------- |
| `git branch`                                         | _List branches (the asterisk denotes the current branch) _ |
| `git branch -a`                                      | _List all branches (local and remote)_                     |
| `git branch [branch name]`                           | _Create a new branch_                                      |
| `git branch -d [branch name]`                        | _Delete a branch_                                          |
| `git push origin --delete [branch name]`             | _Delete a remote branch_                                   |
| `git checkout -b [branch name]`                      | _Create a new branch and switch to it_                     |
| `git checkout -b [branch name] origin/[branch name]` | _Clone a remote branch and switch to it_                   |
| `git branch -m [old branch name] [new branch name]`  | _Rename a local branch_                                    |
| `git checkout [branch name]`                         | _Switch to a branch_                                       |
| `git checkout -`                                     | _Switch to the branch last checked out_                    |
| `git checkout -- [file-name.txt]`                    | _Discard changes to a file_                                |
| `git merge [branch name]`                            | _Merge a branch into the active branch_                    |
| `git merge [source branch] [target branch]`          | _Merge a branch into a target branch_                      |
| `git stash`                                          | _Stash changes in a dirty working directory_               |
| `git stash clear`                                    | _Remove all stashed entries_                               |

## Updating

| Command                                                                           | Description                                                   |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| `git push origin [branch name]`                                                   | _Push a branch to your remote repository_                     |
| `git push -u origin [branch name]`                                                | _Push changes to remote repository (and remember the branch)_ |
| `git push`                                                                        | _Push changes to remote repository (remembered branch)_       |
| `git push origin --delete [branch name]`                                          | _Delete a remote branch_                                      |
| `git pull`                                                                        | _Update local repository to the newest commit_                |
| `git pull origin [branch name]`                                                   | _Pull changes from remote repository_                         |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git`     | _Add a remote repository_                                     |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | _Set a repository's origin branch to SSH_                     |

## Comparison

| Command                                    | Description                      |
| ------------------------------------------ | -------------------------------- |
| `git log`                                  | _View changes_                   |
| `git log --summary`                        | _View changes (detailed_)        |
| `git log --oneline`                        | _View changes (briefly)_         |
| `git diff [source branch] [target branch]` | _Preview changes before merging_ |

