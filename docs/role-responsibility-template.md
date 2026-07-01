# Role Responsibility & RACI Template

Purpose
- Provide a lightweight, repeatable template teams can use to capture who is Responsible, Accountable, Consulted, and Informed (RACI) for key activities and deliverables.

How to use
1. For a given feature, milestone, or operational activity, copy the table below into the project README or a short doc in docs/.
2. Fill the columns with people or roles (e.g., PdM, PM, TPM, EM, Developer, QA, Release Manager).
3. Keep it minimal: prefer roles to individual names. Update responsibilities during planning.

RACI table template (example)
| Activity / Deliverable | Responsible (R) | Accountable (A) | Consulted (C) | Informed (I) |
|---|---:|---:|---:|---:|
| Define success metrics | Data Analyst / PdM | PdM | PM, Developer | Stakeholders |
| Release planning | Release Manager | PM | DevOps, QA, PdM | Support, Legal |
| Security review | Security Owner | Security Owner | DevOps, EM | PdM, PM |
| Post-release verification | Release Manager | PM | DevOps, QA | Stakeholders & Support |

Optional extended fields
- Contact: (role or person)
- SLA / expected turnaround
- Escalation path (who to contact if blocked)

Tip: Add this as a short section in the project README and link to docs/role-responsibility-template.md for anyone onboarding to the project.
