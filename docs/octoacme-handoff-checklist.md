# OctoAcme Handoff Checklist

This checklist provides structured guidance for role-to-role and phase-to-phase transitions to reduce handoff gaps and ensure continuity of context, ownership, and accountability across the project lifecycle.

Use this checklist at every major transition point. The outgoing owner is responsible for completing the checklist; the incoming owner is responsible for confirming receipt and raising any gaps.

---

## Phase Transition Checklists

### Initiation → Planning Handoff

**Outgoing owner:** Project Manager  
**Incoming owner:** Project Manager (planning lead), Product Manager, Technical Lead

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | Project charter or one-pager is finalized and accessible | PM | ☐ |
| 2 | Go/no-go decision is documented with rationale | PM / SR | ☐ |
| 3 | Stakeholder list is complete and includes contact information | PM | ☐ |
| 4 | Initial risk register is created with at least top risks identified | RC / PM | ☐ |
| 5 | Problem statement and SMART goal are approved by the Stakeholder Representative | PdM / SR | ☐ |
| 6 | High-level timeline and milestone expectations are shared with the team | PM | ☐ |
| 7 | Planning kickoff is scheduled | PM | ☐ |

---

### Planning → Execution Handoff

**Outgoing owner:** Project Manager (planning)  
**Incoming owner:** Project Manager (execution), Developers, QA / Testing Lead

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | Kickoff session has been run and action items are captured | PM | ☐ |
| 2 | Backlog is prioritized and sprint-ready with acceptance criteria on all top items | PdM | ☐ |
| 3 | Definition of Done is agreed and documented | QA | ☐ |
| 4 | Milestones and release plan are published and accessible | PM | ☐ |
| 5 | Risk register is reviewed and assigned for execution tracking | RC / PM | ☐ |
| 6 | Technical approach is documented (architecture, key decisions) | TL | ☐ |
| 7 | Test strategy is defined and shared with Developers | QA | ☐ |
| 8 | Cross-team dependencies are identified and owners confirmed | DL / PM | ☐ |
| 9 | Communication plan is in place (cadences, escalation paths) | PM | ☐ |
| 10 | Process documentation is updated to reflect the project context | DO | ☐ |

---

### Execution → Release Handoff

**Outgoing owner:** Project Manager (execution), Developers, QA / Testing Lead  
**Incoming owner:** QA / Testing Lead (release sign-off), Change Management Lead, Release team

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | All acceptance criteria are met and verified | QA | ☐ |
| 2 | Definition of Done is satisfied for all items in scope | QA / Dev | ☐ |
| 3 | Known defects are triaged; critical and high severity defects resolved | QA | ☐ |
| 4 | Release readiness sign-off (quality) is obtained | QA | ☐ |
| 5 | Release readiness sign-off (business) is obtained | SR | ☐ |
| 6 | Compliance and governance checkpoint is completed | RC | ☐ |
| 7 | Communications plan is finalized and stakeholders briefed | CM | ☐ |
| 8 | Deployment runbook is documented and reviewed | TL / Dev | ☐ |
| 9 | Rollback plan is documented and communicated | TL / Dev | ☐ |
| 10 | Post-deployment verification criteria are defined | QA | ☐ |
| 11 | User-facing documentation is published or staged for publish | DO / CM | ☐ |

---

### Release → Retrospective Handoff

**Outgoing owner:** Project Manager, QA / Testing Lead  
**Incoming owner:** Project Manager (retrospective facilitator), all team roles

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | Post-deployment verification is complete | QA | ☐ |
| 2 | Stakeholder announcement is sent | CM / PM | ☐ |
| 3 | Adoption and outcome metrics are baselined | CM / PdM | ☐ |
| 4 | Retrospective is scheduled with all participants | PM | ☐ |
| 5 | Release summary (what shipped, known issues, follow-ups) is documented | PM | ☐ |

---

### Retrospective → Next Cycle Handoff

**Outgoing owner:** Project Manager (retrospective facilitator)  
**Incoming owner:** Project Manager (next cycle), all role owners of action items

| # | Item | Owner | Done |
|---|---|---|---|
| 1 | Retrospective notes are documented and published | PM | ☐ |
| 2 | Action items have named owners and target dates | PM | ☐ |
| 3 | Process documentation is updated to reflect lessons learned | DO | ☐ |
| 4 | Risk posture has been reviewed and carryover risks are re-rated | RC | ☐ |
| 5 | Adoption data review is complete and findings shared | CM | ☐ |
| 6 | Next cycle planning or backlog refinement is initiated | PdM / PM | ☐ |

---

## Role-to-Role Handoff Notes

### Product Manager → QA / Testing Lead (Acceptance Criteria Handoff)

Before entering execution, the Product Manager should confirm with the QA / Testing Lead that:

- Acceptance criteria are written in a testable format
- Edge cases and error states are covered in criteria
- Dependencies on external systems are documented
- Priority of test scenarios is agreed upon

### Technical Lead → Developers (Design Handoff)

Before implementation begins, the Technical Lead should confirm with Developers that:

- Architecture decision records or design docs are published
- Key technical risks are communicated
- Coding standards and patterns are agreed upon
- Integration points with external systems are documented

### Developers → QA / Testing Lead (Feature Handoff)

Before feature review and QA, Developers should confirm with the QA / Testing Lead that:

- Feature is deployed to the agreed test environment
- Unit tests are passing
- Known limitations or scope exclusions are documented
- Test data requirements are met

### Project Manager → Delivery Lead (Escalation Handoff)

When escalating a cross-team issue to the Delivery Lead, the Project Manager should provide:

- Summary of the blocker and its impact on milestones
- Teams and owners involved
- Actions already attempted
- Recommended resolution path (if known)
- Target resolution date needed to avoid downstream impact

---

## Checklist Usage Notes

- This checklist should be reviewed at the start of each phase transition in project planning
- Not all items will apply to every project; teams should adapt the checklist at kickoff
- Incomplete items should be flagged as risks in the risk register before a phase transition proceeds
- See [RACI Matrix](./octoacme-roles-raci-matrix.md) for accountability assignments per activity
- See [Roles and Personas](./octoacme-roles-and-personas.md) for full role descriptions
