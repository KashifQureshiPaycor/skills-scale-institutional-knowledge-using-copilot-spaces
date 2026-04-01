# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
| Type | Description | Examples |
|------|-------------|---------|
| Patch | Hotfixes addressing critical production issues | Bug fixes, security patches |
| Minor | Incremental features and improvements | New feature flags, UI improvements |
| Major | Significant functionality or breaking changes | API version changes, major redesigns |

## Pre-release requirements
- All acceptance criteria met and PRs merged
- All items in scope meet the [Definition of Done](templates/definition-of-ready-and-done.md)
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Release Readiness Checklist
Use the **[Release Readiness Checklist](templates/release-readiness-checklist.md)** to confirm all quality gates, approvals, and operational tasks are complete. The checklist covers:
1. Code & Quality Gates
2. Release Documentation
3. Staging / Pre-Production Validation
4. Operational Readiness
5. Stakeholder Approvals
6. Post-Deploy Verification

## Deployment Checklist
- [ ] [Release Readiness Checklist](templates/release-readiness-checklist.md) complete and all approvals obtained
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items in the [RAID Log](templates/raid-log-template.md)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

---

**Previous phase:** [Execution & Tracking ←](octoacme-execution-and-tracking.md) | **Next phase:** [Retrospective →](octoacme-retrospective-and-continuous-improvement.md)
