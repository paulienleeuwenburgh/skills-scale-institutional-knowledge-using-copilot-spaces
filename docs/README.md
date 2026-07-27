# OctoAcme Project Management Documentation

This folder contains the end-to-end project management process documentation for OctoAcme. Use the index below to navigate individual process guides, or read the summary below for a quick orientation.

---

## Overview

OctoAcme uses a structured but lightweight project lifecycle that moves from **initiation** through **planning**, **execution**, **release**, and **retrospective improvement**. Work begins with a one-pager that clarifies the problem statement, SMART-style goals, success metrics, stakeholders, timeline, risks, and team roles. A go/no-go decision is made before planning begins, based on stakeholder alignment, clear metrics, and team availability. Once approved, planning breaks initiatives into shippable backlog increments with acceptance criteria, estimates, dependencies, milestones, and a documented Definition of Done.

Roles are clearly defined to support cross-functional delivery. **Product Managers** set outcomes, prioritize the roadmap and backlog, and validate value through user and business metrics. **Project Managers** coordinate timelines, risks, dependencies, communication, and meeting cadence while maintaining transparency through status reporting and documentation. **Developers** implement and test features, support estimation, participate in design and code reviews, and surface technical risks. QA/testing contributors validate acceptance criteria and release readiness, while stakeholders provide direction, approvals, and feedback at key checkpoints.

Execution is organized around repeatable team rhythms and board-based workflow tracking. Teams use daily standups and weekly delivery syncs to monitor progress, blockers, and risks, with demos and reviews at sprint or milestone boundaries. Work is tracked through staged board columns (Backlog → Ready → In Progress → In Review → QA → Done), and pull request practices emphasize small changes, issue linkage, acceptance criteria, CI checks, and required approval before merge. Risk management is continuous: risks are logged with impact and likelihood ratings, owners, mitigations, and status, with a defined escalation path from team triage to PM, Product Lead, and sponsor as business impact increases.

Quality and release discipline are embedded throughout delivery. OctoAcme expects unit tests for new logic, integration and end-to-end smoke coverage for critical flows, CI-based linting and security scanning, and manual QA where appropriate. Releases are categorized (patch/minor/major) and gated by acceptance completion, passing CI and security checks, release notes, rollback planning, and post-deploy verification. After each sprint, release, or incident, retrospectives capture what worked, what didn't, and 2–3 prioritized action items with owners and due dates—ensuring process improvements are tracked, measured, and fed back into living documentation.

---

## Documentation Index

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's project management approach, principles, core roles, key artifacts, and lifecycle. |
| [Project Initiation](octoacme-project-initiation.md) | How to start a project: one-pager structure, stakeholder alignment, and go/no-go criteria. |
| [Project Planning](octoacme-project-planning.md) | Scope, backlog, milestones, dependencies, and Definition of Done. |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Team rhythms, board workflows, PR practices, and progress monitoring. |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication cadence. |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release categories, gating criteria, rollback planning, and post-deploy verification. |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint and release retrospectives, action item tracking, and living documentation practices. |
| [Roles and Personas](octoacme-roles-and-personas.md) | Responsibilities, goals, and communication patterns for each role in OctoAcme projects. |
