# 0 - Better_Config (Mejor configuración)

| Comando | Descripción |
| :----------------------------------------: | :------------------------------------------------------------------------- |
| `git config --list` | Muestra la configuración actual de Git |
| `git config --global user.name "YourUserNickName"` | Establece el nombre de usuario global |
| `git config --global user.email "YourUserEmailName@Email.com"` | Establece la dirección de correo electrónico global |
| `ssh-keygen -t ed25519 -C "YourUserEmailName@Email.com"` | Genera una clave SSH usando el correo electrónico para identificación |
| `ssh -T git@github.com` | Verifica la conexión SSH con GitHub |
| `C:\Users\YourUserExamplePc\.ssh` | Ubicación predeterminada de la clave SSH en Windows |
| `config` (archivo de configuración SSH) | Archivo de configuración SSH personalizado para múltiples hosts |

## bibliography (bibliografía)

- [Descargar Git](https://git-scm.com/downloads)  
- [Generar y agregar una llave SSH en GitHub](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## 5 - Ignore Files (Ignorar Archivos)

## Ignorar carpetas del sistema operativo

```bash
.DS_Store         # macOS
Thumbs.db         # Windows
```

## Ignorar archivos de logs

```bash
*.log
logs/
npm-debug.log*
```

## Ignorar dependencias comunes

```bash
node_modules/
vendor/
```

## Ignorar entornos virtuales (Python)

```bash
venv/
.env/
*.env
```

## Ignorar archivos temporales y de respaldo

```bash
*.tmp
*.bak
*.swp
*~
```

## Ignorar archivos de compilación

```bash
dist/
build/
out/
*.class
*.o
*.exe
```

## Ignorar archivos de configuración local

```bash
.idea/
.vscode/
*.code-workspace
```

## Ignorar cobertura de pruebas

```bash
coverage/
*.lcov
```

## Ignorar bases de datos locales o exportaciones

```bash
*.sqlite
*.db
*.sql
```

## Ignorar archivos de entorno

```bash
.env
.env.local
.env.*.local
```

## Ignorar archivos generados por sistemas de control de versiones o herramientas externas

```bash
*.tgz
*.zip
*.tar.gz
```

## Ignorar carpetas específicas del proyecto (ejemplo)

```bash
my-secret-folder/
```