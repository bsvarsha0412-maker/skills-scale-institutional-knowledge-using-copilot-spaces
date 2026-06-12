# OctoAcme Project Management Process Documentation

Welcome to the OctoAcme project management documentation hub. This folder contains comprehensive guides and templates for running projects using the OctoAcme methodology—a customer-focused, iterative approach to delivering product features, services, and integrations.

## Quick Overview of OctoAcme Processes

OctoAcme follows a structured yet flexible **five-phase lifecycle**:

1. **Initiation**: Validate business need, define success metrics, and align stakeholders through a lightweight Project One-pager before committing resources to planning.
2. **Planning**: Break work into shippable increments with clear acceptance criteria, estimate scope, identify dependencies, and create a prioritized backlog and release plan.
3. **Execution**: Deliver iteratively through a project board workflow, supported by daily standups, weekly syncs, automated CI/CD, and quality gates. Small PRs, code reviews, and comprehensive testing ensure maintainability and reliability.
4. **Release**: Deploy to production following pre-release checklists, smoke tests, and documented rollback plans to minimize risk and maintain observability.
5. **Retrospective**: Capture learnings after each sprint or milestone, convert insights into tracked action items, and embed continuous improvement into team culture.

### Key Principles

- **Customer-first**: Prioritize customer value and usability in every decision.
- **Iterative delivery**: Deliver small, testable increments and measure impact.
- **Clear ownership**: Each project has named roles (Project Manager, Product Manager) and clear responsibilities.
- **Data-informed decisions**: Measure outcomes and iterate based on evidence.
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives.

### Core Roles

- **Developers**: Implement features, write tests, participate in design reviews, and identify technical risks.
- **Product Managers**: Define vision, prioritize the backlog, validate solutions, and measure success.
- **Project Managers**: Coordinate delivery, manage schedules, handle risks and dependencies, and facilitate communication.

### Quality & Risk Management

- Unit tests, integration tests, and end-to-end smoke tests before release.
- Security scanning in CI pipelines.
- Small PRs (≤400 lines when possible) with mandatory code review.
- **Risk Register** maintained throughout the project lifecycle and reviewed weekly.
- Escalation paths: Team → PM → Product Lead → Sponsor.

---

## Process Documents

Navigate to the relevant document based on your current project phase or role:

### [octoacme-project-management-overview.md](./octoacme-project-management-overview.md)
High-level introduction to OctoAcme's approach, principles, core roles, key artifacts, and project lifecycle. **Start here** if you're new to OctoAcme.

### [octoacme-project-initiation.md](./octoacme-project-initiation.md)
Guidance for validating and authorizing new work. Covers the Project One-pager template, stakeholder alignment, and the decision gate to move into planning.

### [octoacme-project-planning.md](./octoacme-project-planning.md)
Turn an approved initiative into an actionable plan. Includes backlog templates, sprint planning, risk and dependency management, and Definition of Done.

### [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)
Day-to-day execution guidance. Covers team rhythm (standups, syncs, demos), project board workflows, PR practices, quality standards, and blocker escalation.

### [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)
Standardized release and deployment process. Includes release types, pre-release checklist, deployment workflow, rollback playbook, and release notes template.

### [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)
Running effective retrospectives and tracking improvements. Covers retro structure, action item templates, and building a continuous improvement culture.

### [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)
Risk identification, management, and escalation. Includes Risk Register template, communication templates for status updates and incidents, and escalation paths.

### [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)
Detailed role definitions for Developers, Product Managers, and Project Managers, including responsibilities, goals, and typical communication patterns.

---

## How to Propose Updates

Found a gap in our processes? Want to refine a template or add clarification? Please use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template to submit your suggestion.

When proposing updates:
- Clearly describe what content you want to add or modify.
- Explain the rationale (e.g., gap identified, team feedback, best practice).
- Include suggested content if available.
- Link to relevant docs or decision logs.

Your feedback helps us keep these processes current and effective for everyone.

---

## Using These Docs with Copilot Spaces

Add these process documents to a Copilot Space to ground Copilot's knowledge in OctoAcme practices. This gives you context-specific guidance when planning projects, running standups, drafting PRs, or preparing releases.

---

**Last updated**: June 2026  
**Questions?** Reach out to your Project Manager or Product Lead.
