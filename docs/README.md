# OctoAcme Project Management Docs

This folder collects OctoAcme's project management process documents and provides a short, navigable introduction for new team members and contributors.

## Overview

OctoAcme runs projects using an iterative, customer-focused approach that emphasizes small, testable increments and clear ownership. Projects start with a lightweight initiation (a one-pager capturing the problem, goals, success metrics, and stakeholders), move into planning where the work is broken down into a prioritized backlog with estimates and a Definition of Done, and then proceed to execution, release, and continuous improvement. The team uses a project board to track work across stages (Backlog → Ready → In Progress → In Review → QA → Done) and follows a regular cadence of standups, delivery syncs, and demos to keep work visible and risks managed.

Roles are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedules, and risks; Developers implement and test features; and QA validates acceptance criteria. Templates for backlog items, risk registers, and one-pagers help standardize artifacts and responsibilities so collaborators know where to contribute and where to find authoritative process information.

Quality is enforced through PR and CI conventions: small, reviewable pull requests (guidance suggests keeping changes small when possible), automated unit and integration tests, end-to-end smoke tests for critical flows, linting, and security scans. Release and deployment practices include pre-release checks, staging and production smoke tests, rollback plans, and an incident playbook for fast, blameless triage.

## Documents
- [Project Management Overview](octoacme-project-management-overview.md) — concise intro to roles, principles, and lifecycle.
- [Project Initiation Guide](octoacme-project-initiation.md) — how to validate and authorize new initiatives.
- [Project Planning](octoacme-project-planning.md) — planning steps, backlog templates, and checklists.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, workflows, and execution checklist.
- [Release & Deployment](octoacme-release-and-deployment.md) — release types, deployment checklist, and incident playbook.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — running retros and tracking improvements.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register and communication templates.
- [Roles & Personas](octoacme-roles-and-personas.md) — role definitions and responsibilities.

## Usage
Add this README to the docs/ folder and update it whenever process docs change. Link to this file from the project README or .copilot/ to give Copilot Spaces and new contributors a single entry point for process documentation.
