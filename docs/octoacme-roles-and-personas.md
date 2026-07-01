# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas & Responsibilities

This section adds commonly involved cross-functional and operational personas to clarify ownership, handoffs, and escalation paths.

- Technical Program Manager (TPM)  
  Responsibilities: Coordinate complex cross-team schedules, manage milestone dependency maps, and own program-level risk tracking.  
  Primary interactions: Works closely with PM and PdM for prioritization; negotiates timelines and scope with Engineering Managers and TPMs in dependent teams.

- Engineering Manager (EM)  
  Responsibilities: People management, capacity planning, and delivery trade-off decisions for engineering teams.  
  Primary interactions: Partners with PM/TPM on resourcing and with Developers to unblock technical execution; escalates staffing or skills gaps.

- UX Researcher / Designer  
  Responsibilities: Lead user research, prototypes, usability testing, and accessibility guidance; contribute to acceptance criteria and UX validation.  
  Primary interactions: Collaborates with PdM to define user outcomes and Developer/QA to validate designs against acceptance criteria.

- Release Manager  
  Responsibilities: Coordinate release windows, maintain runbooks, produce release notes, and own rollback plans and post-release verifications.  
  Primary interactions: Works with PM, DevOps/Platform, Support/Customer Success, and Security to ensure safe deployments and stakeholder notifications.

- DevOps / Platform Engineer  
  Responsibilities: Maintain CI/CD pipelines, infrastructure-as-code, observability, and deployment safety.  
  Primary interactions: Supports Developers and Release Manager during deployments; works with Security Owner for compliance and with PM/TPM for environment needs.

- Security Owner  
  Responsibilities: Lead threat modeling, security reviews, and ensure security scans/controls are included in CI and release gates.  
  Primary interactions: Engages with PdM for risk trade-offs and with DevOps/Developers for remediation timelines; advises Release Manager.

- Data Analyst / Data Engineer  
  Responsibilities: Define and instrument success metrics, build dashboards and queries for monitoring project outcomes.  
  Primary interactions: Works with PdM to validate success metrics and with PM/Developers to prioritize telemetry and measurement work.

- Customer Success / Support Liaison  
  Responsibilities: Represent customer signals, triage support-impacting issues, and coordinate customer communications and known-issues lists.  
  Primary interactions: Feeds customer feedback to PdM and PM; coordinates post-release communications with Release Manager and Support.

- Accessibility Specialist  
  Responsibilities: Validate accessibility requirements, review designs, and test critical flows for compliance.  
  Primary interactions: Collaborates with UX and Developers to include accessibility in acceptance criteria and release checkpoints.

- Legal / Compliance Liaison  
  Responsibilities: Review regulatory/data handling impacts, contracts, and required approvals; surface constraints at planning.  
  Primary interactions: Engages at planning with PdM/PM and revisits during design and release for compliance sign-off.

How this helps
- Clarifies ownership for operational tasks (releases, security, observability) preventing last-minute confusion.  
- Improves handoffs by specifying interactions and expected inputs/outputs between roles.  
- Reduces risk and delivery delays by making stakeholders explicit for common escalation paths.

Suggested usage
- Keep descriptions short (1–3 lines). Where useful, link to role-specific runbooks (e.g., Release Manager runbook).  
- Add a one-line "Primary interactions" note for each new persona so teams understand expected handoffs quickly.
