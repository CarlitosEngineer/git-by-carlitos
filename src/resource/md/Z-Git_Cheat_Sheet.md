# Z - Git Cheat Sheet (Hoja de Trucos de Git)

- **Listar** todas las ramas **local y remota** `git branch -a`

- **Crear** rama `git branch Name_Rama`
- **Cambiar** rama `git checkout Name_Rama`

- **Agregar** cambios `git add .`
- **Registrar** cambios `git commit -m "feat: agrega validación al formulario de login"`
- **Empujar** cambios `git push`

- **Borrar** rama **Local** `git branch -d Name_Rama`
- **Borrar** rama **Remoto** `git push origin --delete Name_Rama`

- Ligar **rama local** con **rama remota**; Estoy ubicado en `Hotfix` y ingreso `git push -u origin develop` cada push sera de `hotfix` a `develop`.

# áreas de trabajo - (ciclo de vida de los archivos en Git)

    Workspace (Working Directory)           Nothing

        Staging Area (Index)                add

            Repository (Local Repo)         commit

                Remote Repository           push