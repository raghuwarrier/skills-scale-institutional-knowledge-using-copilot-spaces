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

---

## UX Designer

### Role Summary
UX Designers are responsible for designing intuitive, accessible interfaces and ensuring the overall usability of the product. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Create wireframes, prototypes, and high-fidelity mockups
- Conduct usability testing and synthesize findings
- Maintain a design system and component library
- Collaborate with Product Managers on user stories and acceptance criteria
- Provide design assets and specs to Developers
- Iterate designs based on user feedback and analytics

### Goals
- Deliver experiences that are intuitive, accessible, and delightful
- Reduce friction in user journeys and support task completion
- Align visual and interaction design with brand standards

### Typical Communication
- Design reviews with Developers and Product Managers during sprint planning and mid-sprint
- Async design feedback via design tools (e.g., Figma comments) and PR reviews
- Participation in retrospectives to share usability feedback collected post-release

### Interaction with Existing Roles
- **Product Manager:** Co-define acceptance criteria for UX quality; validate designs against user research
- **Developers:** Provide design specs and answer implementation questions; review PR screenshots/demos
- **Project Manager:** Flag design-related risks or dependencies (e.g., asset readiness, design debt)

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage CI/CD pipelines, infrastructure automation, deployment orchestration, and the reliability of production systems. They ensure software can be delivered safely and repeatably.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Manage infrastructure as code (IaC) and cloud environments
- Monitor system health, performance, and availability
- Coordinate with Developers and Project Managers for release planning
- Define deployment runbooks and rollback procedures
- Respond to and lead resolution of infrastructure incidents

### Goals
- Enable fast, safe, and automated deployments
- Minimize production incidents and mean time to recovery (MTTR)
- Maintain infrastructure security, reliability, and cost efficiency

### Typical Communication
- Participate in release planning meetings and deployment window scheduling
- On-call rotation and incident bridges for production issues
- Infrastructure change announcements and post-incident reviews

### Interaction with Existing Roles
- **Developers:** Assist with build/deployment configuration; advise on containerization and cloud services
- **Project Manager:** Provide release readiness confirmation; flag infrastructure risks ahead of deployments
- **Quality Lead:** Coordinate staging environment availability for test cycles

---

## Business Analyst

### Role Summary
Business Analysts identify and document business requirements, facilitate alignment between stakeholders and the delivery team, and ensure the solution addresses the right problem.

### Responsibilities
- Lead discovery sessions and stakeholder interviews
- Document requirements, process flows, and use cases
- Validate backlog items against business objectives
- Identify gaps between current-state processes and desired outcomes
- Support UAT (User Acceptance Testing) coordination

### Goals
- Ensure delivery solves the right business problems
- Produce clear, testable requirements that reduce rework
- Bridge communication gaps between technical and business stakeholders

### Typical Communication
- Discovery workshops and requirements reviews at initiation and planning
- Ongoing collaboration with Product Manager and Project Manager during sprints
- UAT coordination with stakeholders and the Quality Lead prior to release

### Interaction with Existing Roles
- **Product Manager:** Collaborate on backlog refinement and requirements validation
- **Project Manager:** Surface scope changes and dependency risks early
- **Quality Lead:** Provide requirements documentation as input to test planning

---

## Support Lead

### Role Summary
The Support Lead serves as the front-line owner for end-user issues and post-release feedback cycles. They triage incoming bugs, coordinate issue resolution, and relay customer insights back to the delivery team.

### Responsibilities
- Monitor support channels and triage incoming bugs and user issues
- Coordinate escalation of critical issues to Developers and Project Manager
- Document recurring issues and support trends for continuous improvement
- Participate in release reviews to understand upcoming changes
- Provide post-deployment feedback on user-reported issues

### Goals
- Minimize customer impact from bugs and release issues
- Close the feedback loop between end users and the delivery team
- Reduce repeat support tickets through root-cause resolution

### Typical Communication
- Weekly bug triage reviews with Developers
- Post-release briefings with the Project Manager on support trends
- Incident updates to stakeholders during active production issues

### Interaction with Existing Roles
- **Developers:** Report reproducible bugs with context; confirm fixes before closing tickets
- **Project Manager:** Provide support trend summaries; flag patterns requiring prioritization
- **DevOps Engineer:** Escalate infrastructure-related customer issues; coordinate on hotfix deployments

---

## Quality Lead

### Role Summary
The Quality Lead oversees the overall QA strategy, test planning, automation, and defect management to ensure releases meet defined quality standards.

### Responsibilities
- Develop and maintain the test strategy and test plans
- Own test case authoring, execution, and automation frameworks
- Drive defect triage and resolution processes
- Coordinate UAT with Business Analysts and stakeholders
- Sign off on release readiness from a quality perspective

### Goals
- Prevent regressions and ensure new features meet acceptance criteria
- Increase test automation coverage to support faster release cycles
- Provide clear quality metrics and reporting to the Project Manager

### Typical Communication
- Daily collaboration with Developers during active sprints
- Weekly quality status reporting to the Project Manager
- Pre-release signoff meetings before deployments

### Interaction with Existing Roles
- **Developers:** Pair on bug reproduction, fix validation, and test automation
- **Project Manager:** Provide quality gates and release readiness assessments
- **DevOps Engineer:** Align on test environment availability and pipeline integration for automated tests
- **Business Analyst:** Use requirements and use cases as the basis for test planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

