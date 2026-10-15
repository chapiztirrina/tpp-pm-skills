---
name: meeting-summarizer
description: Resume una reunión a partir de una transcripción o notas y extrae decisiones, next steps con responsable y fecha, pendientes y riesgos, con un mensaje listo para enviar. Usar cuando se pegue una transcripción, notas o la grabación de una reunión y se necesite el resumen y las acciones. Disparadores - "resume esta reunión", "saca los next steps", "minuta", "qué quedó pendiente".
---

# Meeting Summarizer

## Objetivo

Convertir una reunión en un resumen corto y accionable que se pueda enviar el mismo día: qué se decidió, quién hace qué y para cuándo.

## Entrada

Transcripción, notas sueltas o una combinación. Si se conocen, usar: nombre de la reunión, participantes y fecha. Si no están, no inventarlos.

## Formato de entrega

### TL;DR
2-3 líneas: de qué se trató y el resultado principal.

### Decisiones
Lista de lo que **se acordó**, una línea cada una. Una sugerencia o idea no es una decisión: pasarla a "Pendientes".

### Next steps
| Acción | Responsable | Fecha | Estado |
|---|---|---|---|
Si falta responsable o fecha, escribir `Sin responsable` / `Sin fecha` en lugar de suponer.

### Pendientes y preguntas abiertas
Lo que quedó sin resolver y quién podría resolverlo.

### Riesgos y bloqueos
Lo que puede frenar el avance, si se mencionó.

### Temas discutidos (opcional)
Máximo 5 viñetas de una línea. Solo si aporta contexto a quien no estuvo.

### Mensaje listo para enviar
Versión corta para Slack o correo, con TL;DR, decisiones y next steps. Pedir confirmación de las acciones asignadas.

## Reglas

- **No inventar** responsables, fechas, decisiones ni cifras. Lo que no esté en la fuente se marca como faltante.
- Distinguir claramente decisión, sugerencia y pregunta.
- Brevedad: el resumen debe leerse en menos de un minuto.
- Usar los nombres tal como aparecen en la transcripción; si hay duda sobre quién dijo qué, indicarlo.
- Cerrar señalando los 1-3 puntos que conviene confirmar con el equipo.
