# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (Technical Writer with Project Manager)
- User-facing documentation updated (Technical Writer)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Design implementation validated (UX Designer)
- Analytics and metrics verified (Data Analyst)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] UX Designer validates design implementation in staging
- [ ] Data Analyst verifies analytics are functioning correctly
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Technical Writer publishes updated documentation
- [ ] Data Analyst monitors metrics for anomalies post-release

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
- Documentation updates (link to updated docs)
- Prepared by: Technical Writer, reviewed by: Project Manager and Product Manager
