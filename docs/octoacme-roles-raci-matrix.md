# OctoAcme RACI Matrix

This matrix maps key project activities to roles using the RACI framework to clarify ownership and collaboration across the project lifecycle.

**RACI Legend**

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — performs the work |
| **A** | **Accountable** — owns the outcome; final decision authority |
| **C** | **Consulted** — provides input before the decision or action |
| **I** | **Informed** — notified of outcomes or progress |

**Roles Abbreviated**

| Abbreviation | Role |
|---|---|
| Dev | Developer |
| PdM | Product Manager |
| PM | Project Manager |
| TL | Technical Lead |
| QA | QA / Testing Lead |
| DL | Delivery Lead |
| CM | Change Management / Adoption Lead |
| RC | Risk and Compliance Partner |
| DO | Documentation Owner |
| SR | Stakeholder Representative / Business Owner |

---

## Initiation Phase

| Activity | Dev | PdM | PM | TL | QA | DL | CM | RC | DO | SR |
|---|---|---|---|---|---|---|---|---|---|---|
| Define problem statement and project goals | C | A/R | R | C | I | I | C | C | I | C |
| Identify stakeholders | I | R | A/R | I | I | I | C | C | I | A |
| Develop project charter / one-pager | I | C | A/R | C | I | C | C | C | R | C |
| Assess initial risks | C | C | R | C | I | I | I | A/R | I | C |
| Go / no-go decision | I | C | R | C | I | C | I | C | I | A |

---

## Planning Phase

| Activity | Dev | PdM | PM | TL | QA | DL | CM | RC | DO | SR |
|---|---|---|---|---|---|---|---|---|---|---|
| Backlog grooming and prioritization | C | A/R | R | C | C | I | I | I | I | C |
| Kickoff facilitation | C | C | A/R | C | C | C | C | I | I | I |
| Create and maintain project plan | I | C | A/R | C | C | R | I | C | I | I |
| Define acceptance criteria | C | A/R | C | C | R | I | I | I | I | C |
| Define Definition of Done | C | C | C | C | A/R | I | I | I | C | I |
| Map milestones and release plan | C | C | A/R | C | C | R | C | C | I | C |
| Identify and log risks | C | C | R | C | I | C | I | A/R | I | C |
| Update process documentation | I | I | C | C | I | I | I | I | A/R | I |

---

## Execution Phase

| Activity | Dev | PdM | PM | TL | QA | DL | CM | RC | DO | SR |
|---|---|---|---|---|---|---|---|---|---|---|
| Feature implementation | A/R | I | I | C | I | I | I | I | I | I |
| Code review | R | I | I | A/R | I | I | I | I | I | I |
| Test execution and defect triage | C | I | I | C | A/R | I | I | I | I | I |
| Daily standup facilitation | I | I | A/R | I | I | I | I | I | I | I |
| Risk register updates | I | I | R | C | I | I | I | A/R | I | I |
| Dependency tracking | I | I | R | C | I | A/R | I | C | I | I |
| Status reporting | I | I | A/R | I | I | R | I | I | I | I |
| Escalation management | I | C | R | C | C | C | I | A/R | I | C |

---

## Release Phase

| Activity | Dev | PdM | PM | TL | QA | DL | CM | RC | DO | SR |
|---|---|---|---|---|---|---|---|---|---|---|
| Release readiness sign-off (quality) | C | I | I | C | A/R | I | I | C | I | I |
| Release readiness sign-off (business) | I | C | I | I | C | I | C | I | I | A/R |
| Compliance and governance checkpoint | I | I | C | C | I | I | I | A/R | I | C |
| Communications planning | I | C | R | I | I | C | A/R | I | C | C |
| Deployment execution | A/R | I | I | C | C | I | I | I | I | I |
| Post-deployment verification | R | I | R | C | A/R | I | I | I | I | I |
| Stakeholder announcement | I | C | R | I | I | I | A/R | I | I | C |
| Documentation publish | C | I | I | C | I | I | C | I | A/R | I |

---

## Retrospective and Continuous Improvement Phase

| Activity | Dev | PdM | PM | TL | QA | DL | CM | RC | DO | SR |
|---|---|---|---|---|---|---|---|---|---|---|
| Retrospective facilitation | C | C | A/R | C | C | C | C | C | C | I |
| Capture action items | R | R | A/R | R | R | R | R | R | R | I |
| Adoption and outcome measurement | I | R | I | I | I | I | A/R | I | I | C |
| Process documentation updates | C | C | C | C | C | I | C | C | A/R | I |
| Risk posture review | I | I | R | C | I | I | I | A/R | I | C |

---

## Notes on Using This Matrix

- **Accountability (A)** should be held by exactly one role per activity. Where two roles share accountability, the primary is listed first.
- When a role is absent from a project (e.g., no dedicated Delivery Lead), the Project Manager typically absorbs those accountabilities.
- This matrix represents typical assignments; project teams should review and adjust at kickoff if the project context warrants it.
- See [Roles and Personas](./octoacme-roles-and-personas.md) for full descriptions of each role.
- See [Handoff Checklist](./octoacme-handoff-checklist.md) for structured guidance on phase transitions.
