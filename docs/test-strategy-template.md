# Test strategy template

## One-page version (most features)

| Section | Content |
|---|---|
| Feature and goal | What is being built and which business problem it solves |
| Top risks | Three to five risks, rated by impact × likelihood |
| Scope | In and out, with the reason for anything out |
| Test levels and types | API, integration, end to end, non-functional, regression |
| Techniques | Equivalence partitioning, boundary values, decision tables, state transitions, exploratory charters |
| Data and environment | Seeded data at each boundary; mocks for external services |
| Entry criteria | Open questions answered; build deployed; data ready |
| Exit criteria | Pass rates by priority; no open critical or high defects; rollback tested |
| Open questions | With the person who must answer each |

## Full version (large or high-risk features)

1. **Context.** Product, users, feature, business goal and how success is measured.
2. **Requirement analysis.** Assumptions, ambiguities and contradictions, each with the risk if not resolved and who must answer ([checklist](requirements-review-checklist.md)).
3. **Risk assessment.** Risks by impact × likelihood. The highest risks get the deepest coverage and run first.
4. **Approach.** Test levels and types, techniques per area, what is manual and what is automated, and why.
5. **Scope.** In and out, with reasons.
6. **Environment and data.** Environments, external dependencies and how they are mocked, test data at each boundary, access needed.
7. **Entry and exit criteria.**
8. **Prioritised test cases.** P1 money, trust and the main path; P2 secondary rules, roles and channel consistency; P3 scale and rare paths.
9. **Release metrics.** Two or three numbers that answer "did we ship what we meant to ship, safely?" ([catalogue](quality-metrics.md)).
10. **Risks to the plan.** Dependencies, unstable environments, late answers.

## Prioritisation rule

| Priority | Includes | Blocks release? |
|---|---|---|
| P1 | Money, data, trust, legal exposure, main happy path, regression of critical flows | Yes, 100% must pass |
| P2 | Secondary business rules, roles and permissions, consistency across channels | Agreed threshold (often 90%) and no open high defects |
| P3 | Performance at scale, rare paths, cosmetic | No, tracked as known issues |
