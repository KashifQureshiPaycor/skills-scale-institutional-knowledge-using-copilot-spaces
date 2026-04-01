# Definition of Ready & Definition of Done

## Purpose
Establish shared criteria so the team has a consistent understanding of when work can begin (Ready) and when it is genuinely complete (Done).

---

## Definition of Ready (DoR)

A backlog item is **Ready** to be pulled into a sprint/iteration when **all** of the following are true:

| # | Criterion | Owner |
|---|-----------|-------|
| 1 | User story or task is written in agreed format | Product Manager |
| 2 | Acceptance criteria are clear, testable, and understood by the team | Product Manager / Developer |
| 3 | Dependencies identified and either resolved or tracked in the RAID log | Project Manager |
| 4 | Estimate provided (story points or T-shirt size) | Developer(s) |
| 5 | UI/UX designs attached or linked (if applicable) | Designer |
| 6 | Security and privacy considerations noted (if applicable) | Developer / Security Lead |
| 7 | Item has been groomed and approved by Product Manager | Product Manager |

> **Tip:** If any criterion is unmet, move the item back to the backlog for refinement.

---

## Definition of Done (DoD)

A backlog item is **Done** when **all** of the following are true:

| # | Criterion | Owner |
|---|-----------|-------|
| 1 | All acceptance criteria met and verified | Developer / QA |
| 2 | Code reviewed and approved per team PR policy | Reviewer |
| 3 | Unit and integration tests written and passing | Developer |
| 4 | CI pipeline (tests + lint + security scans) passing | Developer |
| 5 | Documentation updated (code comments, README, or process docs) | Developer |
| 6 | Feature tested in staging / pre-production environment | QA |
| 7 | No known critical or high-severity bugs | QA |
| 8 | Release notes entry drafted (if user-facing) | Developer / PM |
| 9 | Product Manager has accepted the work | Product Manager |

---

## DoR / DoD for Releases

### Release Ready
- All stories in scope meet the DoD above
- Release readiness checklist complete (see [`release-readiness-checklist.md`](release-readiness-checklist.md))
- Rollback plan documented and tested
- Stakeholder sign-off obtained

### Release Done
- Deployed to production and verified
- Monitoring alerts confirmed active
- Release notes published
- Post-release verification complete (see [`project-closeout-checklist.md`](project-closeout-checklist.md))

---

## How to Customize
Copy this template into your project repository and adjust criteria to match your team's tech stack, process maturity, and compliance requirements. Review and update DoR/DoD at each retrospective.
