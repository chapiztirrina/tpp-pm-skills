---
name: prd-writer
description: Redacta un PRD (documento de requisitos de producto) completo en español a partir de una idea, notas o contexto, con problema, objetivos, métricas, alcance, requisitos con criterios de aceptación y riesgos. Usar cuando se pida escribir, mejorar o revisar un PRD, una especificación de producto, un one-pager o un brief para prototipar con IA. Disparadores - "escribe un PRD", "especifica esta funcionalidad", "arma el documento de producto", "PRD para prototipar".
---

# PRD Writer (español)

## Objetivo

Convertir una idea o un contexto desordenado en un PRD claro, accionable y honesto: que ingeniería pueda estimar, diseño pueda diseñar y una IA pueda usar para prototipar.

## Proceso

### 1. Entender antes de escribir
Con lo que haya en la conversación, identificar: problema, a quién afecta, por qué ahora y qué resultado se espera. Si faltan datos críticos, hacer **máximo 5 preguntas** agrupadas en un solo mensaje. Si la persona prefiere que se avance, escribir el PRD marcando como `[POR DEFINIR]` lo que falte. Nunca rellenar con datos inventados.

### 2. Elegir formato
- **PRD completo** (por defecto): todas las secciones de abajo.
- **One-pager**: Resumen, problema, objetivo, alcance, métrica, riesgos y próximos pasos.
- **Brief para prototipar con IA**: PRD completo + una sección final con pantallas, flujos, datos de ejemplo y referencias de diseño para pegar en una herramienta de IA.

### 3. Estructura del PRD

1. **Resumen (TL;DR):** 3-4 líneas: qué es, para quién y por qué importa.
2. **Contexto y problema:** qué pasa hoy, a quién le duele y con qué frecuencia.
3. **Evidencia:** datos, entrevistas, feedback o tickets que respaldan el problema. Si no hay, decir "evidencia pendiente".
4. **Personas usuarias:** a quién se sirve y qué necesita, en una línea cada una.
5. **Objetivos y no-objetivos:** qué se busca lograr y qué queda explícitamente fuera.
6. **Métricas de éxito:** una métrica principal, métricas de apoyo y guardarraíles (lo que no debe empeorar), con baseline y meta o `[POR DEFINIR]`.
7. **Alcance:** qué entra en la primera versión y qué no.
8. **Requisitos funcionales:** historias de usuario con **criterios de aceptación** verificables (formato "Dado / Cuando / Entonces" si ayuda).
9. **Requisitos no funcionales:** rendimiento, seguridad, privacidad, accesibilidad, cumplimiento, según aplique.
10. **Flujos y pantallas:** descripción del recorrido principal y de los casos límite.
11. **Diseño:** enlaces o referencias a Figma, design system o ejemplos.
12. **Dependencias y riesgos:** técnicas, de negocio, legales y de adopción, con una mitigación por riesgo.
13. **Plan de lanzamiento:** rollout gradual, comunicación, plan de reversa.
14. **Preguntas abiertas:** lo que falta resolver, con responsable si se conoce.

### 4. Revisión de calidad (antes de entregar)
- ¿El problema se entiende sin leer el resto?
- ¿Cada requisito tiene un criterio de aceptación que se pueda verificar?
- ¿Hay una sola métrica principal?
- ¿Está claro qué NO se va a hacer?
- ¿Las suposiciones están marcadas como suposiciones?
- ¿Se puede estimar y diseñar sin hacer preguntas básicas?

## Principios

- Empezar por el problema y la métrica de éxito, no por la solución.
- Un PRD corto que se lee sirve más que uno largo que se archiva: apuntar a una página para ideas pequeñas.
- Poner límites desde el inicio: qué entra, qué no y cuánto tiempo se invertirá.
- Escribir para abrir la conversación con ingeniería y diseño, no para cerrarla.
- Usar la IA para el primer borrador y el criterio propio para decidir qué queda.

## Errores comunes a señalar

- Palabras minimizadoras como "solo" o "simplemente" en los requisitos.
- Saltar a mockups detallados antes de acordar el problema.
- No escribir los no-objetivos.
- Tratar el PRD como un traspaso: el documento se entrega y no se vuelve a hablar.

## Reglas

- Español claro y directo. Sin relleno ni frases de moda.
- **No inventar** datos, cifras, nombres ni fechas. Usar `[POR DEFINIR]`.
- Preferir el **problema** sobre la solución: describir qué debe lograrse, no cómo construirlo, salvo en restricciones reales.
- Criterios de aceptación medibles, no adjetivos ("rápido", "fácil").
- Terminar con las 3 preguntas abiertas que más riesgo tienen.
