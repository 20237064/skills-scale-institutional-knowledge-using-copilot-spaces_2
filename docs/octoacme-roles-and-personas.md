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

## QA/Testing Lead

### Role Summary
QA/Testing Leads define and execute the quality strategy for projects. They own test planning, acceptance validation, and quality reporting to ensure features meet acceptance criteria before release.

### Responsibilities
- Create and maintain test plans aligned with project scope and release timing
- Define how acceptance criteria will be validated with Product Managers
- Coordinate automated, integration, end-to-end, and manual QA activities with Developers
- Report quality metrics, defects, test coverage, and release readiness risks to Project Managers
- Validate release readiness and coordinate smoke testing before and after deployment
- Participate in retrospectives to improve test coverage and quality processes

### Goals
- Ensure high-quality releases with minimal escaped defects
- Provide early visibility into quality risks and acceptance gaps
- Reduce delivery cycle time through practical test automation and clear validation paths

### Typical Communication
- Test planning and QA approach during project planning
- Defect triage and acceptance validation with Developers and Product Managers
- Quality status, release readiness, and testing risks in weekly project updates

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, approve key decisions, and serve as escalation points for business-impacting issues. They help ensure project work stays aligned with organizational priorities and measurable outcomes.

### Responsibilities
- Approve project scope, success metrics, funding, and resource commitments
- Provide business requirements, customer context, and prioritization input to Product Managers
- Review major milestones, launch readiness, and business outcome reports
- Resolve or escalate business-level risks, trade-offs, and dependency conflicts with Project Managers
- Communicate organizational constraints, timing needs, and adoption expectations to the delivery team
- Participate in post-project reviews when outcomes or investments need stakeholder feedback

### Goals
- Ensure projects deliver measurable customer and business value
- Maintain alignment between delivery work, strategy, and stakeholder expectations
- Minimize business disruption by making timely decisions and escalations

### Typical Communication
- Kickoff alignment, milestone reviews, and monthly stakeholder updates
- Escalation discussions with Project Managers and Product Managers for scope, timing, or priority decisions
- Release announcements and post-deployment outcome reviews with the delivery team

---

## Security Lead

### Role Summary
Security Leads integrate security requirements into project delivery and ensure compliance with organizational security policies. They identify security risks early, guide secure design practices, and coordinate security validation before release.

### Responsibilities
- Define security requirements, threat models, and review expectations during planning
- Review technical designs and architecture decisions for security implications
- Coordinate security scanning, vulnerability triage, and remediation with Developers
- Participate in risk assessment and mitigation planning with Project Managers
- Validate security controls and release readiness for security-sensitive changes
- Guide incident response and escalation for security-related issues

### Goals
- Minimize security vulnerabilities in released features
- Shift security considerations earlier into planning, design, and implementation
- Maintain customer trust and compliance with organizational security standards

### Typical Communication
- Security requirements and risk input during project planning
- Scan results, remediation guidance, and security review feedback in PRs or project updates
- Incident notifications and escalation coordination with Project Managers and on-call teams

---

## Scrum Master/Facilitator

### Role Summary
Scrum Masters and Facilitators help teams run effective ceremonies, maintain healthy collaboration, and remove blockers. They focus on team flow and continuous improvement while Project Managers remain accountable for delivery tracking and stakeholder reporting.

### Responsibilities
- Facilitate standups, sprint planning, retrospectives, and working sessions
- Help the team identify blockers, action items, and owners
- Coach Developers, Product Managers, and Project Managers on effective agile practices
- Protect meeting time by keeping discussions focused, inclusive, and action-oriented
- Track retrospective improvements and follow up on team process commitments
- Surface recurring impediments to Project Managers for escalation when needed

### Goals
- Improve team alignment, psychological safety, and delivery flow
- Reduce unresolved blockers and meeting overhead
- Turn retrospectives into concrete, owned process improvements

### Typical Communication
- Daily standup facilitation and sprint ceremony summaries
- Retrospective action items shared with Developers, Product Managers, and Project Managers
- Blocker follow-up with Project Managers when impediments require escalation

---

## Technical Architect

### Role Summary
Technical Architects guide technical strategy, evaluate design trade-offs, and identify technical risks that affect timelines, quality, scalability, and maintainability. They provide decision support for complex technical choices without replacing Developer ownership of implementation.

### Responsibilities
- Evaluate and recommend technical approaches for projects and major features
- Review architecture decisions for scalability, maintainability, operability, and risk
- Identify technical dependencies, integration points, and sequencing considerations for Project Managers
- Partner with Product Managers to explain feasibility, trade-offs, and technical constraints
- Guide Developers on design patterns, implementation direction, and technical risk mitigation
- Document key architecture decisions and assumptions for future project teams

### Goals
- Ensure technical decisions align with long-term platform and product strategy
- Reduce rework, delivery surprises, and unnecessary technical debt
- Enable reliable, maintainable systems that can scale with business needs

### Typical Communication
- Technical design reviews, architecture notes, and decision records
- Planning input on complexity, dependencies, and implementation sequencing
- Design guidance in code reviews, technical discussions, and risk reviews

---

## Support/Operations Lead

### Role Summary
Support and Operations Leads represent production readiness, monitoring, incident response, and post-deployment support needs. They ensure releases can be operated safely and that support teams are prepared for customer impact.

### Responsibilities
- Define operational readiness, monitoring, alerting, and support requirements
- Review deployment, rollback, and incident response plans with Project Managers and Developers
- Coordinate support documentation, known issues, and customer-facing readiness with Product Managers
- Validate post-deployment health checks, smoke tests, and production verification steps
- Represent on-call, support, and operations concerns during risk and release reviews
- Feed production learnings and support trends into retrospectives and future planning

### Goals
- Ensure releases are supportable, observable, and recoverable in production
- Reduce customer impact from incidents, defects, and unclear support processes
- Improve operational feedback loops between support, product, and engineering teams

### Typical Communication
- Release readiness reviews covering monitoring, rollback, and support plans
- Deployment coordination with Developers and Project Managers
- Post-deployment status, incident updates, and support trends shared with Product Managers and stakeholders

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
