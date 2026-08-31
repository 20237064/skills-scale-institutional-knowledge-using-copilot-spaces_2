# OctoAcme Project Management Documentation

## Welcome

This folder contains the complete OctoAcme project management methodology. Whether you're starting a new project, managing execution, or closing out a release, you'll find guidance and checklists here.

## Our Approach

OctoAcme projects are guided by five core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization operates across five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase has defined deliverables and decision gates. During initiation, teams validate business need and create a lightweight one-pager with success metrics, stakeholders, and timeline. Once approved, the planning phase breaks work into shippable increments, establishes acceptance criteria, and identifies dependencies. This structured progression ensures alignment early and reduces downstream surprises.

The core team structure relies on three key personas with distinct responsibilities. **Project Managers** coordinate delivery, manage schedules, risks, and stakeholder communication. **Product Managers** define what to build, prioritize the backlog, and measure outcomes through success metrics. **Developers** implement features, write tests, and collaborate on design and code reviews. Clear role delineation prevents overlap and ensures accountability, while weekly PM-to-PdM syncs and twice-weekly standups keep the delivery team synchronized. This role clarity is foundational to OctoAcme's principle of "clear ownership"—every project has a named PM and Product Lead.

Quality assurance and risk management are embedded throughout execution. Teams use small pull requests (≤400 lines), automated CI/CD with tests and security scanning, and manual QA for feature acceptance. A formal Risk Register tracks identified risks with impact, likelihood, mitigation plans, and owners, reviewed weekly during syncs. Communication follows a tiered escalation model: team-level triage → PM escalation → Product Lead → Sponsor, ensuring blockers are surfaced quickly. Release readiness requires passing CI, security scans, drafted release notes, and smoke tests before deployment, with a documented rollback plan for production safety.

Finally, OctoAcme emphasizes continuous improvement through retrospectives held after each sprint or milestone. Teams discuss what went well, what could improve, and capture 2–3 actionable improvements with clear owners and due dates. This feedback loop, combined with regular stakeholder updates and data-informed decision-making, reflects OctoAcme's principle of psychological safety and iterative refinement. By centralizing processes in versioned documentation and Copilot Spaces, the organization ensures consistent execution, faster onboarding, and reduced single-person dependency.

## Project Lifecycle

1. **Initiation** - Validate need, align stakeholders, create one-pager
2. **Planning** - Break into shippable increments, estimate scope
3. **Execution** - Build, test, track progress, manage risks
4. **Release** - Deploy, verify, announce
5. **Close & Retrospective** - Capture learnings, continuous improvement

## Documentation

| Document | Purpose | Audience |
|----------|---------|----------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Quick introduction to roles, principles, and lifecycle | Everyone |
| [Project Initiation](./octoacme-project-initiation.md) | How to validate and authorize new work | PMs, Sponsors |
| [Project Planning](./octoacme-project-planning.md) | Breaking work into backlog items and milestones | Teams, PMs |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution, standups, quality gates | Development teams |
| [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk registers, stakeholder updates, escalations | PMs, Leaders |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Pre-release checklist, deployment, rollback | Developers, DevOps |
| [Retrospectives & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running retros, capturing learnings | All teams |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed role definitions and responsibilities | Everyone |

## Quick Links by Role

**New to OctoAcme?**
Start with [Project Management Overview](./octoacme-project-management-overview.md)

**Starting a new project?**
See [Project Initiation](./octoacme-project-initiation.md)

**Planning a sprint or release?**
See [Project Planning](./octoacme-project-planning.md)

**Managing day-to-day work?**
See [Execution & Tracking](./octoacme-execution-and-tracking.md)

**Identifying and managing risks?**
See [Risk Management & Communication](./octoacme-risks-and-communication.md)

**Ready to ship?**
See [Release & Deployment](./octoacme-release-and-deployment.md)

**Reflecting and improving?**
See [Retrospectives & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

*For questions or to suggest updates to these processes, please open an issue using the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.*
