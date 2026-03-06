# OctoAcme Project Management Docs

This directory is the entry point for OctoAcme's project management documentation. It provides the processes, templates, and guidance used by all cross-functional teams to plan, execute, and ship product work consistently.

## Overview

OctoAcme follows an iterative delivery lifecycle with five key phases: **Initiation**, **Planning**, **Execution & Tracking**, **Release & Deployment**, and **Retrospective/Continuous Improvement**. Each project begins with a lightweight one-pager that captures the problem statement, success metrics, and stakeholder alignment before moving to planning. Planning produces a prioritized backlog, a Definition of Done (DoD), a release plan, and a risk register. Work is then delivered in short iterations with daily standups, sprint demos, and weekly syncs to keep teams aligned and blockers surfaced early.

The team is organized around clear **roles**: the Project Manager (PM) coordinates delivery, schedules, risks, and cross-team communications; the Product Manager (PdM) owns the product vision, backlog prioritization, and success metrics; Developers implement features and maintain tests and documentation; QA/Testing validates acceptance criteria and quality standards; and Stakeholders provide input and approvals at key decision gates. Each project charter names a PM and Product Lead so ownership is always explicit.

**Communication** follows a defined cadence: twice-weekly standups for the delivery team, a weekly PM + PdM sync, and monthly stakeholder updates. Risks and blockers are tracked in a shared risk register reviewed each week. Escalation paths are tiered—team-level triage first, then PM escalation to the Product Lead, and sponsor-level escalation for business-impacting issues. Security incidents follow a dedicated runbook and notify the Security on-call team immediately.

**Quality assurance** is built into every phase. Acceptance criteria are defined per backlog item and rolled up into the project's Definition of Done. Pull requests are kept small (≤ 400 lines where possible), include an issue link and acceptance criteria, and require at least one approval after passing automated tests, linting, and security scans in CI. Before any release, smoke tests run against staging, release notes are drafted, and a rollback plan is in place. After each sprint or milestone, the team holds a blameless retrospective to capture learnings and track improvement action items.

## Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
