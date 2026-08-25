# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains guidance on how we plan, execute, and deliver projects across the organization.

## Quick Start

New to OctoAcme? Start with the [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for a concise introduction to our approach, key roles, and core artifacts.

## OctoAcme Project Management Overview

OctoAcme follows a structured lifecycle that moves projects through five distinct phases: **Initiation, Planning, Execution, Release, and Closure & Retrospective**. The Initiation phase validates business need and stakeholder alignment through a lightweight Project One-pager that captures the problem statement, success metrics, and resource requirements. Once approved, the Planning phase breaks work into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. This disciplined approach ensures teams move only to execution when success criteria are clear and stakeholder buy-in is confirmed, reducing rework and misalignment downstream.

Execution and delivery are governed by a team rhythm that balances daily focus with strategic oversight: daily standups (15 min) address progress and blockers, weekly delivery syncs review milestones and risks, and sprint-based iteration planning ensures predictable cadence. The project board (GitHub Projects) provides visibility across Backlog → Ready → In Progress → In Review → QA → Done columns, while pull request workflows emphasize small, reviewable changes (≤400 lines), automated CI/CD checks, and mandatory approvals before merge. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, and security scanning, with manual QA for feature acceptance when needed.

Clear role definition is fundamental to OctoAcme's structure: **Project Managers** own schedules, risks, and communications; **Product Managers** define outcomes and prioritize the backlog; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates acceptance criteria. Stakeholder communication follows a weekly cadence with a single source of truth (project README or release doc), and a three-level escalation path (Team → PM → Product Lead → Sponsor) ensures risks and blockers are surfaced promptly. After release, retrospectives capture learnings and convert them into actionable improvements tracked in the project backlog, closing the feedback loop and embedding continuous improvement into the team's culture.

## Project Lifecycle

OctoAcme projects follow a structured lifecycle:

1. **[Initiation](octoacme-project-initiation.md)** — Validate the business need, align stakeholders, and confirm go/no-go
2. **[Planning](octoacme-project-planning.md)** — Break work into shippable increments and define the delivery roadmap
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, track progress, and address blockers
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how we release features to production
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and drive improvements

## Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Understand key roles and responsibilities

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features and collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## How to Use These Docs

- **As a reference**: Use the lifecycle documents to understand what activities occur at each phase
- **During project setup**: Reference the Project One-pager template and checklists when initiating new work
- **For onboarding**: Share this README with new team members to orient them to OctoAcme's approach
- **For continuous improvement**: Check the Retrospective guide to capture learnings and drive team improvements

---

**Last Updated**: August 2026  
**Maintained by**: OctoAcme Project Management Team
