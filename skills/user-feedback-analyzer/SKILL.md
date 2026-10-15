---
name: user-feedback-analyzer
description: Analiza feedback de usuarios (reseñas, tickets de soporte, respuestas de NPS o encuestas, comentarios, transcripciones de entrevistas) y lo convierte en temas, frecuencias, citas literales, oportunidades y decisiones de producto. Usar cuando se pegue feedback crudo y se quiera saber qué está pasando, qué priorizar o qué validar. Disparadores - "analiza este feedback", "qué dicen los usuarios", "resume estas reseñas", "patrones en los tickets".
---

# User Feedback Analyzer

## Objetivo

Convertir feedback crudo en inteligencia de producto: qué temas hay, qué tan frecuentes y graves son, qué dice la gente con sus propias palabras y qué decisión sugiere cada hallazgo. El resultado son decisiones, no observaciones genéricas.

## Entrada

Feedback pegado en la conversación o en un archivo (reseñas, tickets, NPS, encuestas, entrevistas, comentarios). Si hay metadatos (fecha, segmento, plan, canal, puntuación), usarlos. Preguntar solo lo imprescindible: qué producto o funcionalidad es y qué decisión se quiere tomar.

## Proceso

1. **Inventario:** cuántas piezas de feedback hay (N), fuentes y rango de fechas. Si N es pequeño (menos de ~20), advertirlo: los resultados son direccionales.
2. **Limpieza:** ignorar duplicados y spam. Si un comentario toca varios temas, contarlo en cada uno.
3. **Agrupar por temas.** Para cada tema:
   - **Qué pasa** (una frase).
   - **Frecuencia:** cuántos comentarios (n de N).
   - **Severidad:** ¿bloquea, frustra o es una molestia?
   - **Segmento afectado**, si se puede saber.
   - **Citas literales** (2-3, sin editar).
4. **Lo que gusta:** mismos campos para los temas positivos, para saber qué proteger.
5. **Necesidades detrás del feedback:** qué quiere lograr la persona, más allá de lo que pide ("pide X, necesita Y").
6. **Priorizar:** ordenar temas por frecuencia × severidad y marcar los que justifican una decisión ahora.
7. **Qué NO se puede concluir:** sesgos (solo quien se queja escribe), muestra pequeña, falta de segmentación.
8. **Siguientes pasos:** qué validar, con quién hablar y qué medir.

## Formato de entrega

- **Resumen en 5 líneas:** los 3 hallazgos más importantes y la decisión que sugieren.
- **Tabla de temas:** Tema | n/N | Severidad | Segmento | Cita representativa.
- **Oportunidades:** lista priorizada, cada una con el supuesto que habría que validar.
- **Lenguaje de la gente:** frases literales útiles para mensajes, onboarding o copy.
- **Límites del análisis.**
- **Próximos pasos.**

## Reglas

- **No inventar** citas, cifras ni segmentos. Todo número sale de contar el feedback recibido.
- **Separar hechos de interpretación:** lo que dijeron vs. lo que se cree que significa.
- Un comentario aislado no es un patrón: marcarlo como anécdota.
- No resolver con una solución por reflejo: proponer el problema y cómo validarlo.
- Respetar la privacidad: no repetir nombres, correos ni datos personales que aparezcan en el feedback.
