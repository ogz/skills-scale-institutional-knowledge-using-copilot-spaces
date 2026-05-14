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

## Suggested Additional Personas (proposed additions)

Below are suggested personas that can improve clarity, accountability, and cross-team coordination for OctoAcme projects. Each entry includes a short responsibilities list and how the role typically interacts with existing roles.

### Tech Lead / Software Architect

Role Summary
The Tech Lead (or Architect) owns technical direction for a project, makes architecture decisions, and ensures design consistency across the codebase.

Responsibilities
- Define and communicate system architecture and major technical decisions
- Review designs and significant PRs for alignment with architecture
- Mentor developers and guide implementation approaches
- Own non-functional requirements (scalability, performance)

Interactions
- Works with Project Managers on technical risk and estimates
- Partners with Product Managers to align technical trade-offs with product priorities
- Reviews work with Developers and collaborates with QA and DevOps for production readiness

### Engineering Manager

Role Summary
The Engineering Manager supports team health, career development, and resource planning while coordinating with PMs and Tech Leads to deliver outcomes.

Responsibilities
- Manage team capacity and allocation
- Facilitate hiring, onboarding, and performance feedback
- Support removal of blockers and organizational impediments
- Ensure engineering process adherence and continuous improvement

Interactions
- Coordinates with Project Managers on resourcing and timelines
- Works with Tech Leads on technical direction
- Supports Developers with coaching and performance management

### UX Researcher / Product Designer

Role Summary
Responsible for user research, interaction design, and ensuring product decisions are grounded in user needs.

Responsibilities
- Conduct user research and usability testing
- Produce wireframes, prototypes, and design specs
- Validate designs against success metrics and accessibility standards
- Collaborate on acceptance criteria for user-facing features

Interactions
- Partners with Product Managers to translate user needs into product requirements
- Works closely with Developers to implement designs and clarify UX details
- Shares findings with stakeholders and QA for testing scenarios

### QA Lead / Test Engineer

Role Summary
Focuses on test strategy, automation coverage, and quality gates to reduce defects and improve release confidence.

Responsibilities
- Define testing strategy (unit, integration, E2E) and maintain test plans
- Implement and maintain automated test suites and CI checks
- Coordinate manual testing for acceptance when required
- Track quality metrics and work with teams to close gaps

Interactions
- Works with Developers and Tech Leads to design testable systems
- Partners with Project Managers to set exit criteria for releases
- Collaborates with DevOps for reliable test environments

### DevOps / Platform Engineer

Role Summary
Ensures build/release pipelines, infrastructure as code, observability, and runbook readiness for production systems.

Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, monitoring, and alerting
- Support performance tuning and incident response readiness
- Own deployment and rollback procedures

Interactions
- Works with Project Managers and Release Manager to coordinate deployments
- Partners with Developers and QA for environment parity and testing
- Collaborates with Security on hardening and compliance

### Security & Compliance Lead

Role Summary
Responsible for security risk assessment, threat modeling, and ensuring compliance standards are met.

Responsibilities
- Conduct security reviews and threat models for features
- Define security acceptance criteria and remediation plans
- Coordinate security scans and manage vulnerabilities
- Liaise with legal/compliance for regulatory requirements

Interactions
- Works with Tech Leads and DevOps to implement mitigations
- Coordinates with Product Managers and PMs to prioritize security work
- Engages with Stakeholders for compliance sign-off

### Data Analyst / Data Engineer

Role Summary
Provides data insights, measurement instrumentation, and pipeline support to validate success metrics and inform decisions.

Responsibilities
- Define tracking and instrumentation for success metrics
- Build dashboards and reports to measure feature impact
- Clean and transform data for analysis and shareable insights
- Support experiments and A/B testing

Interactions
- Partners with Product Managers on success metrics and experiments
- Works with Developers to ensure correct telemetry and event design
- Reports findings to PMs, PdMs, and stakeholders

### Customer Success / Support Owner

Role Summary
Represents post-release customers and support needs; captures feedback that informs product improvements and operational support.

Responsibilities
- Triage customer-reported issues and escalations
- Provide input on prioritization based on customer impact
- Produce support-runbooks and knowledge-base updates
- Track customer satisfaction metrics

Interactions
- Works with PMs and Project Managers on prioritization for customer-impacting issues
- Collaborates with Developers, QA, and DevOps during incident triage
- Shares feedback with Product Managers for roadmap adjustments

### Release Manager

Role Summary
Coordinates release activities across teams to ensure smooth, low-risk deliveries.

Responsibilities
- Maintain release calendar and coordinate release windows
- Ensure release checklist and rollback plans are completed
- Coordinate stakeholder communications pre/post-release
- Verify post-deploy verifications and monitor metrics

Interactions
- Works closely with DevOps, Project Managers, and PMs to schedule and execute releases
- Coordinates with QA and Customer Success for verification and announcements

---

How to adopt these additions
- Start by adding a "Suggested Additional Personas" section (this change is proposed to docs/octoacme-roles-and-personas.md).
- For each project, identify which of these personas are applicable and capture role owners in the project charter.
- Update ISSUE_TEMPLATE for process-doc updates to include an explicit checkbox for persona additions.

