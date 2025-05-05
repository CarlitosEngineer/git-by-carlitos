# 2 - Better_Commits (Registro de Cambios)

```bash
git commit -m "tipo: descripción breve"
git commit -m "feat: agrega validación al formulario de login"
```

## 🧠 Tipos más comunes (estilo [Conventional Commits](https://www.conventionalcommits.org/))

| Tipo       | Uso común                              |
|------------|----------------------------------------|
| `feat`     | Nueva funcionalidad                    |
| `fix`      | Corrección de errores                  |
| `docs`     | Cambios en documentación               |
| `style`    | Cambios de formato (espacios, comas...)|
| `refactor` | Reestructuración de código             |
| `test`     | Añadir o modificar pruebas             |
| `chore`    | Tareas menores (scripts, configs...)   |

---

## 📏 Reglas para conseguir un mejor commit (Buenas practicas)

1. usa palabras **imperativas** para los commits. Aqui te dejo una lista de ejemplos:

add (agrega)
fix (arregla)
update (actualiza)
remove (elimina)
create (crea)
rename (renombra)
refactor (refactoriza / reestructura)
optimize (optimiza)
clean (limpia)
implement (implementa)
change (cambia)
improve (mejora)
revert (revierte)
configure (configura)
test (prueba)
document (documenta)
format (formatea)
initialize (inicializa)
merge (fusiona)
split (divide)
validate (valida)
handle (maneja)
replace (reemplaza)
upgrade (actualiza/mejora)
downgrade (regrésalo a una versión anterior)

2. Debemos ser claros, directos y breves. (menor a 72 caracteres)

3. Los commits deben ser atomicos, (**Un Commit** por un **cambio logico**).

## ✍️ Ejemplos buenos

- `feat: permite editar perfil de usuario`
- `fix: corrige error al guardar sin conexión`
- `docs: actualiza README con instrucciones`
- `refactor: simplifica lógica de validación`