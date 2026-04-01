# Risk Register Template

## Purpose
Track, assess, and manage project risks throughout the project lifecycle. Update this register at minimum weekly during execution.

---

## Risk Register

| ID | Category | Description | Probability (H/M/L) | Impact (H/M/L) | Risk Score | Owner | Mitigation Plan | Contingency Plan | Status | Last Updated |
|----|----------|-------------|---------------------|----------------|------------|-------|-----------------|-----------------|--------|--------------|
| R-001 | | | | | | | | | Open | |
| R-002 | | | | | | | | | Open | |

**Risk Score** = Probability × Impact using the matrix below.

---

## Risk Scoring Matrix

| | **Low Impact** | **Medium Impact** | **High Impact** |
|---|---|---|---|
| **High Probability** | Medium | High | Critical |
| **Medium Probability** | Low | Medium | High |
| **Low Probability** | Low | Low | Medium |

**Thresholds:**
- **Critical / High** → Immediate mitigation required; escalate to sponsor
- **Medium** → Active mitigation plan; review weekly
- **Low** → Monitor only; review at milestones

---

## Risk Categories

| Code | Category |
|------|----------|
| TECH | Technical / Architecture |
| RES | Resource / Staffing |
| SCHED | Schedule / Timeline |
| SCOPE | Scope Creep |
| EXT | External / Vendor / Dependency |
| COMP | Compliance / Regulatory |
| SEC | Security |
| BUS | Business / Stakeholder |

---

## Risk Lifecycle

1. **Identify** — Surface risks during planning, standups, or retrospectives.
2. **Assess** — Assign probability, impact, and risk score.
3. **Plan** — Define mitigation (reduce likelihood) and contingency (reduce impact).
4. **Monitor** — Review status at each weekly sync; update `Last Updated`.
5. **Close** — Mark resolved risks as `Closed` with a brief resolution note.

---

## Escalation Triggers

| Risk Score | Action | SLA |
|------------|--------|-----|
| Critical | Escalate to Sponsor immediately | Same business day |
| High | Escalate to Product Lead | Within 1 business day |
| Medium | Review in weekly sync | Within current sprint |
| Low | Monitor; revisit at next milestone | — |

---

## Related Documents
- [RAID Log Template](raid-log-template.md) — for Risks, Assumptions, Issues, and Dependencies in one view
- [Risks & Communication Guide](../octoacme-risks-and-communication.md)
- [Project Planning Guide](../octoacme-project-planning.md)
