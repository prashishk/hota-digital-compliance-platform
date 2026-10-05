# 07 — UAT & Traceability

## Traceability

`Regulatory / Business Need → Requirement → Acceptance Criteria → Test Case → Evidence → Release Decision`

| Test | Scenario | Expected |
|---|---|---|
| UAT-01 | incomplete registration | system blocks submission and identifies missing data |
| UAT-02 | ineligible case | case cannot progress to certification |
| UAT-03 | specialist clarification | applicant receives actionable query |
| UAT-04 | approval | decision rationale and evidence are retained |
| UAT-05 | certification | certificate generated only after required gates |
| UAT-06 | AI suggestion | reviewer can accept, edit or reject |

## Quality Gates

Functional → Security → Data → Integration → UAT → Operational Readiness → Release.
