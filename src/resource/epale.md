
PS E:\dev\git-by-carlitos> git branch -a
* main  // rama ubicado actual              (local)
  remotes/origin/HEAD -> origin/main        (rama principal del repositorio remoto)
  remotes/origin/main                       (rama main, pero en remoto)
PS E:\dev\git-by-carlitos> 



git clone



git branch
git checkout



# Estrategia de ramificación (branching strategy)

En git existen varias formas y metodos para trabajar y colaborar, pero **existen dos** por encima de todos que se *deben de aprender*, por ser las mas basicas y mas usadas.

- *GitHub Flow (ágil y continuo, para equipos pequeños o medianos, proyectos web que hacen despliegues frecuentes)
- *Git Flow (recomendado en proyectos más grandes, Bueno si tienes versiones, lanzamientos planeados, hotfixes, etc.)
- GitLab Flow
- Trunk Based Development
- Forking Workflow
- One Flow
- Release Flow (usado por Microsoft)
- Feature Branch Workflow

- NOTA!:
    - GitHub Flow --> como la mas basica y usada.
    - Git Flow --> la mas usada para proyectos formales y grandes.

**Git Flow** es una **estrategia de ramificación** la que consiste en crear y tener 5 tipos de ramas.

[ main , develop , feature/* , release/* , hotfix/* ]

- **main**; contiene el código de producción.

    - **hotfix**; Sirve para errores criticos de ultimo momento, se crea apartir de **main** `release/1.2.0`

- **develop**; es la **Rama Base** Contiene el desarrollo de las **nuevas funcionalidades**.

    - **feature**; Sirve para desarrollar **nuevas funciones** ´feature/login-form´. se crea a partir de **develop**

    - **release**; Sirve para crear una nueva versión. (Corregir: bugs menores y ajustes finales) se crea a partir de **develop**