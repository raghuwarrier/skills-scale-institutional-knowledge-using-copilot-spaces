# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
  - Developers, Quality Lead, and UX Designer resolve within the team where possible
- Level 2: PM escalates to Product Lead and dependent teams
  - DevOps Engineer consulted for infrastructure/deployment blockers
  - Business Analyst consulted for requirement ambiguity blockers
- Level 3: Sponsor-level escalation for business-impacting issues
  - Support Lead notified for customer-facing issues
  - Quality Lead provides severity assessment for quality-related escalations

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Quality Lead signoff obtained before release candidate is declared
- [ ] DevOps Engineer confirms release readiness (pipeline, infra, rollback plan)
- [ ] UX feedback loop in place: design review completed before implementation and post-release usability feedback collected
- [ ] Business Analyst has validated backlog items against requirements before sprint start
- [ ] Support Lead briefed on upcoming changes before each release
