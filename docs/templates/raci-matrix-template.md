# RACI Matrix Template

## Purpose
Clarify ownership and accountability for key project activities and decisions. Use during planning to prevent confusion and gaps in responsibility.

---

## How to Read a RACI Matrix

| Letter | Role | Description |
|--------|------|-------------|
| **R** | Responsible | Does the work. There must be at least one R per activity. |
| **A** | Accountable | Owns the outcome; approves the work. Only **one A** per activity. |
| **C** | Consulted | Provides input; two-way communication required before decisions. |
| **I** | Informed | Kept up-to-date on progress/decisions; one-way communication. |

---

## RACI Matrix

Replace the roles in the header row with your project's actual roles/names.

| Activity / Decision | Project Manager | Product Manager | Developer(s) | QA / Testing | Security Lead | Sponsor / Stakeholder |
|---------------------|-----------------|-----------------|--------------|--------------|---------------|-----------------------|
| **Initiation** | | | | | | |
| Define problem statement | C | A/R | I | I | I | C |
| Stakeholder alignment | R | A | I | I | I | C |
| Go/No-Go decision | I | C | I | I | I | A/R |
| **Planning** | | | | | | |
| Backlog creation & prioritization | C | A/R | C | C | C | I |
| Resource & timeline planning | A/R | C | C | I | I | I |
| Definition of Ready / Done | A/R | C | R | R | C | I |
| Risk & dependency identification | A/R | C | C | C | C | I |
| **Execution** | | | | | | |
| Sprint / iteration planning | A/R | C | R | C | I | I |
| Feature implementation | I | I | A/R | C | C | I |
| Code review | I | I | A/R | I | C | I |
| QA & acceptance testing | C | A | C | R | C | I |
| Risk log updates | A/R | C | C | C | C | I |
| Weekly status reporting | A/R | C | I | I | I | I |
| **Release** | | | | | | |
| Release readiness sign-off | A/R | C | C | C | C | I |
| Deployment execution | C | I | A/R | C | C | I |
| Post-deploy verification | R | I | C | A/R | C | I |
| Release announcement | R | A | I | I | I | I |
| **Close & Retrospective** | | | | | | |
| Retrospective facilitation | A/R | C | C | C | I | I |
| Action item tracking | A/R | C | C | C | I | I |
| Project closeout checklist | A/R | I | I | I | I | C |

---

## Customization Notes
- Add or remove columns to match your actual team structure.
- Ensure every row has exactly one **A** (accountable).
- Revisit the RACI at the start of each new phase or when team composition changes.
- Document exceptions or overrides in the [Decision Log](decision-log-template.md).

---

## Related Documents
- [Decision Log Template](decision-log-template.md)
- [Roles and Personas](../octoacme-roles-and-personas.md)
- [Project Initiation Guide](../octoacme-project-initiation.md)
