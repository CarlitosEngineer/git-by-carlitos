# Learn Git with Carlitos

![Header](./src/Git_01.webp)

Welcome to this repository, created to help you understand and improve your Git skills in your development projects. Here you will find notes, guides, and practical tips about Git, aimed at establishing a solid foundation for effective repository management.

## General Objectives

- Establish a well-organized and optimized development environment using Git.

## Specific Objectives

1. **Basic Git Setup**
   - Download and install Git on your machine.
   - Configure your user settings and Git preferences.

2. **Repository Management**
   - Create, clone, push, and manage repositories on GitHub.
   - Understand the Git workflow, including commits, pull requests, and merges.

3. **Branching Models**
   - Learn about different branching models for various types of projects.
   - Understand Git Flow, GitHub Flow, and other popular branching strategies.

## Resources and References

- Visit my YouTube channel for video tutorials on Git and development: [Developing With Carlitos](https://www.youtube.com/@DevelopingWithCarlitos).
- [Download Git](https://git-scm.com/downloads) – Official page to download Git.
- [Generate and Configure SSH Keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) – Guide for generating an SSH key and adding it to your SSH agent.

### Installation Steps

1. **Download Git:**
   - Go to: https://git-scm.com/downloads
   - Download and install the version for your OS. Use default options.
   
2. **Check current configuration:**
   - Use `git config --list` to see the current configuration.
   
3. **Set up your user details:**
   - Set global username and email using:
     - `git config --global user.name "LearnWithCarlitos"`
     - `git config --global user.email "LearnWithCarlitos@gmail.com"`

4. **Generate an SSH key:**
   - Generate an SSH key using your email for identification:
     - `ssh-keygen -t ed25519 -C "LearnWithCarlitos@gmail.com"`
   - Locate the file in the `.ssh` folder, e.g., `C:\Users\YourUserExamplePc\.ssh`.

5. **Add your SSH public key to GitHub:**
   - Add the generated SSH key to your GitHub account in the SSH settings.

6. **Verify the connection:**
   - Use the command `` to verify the SSH connection to GitHub.

---

### 01 - Configuration Commands

| Command                                    | Description                                                                 |
| :----------------------------------------: | :-------------------------------------------------------------------------: |
| `git config --list`                        | Muestra la configuración actual de Git                                      |
| `git config --global user.name "YourUserNickName"` | Configura el nombre de usuario global                                |
| `git config --global user.email "YourUserEmailName@Email.com"` | Configura el correo electrónico global                            |
| `ssh-keygen -t ed25519 -C "YourUserEmailName@Email.com"` | Genera una clave SSH usando el correo electrónico para identificación |
| `ssh -T git@github.com`                    | Verifica la conexión SSH con GitHub                                         |
| `C:\Users\YourUserExamplePc\.ssh`          | Ubicación predeterminada de las claves SSH en Windows                       |
| `config` (SSH config file)                 | Archivo de configuración SSH personalizado para múltiples hosts             |

### 02 - Commands List

| Command                                   | Description                                                       |
| :---------------------------------------: | :---------------------------------------------------------------- |
| `git branch nameNewBranch`                | Crea una nueva rama                                                |
| `git branch`                              | Lista todas las ramas locales                                      |
| `git branch -a`                           | Lista todas las ramas (locales y remotas)                          |
| `git branch -r`                           | Lista las ramas remotas                                            |
| `git branch -l`                           | Lista las ramas locales                                            |
| `git checkout`                            | Cambia a la rama indicada                                          |
| `git checkout -b nombre-de-la-rama`       | Crea y cambia a la rama nueva                                      |
| `git checkout nameBranch`                 | Cambia a la rama nombrada                                          |
| `git checkout develop`                    | Cambia a la rama 'develop'                                         |
| `git remote -v`                           | Ver el origen del repositorio remoto                               |
| `git log --oneline`                       | Ver el último commit                                               |
| `git log --oneline -5`                    | Ver los últimos 5 commits                                          |
| `git clone <URL>`                         | Clonar un repositorio desde la URL                                 |
| `git remote add origin <URL>`             | Asociar un repositorio local con un repositorio remoto             |
| `git push origin <branch>`                | Subir los cambios de una rama local al repositorio remoto          |
| `git pull origin <branch>`                | Descargar y fusionar los cambios del remoto a tu rama local        |
| `git push --set-upstream origin <branch>` | Subir una nueva rama que no existe en el repositorio remoto        |
| `git reset --hard HEAD`                   | Restaurar al último commit de tu rama actual                       |
| `git merge <feature-branch>`              | Fusionar una rama (ejemplo: `feature/update-project-settings`)     |
| `git pull origin develop`                 | Actualizar la rama actual con los cambios de 'develop'             |
| `git push origin develop`                 | Subir los cambios a la rama 'develop' en el repositorio remoto     |

---
