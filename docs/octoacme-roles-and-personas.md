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

## Delivery Lead

### Role Summary
The Delivery Lead focuses on day-to-day execution across squads, ensuring sprint commitments, coordination, and timely escalation of blockers.

### Responsibilities
- Own sprint planning and tracking for one or more teams
- Coordinate cross-squad dependencies and capacity balancing
- Surface and escalate blockers to the Project Manager or Product Manager
- Track team-level delivery metrics and support continuous improvement

### Typical Handoffs / Interaction
- Works with PM to translate roadmap milestones into sprintable work
- Aligns with Developers and QA to confirm scope and acceptance criteria
- Hands off unresolved cross-team blockers to PM or Product Manager for escalation

### Decision Authority
- Operates within agreed sprint scope and capacity limits
- Can re-prioritize team-level tasks during a sprint in coordination with PM/PdM

### Key Artifacts
- Sprint board updates, daily standup notes, sprint retrospective action items

---

## Engineering Manager (EM)

### Role Summary
The EM provides technical leadership and people management, focusing on technical health, capacity planning, career development, and cross-team technical alignment.

### Responsibilities
- Line-management and career support for engineers
- Prioritize technical debt and engineering work alongside feature work
- Ensure proper technical reviews and architecture alignment
- Coordinate hiring/resource planning and capacity estimates

### Typical Handoffs / Interaction
- Partners with PM/PdM on technical trade-offs and feasibility
- Works with Developers on design review and technical approach
- Escalates major technical constraints to Product Lead or stakeholders

### Decision Authority
- Makes team-level technical and staffing decisions
- Escalates cross-team architecture decisions to technical leadership as needed

### Key Artifacts
- Architecture notes, capacity plans, technical debt backlog

---

## Product Designer / UX Lead

### Role Summary
The Product Designer or UX Lead owns design outcomes, user research, accessibility, and the user-facing quality of solutions.

### Responsibilities
- Lead user research and translate findings into design solutions
- Produce wireframes, prototypes, and high-fidelity designs
- Define accessibility and usability acceptance criteria
- Collaborate on acceptance criteria and usability validation

### Typical Handoffs / Interaction
- Works directly with PdM to shape requirements and success metrics
- Hands off finalized assets and specs to Developers with clear acceptance criteria
- Partners with QA to define usability and accessibility test cases

### Decision Authority
- Final authority for design direction and accessibility decisions within scope
- Escalates trade-offs that impact product strategy to PdM

### Key Artifacts
- Design files, research summaries, accessibility checklists, interaction specs

---

## Customer Success / Support Liaison

### Role Summary
The Customer Success or Support Liaison channels field feedback, helps define rollout plans, and ensures the product meets customer-operational needs.

### Responsibilities
- Gather and prioritize customer and support feedback
- Advise on rollout and communication plans for releases
- Help define success criteria from a customer/support perspective
- Coordinate support readiness and knowledge-base updates

### Typical Handoffs / Interaction
- Informs PdM and PM of customer-impacting issues and feature requests
- Works with Release Engineer and PM for support runbooks and communications
- Provides post-release feedback to Data Analyst and PdM for impact assessment

### Decision Authority
- Authority to delay or request mitigation for releases that would cause unacceptable customer impact
- Recommend prioritization of hotfixes or support-related tasks to PM/PdM

### Key Artifacts
- Customer impact briefs, support runbooks, KB articles, rollout checklists

---

## Release Engineer / SRE Representative

### Role Summary
The Release Engineer or SRE representative ensures safe, repeatable deployments and production reliability.

### Responsibilities
- Maintain deployment pipelines, automation, and rollback mechanisms
- Define production verification steps and runbook procedures
- Participate in release planning and incident response
- Help establish SLOs, alerts, and on-call rotations

### Typical Handoffs / Interaction
- Works with Developers and PM during release planning to validate deployment readiness
- Handoffs runbooks and rollback steps to on-call and support teams
- Collaborates with Data Analyst to ensure observability and dashboards are available post-release

### Decision Authority
- Can pause or block a deployment for operational or safety reasons
- Escalates significant reliability risks to PM and engineering leadership

### Key Artifacts
- CI/CD pipeline definitions, runbooks, SLO/SLA docs, incident playbooks

---

## Data Analyst / Analytics Owner

### Role Summary
The Data Analyst defines measurement approaches, implements telemetry, and validates release impact against success metrics.

### Responsibilities
- Define instrumentation and telemetry needed to measure success metrics
- Implement dashboards and data queries to validate impact
- Run analysis on releases and surface insights to PdM and stakeholders
- Validate data quality and correct metric definitions

### Typical Handoffs / Interaction
- Works with PdM to refine measurable success criteria
- Hands off instrumentation requirements to Developers and verifies implementation
- Provides post-release reports to PM, PdM, and stakeholders

### Decision Authority
- Authority to define metrics and measurement approach; recommends go/no-go when metrics are not instrumented
- Escalates significant data quality issues to PM and engineering for remediation

### Key Artifacts
- Telemetry plan, dashboards, measurement cookbook, post-release analysis

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
