# Quality metrics catalogue

A short list on purpose. Pick three to five that answer the questions your team is actually asking.

| Metric | Formula | Decision it informs |
|---|---|---|
| Defect leakage | Defects found after release ÷ all defects found for that release (or period) | Is our testing catching what matters? Where do we add coverage? |
| Escaped defects by severity | Count of production defects by severity per release | Do we slow down, or invest in a specific area? |
| Risk coverage | P1 and P2 cases passed ÷ planned, plus % of business rules traced to at least one case | Are we ready to release? |
| Requirement defects found before development | Count of ambiguities and contradictions found in review, per story | Is refinement good enough? Where should product spend more time? |
| Lead time for changes | Time from commit (or story start) to production | Is testing a bottleneck, and where? |
| Change failure rate | Releases that needed a hotfix or rollback ÷ all releases | Is the release process safe? |
| Mean time to restore | Average time from incident detection to resolution | Are monitoring and rollback working? |
| Support tickets caused by defects | Tickets classified as product defects per period | Is quality improving the customer experience? |
| Rework | Effort spent reopening and fixing ÷ total effort | Where is quality costing the team time? |

## Rules

- Every metric has an owner, a definition written down and a review moment.
- Show trends, not snapshots.
- Never use a quality metric to rank individuals. It stops being honest the day you do.
- Report numerator and denominator, so a 100% from two cases is not mistaken for a 100% from two hundred.

## From experience

Two numbers have mattered most in the teams I led: **defect leakage**, which I kept at 5% or less on new development, and **support tickets caused by defects**, which fell by 60% after building a QA function from scratch in a HealthTech company. Both are understood by business people without explanation.
