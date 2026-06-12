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
A delivery-focused coordinator who ensures backlog readiness, sprint flow, and cross-team commitments are met. The Delivery Lead operates at the tactical level to remove blockers and maintain team velocity.

### Responsibilities
- Coordinate sprint planning, manage delivery timelines, and track dependencies across teams
- Maintain the project board and ensure work items meet the Definition of Done before they are pulled into a sprint
- Facilitate removal of operational blockers and escalate issues through the established escalation path
- Monitor sprint health and flag risks early to the Project Manager

### Goals
- Maintain consistent team velocity and on-time delivery
- Reduce friction in the sprint workflow
- Ensure clear, actionable backlog prioritization

### Typical Communication
- Daily standup facilitation and sprint health checks
- Slack updates on blocker status and escalations
- Coordination with Developers, QA, and Project Manager on readiness

### Interactions
- Works closely with the Project Manager to keep the plan and schedule current
- Partners with Developers and QA to confirm acceptance criteria and readiness
- Reports status and risks to the Product Manager and Project Manager

---

## Technical Program Manager (TPM)

### Role Summary
A technical leads-level planner who manages complex technical dependencies, releases, and architecture trade-offs. The TPM bridges technical and project management concerns to ensure architectural coherence and release confidence.

### Responsibilities
- Map and track technical dependencies (internal and cross-team) and coordinate timing for integrations and releases
- Drive technical planning sessions and ensure design/architecture decisions are communicated and documented
- Maintain technical risk register entries and mitigation plans
- Validate that deployment strategies, rollback plans, and capacity planning are in place

### Goals
- Minimize technical surprises and integration issues
- Enable confident, predictable releases
- Maintain architectural consistency across initiatives

### Typical Communication
- Technical design reviews and architecture discussions
- Dependency mapping and release coordination meetings
- Technical risk escalations and mitigation updates

### Interactions
- Collaborates with Developers and SREs on architecture and release readiness
- Aligns with the Product Manager on scope and technical trade-offs
- Works with the Project Manager on scheduling and dependency resolution

---

## UX Researcher

### Role Summary
Ensures user needs and usability are incorporated into feature design and acceptance criteria. The UX Researcher validates that features solve real user problems and are easy to use.

### Responsibilities
- Run quick research and usability testing for high-impact features
- Provide research-backed recommendations and acceptance criteria to the Product Manager and Design team
- Validate prototypes and gather metric targets for success
- Participate in acceptance testing to confirm usability requirements are met

### Goals
- Ensure features are user-centered and solve real customer problems
- Reduce rework and support costs through better upfront validation
- Establish measurable usability success criteria

### Typical Communication
- Research findings and usability test reports
- Acceptance criteria recommendations and feedback on prototypes
- Participation in design reviews and QA testing sessions

### Interactions
- Works with Product Managers and Developers to translate research findings into acceptance criteria
- Partners with QA to define exploratory test scenarios for usability
- Collaborates with the Design team on user flows and interaction validation

---

## Site Reliability Engineer (SRE)

### Role Summary
Focuses on reliability, observability, and operational readiness of features in production. The SRE ensures that new features don't compromise system stability and can be safely deployed and operated.

### Responsibilities
- Define SLOs/SLIs for critical user journeys and validate observability coverage
- Advise on deployment strategy, rollback plans, and capacity considerations
- Assist with post-deploy verification and incident response readiness
- Review operational runbooks and support escalation procedures

### Goals
- Maintain high system reliability and uptime
- Enable fast incident detection and resolution
- Reduce unplanned downtime and customer impact

### Typical Communication
- Observability and SLO definitions in technical design reviews
- Deployment readiness checklists and runbook reviews
- Post-deploy verification results and incident retrospectives

### Interactions
- Works with Developers and the Delivery Lead to ensure production readiness
- Aligns with Project Manager and Product Manager on risk and rollout plans
- Partners with QA on end-to-end smoke testing and incident simulation

---

## Compliance / Ops Liaison

### Role Summary
Ensures project work meets regulatory, security, and operational requirements. The Compliance / Ops Liaison identifies and surfaces constraints early to avoid late-stage surprises and rework.

### Responsibilities
- Review feature plans for compliance/regulatory impact and surface required controls
- Coordinate with Security/Legal/Operations teams and track required approvals
- Maintain compliance-related checklist items in project artifacts
- Validate that compliance and operational requirements are met before release

### Goals
- Reduce compliance and security risks
- Accelerate approvals by surfacing requirements early
- Maintain organizational standards and audit readiness

### Typical Communication
- Compliance review recommendations and requirement summaries
- Approval status updates and escalations
- Pre-release compliance checklists and sign-off documentation

### Interactions
- Works with Product Managers and Project Managers to identify compliance needs early
- Provides clear acceptance criteria related to compliance and coordinates final sign-off
- Collaborates with Security and Legal teams on risk assessment and controls implementation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance
- The expanded set of personas enables more realistic cross-functional coordination scenarios
- Reference persona interactions to illustrate dependencies and communication patterns
