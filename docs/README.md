# OctoAcme Project Management Docs

This folder is the entry point to OctoAcme's project management guidance. OctoAcme prioritizes customer value, iterative delivery, clear ownership, data-informed decisions, and psychological safety. The process takes cross-functional work from a validated need through safe delivery and continuous improvement.

## Project management process

- **Initiation:** Validate the business need, identify stakeholders, define measurable success criteria, and decide whether to move forward.
- **Planning:** Break approved work into shippable increments, define acceptance criteria and the Definition of Done (DoD), estimate work, and capture risks and dependencies.
- **Execution & tracking:** Use the project board and pull request workflow; keep PRs small when possible, link issues, and run tests and linting. Track progress and blockers through standups, delivery syncs, and status reporting.
- **Risk management & communication:** Maintain a risk register and review it regularly. Share weekly or milestone-based updates, with clear escalation paths for blockers and incidents.
- **Release & deployment:** Require passing CI and security scans, prepare release notes, deploy safely with smoke tests and post-deployment checks, and maintain rollback and incident-response procedures.
- **Retrospective & continuous improvement:** Hold retrospectives after sprints, releases, milestones, and incidents. Capture owned action items and track follow-up improvements.

## Documentation

- [Project Management Overview](octoacme-project-management-overview.md) — principles, roles, artifacts, lifecycle, and cadence
- [Project Initiation](octoacme-project-initiation.md) — validate and authorize proposed work
- [Project Planning](octoacme-project-planning.md) — shape approved work into a delivery plan
- [Execution & Tracking](octoacme-execution-and-tracking.md) — coordinate day-to-day work and quality
- [Risk Management & Communication](octoacme-risks-and-communication.md) — manage risks, updates, and escalations
- [Release & Deployment](octoacme-release-and-deployment.md) — prepare, deploy, verify, and recover releases
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — turn learnings into tracked improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — responsibilities and communication by role

## Quick navigation by role

- **Developers:** Start with [Roles & Personas](octoacme-roles-and-personas.md), then use [Execution & Tracking](octoacme-execution-and-tracking.md) and [Release & Deployment](octoacme-release-and-deployment.md) for delivery practices.
- **Product Managers:** Start with [Project Initiation](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md), then refer to [Risk Management & Communication](octoacme-risks-and-communication.md) to keep stakeholders aligned.
- **Project Managers:** Start with the [Project Management Overview](octoacme-project-management-overview.md), and use [Project Planning](octoacme-project-planning.md), [Execution & Tracking](octoacme-execution-and-tracking.md), and [Risk Management & Communication](octoacme-risks-and-communication.md) to coordinate delivery.

## Using these docs with Copilot Spaces

Use this documentation as a shared, versioned knowledge source for a Copilot Space: add this repository or the relevant `docs/` files as the Space's knowledge sources, and keep guidance updated through the repository's normal review and version-control workflow. Start with this README to orient people and Copilot, then include the process-specific documents that match the team's work. Updating the docs in the repository keeps the reviewed source of truth together; confirm the Space's configured sources reflect the latest version.
