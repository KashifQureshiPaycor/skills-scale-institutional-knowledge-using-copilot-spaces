# Decision Log Template

## Purpose
Record key project decisions to provide traceability, reduce repeated debates, and support onboarding of new team members.

---

## Decision Log

| ID | Date | Decision | Context / Problem | Options Considered | Decision Rationale | Owner | Stakeholders Notified | Status |
|----|------|----------|-------------------|-------------------|-------------------|-------|----------------------|--------|
| D-001 | YYYY-MM-DD | | | | | | | Accepted |
| D-002 | YYYY-MM-DD | | | | | | | Accepted |

---

## Field Definitions

| Field | Description |
|-------|-------------|
| **ID** | Unique identifier (e.g., D-001) |
| **Date** | Date the decision was made |
| **Decision** | One-line summary of what was decided |
| **Context / Problem** | What triggered the need for a decision |
| **Options Considered** | Alternatives that were evaluated |
| **Decision Rationale** | Why this option was chosen |
| **Owner** | Person accountable for the decision and its outcomes |
| **Stakeholders Notified** | Who needs to know and has been informed |
| **Status** | `Proposed` / `Accepted` / `Superseded` / `Revoked` |

---

## Decision Lifecycle

1. **Propose** — Any team member can propose a decision. Add to log with status `Proposed`.
2. **Review** — Discuss in the relevant meeting or async. Document options and rationale.
3. **Accept** — Owner finalizes; update status to `Accepted` and notify stakeholders.
4. **Supersede / Revoke** — If a decision changes, add a new entry and mark old one `Superseded` with a reference to the new ID.

---

## Best Practices
- Log decisions as they happen — don't backfill weeks later.
- Keep rationale brief but meaningful; future readers need enough context to understand *why*.
- Link to relevant design docs, meeting notes, or ADRs (Architecture Decision Records) where applicable.
- Review the decision log during retrospectives to check if any decisions should be revisited.

---

## Related Documents
- [Project Initiation Guide](../octoacme-project-initiation.md)
- [RACI Matrix Template](raci-matrix-template.md)
- [RAID Log Template](raid-log-template.md)
