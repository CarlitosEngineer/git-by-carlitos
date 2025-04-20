# 5 - Ignore Files (Ignorar Archivos)

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