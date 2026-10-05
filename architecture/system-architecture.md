# System architecture

```mermaid
flowchart LR
  U[Hospital user] --> W[Case workflow]
  W --> V[Validation and evidence]
  V --> R[Specialist review]
  R --> C[Clarification]
  C --> A[Approval decision]
  A --> AU[Audit history]
  W --> D[(Case data)]
  R --> D
  A --> D
```

**Production boundary:** authentication, persistent storage, document storage, notifications, monitoring and policy-controlled access would sit behind the prototype workflow. All demo records are synthetic.