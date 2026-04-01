# RAID Log Template

## Purpose
Provide a single-view log of **Risks, Assumptions, Issues, and Dependencies** for a project. Use this alongside (or instead of) separate registers to maintain one source of truth.

---

## RAID Log

### Risks

| ID | Description | Probability (H/M/L) | Impact (H/M/L) | Score | Owner | Mitigation | Status |
|----|-------------|---------------------|----------------|-------|-------|------------|--------|
| R-001 | | | | | | | Open |

> See [Risk Register Template](risk-register-template.md) for the full risk register with escalation guidance.

---

### Assumptions

> Assumptions are facts believed to be true but not yet confirmed. Validate each assumption before it becomes a dependency.

| ID | Description | Basis / Evidence | Validation Due | Owner | Status |
|----|-------------|-----------------|----------------|-------|--------|
| A-001 | | | YYYY-MM-DD | | Unvalidated |

---

### Issues

> Issues are problems that have already occurred and require active management (unlike risks, which are potential future problems).

| ID | Date Raised | Description | Impact | Priority (H/M/L) | Owner | Resolution Plan | Target Resolution | Status |
|----|-------------|-------------|--------|-----------------|-------|-----------------|-------------------|--------|
| I-001 | YYYY-MM-DD | | | | | | YYYY-MM-DD | Open |

---

### Dependencies

> Dependencies are work items, decisions, or deliverables that this project relies on from external teams, vendors, or other projects.

| ID | Description | Type (Internal/External) | Dependent Team / Vendor | Due Date | Owner | Status |
|----|-------------|--------------------------|------------------------|----------|-------|--------|
| D-001 | | | | YYYY-MM-DD | | On Track |

---

## Status Values

| Status | Meaning |
|--------|---------|
| Open | Active — needs attention |
| In Progress | Being actively mitigated / resolved |
| Blocked | Needs escalation |
| Closed | Resolved, validated, or no longer relevant |
| On Track | Meeting expected timeline (Dependencies) |
| At Risk | May not meet expected timeline (Dependencies) |

---

## Review Cadence

| Frequency | Activity |
|-----------|----------|
| Weekly | Review open Risks, Issues, and at-risk Dependencies in PM sync |
| Sprint/Milestone | Validate outstanding Assumptions; close resolved items |
| Retrospective | Review RAID log for process improvement insights |

---

## Related Documents
- [Risk Register Template](risk-register-template.md) — extended risk management
- [Decision Log Template](decision-log-template.md)
- [Risks & Communication Guide](../octoacme-risks-and-communication.md)
- [Project Planning Guide](../octoacme-project-planning.md)
