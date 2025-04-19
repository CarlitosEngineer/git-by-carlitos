
### 02 - Commands List

| Command                                   | Description                                                       |
| :---------------------------------------: | :---------------------------------------------------------------- |
| `git branch nameNewBranch`                | Creates a new branch                                              |
| `git branch`                              | Lists all local branches                                          |
| `git branch -a`                           | Lists all branches (local and remote)                             |
| `git branch -r`                           | Lists remote branches                                             |
| `git branch -l`                           | Lists local branches                                              |
| `git checkout`                            | Switches to the specified branch                                  |
| `git checkout -b new-branch-name`         | Creates and switches to a new branch                              |
| `git checkout nameBranch`                 | Switches to the named branch                                      |
| `git checkout develop`                    | Switches to the 'develop' branch                                  |
| `git remote -v`                           | Views the remote repository origin                                |
| `git log --oneline`                       | Views the latest commit                                           |
| `git log --oneline -5`                    | Views the last 5 commits                                          |
| `git clone <URL>`                         | Clones a repository from the URL                                  |
| `git remote add origin <URL>`             | Links a local repository with a remote repository                 |
| `git push origin <branch>`                | Pushes changes from a local branch to the remote repository       |
| `git pull origin <branch>`                | Pulls and merges changes from the remote to your local branch     |
| `git push --set-upstream origin <branch>` | Pushes a new branch not yet in the remote repository              |
| `git reset --hard HEAD`                   | Restores to the latest commit in the current branch               |
| `git merge <feature-branch>`              | Merges a branch (e.g., `feature/update-project-settings`)         |
| `git pull origin develop`                 | Updates the current branch with changes from 'develop'            |
| `git push origin develop`                 | Pushes changes to the 'develop' branch in the remote repository   |
