# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm

| Ceremony | Frequency | Duration | Owner | Purpose |
|----------|-----------|----------|-------|---------|
| Standup | Daily | 15 min | Team | Progress, blockers, dependencies |
| Weekly delivery sync | Weekly | 30–45 min | PM | Status review, risk updates, decisions |
| Sprint demo / review | Per sprint | 60 min | Team | Showcase progress, gather feedback |
| PM + PdM sync | Weekly | 30 min | PM | Alignment on backlog, risks, priorities |
| Stakeholder status update | Weekly | Async | PM | [Weekly Status Update](templates/weekly-status-update-template.md) |

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: **Backlog → Ready → In Progress → In Review → QA → Done**
- Items must meet the [Definition of Ready](templates/definition-of-ready-and-done.md) before moving to "Ready"
- Pull Request workflow:
  - Small PRs (≤ 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
- Items must meet the [Definition of Done](templates/definition-of-ready-and-done.md) before moving to "Done"

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Send [Weekly Status Updates](templates/weekly-status-update-template.md) to stakeholders every week
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation

| Level | Trigger | Action | Owner | SLA |
|-------|---------|--------|-------|-----|
| Level 1 | Team-level blocker | Triage in daily standup | Team lead | Same business day |
| Level 2 | Cross-team dependency or recurring blocker | PM escalates to Product Lead and dependent teams | PM | Within 1 business day |
| Level 3 | Business-impacting or sponsor-level issue | PM escalates to Sponsor | PM | Within 4 business hours |

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] [Definition of Ready & Done](templates/definition-of-ready-and-done.md) agreed and visible to team
- [ ] CI configured for tests, lint, and security scans
- [ ] Regular demos scheduled
- [ ] [RAID Log](templates/raid-log-template.md) updated weekly
- [ ] [Weekly Status Updates](templates/weekly-status-update-template.md) sent on schedule

---

**Previous phase:** [Project Planning ←](octoacme-project-planning.md) | **Next phase:** [Release & Deployment →](octoacme-release-and-deployment.md)
