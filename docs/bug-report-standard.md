# Bug report standard

## Template

```
Title        [Area] What fails, in which condition
Environment  Build / version · browser or device · OS · test data used
Severity     Critical · High · Medium · Low
Priority     Set in triage by the Product Owner

Steps to reproduce
1.
2.
3.

Expected result
Actual result
Business impact   Who is affected and how (money, trust, data, blocked task)
Evidence          Screenshot, video, logs, request and response
Links             Story, test case, related defects
```

## Severity vs priority

| | Severity | Priority |
|---|---|---|
| Measures | Impact on the system or the user | Urgency of fixing it |
| Set by | QA | Product Owner, in triage |
| Example | A typo on the payment page: low severity | Same typo in a launch campaign: high priority |

## Severity scale

| Severity | Meaning |
|---|---|
| Critical | Data loss or exposure, money handled wrongly, main flow blocked with no workaround |
| High | Main flow broken with a costly workaround, or a business rule applied wrongly |
| Medium | Secondary flow broken, or main flow degraded |
| Low | Cosmetic or minor inconvenience |

## Triage rules

- Triage at a fixed cadence (daily during a release, weekly otherwise).
- A change of priority is recorded with who changed it and why.
- Duplicates are linked, not deleted.
- A reopened defect returns to triage.
- Every critical defect that reached production gets a regression test.
