# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management documentation. This folder contains the process guides and templates the team uses to run projects from initiation through closure. The docs emphasize customer-first, iterative delivery, clear ownership, data-informed decisions, and continuous improvement.

## Overview

OctoAcme follows a simple lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Projects start with a lightweight Project One-pager that captures problem, objective, success metrics, stakeholders, timeline, and risks. Approved initiatives move into planning to create a prioritized backlog, estimates, and a Definition of Done so the team can deliver shippable increments.

During execution the team uses an iterative workflow and a project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull request conventions encourage small, reviewable changes (target ≤400 lines), require linking issues and acceptance criteria, and run CI (tests, linting, security scans) before requesting reviews. Quality assurance is layered: unit and integration tests, end-to-end smoke tests for critical flows, manual QA as needed, and pre-release verification and rollback plans for production deployments.

## Roles & Communication

Roles are defined to make ownership explicit: Product Managers (outcomes & prioritization), Project Managers (schedules, risks, comms), Developers (implement & test), and QA (validate acceptance and quality). The team maintains a steady communication cadence — daily standups for blockers and progress, weekly delivery syncs, sprint demos, monthly stakeholder updates, and templated status and incident messages. Escalation paths move from team → PM → Product Lead → Sponsor, with a security incident runbook for safety-critical issues.

## Documentation index

- Project Lifecycle
  - [Project Management Overview](./octoacme-project-management-overview.md)
  - [Project Initiation](./octoacme-project-initiation.md)
  - [Project Planning](./octoacme-project-planning.md)
  - [Execution & Tracking](./octoacme-execution-and-tracking.md)
  - [Release & Deployment](./octoacme-release-and-deployment.md)
  - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- Cross-cutting
  - [Risk Management & Communication](./octoacme-risks-and-communication.md)
  - [Roles and Personas](./octoacme-roles-and-personas.md)

## Quick start for new team members

1. Read the Project Management Overview to learn principles and core roles.
2. Use this README as your navigation hub.
3. Open the Project Initiation guide when starting a new idea, then follow Planning → Execution → Release guides as the project progresses.
4. Use the ISSUE_TEMPLATE in .github/ISSUE_TEMPLATE to propose process updates.

## Key concepts (brief)

- One-pager: A lightweight charter capturing problem, goal, metrics, stakeholders, and timeline.
- Definition of Done (DoD): The checklist that ensures a backlog item is shippable.
- Risk Register: A running list of risks with owner, impact, likelihood, and mitigation.
- PR Conventions: Rules for small, test-backed PRs that include acceptance criteria and CI-green status before review.
