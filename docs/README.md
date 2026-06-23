# OctoAcme Project Management — Process Docs Index

This README provides a brief summary of OctoAcme's project management processes and links to the full process documents in this repository's docs/ directory.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based project management methodology that emphasizes customer value, iterative delivery, and clear ownership. The approach consists of five primary phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that captures the problem statement, success metrics, and high-level timeline. This decision gate ensures that only well-scoped, strategically aligned work moves forward into planning, where the team breaks deliverables into prioritized backlog items with clear acceptance criteria, estimates scope, and establishes dependencies and release milestones.

The organization defines clear roles and responsibilities to enable efficient collaboration. **Project Managers** coordinate delivery schedules, manage risks, and ensure transparency across stakeholders. **Product Managers** own the product vision, prioritize the backlog, and measure outcomes through data-driven decisions. **Developers** implement features, write tests, and contribute to design and estimating conversations. This separation of concerns—combined with regular communication cadences (daily standups, weekly PM/PdM syncs, and monthly stakeholder updates)—ensures alignment and accountability throughout delivery.

Execution emphasizes quality and visibility through a structured workflow supported by GitHub Projects (with columns: Backlog, Ready, In Progress, In Review, QA, Done) and disciplined pull request practices. Teams enforce small PRs (≤400 lines), include issue links and acceptance criteria in descriptions, run automated tests and security scanning in CI, and require at least one approval before merging. Beyond code review, QA practices include unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. A three-level blocker escalation model (team triage → PM escalation → sponsor involvement) ensures rapid risk resolution without bottlenecks.

Release and continuous improvement complete the cycle. Pre-release requirements include passing CI/security scans, drafted release notes, and a documented rollback plan, with deployment validated through staging smoke tests before production deployment. Post-release, retrospectives capture learnings and convert them into actionable improvements tracked in the backlog. Risk management runs throughout all phases via a risk register (tracking ID, description, impact, likelihood, owner, and mitigation), weekly reviews, and a stakeholder communication strategy that uses a single source of truth (project README or release docs) to maintain transparency and enable timely escalation when needed.

## Links to Process Documents

- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme project approach, roles, artifacts, and lifecycle.
- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — Guide and one-pager template for initiating a project and aligning stakeholders.
- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Planning steps, backlog templates, and risk/dependency management practices.
- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Day-to-day execution guidance, PR workflow, QA, and reporting checklist.
- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Release types, deployment checklist, rollback playbook, and release notes template.
- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risk register format, communication templates, and escalation paths.
- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — Retrospective structure and tracking of action items.
- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Role definitions and responsibilities used across OctoAcme projects.

## Contributing

To add or update process content, please use the **"Add Content to Project Management Process Docs"** issue template and reference which document to modify. Keep entries concise and link to supporting artifacts (templates, checklists, runbooks).

---

**Last Updated:** June 2026  
**Maintained by:** OctoAcme Project Management Team
