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
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared
- See [Release Readiness Review Checklist](octoacme-role-handoffs-and-ceremonies-checklist.md#release-readiness-review) for complete ceremony guidance

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred, coordinated by DevOps Engineer)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] See [QA to Release Handoff](octoacme-role-handoffs-and-ceremonies-checklist.md#qa-to-release) and [Release to Operations Handoff](octoacme-role-handoffs-and-ceremonies-checklist.md#release-to-operations) guidelines

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads)
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Follow up with blameless retrospective

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
