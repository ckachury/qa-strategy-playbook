<div align="center">

# QA Strategy Playbook

**Cómo instalo y conduzco la calidad en equipos de producto SaaS: estrategia de pruebas basada en riesgo, revisión de requisitos, gobierno de releases y métricas que sirven para decidir.**

![Estrategia](https://img.shields.io/badge/ESTRATEGIA-pruebas%20basadas%20en%20riesgo-0f4c4a?style=flat-square)
![Gobierno](https://img.shields.io/badge/GOBIERNO-quality%20gates%20·%20go%2Fno--go-d9573a?style=flat-square)
![Requisitos](https://img.shields.io/badge/REQUISITOS-revisión%20·%20criterios%20de%20aceptación-334155?style=flat-square)
![ISTQB](https://img.shields.io/badge/ISTQB-CTFL-b7791f?style=flat-square)

[English](README.md) · Español

</div>

---

## Qué es

Las prácticas, plantillas y checklists que uso cuando lidero QA o construyo una función de QA desde cero. Vienen de ocho años en productos SaaS (LegalTech, HealthTech, logística y e-commerce), donde la calidad tenía que seguirle el ritmo a releases frecuentes y equipos pequeños.

Tres ideas atraviesan todo:

1. **La calidad empieza antes del código.** El defecto más barato es la ambigüedad que se encuentra al revisar una historia de usuario.
2. **El esfuerzo de prueba sigue al riesgo.** No todo merece la misma profundidad; primero el dinero, la confianza y los datos.
3. **Las métricas existen para tomar decisiones.** Si ningún número cambia una decisión, no va en el tablero.

## Contenido

| Ruta | Qué es |
|---|---|
| [docs/test-strategy-template.md](docs/test-strategy-template.md) | Estrategia de pruebas en una página y plantilla completa para funcionalidades grandes |
| [docs/requirements-review-checklist.md](docs/requirements-review-checklist.md) | Qué reviso en una historia o especificación antes del desarrollo |
| [docs/release-governance.md](docs/release-governance.md) | Quality gates, reunión de go/no-go y política de hotfix |
| [docs/quality-metrics.md](docs/quality-metrics.md) | Catálogo breve de métricas, con fórmula y la decisión que apoya cada una |
| [docs/bug-report-standard.md](docs/bug-report-standard.md) | Plantilla de bug report, severidad vs prioridad, reglas de triage |
| [samples/](samples/) | Muestras de portafolio diseñadas (PDF), descritas abajo |

Los documentos detallados están en inglés; este README resume su contenido.

## Casos

| Muestra | Qué muestra |
|---|---|
| [GymFlow Win-back Offer](samples/06-test-strategy-plan-cases-winback.pdf) | Del requerimiento a la decisión de release: 9 preguntas para el equipo, estrategia basada en riesgo, tabla de decisión, 22 casos priorizados en web, móvil y API, y 3 métricas de release. Escenario ficticio. |
| [Revisión de requisitos](samples/01-requirements-review-user-stories.pdf) | 8 historias con criterios de aceptación, 5 brechas y una matriz de riesgo para el prototipo de un marketplace de cuidado de mascotas |
| [Plan y casos de prueba](samples/02-test-plan-test-cases.pdf) | Plan basado en riesgo y casos ejecutados sobre el mismo prototipo |
| [Bug reports](samples/03-bug-reports.pdf) | 8 reportes de una sesión exploratoria, con evidencia e impacto en el negocio |
| [Release readiness](samples/04-release-readiness-go-no-go.pdf) | Una decisión de go/no-go en una página, con las acciones para llegar a go |

El marketplace de mascotas (PawHome) es un prototipo construido por un equipo universitario de mi Magíster.

## Trabajo relacionado

- [ai-quality-governance](https://github.com/ckachury/ai-quality-governance): la misma disciplina aplicada a funcionalidades con IA.
- [test-process-assessment](https://github.com/ckachury/test-process-assessment): medir y mejorar el proceso de pruebas de toda una organización.

Contenido compartido bajo [CC BY-NC-ND 4.0](LICENSE).

---

<sub>Carla Achury · Calidad y Gobierno de IA · Santiago, Chile · [ckachury.github.io](https://ckachury.github.io)</sub>
