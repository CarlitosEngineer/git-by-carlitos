# Learn Git with Carlitos

![Header](./src/resource/img/Header_00.webp)

# Z - Git Cheat Sheet (Hoja de Trucos de Git)

- **Listar** todas las ramas **local y remota** `git branch -a`

- **Crear** rama `git branch Name_Rama`
- **Cambiar** rama `git checkout Name_Rama`

- **Agregar** cambios `git add .`
- **Registrar** cambios `git commit -m "feat: agrega validación al formulario de login"`
- **Empujar** cambios `git push`

- **Unir** rama `git merge Name_Rama` then (Repository)
- **Marcar** version `git tag -a v1.0.0 -m "Versión 1.0.0"`

- **Borrar** rama **Local** `git branch -d Name_Rama`
- **Borrar** rama **Remoto** `git push origin --delete Name_Rama`

# áreas de trabajo - (ciclo de vida de los archivos en Git)

    Workspace (Working Directory)           Nothing

        Staging Area (Index)                add

            Repository (Local Repo)         commit

                Remote Repository           push

# 4 - Image Recommends (Imagenes Recomendadas)

# 3 - Commands List (Lista de comandos)

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
| `git log --oneline`                       | Views the latest commit                                           |
| `git log --oneline -5`                    | Views the last 5 commits                                          |
| `git clone <URL>`                         | Clones a repository from the URL                                  |
| `git remote -v`                           | Views the remote repository origin                                |
| `git remote add origin <URL>`             | Links a local repository with a remote repository                 |
| `git push origin <branch>`                | Pushes changes from a local branch to the remote repository       |
| `git pull origin <branch>`                | Pulls and merges changes from the remote to your local branch     |
| `git pull origin develop`                 | Updates the current branch with changes from 'develop'            |
| `git reset --hard HEAD`                   | Restores to the latest commit in the current branch               |
| `git merge <feature-branch>`              | Merges a branch (e.g., `feature/update-project-settings`)         |
| `git push --set-upstream origin <branch>` | Pushes a new branch not yet in the remote repository              |
| `git push origin develop`                 | Pushes changes to the 'develop' branch in the remote repository   |