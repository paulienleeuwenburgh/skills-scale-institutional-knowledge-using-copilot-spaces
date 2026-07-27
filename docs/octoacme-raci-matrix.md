# OctoAcme RACI Matrix

## Purpose
Define ownership and accountability for key activities across the OctoAcme project lifecycle. Clear RACI assignments reduce ambiguity at handoff points, prevent duplication of effort, and ensure nothing falls through the cracks.

## RACI Key
| Symbol | Meaning |
|--------|---------|
| **R** | **Responsible** — Does the work |
| **A** | **Accountable** — Owns the outcome; approves or signs off |
| **C** | **Consulted** — Provides input before or during the activity |
| **I** | **Informed** — Notified when the activity is complete or status changes |

## Role Abbreviations
| Abbreviation | Role |
|---|---|
| PdM | Product Manager |
| PM | Project Manager |
| Dev | Developer(s) |
| EM | Engineering Manager |
| TL | Tech Lead / Architect |
| UX | UX/UI Designer |
| BA | Business Analyst |
| DO | DevOps / Platform Engineer |
| SC | Security / Compliance Specialist |
| CS | Customer Success / Support Representative |

---

## Initiation Phase

| Activity | PdM | PM | Dev | EM | TL | UX | BA | DO | SC | CS |
|---|---|---|---|---|---|---|---|---|---|---|
| Define problem statement & business case | A/R | C | I | C | C | C | C | I | I | C |
| Draft project one-pager | C | A/R | I | I | C | I | C | I | I | I |
| Identify stakeholders & sponsors | A | R | I | C | I | I | C | I | I | C |
| Define success metrics | A/R | C | C | I | C | C | R | I | I | C |
| Initial risk identification | C | A/R | C | C | C | I | C | C | C | I |
| Go / No-Go decision | A | C | I | I | C | I | I | I | I | I |

---

## Planning Phase

| Activity | PdM | PM | Dev | EM | TL | UX | BA | DO | SC | CS |
|---|---|---|---|---|---|---|---|---|---|---|
| Define scope & acceptance criteria | A | C | C | I | C | C | R | I | C | C |
| Backlog creation & refinement | A/R | C | C | I | C | C | R | I | C | I |
| Architecture & technical design | C | I | R | C | A/R | I | C | C | C | I |
| UX / user flow design | C | I | C | I | C | A/R | C | I | I | C |
| Effort estimation | C | C | R | C | A | I | C | C | I | I |
| Milestone & release plan creation | C | A/R | C | C | C | I | C | C | C | I |
| Dependency mapping | C | A/R | C | C | R | I | C | C | C | I |
| Security requirements definition | C | C | C | I | C | I | C | I | A/R | I |
| Infrastructure & environment planning | I | C | C | C | C | I | I | A/R | C | I |
| Definition of Done approval | C | A | C | C | R | C | C | C | C | I |

---

## Execution Phase

| Activity | PdM | PM | Dev | EM | TL | UX | BA | DO | SC | CS |
|---|---|---|---|---|---|---|---|---|---|---|
| Feature development | I | I | A/R | C | C | C | I | I | I | I |
| Code review | I | I | R | I | A | I | I | I | C | I |
| Design implementation review | C | I | C | I | I | A/R | I | I | I | I |
| Sprint planning & daily standups | C | A/R | R | C | R | C | C | I | I | I |
| Acceptance criteria validation | A | C | C | I | C | C | R | I | I | I |
| Risk monitoring & escalation | C | A/R | C | C | C | I | I | C | C | I |
| Blocker resolution | C | R | R | A | R | C | C | C | C | I |
| Security review / threat modeling | I | I | C | I | R | I | I | C | A/R | I |
| Status reporting | C | A/R | C | C | C | I | I | I | I | I |
| Team capacity management | I | C | I | A/R | C | I | I | I | I | I |

---

## Release Phase

| Activity | PdM | PM | Dev | EM | TL | UX | BA | DO | SC | CS |
|---|---|---|---|---|---|---|---|---|---|---|
| Release readiness review | C | A | C | C | R | C | I | R | R | R |
| Release notes authoring | R | C | C | I | C | I | C | I | I | C |
| Deployment execution | I | C | C | I | C | I | I | A/R | I | I |
| Post-deploy smoke testing | C | C | R | I | R | I | I | R | C | I |
| Stakeholder & customer communications | C | C | I | I | I | I | I | I | I | A/R |
| Rollback decision | C | R | C | C | R | I | I | A | C | I |
| Incident response coordination | I | R | R | A | R | I | I | R | R | C |
| Support readiness (FAQs, docs, training) | C | C | C | I | I | C | C | I | I | A/R |

---

## Retrospective & Continuous Improvement Phase

| Activity | PdM | PM | Dev | EM | TL | UX | BA | DO | SC | CS |
|---|---|---|---|---|---|---|---|---|---|---|
| Retrospective facilitation | I | A/R | R | C | R | C | C | C | C | C |
| Action item definition & ownership | C | A | R | R | R | C | C | C | C | C |
| Process documentation updates | C | R | C | C | C | I | C | C | C | I |
| Metrics & outcome review | A/R | C | C | I | C | C | C | I | I | C |
| Lessons-learned capture | C | A/R | R | R | R | C | C | C | C | C |

---

## Notes
- Multiple roles can be **R** (Responsible) for the same activity — this indicates collaborative execution.
- Only one role should be **A** (Accountable) per activity to preserve clear ownership.
- If a cell is blank, the role has no direct involvement in that activity.
- Adapt this matrix to your specific project context; not all roles may be staffed on every project.
- Review and update this matrix at project kickoff to confirm role assignments with your team.
