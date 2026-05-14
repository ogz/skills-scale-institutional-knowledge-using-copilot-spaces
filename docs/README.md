# OctoAcme Project Management Documentation

Welcome to the **OctoAcme Project Management Documentation**. This repository centralizes the processes, practices, and guidance for planning, executing, and delivering projects at OctoAcme.

Our documentation is designed to:
- ✅ **Centralize institutional knowledge** — Convert tacit team insights into searchable, versioned artifacts
- ✅ **Accelerate onboarding** — Give all team members equal access to processes and decisions
- ✅ **Enable consistency** — Ensure repeatable, predictable project execution
- ✅ **Reduce dependency risk** — Document decisions and rationale to minimize single-person knowledge silos

---

## 🚀 Project Lifecycle

Follow these guides as you move through each stage of your project:

### 1. **Project Initiation**
[📄 octoacme-project-initiation.md](./octoacme-project-initiation.md)

Validate business need, align stakeholders, and authorize work before planning begins.
- When: Before planning a new project or major initiative
- Deliverables: Project One-pager, stakeholder list, high-level timeline
- Decision gate: Proceed to Planning only when success metrics are clear and stakeholders align

### 2. **Project Planning**
[📄 octoacme-project-planning.md](./octoacme-project-planning.md)

Turn an approved initiative into an actionable plan, backlog, and release roadmap.
- Activities: Kickoff, backlog prioritization, estimation, Definition of Done, risk mapping
- Deliverables: Prioritized backlog, release plan, milestone map, test strategy
- Output: Ready-to-execute sprint backlog with acceptance criteria

### 3. **Execution & Tracking**
[📄 octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)

Manage day-to-day delivery and track progress toward milestones.
- Team rhythm: Daily standups (15 min), weekly delivery sync, sprint demos
- Workflow: GitHub Projects board, small PRs, automated testing, at least 1 approval before merge
- Quality gates: Unit tests, integration tests, end-to-end smoke tests, security scanning
- Metrics: Track velocity, burndown, and success metrics from the One-pager

### 4. **Release & Deployment**
[📄 octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)

Standardize releases to production to reduce risk and maintain observability.
- Pre-release: All acceptance criteria met, CI passing, release notes drafted, rollback plan ready
- Deployment: Staging verification → Production deployment → Post-deploy verification
- Incident response: Documented rollback procedures and incident playbook

### 5. **Retrospective & Continuous Improvement**
[📄 octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)

Capture learnings and convert them into actionable improvements.
- When: After each sprint, release, or important milestone
- Structure: What went well → What could improve → Action items with owners and due dates
- Culture: Measure impact of improvements, celebrate wins, iterate continuously

---

## 📚 Core Guidance Documents

### **Project Management Overview**
[📄 octoacme-project-management-overview.md](./octoacme-project-management-overview.md)

Your introduction to how OctoAcme runs projects:
- **Principles**: Customer-first, iterative delivery, clear ownership, data-informed, psychological safety
- **Core roles**: Project Manager, Product Manager, Developers, QA, Stakeholders
- **Key artifacts**: Charter, roadmap, backlog, acceptance criteria, risk register, retrospectives
- **Communication cadence**: Weekly PM+PdM sync, twice-weekly standups, monthly stakeholder updates

### **Roles & Personas**
[📄 octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)

Define typical roles and responsibilities across OctoAcme projects:
- **Developers** — Design, build, test, deliver; write tests and docs; participate in reviews
- **Product Managers** — Define what should be built; prioritize backlog; measure outcomes
- **Project Managers** — Coordinate delivery; manage schedules, risks, communications
- **Stakeholders** — Provide input and approvals; align on priorities and trade-offs

### **Risk Management & Communication**
[📄 octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)

Identify, manage, and communicate risks and dependencies:
- **Risk register**: Track ID, description, impact, likelihood, owner, mitigation, status
- **Stakeholder communication**: Weekly status updates, incident communication templates
- **Escalation paths**: Team-level → PM → Product Lead → Sponsor

---

## 🎯 Our Core Principles

All OctoAcme projects are guided by these five principles:

1. **Customer-First** — Prioritize customer value and usability in all decisions
2. **Iterative Delivery** — Deliver small, testable increments; gather feedback early and often
3. **Clear Ownership** — Each project has a named PM and Product Lead with clear accountability
4. **Data-Informed Decisions** — Measure impact and iterate based on evidence, not assumptions
5. **Psychological Safety** — Encourage feedback, learning, and blameless retrospectives

---

## 🧭 Quick Start by Role

### 👨‍💼 I'm a Project Manager
1. Start with [**Project Management Overview**](./octoacme-project-management-overview.md)
2. For your first project, follow: [**Initiation**](./octoacme-project-initiation.md) → [**Planning**](./octoacme-project-planning.md) → [**Execution & Tracking**](./octoacme-execution-and-tracking.md)
3. Reference [**Risk Management & Communication**](./octoacme-risks-and-communication.md) for escalations and stakeholder updates
4. After delivery, run a [**Retrospective**](./octoacme-retrospective-and-continuous-improvement.md)

### 📊 I'm a Product Manager
1. Review [**Project Management Overview**](./octoacme-project-management-overview.md) to understand the PM relationship
2. Use [**Project Initiation**](./octoacme-project-initiation.md) to validate business need and success metrics
3. Reference [**Project Planning**](./octoacme-project-planning.md) for backlog prioritization and acceptance criteria
4. Track success metrics during [**Execution & Tracking**](./octoacme-execution-and-tracking.md)
5. Participate in [**Release & Deployment**](./octoacme-release-and-deployment.md) for go/no-go decisions

### 💻 I'm a Developer
1. Review [**Roles & Personas**](./octoacme-roles-and-personas.md) to understand developer responsibilities
2. During planning, clarify acceptance criteria with the Product Manager
3. Reference [**Execution & Tracking**](./octoacme-execution-and-tracking.md) for PR workflow, testing, and CI requirements
4. Follow the Definition of Done and contribute to [**Retrospectives**](./octoacme-retrospective-and-continuous-improvement.md)

### 🤝 I'm a New Team Member
1. Start here with the [**Project Management Overview**](./octoacme-project-management-overview.md)
2. Read [**Roles & Personas**](./octoacme-roles-and-personas.md) to understand the team structure
3. Review the [**Project Lifecycle** section above](#-project-lifecycle) for a high-level flow
4. Explore specific docs as you engage with projects

---

## 📖 Document Index

| Document | Purpose | When to Use |
|----------|---------|------------|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | Introduction to OctoAcme approach, roles, and artifacts | Onboarding, reference |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Validate business need and authorize work | Starting a new project |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Create actionable plans and backlog | After initiation, before execution |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Day-to-day delivery and progress tracking | During project execution |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Identify and communicate risks | Ongoing, especially escalations |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Standardize releases to production | Before release to production |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and iterate | After sprints, releases, milestones |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Define roles and responsibilities | Understanding team structure |

---

## 💡 How to Propose Updates

Have an idea to improve these processes? We welcome feedback and continuous improvement!

**To suggest changes or additions:**
1. Create a new issue using the **["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template
2. Describe what should be added, updated, or clarified
3. Explain the rationale (gap in process, team feedback, best practice, etc.)
4. Include suggested content if you have draft text

---

## 🔗 Useful Links

- **Project Board Template**: Use GitHub Projects to manage your project backlog and track progress
- **Issue Templates**: Found in `.github/ISSUE_TEMPLATE/` for process doc updates and project initiation
- **Repository**: [skills-scale-institutional-knowledge-using-copilot-spaces](https://github.com/ogz/skills-scale-institutional-knowledge-using-copilot-spaces)

---

## ❓ FAQs

**Q: Which document should I read first?**  
A: Start with [Project Management Overview](./octoacme-project-management-overview.md). Then follow your role's quick-start guide above.

**Q: How often should we update these docs?**  
A: Regularly! Use retrospectives to identify process improvements, then submit updates via the issue template.

**Q: Can we customize processes for our team?**  
A: Yes, within reason. Use these docs as a foundation, and adapt as needed. Document your team's specific practices in your project repository.

**Q: What if we disagree with a process?**  
A: Great question. Psychological safety means we want your feedback. Create an issue with your suggestion and the reasoning behind it.

---

**Last Updated**: 2026-05-14  
**Version**: 1.0
