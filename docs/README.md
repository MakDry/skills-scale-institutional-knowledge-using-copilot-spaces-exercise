# OctoAcme — Project Management Docs

This README centralizes the OctoAcme project management process documents and provides a short overview of the project management practices used across the program.

## Process summary

OctoAcme uses an iterative, customer-first delivery model with clear ownership, repeatable rituals, and structured project artifacts. Work begins with initiation: the team validates the business need, identifies stakeholders, defines success metrics, and creates a lightweight one-pager that captures the problem, goals, timeline, risks, and resource needs. Once stakeholders align on value and feasibility, the project moves into planning, where the team builds a prioritized backlog, defines acceptance criteria, estimates workload, and creates a release milestone plan.

During execution, the team follows a regular rhythm of daily standups, weekly product/PM syncs, demos, and project board tracking across Backlog, Ready, In Progress, In Review, QA, and Done. Development work is expected to be reviewable and low-risk, with small pull requests, issue links, clear acceptance criteria, CI validation, and required approvals before merge. Quality is reinforced through unit tests, integration tests, smoke tests for critical flows, manual QA where needed, and security scanning in CI.

Communication and risk management are treated as first-class project activities. The team maintains a single source of truth for status updates, uses stakeholder communication templates and escalation paths to surface issues early, and tracks dependencies and risks in a risk register. Release work follows a structured pre-release checklist, smoke testing, deployment verification, and rollback planning to reduce operational risk. After each sprint, milestone, or major incident, the team reflects in a retrospective and turns learning into action items with owners and due dates so the process continues to improve.

## Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — concise introduction to roles, artifacts, and lifecycle.
- [Project Initiation Guide](./octoacme-project-initiation.md) — how to validate and authorize new projects, with a one-pager template.
- [Project Planning](./octoacme-project-planning.md) — planning steps, backlog template, and risk/dependency management.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, workflows, QA, and reporting.
- [Risks & Communication](./octoacme-risks-and-communication.md) — risk register, communication templates, and escalation paths.
- [Release & Deployment](./octoacme-release-and-deployment.md) — release types, deployment checklist, and rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — how to capture learning and track improvements.
- [Roles & Personas](./octoacme-roles-and-personas.md) — role summaries and responsibilities used in the exercise.

## How to use this folder

- Use this README as the central entry point for project management process documentation.
- Keep the document links and summaries current as process docs evolve.
- Add or update the relevant process doc whenever the team changes workflows or adds new practices.

## Related issue

This README was created to satisfy the project management documentation update described in issue #2.
