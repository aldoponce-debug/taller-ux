# Auditoría UX - Taller UX

## Tabla de Heurísticas

| Heurística | Problema que encontraste | Solución aplicada | Gravedad |
| :--- | :--- | :--- | :--- |
| **Visibilidad del estado** | Al enviar el formulario no había respuesta visual para el usuario. | Se añadió un mensaje dinámico de éxito y error en pantalla. | Alta |
| **Prevención de errores** | Se permitía enviar campos vacíos o correos sin formato válido. | Se agregaron validaciones de campos obligatorios y formato de email. | Alta |
| **Control y libertad** | No existía opción segura para cancelar o limpiar datos erróneos. | Se implementó un botón de borrado con confirmación previa. | Media |
| **Reconocer, no recordar** | Faltaban textos de ayuda (`placeholder`) en los inputs del formulario. | Se incluyeron guías visuales y `placeholder` descriptivos. | Media |
| **Accesibilidad** | Las etiquetas y el contraste no cumplían con los estándares mínimos. | Se enlazaron correctamente los `label` con `id` y se mejoró el contraste. | Alta |

## Leyes de UX Aplicadas
* **Ley de Fitts:** El botón principal de acción se diseñó con un área táctil grande y separada del botón secundario para evitar clics accidentales.
* **Ley de Hick:** Se organizaron los elementos del formulario en bloques claros para no saturar al usuario con demasiadas opciones simultáneas.
* **Ley de Miller:** Se estructuró la información en fragmentos reducidos y fáciles de procesar.