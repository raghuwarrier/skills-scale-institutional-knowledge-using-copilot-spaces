# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation! This folder contains guidance, templates, and best practices for running cross-functional projects successfully.

## Overview & Principles

OctoAcme follows a customer-first, iterative delivery approach to project management that emphasizes clear ownership, data-driven decisions, and psychological safety. The organization structures all cross-functional projects around a lightweight lifecycle that spans initiation, planning, execution, release, and retrospectives. At its core, OctoAcme's methodology prioritizes small, testable increments delivered regularly while maintaining transparency across stakeholders through consistent communication cadences—including weekly syncs between Project Managers and Product Managers, twice-weekly standups for delivery teams, and monthly stakeholder updates.

## Key Roles & Responsibilities

OctoAcme designates three primary roles to drive project success. **Product Managers** define what should be built by establishing problem statements, success metrics, and prioritized backlogs based on customer and business value. **Project Managers** coordinate delivery activities, manage schedules, risks, and communications to ensure teams meet commitments efficiently. **Developers** implement features to acceptance criteria, contribute to design and risk identification, and maintain high-quality, well-tested code. Each role has clear ownership boundaries, reducing confusion and enabling faster decision-making. Supporting these core roles are QA/Testing professionals and stakeholders who validate quality and provide necessary inputs and approvals.

## Execution, Quality & Risk Management

During execution, teams use GitHub Projects (or similar boards) with standardized columns—Backlog, Ready, In Progress, In Review, QA, Done—to maintain visibility. The organization enforces rigorous quality standards through unit tests, integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Small pull requests (≤400 lines) with clear issue links and acceptance criteria are required, along with at least one approval before merging. Risk management is built into every phase: teams identify and assess risks during planning and ongoing execution, maintain a risk register with impact/likelihood ratings and mitigation plans, and escalate blockers through three levels (team triage → PM escalation → sponsor escalation). Weekly syncs review risk status and dependencies, ensuring nothing surprises stakeholders.

## Learning & Continuous Improvement

OctoAcme closes each sprint, release, or milestone with structured retrospectives (45–75 minutes) that capture what went well, what could improve, and specific action items with owners and due dates. This culture of blameless learning—especially after incidents—feeds validated improvements back into the living process documentation stored in the repository's `docs/` folder. The organization uses this same documentation framework to onboard new team members quickly, reducing single-person dependency risk and enabling consistent, repeatable project execution across the organization.

---

## Process Docs Index

Navigate to the process documents below based on your project phase:

### Getting Started
- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, core roles, key artifacts, and communication cadence.

### Project Lifecycle

1. **[Project Initiation Guide](./octoacme-project-initiation.md)** — Define business need, validate outcomes, align stakeholders, and move to planning.
   - Use when: Ready to explore a new project idea or feature proposal
   - Deliverables: Project One-pager, stakeholder list, timeline, risk list

2. **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies, and align timelines.
   - Use when: Project is approved and ready for detailed planning
   - Deliverables: Prioritized backlog, Definition of Done, release plan, risk register

3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, track progress, and flag risks.
   - Use when: Team is actively building and shipping work
   - Key practices: Daily standups, weekly syncs, project board, PR workflow, quality gates

4. **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize how features reach production safely.
   - Use when: Ready to release to staging or production
   - Deliverables: Release notes, deployment checklist, rollback plan

5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements.
   - Use when: Completing a sprint, release, or milestone
   - Cadence: 45–75 minutes, prioritize 2–3 action items

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout the project lifecycle.
  - Key artifacts: Risk register, weekly status templates, escalation paths

- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed role definitions and responsibilities for Project Managers, Product Managers, Developers, QA, and Stakeholders.

---

## Quick Tips for New Team Members

1. **Start with the [Project Management Overview](./octoacme-project-management-overview.md)** to understand the big picture.
2. **Reference the [Roles & Personas](./octoacme-roles-and-personas.md)** document to understand team structures and responsibilities.
3. **Use the [Execution & Tracking](./octoacme-execution-and-tracking.md)** guide during sprint planning and daily standups.
4. **Keep the [Risk Register](./octoacme-risks-and-communication.md#risk-register)** updated weekly—it's your safety net for transparency.
5. **Review past [Retrospectives](./octoacme-retrospective-and-continuous-improvement.md)** to learn from recent projects.

## How to Contribute

These docs are living artifacts. If you see a gap, have a suggestion, or want to refine guidance:

1. Open an issue using the **[Process Doc Update template]**(./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
2. Describe the change, rationale, and suggested content
3. Work with your Product Lead and team to refine and merge updates

---

## Questions?

If you can't find what you're looking for, or have questions about OctoAcme's processes:
- Check the relevant process doc for your phase (see index above)
- Ask your Project Manager or Product Lead
- Open an issue to request clarification or new content

---

**Last Updated:** 2026-02-22  
**Maintained by:** OctoAcme Project Management Community
