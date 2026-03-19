# OctoAcme Project Management Docs

This folder contains the program and process documentation for OctoAcme's project management approach. It is the single source of truth for how OctoAcme plans, executes, and delivers projects. New team members should start here to understand our processes and find links to deeper reference material.

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle: **Initiation → Planning → Execution → Release → Close/Retrospective**. Work begins with a Project Charter/One-pager that captures the problem statement, SMART objectives, success metrics, stakeholders, and initial risks. Once approved, the team runs a kickoff, defines a clear Definition of Done, and builds a prioritized backlog with acceptance criteria, estimates, and ownership. Day-to-day execution is managed through a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and small pull requests linked to issues, with automated CI tests and linting required before review.

## Roles and Personas

Roles are intentionally explicit to support clear ownership. The **Project Manager (PM)** coordinates delivery mechanics—timeline, risks, communications, and facilitation. The **Product Manager (PdM)** owns outcomes: prioritization, success metrics, and trade-offs with stakeholders. **Developers** design and implement features with testability in mind and participate in estimation and reviews. The **QA Lead** plans and coordinates quality assurance efforts and reports on test coverage. The **Release Manager** oversees release logistics, coordinates deployments, and owns incident and rollback communication. The **DevOps Engineer** maintains CI/CD pipelines, monitoring, and supports incident response. The **UX Designer** ensures usability and design quality, advocating for user-centric development. The **Stakeholder Champion** represents key stakeholder groups and facilitates feedback loops. **Stakeholders** provide inputs and approvals. This role clarity is reinforced through consistent artifacts (backlog, risk register, release plan, retrospectives) so decisions and status are easy to find without depending on any one person. See [Roles & Personas](octoacme-roles-and-personas.md) for full descriptions.

## Communication and Risk

Communication is structured around a regular team rhythm: short daily standups to surface progress and blockers, a weekly delivery sync to flag risks and dependencies, and demos at sprint or milestone boundaries. A weekly status format (progress, next steps, risks/blockers, asks/decisions) keeps stakeholders informed, with defined escalation paths from team triage up through the product lead to the sponsor when business impact warrants it. Risks are tracked in a simple **risk register** (impact/likelihood, owner, mitigation, status) updated during planning and reviewed weekly.

## Quality Assurance and Release

Quality is built into both execution and release. OctoAcme runs **automated tests, linting, and security scans** in CI before review, and requires at least one approval before merge. Testing expectations scale with risk: unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release—supplemented by manual QA for feature acceptance. Releases follow a standardized checklist covering release notes, rollback/mitigation plan, staging validation, post-deploy verification, and stakeholder announcements. Teams close the loop with retrospectives that produce a small set of owned, time-bound improvement actions.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Project Kickoff Template](octoacme-project-kickoff-template.md) *(new)*
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Stakeholder Communication Templates](octoacme-stakeholder-communication-templates.md) *(new)*
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
