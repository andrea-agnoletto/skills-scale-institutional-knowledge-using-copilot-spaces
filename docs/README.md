# OctoAcme Project Management Docs

This folder collects OctoAcme's project management processes and role guidance. Use this README as an entry point to the lifecycle and the detailed practices.

## Process overview

OctoAcme moves work through initiation, planning, execution and tracking, release, and closeout. Initiation validates the business need, outcomes, stakeholders, timeline, risks, and resources. Planning turns approved work into a prioritized backlog with acceptance criteria, estimates, dependencies, a Definition of Done, and a release plan. Teams deliver in small increments, track work on a project board, and use retrospectives after sprints, releases, or significant milestones to turn lessons into owned improvements.

A named Project Manager coordinates delivery, schedules, risks, and communication; the Product Manager defines outcomes, priorities, and success measures; developers implement and test; QA validates quality and acceptance criteria; and stakeholders provide input and approvals. Regular standups and delivery or stakeholder updates keep progress visible. Risks and dependencies are reviewed and escalated through the agreed chain, from the team through the PM and Product Lead to the sponsor when necessary.

Quality is integrated throughout delivery: teams write unit tests for new logic, add integration tests where applicable, and run tests and linting in CI before review. Releases require acceptance criteria to be met, passing CI and security scans, release notes, a rollback or mitigation plan, and prepared smoke tests. Teams smoke-test staging and verify production after deployment.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risk Management and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
