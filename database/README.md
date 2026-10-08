# database

Scripts SQL de la base de datos de ruta-api.

## Cómo ejecutarlos

1. Abrir el script en DBeaver, en la conexión a localhost (puerto 1433, usuario sa).
2. Ejecutar las instrucciones en orden, de arriba hacia abajo: Ctrl + Enter ejecuta la instrucción donde está el cursor.

## Reglas

- Cada archivo empieza con un número que marca su orden: `01-...`, `02-...`.
- Cada instrucción termina en `;` y se separa de la siguiente con una línea en blanco.
- UPDATE y DELETE siempre con WHERE.
- Sin contraseñas ni datos privados: este repositorio es público.