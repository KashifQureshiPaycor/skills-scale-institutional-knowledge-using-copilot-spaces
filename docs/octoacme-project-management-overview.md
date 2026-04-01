# OctoAcme Project Management Overview

## Table of Contents
- [Purpose](#purpose)
- [Scope](#scope)
- [Principles](#principles)
- [Core Roles](#core-roles)
- [Key Artifacts](#key-artifacts)
- [Lifecycle](#lifecycle-high-level)
- [Communication Cadence](#communication-cadence)
- [Templates & Checklists](#templates--checklists)
- [How to Use These Docs](#how-to-use-these-docs)

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: validate quality and acceptance criteria.
- Stakeholders: provide inputs and approvals.

> See [Roles and Personas](octoacme-roles-and-personas.md) for detailed responsibilities and [RACI Matrix template](templates/raci-matrix-template.md) for activity-level ownership.

## Key Artifacts

| Artifact | Phase | Template |
|----------|-------|----------|
| Project Charter / One-pager | Initiation | [Project Initiation Guide](octoacme-project-initiation.md) |
| RACI Matrix | Initiation | [RACI Matrix Template](templates/raci-matrix-template.md) |
| Decision Log | All phases | [Decision Log Template](templates/decision-log-template.md) |
| Roadmap and Release Plan | Planning | [Project Planning Guide](octoacme-project-planning.md) |
| Sprint/Iteration Backlog | Planning | — |
| Definition of Ready / Done | Planning | [DoR/DoD Template](templates/definition-of-ready-and-done.md) |
| RAID Log | Planning / Execution | [RAID Log Template](templates/raid-log-template.md) |
| Risk Register | Planning / Execution | [Risk Register Template](templates/risk-register-template.md) |
| Weekly Status Update | Execution | [Weekly Status Template](templates/weekly-status-update-template.md) |
| Release Readiness Checklist | Release | [Release Readiness Checklist](templates/release-readiness-checklist.md) |
| Retrospective notes and action items | Retrospective | [Retrospective Guide](octoacme-retrospective-and-continuous-improvement.md) |
| Project Closeout Checklist | Close | [Project Closeout Checklist](templates/project-closeout-checklist.md) |

## Lifecycle (high-level)
1. **Initiation**: problem statement, stakeholders, high-level timeline, RACI, decision log started.
2. **Planning**: scope, resources, milestones, dependencies, Definition of Ready/Done, RAID log.
3. **Execution**: build, test, review, iterate; weekly status updates, risk reviews.
4. **Release**: release readiness checklist, deploy, verify, announce.
5. **Close & Retrospective**: capture learnings, complete closeout checklist, next steps.

## Communication Cadence

| Meeting / Update | Frequency | Owner | Audience |
|------------------|-----------|-------|----------|
| Standup | Daily (or as agreed) | Team | Delivery team |
| PM + PdM sync | Weekly | PM | PM, PdM |
| Weekly status update | Weekly | PM | Stakeholders |
| Stakeholder update | Monthly (or milestone) | PM | All stakeholders |
| Sprint demo / review | Per sprint | Team | PM, PdM, Stakeholders |
| Retrospective | Per sprint / release | PM | Delivery team |
| Escalation (Level 1) | As needed | PM | Team lead |
| Escalation (Level 2) | As needed | PM | Product Lead + dependent teams |
| Escalation (Level 3) | As needed | PM | Sponsor |

> **SLAs:** Level 1 escalations resolved within the same business day; Level 2 within 1 business day; Level 3 within 4 business hours.

## Templates & Checklists
All reusable templates are in [`docs/templates/`](templates/README.md). See the [Templates Index](templates/README.md) for a quick-start guide by phase.

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Use the [Templates Index](templates/README.md) as your single source of truth for reusable artifacts.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
