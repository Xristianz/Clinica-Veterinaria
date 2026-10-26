# Respuesta a la auditoría recibida

**Proyecto:** Clínica Veterinaria Huellitas  
**Ficha:** N.º 18  
**Estudiante:** Cristian Gabriel Moscoso Tello

## Respuesta a los hallazgos

| N.º | Decisión | Justificación | Evidencia | Commit |
|---|---|---|---|---|
| 3 | Aceptar | Se agregaron los atributos `autocomplete` a los campos nombre, teléfono y correo, para identificar correctamente su propósito. | [Antes](evidencias/antes-autocomplete.png) / [Después](evidencias/despues-autocomplete.png) | Pendiente |
| 4 | Aceptar | Se añadió una explicación que indica que los campos marcados con asterisco son obligatorios. | [Antes](evidencias/antes-obligatorios.png) / [Después](evidencias/despues-obligatorios.png) | Pendiente |
| 5 | Aceptar | Se agregó una instrucción sobre el formato del teléfono y se relacionó mediante `aria-describedby`. | [Antes](evidencias/antes-telefono.png) / [Después](evidencias/despues-telefono.png) | Pendiente |
| 8 | Refutar | La página utiliza CSS Grid en `.contenido`, que distribuye el contenido principal y la barra lateral. También utiliza una media query para adaptar la estructura a pantallas pequeñas. | [Evidencia](evidencias/refutacion-grid.png) | No requiere corrección |
| 10 | Aceptar | Se modificaron los bordes de los campos a `#767676` para alcanzar un contraste superior a 3:1, según WCAG 2.2, criterio 1.4.11. | [Antes](evidencias/antes-contraste.png) / [Después](evidencias/despues-contraste.png) | Pendiente |
| 13 | Aceptar| Corregido el texto que tenia mala sintaxis de ilustraccion | [Antes](evidencias/antes-alt.png) / [Después](evidencias/despues-alt.png) | Pendiente |

## Normas utilizadas

- HTML WHATWG: estructura y atributos HTML.
- WCAG 2.2, criterio 1.3.5: identificación del propósito de campos.
- WCAG 2.2, criterio 1.4.11: contraste no textual.
- W3C CSS Grid Layout: distribución mediante cuadrículas.
- WCAG 2.2, criterio 1.1.1: contenido no textual.


## Conclusión

Se revisaron las observaciones recibidas y se realizaron correcciones de accesibilidad en el formulario. También se identificó un hallazgo sobre Grid que puede refutarse mediante la inspección del CSS y el navegador.

El informe se completará con los identificadores de los commits y las comprobaciones pendientes.
