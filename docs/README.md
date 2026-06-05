# OctoAcme Project Management Docs

Welcome! This README centralizes all documentation for OctoAcme project management processes. It provides an overview of our approach and direct links to each process guide.

## Summary of Project Management Processes

OctoAcme operates under a structured, lifecycle-based project management approach designed to balance iterative delivery with clear accountability. The organization follows five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Central to this approach are five core principles: customer-first prioritization, iterative delivery of testable increments, clear ownership structures, data-informed decision-making, and psychological safety. Each project is anchored by a **Project One-pager** that captures the problem statement, measurable objectives, success metrics, and stakeholder alignment—ensuring projects move forward only when there is genuine business need and stakeholder consensus.

OctoAcme defines clear roles to eliminate ambiguity and enable effective cross-functional collaboration. **Project Managers** coordinate delivery, manage schedules and risks, and ensure transparency through status reporting; **Product Managers** own vision, prioritize the backlog, and measure outcomes; **Developers** implement features, write tests, and collaborate on design and quality; and **QA/Testing** validates acceptance criteria and quality standards. Communication follows a predictable cadence: daily standups (15 minutes) focus on progress and blockers, weekly PM-PdM syncs ensure alignment, twice-weekly delivery team standups coordinate execution, and monthly stakeholder updates maintain visibility. A structured **escalation path** (Team → PM → Product Lead → Sponsor) ensures risks and blockers are surfaced and resolved efficiently.

Execution is managed through a GitHub Projects workflow with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible) and include issue links and acceptance criteria; all changes require automated CI testing, linting, and security scanning before approval. Quality assurance includes unit tests, integration tests, and end-to-end smoke tests for critical flows; manual QA is conducted when needed for feature acceptance. A **Risk Register** tracks identified risks throughout the project lifecycle, with risks assessed for impact and likelihood, assigned owners, and mitigated through documented plans. Finally, **Retrospectives** are conducted after each sprint, release, or milestone to capture learnings and convert them into prioritized action items, creating a culture of continuous, iterative improvement grounded in team feedback and measurable outcomes.

## Process Documents

Navigate to the detailed process guides below:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, artifacts, and high-level lifecycle.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Initial steps to validate work, align stakeholders, and create a lightweight plan; includes the One-pager template.
- **[Project Planning](octoacme-project-planning.md)** — Turn approved initiatives into actionable plans and backlogs; includes backlog template and sprint planning guidance.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, workflow standards, and blocker escalation.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, assess, and mitigate risks; manage stakeholder communication and escalation paths.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize releases to production with pre-release requirements, deployment checklists, and rollback procedures.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements; includes action item template.
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Define typical roles (Developers, Product Managers, Project Managers) and their responsibilities, goals, and communication patterns.

## How to Use These Docs

- **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) for a quick orientation, then explore specific guides as needed.
- **Active projects**: Keep your project charter and risk register up to date using the templates provided in the Planning and Risk Management docs.
- **Process improvements**: Submit updates or new content via the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

---

**Last Updated**: June 2026
