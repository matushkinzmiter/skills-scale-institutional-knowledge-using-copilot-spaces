# OctoAcme Project Management Process Docs

## Overview
OctoAcme follows a structured, customer-first approach to project delivery. Our process guides teams through five lifecycle phases—Initiation, Planning, Execution, Release, and Retrospective—supported by strong risk management, clear communication, and continuous improvement. These documents provide a single source of truth for project management practices, decision gates, and role responsibilities used across OctoAcme projects.

## Quick Summary of Processes

OctoAcme’s project management approach is structured around a clear, repeatable lifecycle: Initiation, Planning, Execution, Release, and Close/Retrospective. Projects begin with a lightweight Project One-pager to capture the problem, measurable objectives, stakeholders, timeline, and initial risks; a documented decision gate moves work into planning only when success metrics and stakeholder alignment are confirmed. Planning produces a prioritized backlog with acceptance criteria, estimates (T-shirt sizing or story points), a Definition of Done, and a release/milestone map. The team uses a project board with standard columns (Backlog, Ready, In Progress, In Review, QA, Done) and templates for backlog items to ensure clarity and handoffs.

Workflows emphasize small, testable increments and disciplined PR practices. Pull requests should be small (<= 400 lines when possible), include linked issues and acceptance criteria, run automated tests and linters in CI, and require at least one approval before merging. Sprint planning is timeboxed, items must meet DoD, and cross-team dependencies and risks are tracked in a Risk Register (ID, impact, likelihood, owner, mitigation, status) and escalated via a defined path (team → PM → Product Lead → Sponsor). Release and deployment follow a checklisted process (staging smoke tests, automated pipelines, rollback plan) with distinct release types (patch, minor, major) and pre-release requirements such as passing CI and security scans.

Roles and personas are explicit: Product Managers define outcomes, prioritize the backlog, and measure success; Project Managers coordinate delivery, timelines, risks, and stakeholder communication; Developers implement features, write tests, and participate in reviews; QA validates acceptance criteria and performs manual or automated testing as needed. This role clarity supports ownership of artifacts like the Project Charter, release notes, risk register, and retrospective action items.

Communication and quality assurance are baked into cadence and tooling. The team runs daily standups for progress and blockers, weekly delivery syncs for progress and risks, regular demos at milestone ends, and monthly stakeholder updates; PM/PdM syncs are weekly. QA practices require unit tests, integration tests where applicable, end-to-end smoke tests for critical flows, CI security scanning, and manual QA for acceptance when necessary. Retrospectives capture learnings and convert them into prioritized action items tracked in the backlog, closing the loop so process and quality improvements are continuously surfaced and measured.

## Process Documents

### Getting Started
- [Project Management Overview](./octoacme-project-management-overview.md) — Start here for high-level roles, artifacts, and lifecycle phases

### Project Lifecycle Phases
1. [Project Initiation](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and decide go/no-go
2. [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments and create an actionable backlog
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, standups, testing, and progress tracking
4. [Release & Deployment](./octoacme-release-and-deployment.md) — Standardize feature releases and production deployments
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Roles & Personas](./octoacme-roles-and-personas.md) — Typical roles (Developer, Product Manager, Project Manager) and responsibilities

## Quick Start
- **New project?** Start with [Initiation](./octoacme-project-initiation.md)
- **Planning sprint work?** Use [Planning](./octoacme-project-planning.md)
- **Managing daily execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md)
- **Preparing a release?** Check [Release & Deployment](./octoacme-release-and-deployment.md)
- **Learning from a milestone?** Run a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)

## How to update these docs
- Use the issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml to propose new content or changes.
- Suggested flow: open an issue using the template → discuss with stakeholders → submit a PR that references the issue.

## Acceptance Criteria
- Content aligns with existing process docs
- Update improves discoverability and onboarding
- README includes links to all core process documents

