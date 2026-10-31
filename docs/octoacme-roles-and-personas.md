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

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads protect the organization by ensuring work meets required security, privacy, and regulatory standards before release.

### Responsibilities
- Review architectures, data flows, and dependencies for risk
- Define and validate security requirements, controls, and review gates
- Coordinate compliance checks, audit evidence, and exception handling
- Partner with engineering on remediation plans and risk mitigation
- Support incident triage, escalation, and post-incident follow-up

### Goals
- Reduce product and organizational risk
- Ensure compliance with internal and external standards
- Enable safe delivery without slowing critical work unnecessarily

### Typical Communication
- Security reviews and architecture discussions
- Risk register updates and escalation briefings
- Release readiness checks and compliance sign-off

### Interaction with Existing Roles
- Works closely with Developers to review risky changes and secure-by-design decisions.
- Partners with Project Managers to track remediation actions and release blockers.
- Provides input to Product Managers and stakeholders on compliance trade-offs and constraints.
- Coordinates with Release Manager or stakeholder communications when launch readiness depends on security sign-off.

---

## UX Researcher / User Advocate

### Role Summary
UX Researchers and User Advocates ensure product decisions are grounded in user needs, usability, and customer outcomes.

### Responsibilities
- Conduct discovery, interviews, usability testing, and problem validation
- Translate user feedback into actionable requirements and opportunity areas
- Collaborate on journey mapping, prioritization, and feature refinement
- Make user impact visible to engineering and product leadership
- Support acceptance checks for usability and accessibility

### Goals
- Improve customer experience and product adoption
- Reduce rework caused by unclear or unvalidated assumptions
- Ensure product decisions reflect user needs, not just stakeholder preferences

### Typical Communication
- Research synthesis, user interviews, and test findings
- Product backlog refinement and prioritization workshops
- Feedback loops with PMs, designers, and developers during iteration

### Interaction with Existing Roles
- Supports Product Managers by informing problem definition and success criteria.
- Works with Developers to clarify task intent, edge cases, and usability constraints.
- Helps Project Managers understand dependencies related to user feedback and iteration cycles.
- Provides evidence that informs rollout decisions and stakeholder updates.

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads ensure the team makes decisions based on measurable outcomes, adoption trends, and operational quality signals.

### Responsibilities
- Define key metrics, dashboards, and instrumentation needs
- Monitor adoption, retention, quality, and operational health indicators
- Partner with PMs and stakeholders on success criteria and reporting cadence
- Validate whether shipped work is achieving the intended business or customer outcomes
- Identify gaps in measurement that could block clear decision-making

### Goals
- Improve decision quality with measurable evidence
- Detect issues early through operational and product metrics
- Tie delivery work to customer value and business outcomes

### Typical Communication
- Metric definitions and dashboard reviews
- Weekly or milestone performance updates
- Cross-functional analysis of release impact and adoption trends

### Interaction with Existing Roles
- Helps Product Managers define actionable success metrics and reporting thresholds.
- Collaborates with Developers and QA on what to instrument and how to validate changes.
- Provides objective evidence to Project Managers for status updates, risks, and milestone decisions.
- Supports stakeholders with data-informed release and adoption narratives.

---

## Release Manager / Enablement Lead

### Role Summary
Release Managers coordinate launch readiness, deployment quality, stakeholder communication, and operational readiness for production changes.

### Responsibilities
- Coordinate versioning, launch windows, rollback planning, and release communications
- Ensure release checklists and deployment readiness criteria are met
- Align release timing with engineering, support, and stakeholder expectations
- Manage dependencies among teams for high-risk or cross-functional launches
- Support post-release validation and knowledge sharing

### Goals
- Reduce release risk and confusion across teams
- Improve predictability of production launches
- Ensure stakeholders and support teams are ready for new changes

### Typical Communication
- Release readiness reviews and deployment checklists
- Launch announcements and stakeholder updates
- Incident or rollback coordination when release issues occur

### Interaction with Existing Roles
- Works with Developers and QA to validate readiness before production deployment.
- Coordinates with Project Managers on timelines, dependencies, and communication plans.
- Partners with Security / Compliance Lead for sign-off on release readiness.
- Keeps Product Managers informed on launch status, risks, and customer impact.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These additional roles help clarify ownership, escalation paths, and decision-making across product, project, engineering, and operational workstreams.

