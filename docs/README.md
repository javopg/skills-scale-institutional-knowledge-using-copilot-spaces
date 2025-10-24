# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation. The purpose of these documents is to centralize how we initiate, plan, execute, release, and improve projects so new and existing team members can find consistent guidance, reduce single-person dependencies, and follow repeatable practices.

## Overview

OctoAcme runs projects iteratively and customer-first: projects start with a lightweight Project One‑pager that captures the problem, success metrics, stakeholders, and an initial risk register. Planning turns approved initiatives into a prioritized, estimated backlog with clear acceptance criteria, a Definition of Done, and a release/milestone map. Execution uses a visible project board and a small‑PR workflow to keep changes incremental and reviewable.

Day-to-day delivery is supported by a steady team rhythm (short standups, weekly delivery syncs, demos) and explicit risk & dependency management (a Risk Register with owners and escalation paths). Roles are clearly defined — Project Manager, Product Manager, Developers, QA/Testing, and Stakeholders — so responsibilities for planning, implementation, and communications are unambiguous.

Quality assurance is embedded in the pipeline: unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and a pre‑release checklist with rollback plans. Retrospectives after sprints, releases, or incidents convert learnings into prioritized action items tracked in the backlog to support continuous improvement.

## Process Documentation Links

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Operational Checklists](octoacme-checklists.md)
- [Onboarding Notes](octoacme-onboarding-notes.md)

## Using These Docs with Copilot Spaces

Keep the Project Charter updated in the project repo. Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context for code generation and project understanding.

## Issue Templates

Project-specific issue templates are available in [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/) to help standardize project initiation and tracking.
