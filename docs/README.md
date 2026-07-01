# OctoAcme Project Management Docs

## Overview

This directory contains comprehensive process documentation for OctoAcme's project management approach. Our methodology emphasizes customer-first delivery, iterative development, clear ownership, and data-informed decisions.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features and collaborate on design and quality
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

---

## Quick Start Guide

### For New Team Members
1. Read this README to understand the OctoAcme approach
2. Review [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) to understand your role
3. Check [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for the high-level approach
4. Deep-dive into the phase that matches your current work (see Project Lifecycle below)

### For Project Kickoff
1. Review [octoacme-project-initiation.md](./octoacme-project-initiation.md) - validate business need and align stakeholders
2. Move to [octoacme-project-planning.md](./octoacme-project-planning.md) - break work into shippable increments
3. Execute using [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)

### For Risk Management
- See [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for identifying, assessing, and escalating risks

---

## OctoAcme Project Management Process Summary

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer value, iterative delivery, and clear ownership. The process flows through five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective & Continuous Improvement**. Each phase has defined deliverables and decision gates to ensure alignment and reduce risk. In the initiation phase, teams validate business need and create a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and resource requirements. Once stakeholder alignment is confirmed, the project moves into planning, where the work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a release plan is established. This deliberate front-loading of scope and stakeholder agreement prevents scope creep and sets clear expectations.

Execution emphasizes rapid, collaborative delivery through a structured team rhythm and workflow discipline. Teams conduct daily standups (15 minutes), weekly delivery syncs, and sprint-based planning cycles. Work flows through a project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), and pull requests are kept small (≤400 lines when possible) with automated CI checks for tests, linting, and security scanning before human review. Quality is non-negotiable: unit tests, integration tests, and smoke tests are standard practice, with manual QA for feature acceptance when needed. Blockers are escalated in three levels—team triage, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues—ensuring problems surface quickly and get attention proportional to their impact.

OctoAcme operates with clearly defined personas and a strong communication culture. Project Managers coordinate schedules, manage risks, and facilitate stakeholder alignment; Product Managers own prioritization, success metrics, and product vision; Developers implement features and collaborate on design and quality; and QA/Testing validates acceptance criteria. Communication is structured and frequent—weekly syncs between PM and PdM, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations as needed. A Risk Register is maintained throughout the project lifecycle to identify, assess, mitigate, and monitor risks, with owners assigned for each item. Incident communication and escalation paths are pre-defined, reducing uncertainty during crises.

Finally, OctoAcme closes the loop through retrospectives and continuous improvement. After each sprint, release, or important milestone, teams gather to discuss what went well, what could improve, and to define 2-3 prioritized action items with clear owners and due dates. These improvements feed back into the project backlog or process documentation, creating a cycle of learning and refinement. This commitment to capturing and acting on learnings—combined with structured roles, clear communication cadences, and quality-first execution—positions OctoAcme to deliver reliable products while building a culture of psychological safety and continuous growth.

---

## Project Lifecycle

### 1. Initiation

[octoacme-project-initiation.md](./octoacme-project-initiation.md) - Define initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.

**Key deliverables**: Project One-pager, Stakeholder list, High-level timeline, Initial risk list, Resource needs

**Decision gate**: Move to Planning when success metrics are clear, stakeholders agree on priority, and team availability is confirmed.

### 2. Planning

[octoacme-project-planning.md](./octoacme-project-planning.md) - Turn approved initiatives into actionable plans and backlogs for delivery.

**Key deliverables**: Prioritized backlog with acceptance criteria, Definition of Done, Release plan and milestone map, Risk register

**Decision gate**: Backlog is prioritized, releases are planned, and all dependencies are identified.

### 3. Execution & Tracking

[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) - Manage day-to-day execution and track progress toward project milestones.

**Key activities**: Daily standups, Weekly delivery syncs, Sprint planning, PR reviews, Quality assurance, Blocker escalation

**Rhythm**: Daily standups (15 min), Weekly delivery syncs, Demo/Review at end of sprint or milestone

### 4. Release & Deployment

[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) - Standardize how OctoAcme releases features to production to reduce risk and improve observability.

**Key activities**: Pre-release verification, Deployment to staging and production, Smoke testing, Rollback procedures, Release announcements

**Release types**: Patch (hotfixes), Minor (features), Major (breaking changes)

### 5. Retrospective & Continuous Improvement

[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and convert them into actionable improvements.

**Key activities**: Sprint/release retrospectives, Incident retrospectives, Action item tracking, Process refinement

**Cadence**: After each sprint, release, or important milestone (45-75 min sessions)

---

## Key Artifacts

Every project should maintain these core artifacts:

- **Project Charter / One-pager**: Problem statement, goals, success metrics, stakeholders, timeline
- **Roadmap and Release Plan**: High-level features and release schedule
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Definition of Done**: Shared understanding of what "done" means
- **Risk Register**: Identified risks, impact, mitigation plans, and status
- **Retrospective Notes**: Action items and learnings from reviews

---

## Communication Cadence

| Cadence | Participants | Purpose |
|---------|--------------|---------|
| **Daily Standup** | Delivery team | Progress, blockers, dependencies |
| **Twice-weekly Sync** | Delivery team | Planning and coordination |
| **Weekly PM + PdM Sync** | PM, Product Manager | Alignment on strategy and priorities |
| **Weekly Delivery Sync** | PM, PdM, Tech lead | Show progress, flag risks |
| **Monthly Stakeholder Update** | All stakeholders | High-level status and business impact |
| **Ad-hoc Escalation** | Relevant parties | Address blockers and critical issues |

---

## Reference Documents

- [Risk Management & Communication](./octoacme-risks-and-communication.md) - How to identify, manage, assess, mitigate, and communicate risks and dependencies throughout the project lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) - Detailed definitions of project roles and responsibilities with goals and typical communication patterns
- [Project Management Overview](./octoacme-project-management-overview.md) - Concise introduction to OctoAcme approach, principles, and high-level lifecycle

---

## How to Use These Docs

- **New to OctoAcme?** Start with this README, then read [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for a quick introduction.
- **Starting a new project?** Follow the lifecycle in order: Initiation → Planning → Execution → Release → Retrospective.
- **Need role guidance?** Consult [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) to understand your responsibilities and typical interactions.
- **Managing risks or dependencies?** Reference [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for structured approaches and escalation paths.
- **Process improvement?** See [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) for how to capture and implement learnings.

---

## Contributing to These Docs

We welcome feedback and contributions to improve our processes! To propose updates or new content:

1. **Create an issue** using the **["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. **Describe the change** - what's missing, what needs improvement, or what best practice should be added
3. **Provide rationale** - explain why this change is needed
4. **Suggest content** - optionally include draft text or examples

Our process docs are living documents that evolve with team feedback and learnings. Thank you for helping us scale institutional knowledge across OctoAcme!

---

## FAQ

**Q: What if my project doesn't fit neatly into these phases?**  
A: These phases are guidelines, not rigid requirements. Adapt them to your project's needs while maintaining the core principles of validation, planning, execution, and reflection.

**Q: How detailed should my documentation be?**  
A: Aim for clarity over completeness. Document decisions, trade-offs, and outcomes that future team members need to understand. Avoid unnecessary bureaucracy.

**Q: Who should be involved in retrospectives?**  
A: Include the full delivery team plus relevant stakeholders. Keep sessions focused on learning and improvement rather than blame.

**Q: Where do I find examples or templates?**  
A: Check the individual process documents (e.g., [Project One-pager Template](./octoacme-project-initiation.md#project-one-pager-template)) for specific templates and checklists.
