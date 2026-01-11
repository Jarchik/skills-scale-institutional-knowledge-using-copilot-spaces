# OctoAcme Project Management Docs

## Overview

OctoAcme runs projects with a lightweight, artifact-driven approach that moves initiatives from a one‑page Project One‑pager into a prioritized backlog and shippable releases. Projects begin with initiation to clarify problem, goals, stakeholders and success metrics; planning breaks approved work into backlog items with acceptance criteria and a Definition of Done; execution focuses on small, testable increments with a disciplined PR and CI workflow; and releases follow a documented checklist with rollback guidance. Each release and milestone is followed by a retrospective to capture lessons and drive continuous improvement.

Key workflows center on a project board moving work through Backlog → Ready → In Progress → In Review → QA → Done, a small-PR pull request practice (include issue link and acceptance criteria, run CI), and a deployment checklist that requires passing CI/security scans and smoke tests in staging before production. Backlog items follow a standard template (title, description, acceptance criteria, estimate, owner) and are estimated and prioritized during planning so teams can deliver iteratively and predictably.

Roles and responsibilities are explicit: Product Managers (PdM) own outcomes and prioritization, Project Managers (PM) coordinate schedules, risks and communications, Developers implement and test features, UX/UI Designers ensure usability, Technical Writers maintain documentation, DevOps/Platform Engineers manage infrastructure and deployments, Security Leads champion security practices, Customer/Support Advocates represent the customer voice, and QA validates quality, with Stakeholders providing input and approvals. This role clarity supports ownership across initiation, planning, execution and close; key artifacts (one‑pager, release plan, risk register, acceptance criteria, retrospective action items) each have an accountable owner. See [Roles and Personas](docs/octoacme-roles-and-personas.md) for complete role descriptions.

Communication is cadence-based and templated to reduce ambiguity: daily standups, weekly delivery syncs and PM+PdM check‑ins, scheduled demos, and monthly stakeholder updates. Risks and incidents use a maintained Risk Register and defined escalation paths (team → PM → Product Lead → Sponsor), while incident communications follow triage, action, timeline and blameless retrospective patterns. Quality assurance is built in with unit/integration/e2e tests, CI security scanning, pre‑release smoke tests, and documented rollback/playbooks.

## Process Documentation

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)
- [Role Onboarding Checklist](docs/role-onboarding-checklist.md)

Each link goes to a focused process document. To propose updates or raise questions about these processes, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ and reference the relevant doc.
