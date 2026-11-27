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

## Release Manager / Release Coordinator

### Role Summary
Release Managers coordinate release planning and readiness across engineering, QA, operations, and support. They provide a clear owner for release windows, approvals, and deployment communication.

### Responsibilities
- Plan release windows and coordinate go/no-go readiness reviews
- Confirm that acceptance criteria, CI, security checks, smoke tests, and rollback plans are complete
- Coordinate handoffs with engineering, QA, operations, and support
- Communicate release status, known issues, and deployment outcomes
- Maintain release notes and post-release follow-up actions

### Goals
- Reduce deployment risk and release disruptions
- Make release readiness and ownership explicit
- Deliver predictable, observable releases

### Typical Communication
- Release readiness reviews and go/no-go decisions
- Coordination with Product Managers on scope and timing
- Scheduling and risk updates with Project Managers
- Deployment instructions and handoffs with Developers, QA, and Operations/Support

### Interaction with existing roles
- Project Managers track release milestones and escalations.
- Product Managers confirm customer-facing scope and prioritization.
- Developers and QA provide implementation, testing, and rollback evidence.

---

## UX / Design

### Role Summary
UX and Design translate customer and user needs into clear, usable, accessible experiences. They work with Product and delivery teams to validate solutions before and during implementation.

### Responsibilities
- Gather and incorporate user needs, feedback, and research
- Create flows, prototypes, and interface specifications
- Define usability and accessibility requirements
- Participate in design reviews and solution validation
- Help keep acceptance criteria focused on the intended experience

### Goals
- Improve usability and accessibility
- Reduce rework caused by unclear or unvalidated designs
- Ensure implementation matches the intended user experience

### Typical Communication
- Discovery and design workshops with Product Managers and stakeholders
- Design reviews with Developers and QA
- Usability validation and user research findings

### Interaction with existing roles
- Product Managers provide problem statements and customer priorities.
- Developers coordinate feasibility and implementation details.
- QA incorporates usability and accessibility checks into acceptance validation.
- Project Managers ensure design work and reviews are included in delivery plans.

---

## Security Lead

### Role Summary
Security Leads define and coordinate security expectations for the project. They help teams identify threats, apply safeguards, and respond to security findings or incidents.

### Responsibilities
- Define applicable security requirements and threat considerations
- Review security-sensitive designs and changes
- Coordinate security scanning, remediation, and risk acceptance
- Support incident response and security escalations
- Help maintain secure implementation and operational practices

### Goals
- Reduce security risk and avoid preventable vulnerabilities
- Make security ownership and exceptions visible
- Improve readiness for security events and audits

### Typical Communication
- Security reviews during planning and design
- Vulnerability and remediation updates
- Incident coordination with on-call and operations teams
- Risk and escalation updates with Project Managers

### Interaction with existing roles
- Developers implement approved security controls and remediation.
- QA validates security requirements and test coverage.
- Project Managers track security risks, dependencies, and escalation needs.
- Product Managers balance security constraints against product priorities.
- Release Managers coordinate security sign-off and blocking findings before release.

---

## Data / Analytics

### Role Summary
Data and Analytics roles define, validate, and evaluate the measurements that show whether a project achieves its intended outcomes.

### Responsibilities
- Translate success goals into measurable metrics and instrumentation
- Define data quality and reporting requirements
- Validate event tracking, dashboards, and experiment data
- Analyze adoption and outcome trends
- Communicate evidence and uncertainty to decision-makers

### Goals
- Improve the quality and reliability of project measurement
- Enable evidence-based product and delivery decisions
- Establish traceability from features to outcomes

### Typical Communication
- Metric definition and instrumentation reviews
- Dashboard updates and experiment analysis
- Outcome reviews with Product Managers and stakeholders

### Interaction with existing roles
- Product Managers set success hypotheses and prioritize questions to answer.
- Developers implement telemetry and instrumentation agreed with Data/Analytics.
- Project Managers include measurement milestones and dependencies in plans.
- UX/Design aligns metrics with validated user journeys.
- Stakeholders use findings to make informed decisions and next-step commitments.

---

## Operations / Support

### Role Summary
Operations and Support roles prepare and maintain the operational and customer-facing environment for a successful launch and ongoing service.

### Responsibilities
- Develop runbooks, monitoring, support guidance, and escalation paths
- Validate observability and on-call readiness
- Prepare support coverage and known-issue documentation
- Triage production issues and communicate customer impact
- Feed operational findings and recurring incidents into backlog priorities

### Goals
- Improve service readiness and recovery
- Reduce customer impact and support response time
- Create a reliable operational handoff from delivery to support

### Typical Communication
- Operational readiness and release handoff reviews
- Incident updates and escalation coordination
- Support feedback in delivery and product syncs

### Interaction with existing roles
- Developers provide technical troubleshooting, fixes, and implementation context.
- Release Managers coordinate handoffs, deployment windows, and release communications.
- Project Managers track operational risks and follow-up actions.
- Product Managers use support trends and customer impact to inform priorities.
- Security Leads coordinate security incidents and response procedures.

---

## Change Manager / Adoption Lead

### Role Summary
Change Managers and Adoption Leads plan how stakeholders and users move from existing practices to a released product or process. They turn release activity into an adoption plan.

### Responsibilities
- Identify affected stakeholder groups and adoption needs
- Plan communications, training, documentation, and rollout support
- Coordinate rollout sequencing and readiness activities
- Measure adoption and user feedback
- Capture barriers and recommend follow-up actions

### Goals
- Increase adoption and reduce disruption
- Make stakeholder impacts and responsibilities clear
- Ensure the launch includes enablement and follow-up

### Typical Communication
- Stakeholder and change-impact planning
- Training and communication readiness reviews
- Adoption updates and feedback summaries

### Interaction with existing roles
- Product Managers clarify customer value, target audiences, and success measures.
- Project Managers align change activities with milestones and dependencies.
- UX/Design provides user guidance informed by validated experiences.
- Operations/Support prepares enablement materials and handles post-launch questions.
- Stakeholders sponsor, approve, and participate in rollout decisions.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
