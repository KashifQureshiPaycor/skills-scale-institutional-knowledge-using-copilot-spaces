# Release Readiness Checklist

## Purpose
Confirm that all quality gates, approvals, and operational tasks are complete before deploying to production.

---

## How to Use
Copy this checklist into the release issue or PR for each release. Complete all items in order. Obtain required approvals before proceeding to the next section.

**Release:** `[Release name / version]`
**Target Date:** `YYYY-MM-DD`
**Release Manager:** `[Name]`

---

## 1 — Code & Quality Gates

- [ ] All stories / features in scope meet the [Definition of Done](definition-of-ready-and-done.md)
- [ ] All PRs merged to the release branch
- [ ] CI pipeline passing (build, unit tests, integration tests, lint)
- [ ] Security scan passing with no new critical/high vulnerabilities
- [ ] Code coverage meets or exceeds team threshold
- [ ] No known P1 or P2 bugs outstanding (or exceptions documented and approved)

**Code & Quality Gate Approver:** `[Name]` **Date:** `YYYY-MM-DD`

---

## 2 — Release Documentation

- [ ] Release notes drafted and reviewed (see [Release & Deployment Guide](../octoacme-release-and-deployment.md))
- [ ] Migration guide or upgrade notes written (if applicable)
- [ ] User-facing documentation updated
- [ ] Internal runbooks / playbooks updated
- [ ] API changelog updated (if applicable)

**Documentation Approver:** `[Name]` **Date:** `YYYY-MM-DD`

---

## 3 — Staging / Pre-Production Validation

- [ ] Deployed to staging environment successfully
- [ ] Smoke tests executed and passing
- [ ] End-to-end tests executed and passing (if applicable)
- [ ] Performance / load testing completed (if applicable)
- [ ] Exploratory / manual QA completed and signed off
- [ ] Data migration tested in staging (if applicable)

**QA Approver:** `[Name]` **Date:** `YYYY-MM-DD`

---

## 4 — Operational Readiness

- [ ] Deployment runbook reviewed and updated
- [ ] Rollback plan documented and validated
- [ ] Feature flags / toggles configured correctly
- [ ] Monitoring and alerting verified (dashboards, alert thresholds)
- [ ] On-call rotation confirmed for release window
- [ ] Support team briefed on new features and known issues
- [ ] Deployment window communicated to stakeholders

**Ops Approver:** `[Name]` **Date:** `YYYY-MM-DD`

---

## 5 — Stakeholder Approvals

- [ ] Product Manager sign-off
- [ ] Project Manager sign-off
- [ ] Security / Compliance sign-off (if required)
- [ ] Sponsor / Executive sign-off (for Major releases)

**Final Go/No-Go Decision:** ✅ Go / ❌ No-Go
**Decision Owner:** `[Name]` **Date:** `YYYY-MM-DD`

---

## 6 — Post-Deploy Verification (complete after deployment)

- [ ] Application is accessible and healthy in production
- [ ] Key user flows verified in production (smoke test)
- [ ] Monitoring dashboards showing expected baseline
- [ ] No spike in error rates or latency
- [ ] Release announcement sent to stakeholders
- [ ] Release notes published

**Post-Deploy Sign-Off:** `[Name]` **Date:** `YYYY-MM-DD`

---

## Release Summary

| Item | Detail |
|------|--------|
| Version | |
| Deployment method | Automated pipeline / Manual |
| Deployment start time | |
| Deployment end time | |
| Rollback required? | Yes / No |
| Issues encountered | |

---

## Related Documents
- [Definition of Ready & Done](definition-of-ready-and-done.md)
- [Risk Register Template](risk-register-template.md)
- [Release & Deployment Guide](../octoacme-release-and-deployment.md)
- [Project Closeout Checklist](project-closeout-checklist.md)
