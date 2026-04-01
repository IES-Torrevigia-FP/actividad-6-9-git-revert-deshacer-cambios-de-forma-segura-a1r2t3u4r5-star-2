## Diferencia entre git reset y git revert

git reset mueve la rama hacia atrás y puede eliminar commits del historial, reescribiéndolo.
git revert crea un nuevo commit que deshace cambios anteriores sin borrar el historial.

## Cuándo usar git revert

Cuando ya has hecho push a un repositorio compartido.
Cuando trabajas en equipo y necesitas mantener un historial limpio y ordenado.

## Forward-moving undo

Se llama así porque no elimina el pasado, sino que añade un nuevo commit que corrige errores.
Esto es importante en equipos porque evita conflictos, mantiene trazabilidad y permite ver qué pasó realmente en la historia del proyecto.
