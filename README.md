# TPP PM Skills

5 skills en español para Product Managers, listos para usar con Claude Code y otros agentes que lean archivos `SKILL.md`. Creados por [TPP Academy (The Pro Producto Academy)](https://www.skool.com/the-pro-producto-4548).

| Skill | Para qué sirve |
|---|---|
| [`product-committee`](https://github.com/chapiztirrina/tpp-pm-skills/tree/main/skills/product-committee) | Comité de 5 voces (usuario, negocio, ingeniería, diseño y datos) que debate una idea y recomienda qué hacer |
| [`prd-writer`](https://github.com/chapiztirrina/tpp-pm-skills/tree/main/skills/prd-writer) | Escribe un PRD en español, en versión completa, one-pager o brief para prototipar con IA |
| [`user-feedback-analyzer`](https://github.com/chapiztirrina/tpp-pm-skills/tree/main/skills/user-feedback-analyzer) | Convierte reseñas, tickets, NPS o entrevistas en temas, citas y oportunidades |
| [`meeting-summarizer`](https://github.com/chapiztirrina/tpp-pm-skills/tree/main/skills/meeting-summarizer) | Resume una reunión y saca decisiones y next steps con responsable y fecha |
| [`weekly-update-writer`](https://github.com/chapiztirrina/tpp-pm-skills/tree/main/skills/weekly-update-writer) | Redacta un update semanal corto y con la conclusión primero |

## Instalación

**Claude Code:** copiar las carpetas de `skills/` a `~/.claude/skills/` (para todos los proyectos) o a `.claude/skills/` dentro de un proyecto.

```bash
git clone https://github.com/chapiztirrina/tpp-pm-skills.git
cp -r tpp-pm-skills/skills/* ~/.claude/skills/
```

**Otras herramientas:** cualquier agente que lea archivos `SKILL.md` puede usarlos. Si la herramienta no soporta skills, pegar el contenido del archivo como instrucciones del proyecto.

## Cómo usarlos

Pedirlos en lenguaje natural. Ejemplos:

- `Debate esta idea con el product committee: [idea]`
- `Escribe un PRD para [funcionalidad]. Contexto: [notas]`
- `Analiza este feedback de usuarios: [pegar reseñas o tickets]`
- `Resume esta reunión y saca los next steps: [transcripción]`
- `Escribe mi update semanal para liderazgo. Notas: [notas de la semana]`

## Principios compartidos

- Sin datos inventados: lo que falta se marca como `[POR DEFINIR]`.
- Conclusión primero y respuestas cortas.
- Separar hechos de supuestos.

## Créditos e inspiración

Estos skills son originales y no copian texto de otros proyectos. Los principios generales de `prd-writer` y `user-feedback-analyzer` coinciden con ideas ampliamente difundidas en la comunidad de producto, entre ellas las que recoge el proyecto comunitario [RefoundAI/lenny-skills](https://github.com/RefoundAI/lenny-skills), basado en el podcast y el newsletter de Lenny Rachitsky. Ese contenido pertenece a Lenny Rachitsky y sus invitados. Este repositorio no está afiliado ni respaldado por ellos. Quien quiera la versión en inglés con fuentes y citas verificadas puede usar ese repositorio directamente.

## Licencia

MIT. Ver [LICENSE](LICENSE).
