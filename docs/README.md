# OctoAcme — Project Management Docs (README)

This README collects the OctoAcme project management process documents and provides a short summary of the processes used. It lives in docs/ as the central entry point for OctoAcme process documentation.

## Process summary

OctoAcme follows an iterative, customer-first approach that emphasizes clear outcomes, cross-functional collaboration, and small, testable increments. Work starts with initiation — capturing the problem, stakeholders, and measurable success metrics in a one-pager — then moves into planning where the team creates a prioritized backlog with acceptance criteria, estimates, and a release plan. Execution is driven by a regular team rhythm: daily standups, weekly delivery syncs, and milestone demos, paired with a visible project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) that keeps work traceable.

Quality and release practices are embedded throughout the lifecycle: developers write unit and integration tests, CI runs automated tests and security scans, PRs are kept small and include acceptance criteria, and manual QA or smoke tests are used before releases. Releases follow a checklist (pre-release checks, staging verification, automated deployment when possible, and rollback plans) and are accompanied by release notes and post-deploy verifications.

Communication, risk management, and continuous improvement are formalized: roles (Product Manager, Project Manager, Developers, QA, Stakeholders) have clear responsibilities; the team maintains a risk register and uses escalation paths (team → PM → Product Lead → Sponsor) for blocking issues; and retrospectives convert learnings into tracked action items. This README links to the detailed process documents below.

## Documents

- [Project Management Overview](./octoacme-project-management-overview.md) — concise introduction to roles, artifacts, and lifecycle.
- [Project Initiation Guide](./octoacme-project-initiation.md) — how to validate and authorize new projects, one-pager template.
- [Project Planning](./octoacme-project-planning.md) — planning steps, backlog template, risk & dependency management.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, workflows, QA, and reporting.
- [Risks & Communication](./octoacme-risks-and-communication.md) — risk register, communication templates, and escalation paths.
- [Release & Deployment](./octoacme-release-and-deployment.md) — release types, deployment checklist, and rollback playbook.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — running retros, tracking action items.
- [Roles & Personas](./octoacme-roles-and-personas.md) — role summaries and responsibilities used in the exercise.

## How to use

- Place this README at docs/README.md as the central entry point for OctoAcme process docs.
- Link to this README from the repository root README and onboarding materials.
- When updating or adding process docs, update this README to keep summaries and links current.
