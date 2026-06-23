# OctoAcme Project Management — Process Docs Index

This README provides a brief summary of OctoAcme's project management processes and links to the full process documents in this repository's docs/ directory.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization operates across five distinct phases:

- **Initiation**: New ideas are validated through a lightweight one-pager that captures the problem statement, success metrics, and stakeholder alignment.
- **Planning**: Approved initiatives are broken into shippable increments with prioritized backlogs and defined acceptance criteria.
- **Execution**: Teams deliver incrementally with daily standups and weekly syncs to track progress and manage blockers.
- **Release**: Features are deployed to production through a standardized checklist that includes security scans, smoke tests, and rollback plans.
- **Close & Retrospective**: Learnings are captured and converted into actionable improvements.

### Key Principles
- **Customer-first**: Prioritize customer value and usability.
- **Iterative delivery**: Deliver small, testable increments.
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage feedback and learning.

### Core Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications.
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success.
- **Developers**: Implement features, collaborate on design and testability.
- **QA/Testing**: Validates quality and acceptance criteria.
- **Stakeholders**: Provide inputs and approvals.

### Communication & Risk Management
- **Regular cadence**: Daily standups (15 min), weekly delivery syncs, monthly stakeholder updates.
- **Risk Register**: Tracks potential issues by impact, likelihood, and mitigation status with escalation paths (team-level → PM → Product Lead → Sponsor).
- **Transparency**: Project board (GitHub Projects) with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done).

### Quality Assurance
- Small, focused pull requests (≤400 lines when possible)
- Automated CI/CD testing and linting before review
- At least one approval before merging
- Unit tests, integration tests, and end-to-end smoke tests
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Links to Process Documents

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme project approach, roles, artifacts, and lifecycle.
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** — Guide and one-pager template for initiating a project and aligning stakeholders.
- **[octoacme-project-planning.md](octoacme-project-planning.md)** — Planning steps, backlog templates, and risk/dependency management practices.
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** — Day-to-day execution guidance, PR workflow, QA, and reporting checklist.
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** — Release types, deployment checklist, rollback playbook, and release notes template.
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** — Risk register format, communication templates, and escalation paths.
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure and tracking of action items.
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** — Role definitions and responsibilities used across OctoAcme projects.

## Contributing

To add or update process content, please use the "[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)" issue template and reference which document to modify. Keep entries concise and link to supporting artifacts (templates, checklists, runbooks).
