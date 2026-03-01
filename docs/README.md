# OctoAcme — Project Management Docs

## Overview

This directory centralizes OctoAcme's project management process documentation, capturing key workflows, responsibilities, and quality practices used to deliver projects effectively. By standardizing and versioning this knowledge in one place, all team members can quickly access the processes, decisions, and rationales that guide consistent project delivery and continuous improvement.

## Summary of Project Management Processes

OctoAcme's project management is grounded in a **five-phase lifecycle**: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each project starts with validating business need and stakeholder alignment through a lightweight **Project One-pager** that captures the problem statement, objectives, success metrics, and initial resource needs. Once approved by the Product Lead and sponsor, the team moves into planning, where work is broken into shippable increments, dependencies are identified, and a prioritized backlog with acceptance criteria is established. Throughout execution, the team follows a pull-request-driven workflow with small PRs (≤400 lines), automated CI/CD testing, and code review requirements.

Key roles are defined for clarity and accountability: **Project Managers** coordinate delivery activities, manage risks, and maintain transparency through status reporting and escalation; **Product Managers** define what to build, prioritize the backlog, and measure outcomes through success metrics; and **Developers** implement features, write tests, and collaborate on design and quality. A consistent communication rhythm supports alignment—daily standups (15 minutes) focus on progress and blockers, weekly syncs between PM and Product Manager ensure coordination, and monthly stakeholder updates maintain transparency. Escalation follows a three-level path: team-level triage in standups, PM escalation to Product Lead and dependent teams, and finally sponsor-level escalation for business-impacting issues.

Quality is embedded throughout OctoAcme's execution model, with unit tests for new logic, integration tests where applicable, and end-to-end smoke tests before release. A formal **risk register**—updated weekly and reviewed during syncs—tracks risks by impact, likelihood, owner, and mitigation plan. Security scanning occurs in CI, and manual QA validates feature acceptance when needed. The release process includes pre-release requirements such as passed CI checks, drafted release notes, and documented rollback plans. Additionally, OctoAcme fosters continuous improvement through structured retrospectives held after each sprint, release, or significant milestone, where teams capture learnings and convert them into actionable improvements.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
