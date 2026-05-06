# OctoAcme Project Management Docs

## Purpose of this docs folder
This `docs/` folder is OctoAcme's central source of truth for project management processes. It is designed to keep onboarding and delivery guidance in one place so teams can run projects consistently and provide reliable context for Copilot Spaces.

## OctoAcme process overview
OctoAcme uses a lightweight lifecycle that runs from **initiation** to **planning**, **execution**, **release**, and **retrospective improvement**. Work starts with a one-pager that defines the problem, goals, stakeholders, risks, and initial timeline. Approved initiatives then move into planning, where teams prioritize backlog items, define acceptance criteria and Definition of Done, map milestones, and identify dependencies.

During execution, teams track work through a shared board, deliver in small increments, and review progress through standups, weekly syncs, and sprint or milestone demos. Releases follow pre-release checks (including CI and security scans), staged deployment/smoke testing, post-deploy verification, and stakeholder communication. After each sprint, release, or incident, retrospectives capture lessons learned and turn them into owned action items for continuous improvement.

## Key roles and personas
- **Project Manager (PM):** coordinates plans, timelines, risks, and cross-team communication.
- **Product Manager (PdM):** defines outcomes, prioritizes backlog, and measures impact.
- **Developers:** design and implement features, contribute to estimation, and surface technical risks.
- **QA/Testing:** validates acceptance criteria and overall quality through test strategy and verification.
- **Stakeholders/Sponsors:** provide direction, approvals, and business alignment.

## Communication rhythm and escalation
- Daily standups for delivery progress, blockers, and dependencies.
- Weekly PM/Product and delivery syncs for status, risks, and decisions.
- Sprint/milestone demos and monthly stakeholder updates for visibility.
- Escalation path for blockers and risk: **Team triage -> PM -> Product Lead -> Sponsor**.

## Quality and release practices
- Define acceptance criteria and Definition of Done during planning.
- Keep PRs focused, link PRs to issues, and require at least one approval.
- Run automated tests/linting and security scanning in CI before merge/release.
- Use unit tests, integration tests, and critical-flow smoke tests, plus manual QA when needed.
- Prepare release notes, rollback plans, and post-deployment verification checks.

## Related process documents
- `octoacme-project-management-overview.md`
- `octoacme-project-initiation.md`
- `octoacme-project-planning.md`
- `octoacme-execution-and-tracking.md`
- `octoacme-release-and-deployment.md`
- `octoacme-risks-and-communication.md`
- `octoacme-retrospective-and-continuous-improvement.md`
- `octoacme-roles-and-personas.md`
