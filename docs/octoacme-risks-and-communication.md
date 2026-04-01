# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a dedicated risk register using the [Risk Register Template](templates/risk-register-template.md). At minimum, track:

| Field | Description |
|-------|-------------|
| ID | Unique identifier (e.g., R-001) |
| Description | Clear statement of the risk |
| Impact | High / Medium / Low |
| Likelihood | High / Medium / Low |
| Risk Score | Impact × Likelihood (Critical / High / Medium / Low) |
| Owner | Person responsible for mitigation |
| Mitigation Plan | Steps to reduce likelihood |
| Contingency Plan | Steps to reduce impact if risk materializes |
| Status | Open / In Progress / Closed |

> For risks, assumptions, issues, and dependencies in one view, use the [RAID Log Template](templates/raid-log-template.md).

## Risk Lifecycle
1. **Identify**: during planning and ongoing execution
2. **Assess**: estimate impact and likelihood; assign a risk score
3. **Mitigate**: reduce via actions or contingency plans
4. **Monitor**: review at weekly syncs and update status
5. **Close**: mark resolved risks as `Closed` with a brief resolution note

## Escalation SLAs

| Risk Score | Action | SLA |
|------------|--------|-----|
| Critical | Escalate to Sponsor | Same business day |
| High | Escalate to Product Lead | Within 1 business day |
| Medium | Review in weekly sync | Within current sprint |
| Low | Monitor; revisit at next milestone | — |

## Stakeholder Communication

### Communication Channels

| Channel | Audience | Frequency | Owner |
|---------|----------|-----------|-------|
| [Weekly Status Update](templates/weekly-status-update-template.md) | All stakeholders | Weekly | PM |
| Sprint demo / review | PM, PdM, Stakeholders | Per sprint | Team |
| Monthly stakeholder briefing | Executives / Sponsors | Monthly | PM / PdM |
| Escalation email / Slack | Relevant parties | As needed | PM |
| Incident communication (see below) | On-call + stakeholders | As needed | On-call |

### Single Source of Truth
- Project status: `docs/README.md` or the project's main README
- Risk and issues: [RAID Log](templates/raid-log-template.md) / [Risk Register](templates/risk-register-template.md)
- Decisions: [Decision Log](templates/decision-log-template.md)

## Communication Templates

### Weekly Status Update
Use the [Weekly Status Update Template](templates/weekly-status-update-template.md) for consistent, scannable stakeholder updates covering:
- Progress this week / next week
- Key metrics
- Risks & blockers
- Decisions needed
- Upcoming milestones

### Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level → PM → Product Lead → Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

---

**Related templates:**
- [Risk Register Template](templates/risk-register-template.md)
- [RAID Log Template](templates/raid-log-template.md)
- [Weekly Status Update Template](templates/weekly-status-update-template.md)
- [Decision Log Template](templates/decision-log-template.md)
