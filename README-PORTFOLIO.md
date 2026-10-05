# Portfolio build

This repository is a redacted portfolio representation of a digital compliance workflow.

## What this demonstrates

- Process discovery and as-is / to-be analysis
- Business requirements and acceptance criteria
- Role and responsibility mapping
- Workflow controls and exception handling
- UAT traceability
- Risk and decision management
- Technical architecture
- Working browser prototype
- Audit-oriented workflow history

## Prototype flow

**Case intake → evidence → specialist review → clarification → approval → certification → audit**

Open the prototype and test a case transition rather than treating this repository as a static case study.

## Technical scope

The prototype uses a lightweight browser implementation so the workflow can be inspected without a backend dependency. Production architecture would introduce authenticated identity, persistent storage, document management, notifications, monitoring and policy-controlled access.

## Evidence

- [`docs/`](./docs) — project analysis and delivery artefacts
- [`architecture/`](./architecture) — system view
- [`app/`](./app) — working prototype
- [`docs/13-build-evidence.md`](./docs/13-build-evidence.md) — implementation scope and test path

## Data boundary

All visible records are synthetic. No patient information, hospital credentials, confidential government records or production source code is included.

## Project framing

This is presented as a **digital transformation / project delivery case study with a working prototype**, not as a claim that the public-sector production system is reproduced in this repository.
