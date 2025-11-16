# OctoAcme Project Management Docs (README)

Welcome — this folder contains OctoAcme's living project management playbook. These docs are intended to orient new contributors, capture decisions, and make it easy to find the policies and templates that help teams deliver reliably.

Overview
OctoAcme runs cross-functional projects with an iterative, outcome-driven approach. Projects move through a lightweight lifecycle: Initiation → Planning → Execution → Release → Retrospective. We emphasize clear ownership (named Project Manager and Product Lead), small shippable increments, and evidence-based decisions using measurable success metrics.

Key workflows, roles, and communications
- Workflows: Backlog-driven delivery with a project board (Backlog → Ready → In Progress → In Review → QA → Done), small PRs, CI gates, and a release checklist to reduce operational risk.
- Roles & personas: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, risk, and communications; Developers implement and test; QA validates acceptance criteria. Role responsibilities are documented to reduce ambiguity and speed decisions.
- Communication strategies: Regular cadences (daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates), a single source-of-truth project README, and templated weekly/incident updates ensure stakeholders stay informed and escalations are clear.
- Quality assurance: CI checks (tests, lint, security scans), unit/integration/e2e smoke tests for critical flows, manual QA as needed, and a Definition of Done that includes acceptance criteria and verification before release.

Key documents in this folder
- octoacme-project-management-overview.md — high-level philosophy, lifecycle, and principles
- octoacme-project-initiation.md — how to validate and authorize new projects (one-pager, decision gate)
- octoacme-project-planning.md — backlog, estimates, DoD, dependencies and milestones
- octoacme-execution-and-tracking.md — day-to-day workflows, PR conventions, and QA practices
- octoacme-risks-and-communication.md — risk register, stakeholder templates, escalation paths
- octoacme-release-and-deployment.md — pre-release checks, deployment checklist, rollback playbook
- octoacme-retrospective-and-continuous-improvement.md — running retros, tracking actions
- octoacme-roles-and-personas.md — role definitions and responsibilities

How to use these docs
- Keep each project's Project One-pager and README updated in the project repo.
- Add playbook improvements via the process doc issue template (.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
- Convert retrospective action items into backlog issues and track them to completion.

Acceptance criteria
- Content aligns with existing docs
- Improves discoverability and onboarding
- Links to the major process docs in this folder

(If you want a shorter version or a version customized for a particular audience — e.g., engineering onboarding — say which audience and I’ll produce it.)