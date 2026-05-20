# OctoAcme Project Management Documentation

Welcome! This directory contains standardized process guides and templates for managing projects at OctoAcme. Use this README as your starting point to discover, navigate, and understand the project management processes used across the organization.

## Overview of Project Management Processes

OctoAcme's project management approach is structured around a clear project lifecycle that moves from initiation through planning, execution, release, and retrospective improvement. The process begins with a lightweight but explicit project charter or one-pager that defines the problem, goal, success metrics, stakeholders, timeline, risks, and resource needs. Once approved, work is broken down into actionable plans and backlog items, with dependencies, milestones, and release planning captured early so the team can move from idea to delivery with shared expectations.

The core workflow is built around collaboration between defined roles: the Project Manager coordinates delivery, schedules, risks, and communications; the Product Manager owns outcomes, prioritization, and success measurement; developers implement and test the work; QA validates acceptance criteria; and stakeholders provide input and approvals. Teams use a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done—alongside small pull requests, linked issues, and clearly stated acceptance criteria—to keep execution organized and traceable.

Communication is handled through a regular cadence of meetings and status updates. OctoAcme recommends daily standups to surface progress, blockers, and dependencies; weekly PM/PdM syncs to align on priorities and risk; weekly delivery or stakeholder updates to communicate progress and decisions; and demos or reviews at the end of each sprint or milestone. Risk management is treated as an ongoing activity, with a simple risk register maintained during planning and updated during execution, plus an escalation path from the team level up through the PM, Product Lead, and sponsor when issues become more serious.

Quality assurance is woven into the process rather than treated as a final step. The docs call for unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, CI-based linting and security scanning, and manual QA when needed for feature acceptance. Before release, OctoAcme expects acceptance criteria to be met, CI to be passing, release notes and rollback plans to be prepared, and smoke tests to be ready. After delivery, retrospectives capture lessons learned and action items so improvements can be tracked and fed back into future work.

## Project Management Lifecycle

| Phase | Description |
|---|---|
| **Initiation** | Validate business needs, define objectives, and align stakeholders |
| **Planning** | Break approved initiatives into actionable plans, with milestones, Definition of Done, and risk management |
| **Execution & Tracking** | Run sprints, review progress, and manage quality |
| **Release & Deployment** | Standardize release prep, deployment, and rollback procedures |
| **Risk & Communication** | Track, communicate, and escalate risks and dependencies |
| **Retrospective & Continuous Improvement** | Capture learnings and drive improvements |
| **Roles & Personas** | Clarifies typical team roles and responsibilities |

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's approach, core principles, roles, key artifacts, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable backlog, sprint plan, milestones, and release plan
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day team rhythm, PR workflow, quality standards, and blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, risk lifecycle, stakeholder communication templates, and escalation paths
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Pre-release requirements, deployment checklist, rollback playbook, and release notes template
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives, tracking action items, and building a continuous improvement culture
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions and responsibilities for Developers, Product Managers, and Project Managers

## How to Use These Docs

- Use this README as the starting point whenever you are onboarding to OctoAcme processes or need to find the right process guide.
- Keep the Project Charter for your active project updated in the project repository.
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context for role-specific guidance.
- Review and update process docs after each significant project to capture improvements.
