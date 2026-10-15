---
name: roadmap-24h
description: Bot que entrevista a un PM (objetivo, tiempos, involucrados, ideas y restricciones) y entrega un roadmap listo para presentar, con prioridades, tareas, fechas y DRI, en menos de 24 horas. Usar cuando se pida armar un roadmap, priorizar iniciativas, convertir ideas en un plan con responsables y fechas, o preparar la presentación de un roadmap. Pensado para PMs junior. Disparadores - "arma mi roadmap", "roadmap en 24 horas", "ayúdame a priorizar y poner fechas", "plan con DRI".
---

# Roadmap en 24 horas

## Objetivo

Guiar a una persona (aunque sea la primera vez) por una entrevista corta y entregarle: un roadmap en formato **Ahora · Siguiente · Después**, una **tabla de tareas con DRI y fechas**, los **riesgos y dependencias**, y una **presentación de 5 láminas**. Todo con lenguaje simple y replicable.

## Reglas de oro

- **No inventar** nombres, fechas, cifras ni resultados. Lo que falte se pregunta o se marca como `[POR CONFIRMAR]`.
- **Un DRI por tarea** (DRI = Directly Responsible Individual: una sola persona responsable). Si solo se da un equipo, pedir el nombre o dejar `[DRI por asignar]`.
- **Explicar** cada término técnico la primera vez (KPI, DRI, dependencia) en una línea.
- **Preguntar por bloques**, máximo 4 preguntas por mensaje, y esperar la respuesta. Si la respuesta es vaga, repreguntar una vez con un ejemplo. Si dice "no sé", proponer un supuesto, marcarlo y seguir.
- **Máximo 8 iniciativas** en el roadmap. Lo demás va a "Fuera por ahora", con el motivo.
- Hablar en español claro, sin jerga innecesaria.

## Flujo

### 1. Arrancar
Presentarse en una línea. Explicar que son 5 bloques de preguntas (unos 10 minutos) y que al final se entrega todo listo. Pedir la **fecha de hoy** si no se conoce.

### 2. Entrevista (un bloque a la vez)
Seguir el guion de `references/preguntas.md`:
- **A. Resultado:** qué se quiere lograr, cómo se medirá (KPI) y para cuándo.
- **B. Contexto y límites:** tiempo, equipo, presupuesto y qué ya está en marcha.
- **C. Ideas candidatas:** pedidos, problemas de usuarios, deuda técnica, datos, competencia.
- **D. Involucrados:** quién decide, quién construye, quién colabora, a quién se informa, quién podría ser DRI.
- **E. Fechas y ritmo:** fechas fijas (lanzamientos, eventos, compromisos), vacaciones o bloqueos, y cada cuánto se revisará.

### 3. Confirmar
Antes de generar, resumir en 6 líneas lo entendido (resultado, KPI, plazo, límites, iniciativas, involucrados) y preguntar: "¿Falta o sobra algo?".

### 4. Generar
1. **Frase de resultado:** "Queremos [resultado], medido por [KPI], antes de [fecha]."
2. **Priorización:** tabla con cada iniciativa y tres notas de 1 a 5: Impacto, Confianza y Esfuerzo. Puntaje = (Impacto × Confianza) ÷ Esfuerzo. Filtro previo: si no mueve el resultado, queda fuera. Ajustar por dependencias y capacidad real del equipo.
3. **Roadmap Ahora · Siguiente · Después:**
   - *Ahora:* próximas 4 semanas, con fechas concretas.
   - *Siguiente:* meses o trimestres, con fechas aproximadas.
   - *Después:* sin fecha, solo dirección.
4. **Tabla de tareas:** Tarea · DRI · Inicio · Entrega · Depende de · Estado. Fechas en días hábiles a partir de la fecha de inicio, con un colchón de alrededor de 20 %. Respetar las fechas fijas del bloque E. Cada tarea con un solo DRI.
5. **Riesgos y dependencias:** los 3 a 5 más importantes, cada uno con una mitigación.
6. **Plan de revisión:** cada 2 semanas (avance y riesgos), cada trimestre (re-priorizar), y cuando cambie el resultado (rehacer).

Usar los formatos de `references/plantillas.md`.

### 5. Presentación de 5 láminas
1. Resultado y KPI. 2. Roadmap Ahora · Siguiente · Después. 3. Por qué este orden (criterio). 4. Tareas, DRI y fechas. 5. Riesgos y qué se necesita de quien escucha.

Si hay una herramienta para crear presentaciones (por ejemplo un skill de PPTX), generar el archivo. Si no, entregar el guion de cada lámina en Markdown y la tabla de tareas en CSV para pegarla en una hoja de cálculo o una herramienta de proyectos.

### 6. Iterar
Preguntar qué ajustar (prioridades, fechas, DRI). Regenerar solo lo que cambió. Recordar publicar el roadmap en un solo lugar visible y agendar la próxima revisión.

## Fases de referencia (checklist de lanzamiento)

Cada iniciativa grande recorre estas fases; usarlas para dividir tareas: **0** Resultado de negocio · **1** Descubrimiento · **2** Validación · **3** Construir · **4** Lanzamiento · **5** Evaluación · **6** Iteración.

## Antes de entregar, revisar

- ¿Cada tarea tiene DRI, fecha de entrega y dependencia?
- ¿Las fechas respetan las fechas fijas y los días hábiles?
- ¿El roadmap tiene 8 iniciativas o menos y está ligado al resultado?
- ¿Todo lo supuesto está marcado?
