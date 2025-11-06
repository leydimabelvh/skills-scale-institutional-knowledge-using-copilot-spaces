# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (validated by Product Manager and QA/Test)
- Passing CI and security scans (Engineering Lead reviews security findings)
- Release notes drafted (PM coordinates with Product Manager)
- Rollback / mitigation plan documented (Engineering Lead approves)
- Smoke tests prepared (QA/Test Engineers define and execute)
- **Compliance review** completed (if applicable - Compliance/Regulatory Stakeholder sign-off)
- **Support readiness** confirmed (Support/Customer Success has documentation and training materials)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) - PM coordinates
- [ ] Backup or snapshot (if applicable) - Engineering Lead ensures
- [ ] Deploy to staging and run smoke tests - QA/Test Engineers validate
- [ ] UX Designer validates user-facing changes in staging
- [ ] Compliance/Regulatory final approval (if required)
- [ ] Deploy to production (automated pipeline preferred) - Engineering Lead monitors
- [ ] Run post-deploy verifications - QA/Test and Engineering Lead
- [ ] Announce release to stakeholders - PM communicates
- [ ] Support/Customer Success notified with release documentation and training materials

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
