# 6 - Another Adds (Otras Adiciones)

## 1. **Agregar un archivo específico**
- `git add archivo.txt`

## 2. **Agregar varios archivos específicos**
- `git add archivo1.txt archivo2.js`

## 3. **Agregar todos los archivos (nuevos o modificados)**
- `git add .` El punto (`.`) agrega **todo lo que esté en el directorio actual y subcarpetas**.

## 4. **Agregar todo desde el directorio raíz del proyecto**
- `git add -A` Similar a `git add .`, pero también detecta archivos eliminados.

## 5. **Agregar archivos eliminados**
- `git add -u` Solo agrega archivos **modificados o eliminados**, no los nuevos.

## 6. **Agregar interactivamente (para revisar antes de agregar)**
- `git add -p` Te deja ver los cambios por partes y decidir qué sí o no agregar.

### 🧠 Tip resumen

| Comando         | Qué hace                                    |
|-----------------|---------------------------------------------|
| `git add .`     | Todo desde la carpeta actual hacia abajo    |
| `git add -A`    | Todo el proyecto, incluyendo eliminados     |
| `git add -u`    | Solo archivos modificados o borrados        |
| `git add -p`    | Agregar interactivamente (por partes)       |