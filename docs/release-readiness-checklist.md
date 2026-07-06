# Release Readiness Checklist

Purpose: a lightweight, reproducible checklist to confirm readiness for staging and production releases. Intended to be referenced from the Release & Deployment Guide.

- Release title / tag:
- Release owner (name):
- Linked issue / PRs:
- Release type: (patch/minor/major)
- Release date / window:
- Cutover owner / Delivery Lead:
- Rollback owner and plan documented: [ ] Yes

Pre-deploy
- [ ] All linked PRs merged and passing CI
- [ ] Security scans completed and any critical findings resolved or mitigated
- [ ] Migration steps (if any) documented and validated in staging
- [ ] Release automation runbook available and validated
- [ ] Deployment checklist created and assigned
- [ ] Release notes drafted and reviewed

Staging verification
- [ ] Smoke tests executed and passing
- [ ] End-to-end critical flows validated
- [ ] Observability: monitors/dashboards validated for new changes
- [ ] Runbooks and playbooks reviewed by SRE/Observability representative
- [ ] UX/PM sign-off on visible user-facing changes

Production deployment
- [ ] Backup/snapshot (if applicable) completed
- [ ] Deployment performed by Release Engineer / automation
- [ ] Post-deploy smoke tests executed
- [ ] Metrics & alerts observed for N minutes after deploy (agreed window)
- [ ] Customer communications sent (if applicable)

Post-deploy
- [ ] Incident/roll-forward checklist available
- [ ] Post-release retrospective scheduled
- [ ] Action items created and added to project board

Notes: link any runbooks, dashboards, and support pages here.
