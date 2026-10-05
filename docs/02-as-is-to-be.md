# 02 — As-Is to To-Be

## As-Is

`Hospital Registration → Documents → Manual Eligibility Check → Specialist Review → Clarification → Decision → Certification`

### Design Problems

- inconsistent information capture
- repeated document requests
- limited case-status visibility
- manual follow-up
- difficult cross-case reporting
- weak linkage between evidence and decision

## To-Be

`Digital Intake → Eligibility Gate → Evidence Checklist → Specialist Review → Clarification / Exception → Approval → Certification → Audit Record`

## State Model

`Draft → Submitted → Validation → Under Review → Clarification → Approved / Rejected → Certified`

Each transition has an owner, timestamp and permitted action.
