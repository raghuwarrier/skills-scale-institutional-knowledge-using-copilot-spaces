# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

### Communication Pathways by Persona
| Persona | Primary Channel | Cadence | Key Audience |
|---|---|---|---|
| UX Designer | Design review meetings, Figma comments | Per sprint / milestone | Product Manager, Developers |
| DevOps Engineer | Deployment announcements, incident bridges | Per release / incident | Developers, Project Manager, Support Lead |
| Business Analyst | Requirements docs, stakeholder workshops | Initiation, planning, ongoing | Product Manager, Project Manager |
| Support Lead | Bug triage reviews, post-release reports | Weekly / post-release | Developers, Project Manager |
| Quality Lead | Quality status reports, release signoff meetings | Weekly / pre-release | Project Manager, Developers |

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

### Role-Specific Escalation Paths
- **Quality Lead:** Quality blocker or critical defect -> Quality Lead -> PM -> Product Lead
- **DevOps Engineer:** Infrastructure/deployment failure -> DevOps Engineer -> PM -> Sponsor (if production-impacting)
- **UX Designer:** Design dependency blocking sprint -> UX Designer -> PM -> Product Lead
- **Business Analyst:** Requirement ambiguity blocking delivery -> Business Analyst -> PM -> Stakeholder
- **Support Lead:** Critical customer-facing issue -> Support Lead -> PM -> DevOps Engineer (for hotfix coordination)

### Risk Examples by Role
| Role | Example Risk | Mitigation |
|---|---|---|
| Quality Lead | Insufficient test coverage before release | Engage Quality Lead in sprint planning to size test work |
| DevOps Engineer | CI/CD pipeline failure blocking deployment | DevOps review of pipeline health before release window |
| UX Designer | Design assets late, blocking development | Include design milestones in sprint planning |
| Business Analyst | Requirement change late in sprint | BA validates requirements with stakeholders before sprint start |
| Support Lead | Surge in post-release support tickets | Support Lead attends release briefing; feedback loop to PM and Devs |
