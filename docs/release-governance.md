# Release governance

## Quality gates

| Gate | When | Criteria |
|---|---|---|
| Definition of Ready | Before a story enters the sprint | Acceptance criteria agreed; open questions answered or explicitly assumed; test data identified |
| Definition of Done | Before a story is closed | Criteria verified; tests passed at the agreed level; no open critical or high defects; documentation updated |
| Release candidate | Before the go/no-go | Regression run on the candidate build; P1 100% passed; known issues listed with impact |
| Post-release | First hours and days | Smoke test in production; monitoring and support watching; rollback ready |

## Go/no-go meeting

**Who:** Product Owner (decides), QA lead (evidence), tech lead (technical risk), support or customer success (customer impact).

**Agenda (20 minutes):**

1. Scope of the release and what changed since the last one.
2. Test results by priority, and coverage of the riskiest areas.
3. Open defects: severity, workaround, who is affected.
4. Operational readiness: rollback, feature flags, monitoring, support briefed.
5. Decision: **go**, **go with known issues** (each with an owner and a date), or **no-go** (with what is needed to reach go).

The decision and the known issues are recorded where the whole team can see them.

## Hotfix policy

- A hotfix fixes one problem. Nothing else rides along.
- Minimum test tier: the fix itself, the flow it touches and a short smoke test of critical paths.
- After the hotfix, the full regression of that area runs in the next regular cycle, and a test that would have caught the problem is added.

## Roles in a small team

When there is no dedicated release manager, QA prepares the evidence and the Product Owner decides. QA's job is to make the risk visible and understandable, not to own the decision alone.
