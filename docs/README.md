# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation.

## Summary

OctoAcme runs projects through a five-stage lifecycle — **Initiation → Planning → Execution → Release → Close & Retrospective** — guided by four principles: customer-first prioritization, iterative delivery of small testable increments, clear ownership (a named PM and Product Lead on every project), and data-informed decision making.

Initiation requires a validated Project One-pager (problem, goal, success metrics), stakeholder alignment, and a go/no-go decision before planning begins. Planning converts the approved idea into a prioritized, estimated backlog with a Definition of Done, dependency and risk mapping, and a release/milestone plan.

Three core personas drive execution: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** own outcomes and backlog prioritization; and **Developers** implement and test features while flagging technical risks. Execution follows a team rhythm of daily standups, weekly delivery syncs, and milestone demos, tracked on a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done), with a PR workflow enforcing small changes, linked acceptance criteria, CI checks, and required approvals.

Communication is structured around a weekly PM/PdM sync, team standups, and monthly stakeholder updates using standard templates, with a three-tier escalation path (team → PM/Product Lead → Sponsor) and a living Risk Register reviewed weekly. Quality assurance spans unit, integration, and end-to-end smoke tests, security scanning in CI, and manual QA, with releases requiring met acceptance criteria, passing CI/security scans, and documented rollback plans before production deployment. Each sprint/release closes with a timeboxed retrospective feeding continuous improvement back into these docs.

## Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
