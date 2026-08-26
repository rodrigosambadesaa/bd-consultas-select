# Revisión de la entrega de 2018

`legacy/practica_consultas_select.sql` se conserva sin cambios. `solutions.sql` es la revisión moderna.

Correcciones relevantes:

- **15**: el `UNION` original devolvía distinto número de columnas en cada rama; ahora ambas proyectan las mismas cuatro columnas.
- **18**: se hace complementario real incluyendo empleados cuyo jefe es `NULL`.
- **19**: `COALESCE` trata las comisiones nulas como cero.
- **22**: el enunciado pide administrativos que **no** trabajan en el departamento 10; el original usaba `= 10`.
- **25**: “comienza por A” requiere `LIKE 'A%'`, no `LIKE 'A_'`.
- **37**: se compara estrictamente con los demás compañeros, excluyendo al propio empleado.
- **40**: el enunciado compara **puestos** con personas del departamento VENTAS; el original comparaba salarios con el departamento 20.
- **42**: se usa un `JOIN` explícito con `departamentos` para localizar Dallas/New York.

También se modernizan nombres de alias, `CHAR_LENGTH`, `utf8mb4` y el esquema de ejemplo reproducible.
