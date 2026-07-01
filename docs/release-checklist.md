# Release & Deployment Checklist (expanded)

Purpose
- A short, actionable checklist to reduce deployment risk and ensure consistent runbook steps for releases.

Pre-release (staging)
- [ ] All acceptance criteria met and verified in PRs
- [ ] Passing CI and automated security scans
- [ ] Release Manager assigned (name or role)
- [ ] RACI: release activity responsibilities confirmed
- [ ] Migration or data-change plan reviewed (if applicable)
- [ ] Feature flags prepared (if feature rollout staged)
- [ ] Staging smoke tests defined and scheduled

Deployment
- [ ] Deployment window scheduled and communicated
- [ ] Backups/snapshots taken (if applicable)
- [ ] Runbook ready and owner confirmed
- [ ] Rollback plan and steps documented and tested
- [ ] Execute deployment via automated pipeline where possible
- [ ] Run post-deploy smoke tests (owner: Release Manager / QA)
- [ ] Validate critical metrics and alerts (owner: Data / DevOps)
- [ ] Verify accessibility-critical flows (owner: Accessibility Specialist / QA)
- [ ] Notify stakeholders and support (owner: PM / Release Manager)

Post-release
- [ ] Monitor dashboards for 15–60 minutes (or longer for important changes)
- [ ] Triage and escalate any regressions via defined escalation path
- [ ] Capture release notes and known issues
- [ ] Close roll-forward/rollback logs and record lessons if any

Roles & suggested owners
- Release Manager: runbook execution and stakeholder notifications  
- DevOps / Platform Engineer: pipeline and infra health  
- QA: smoke and acceptance checks  
- Data Analyst: verify metrics/telemetry  
- Support/Customer Success: monitor customer reports

Templates & links
- Link this file from the project README and to the Release Manager runbook (if one exists).
