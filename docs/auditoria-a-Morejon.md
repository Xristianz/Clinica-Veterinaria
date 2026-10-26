
# Auditoría del proyecto de Mateo Morejón — Ficha 17

**Proyecto:** Club Deportivo  
**Auditor:** Cristian Gabriel Moscoso Tello

## Hallazgos

| N.º | Requisito | Ubicación | Hallazgo | Severidad |
|---|---|---|---|---|
| 1 | HTML válido | index.html, líneas 14 y 46 | El validador detectó un espacio no codificado en la ruta de la imagen y una etiqueta div sobrante. | Alta |
| 2 | Navegación | index.html, menú principal | Los tres enlaces apuntan a #inicio, pero no existe ese identificador. | Media |
| 3 | Validación nativa | index.html, campo de fecha y hora | El campo datetime-local no contiene min ni max. Se debe comprobar si esas restricciones existen en otros campos. | Media |

## Evidencias

### Evidencia 1: Validación HTML

El validador W3C muestra dos errores en el documento.

![Errores HTML](evidencias/auditoria-html.png)

### Evidencia 2: Navegación

Los enlaces Inicio, Fútbol y Servicios apuntan al mismo identificador, que no se encontró en el documento.

![Error de navegación](evidencias/auditoria-navegacion.png)

### Evidencia 3: Validación del formulario

El campo de fecha y hora contiene required, pero no min ni max.

![Validación de fecha](evidencias/auditoria-validacion.png)

## Requisitos que cumple

- Estructura semántica HTML.
- Formulario con cinco campos, labels y fieldset.
- Tabla con caption, thead, tbody y scope.
- Uso de Grid y Flexbox.
- Breakpoint de 800 px.
- Uso de grid-template-areas.
- Campo datetime-local para reservas.

## Observaciones finales

Se encontraron problemas relacionados con la validación HTML y la navegación. También se observó la ausencia de límites en el campo de fecha y hora.

Quedan pendientes las pruebas completas de responsive a 360 px, teclado, contraste y validación CSS.
