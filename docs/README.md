# OctoAcme Project Management Docs

Welcome — this folder contains the core project and program management guidance used by OctoAcme. The documents are intended to be a single, discoverable source of truth that helps teams initiate, plan, execute, release, and continuously improve work. They summarize roles, cadence, artifacts, and expectations so new and existing team members can move quickly while staying aligned.

OctoAcme follows a lightweight, iterative lifecycle: Initiation (one-pagers and stakeholder alignment), Planning (backlog, estimates, Definition of Done), Execution & Tracking (project board columns, small PRs, CI checks, code review), Release & Deployment (release type, staging verification, rollback plan), and Retrospective & Continuous Improvement (action items and tracked follow-up). The process emphasizes delivering small, testable increments, measuring outcomes, and iterating based on evidence.

Key workflows include a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a pull request workflow that favors small changes, links PRs to issues and acceptance criteria, and runs automated tests and security scans before requesting review. Quality assurance practices include unit and integration tests, end-to-end smoke checks for critical flows, security scanning in CI, and manual QA for feature acceptance when needed. Releases follow a checklist (pre-release checks, staging verification, post-deploy verifications) and an incident playbook with rollback and blameless retrospectives when required.

Roles and communication are explicit: Product Managers (PdM) define outcomes and success metrics; Project Managers (PM) coordinate delivery, risks, and status; Developers implement and test; QA validates acceptance criteria; and Stakeholders provide input and approvals. The cadence is driven by daily standups, weekly delivery syncs, PM/PdM alignment, and monthly stakeholder updates, with clear escalation paths for blockers and incidents.

Docs Index

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

How to use these docs

- Keep this README updated as the single entry point for project management guidance.
- Link to the project one-pager, release notes, and the project board from your project repo when starting work.

_Acceptance Criteria_

- Content aligns with existing process docs.
- Update improves clarity and discoverability of the docs.

