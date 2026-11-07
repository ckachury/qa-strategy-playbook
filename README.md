<div align="center">

# QA Strategy Playbook

**How I set up and run quality in SaaS product teams: risk-based test strategy, requirements review, release governance and metrics that support decisions.**

![Strategy](https://img.shields.io/badge/STRATEGY-risk--based%20testing-0f4c4a?style=flat-square)
![Governance](https://img.shields.io/badge/GOVERNANCE-quality%20gates%20·%20go%2Fno--go-d9573a?style=flat-square)
![Requirements](https://img.shields.io/badge/REQUIREMENTS-review%20·%20acceptance%20criteria-334155?style=flat-square)
![ISTQB](https://img.shields.io/badge/ISTQB-CTFL-b7791f?style=flat-square)

English · [Español](README.es.md)

</div>

---

## What this is

The practices, templates and checklists I use when I lead QA or build a QA function from scratch. They come from eight years in SaaS products (LegalTech, HealthTech, logistics and e-commerce), where quality had to keep up with fast releases and small teams.

Three ideas run through everything:

1. **Quality starts before code.** The cheapest defect is the ambiguity found while reviewing a user story.
2. **Test effort follows risk.** Not everything deserves the same depth; money, trust and data come first.
3. **Metrics exist to make decisions.** If no decision changes because of a number, it does not belong on the dashboard.

## Contents

| Path | What it is |
|---|---|
| [docs/test-strategy-template.md](docs/test-strategy-template.md) | One-page test strategy and a full template for larger features |
| [docs/requirements-review-checklist.md](docs/requirements-review-checklist.md) | What I check in a story or spec before development |
| [docs/release-governance.md](docs/release-governance.md) | Quality gates, go/no-go meeting and hotfix policy |
| [docs/quality-metrics.md](docs/quality-metrics.md) | A small catalogue of metrics, with formulas and the decision each one informs |
| [docs/bug-report-standard.md](docs/bug-report-standard.md) | Bug report template, severity vs priority, triage rules |
| [samples/](samples/) | Designed portfolio samples (PDF), described below |

## Case studies

| Sample | What it shows |
|---|---|
| [GymFlow Win-back Offer](samples/06-test-strategy-plan-cases-winback.pdf) | From requirement to release decision: 9 questions for the team, risk-based strategy, decision table, 22 prioritised test cases across web, mobile and API, and 3 release metrics. Fictional scenario. |
| [Requirements review](samples/01-requirements-review-user-stories.pdf) | 8 user stories with acceptance criteria, 5 gaps and a risk matrix for a pet-care marketplace prototype |
| [Test plan & test cases](samples/02-test-plan-test-cases.pdf) | Risk-based plan and executed test cases for the same prototype |
| [Bug reports](samples/03-bug-reports.pdf) | 8 reports from an exploratory session, with evidence and business impact |
| [Release readiness](samples/04-release-readiness-go-no-go.pdf) | A one-page go/no-go decision with the actions needed to reach go |

The pet-care marketplace (PawHome) is a prototype built by a university team in my Master's programme.

## Related work

- [ai-quality-governance](https://github.com/ckachury/ai-quality-governance): the same discipline applied to AI features.
- [test-process-assessment](https://github.com/ckachury/test-process-assessment): measuring and improving the test process of a whole organisation.

Content is shared under [CC BY-NC-ND 4.0](LICENSE).

---

<sub>Carla Achury · Quality & AI Governance · Santiago, Chile · [ckachury.github.io](https://ckachury.github.io)</sub>
