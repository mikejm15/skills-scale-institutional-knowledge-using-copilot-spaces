# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Test Engineers

### Role Summary
QA / Test Engineers define and execute the test strategy that verifies readiness across functional, integration, and release quality gates.

### Responsibilities
- Define risk-based test coverage for stories, integrations, and critical user journeys
- Validate acceptance criteria and Definition of Done with Developers and Product Managers
- Run manual and automated checks, including regression and smoke testing
- Track defects, support triage, and confirm fixes before release
- Provide release readiness quality sign-off input

### Goals
- Prevent customer-impacting defects from reaching production
- Keep quality feedback fast and actionable during execution
- Improve confidence in release decisions

### Typical Communication
- Daily coordination with Developers on testability and defect triage
- Sprint-level quality status shared with PM and PdM
- Release go/no-go recommendations with engineering and project leads

### Interaction with Existing Roles
- **Initiation:** aligns with PM/PdM on quality risks and early acceptance expectations.
- **Planning:** partners with Developers and PM to shape test approach and QA effort in the plan.
- **Execution:** works with Developers on defect triage and quality trends during standups and reviews.
- **Release:** collaborates with Project Managers and Support/Ops on smoke test outcomes and release readiness.
- **Retrospective:** shares defect escape and test coverage insights with PM, PdM, and Developers for improvements.

---

## Engineering Managers

### Role Summary
Engineering Managers ensure team capacity, delivery health, and people enablement so project commitments are realistic and sustainable.

### Responsibilities
- Confirm team staffing, priorities, and delivery capacity
- Remove organizational blockers and escalate resource risks
- Coach engineers and maintain healthy execution practices
- Balance short-term delivery with long-term maintainability
- Partner with PM and PdM on trade-offs that affect timeline or scope

### Goals
- Maintain predictable delivery across milestones
- Keep engineering teams effective, engaged, and supported
- Reduce execution risk caused by capacity or dependency gaps

### Typical Communication
- Weekly delivery and risk reviews with PM/PdM
- Ongoing 1:1 and team coaching conversations
- Leadership updates on staffing, risks, and delivery confidence

### Interaction with Existing Roles
- **Initiation:** validates initial staffing assumptions with PM and Sponsor stakeholders.
- **Planning:** aligns capacity and sequencing with Project Managers and Technical Leads.
- **Execution:** supports Developers and PM by resolving blockers and adjusting staffing as needed.
- **Release:** confirms on-call/support coverage and readiness with Tech Leads and Support/Ops.
- **Retrospective:** sponsors follow-up actions that improve team health and delivery reliability.

---

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads set technical direction, guide implementation choices, and ensure architectural quality throughout delivery.

### Responsibilities
- Define solution approach, architecture boundaries, and technical milestones
- Drive engineering standards for reliability, security, and maintainability
- Review complex changes and guide technical decision-making
- Coordinate cross-team integration and dependency readiness
- Partner with PM/PdM on technical trade-offs and sequencing

### Goals
- Deliver scalable solutions that meet product outcomes
- Reduce rework through clear technical decisions
- Keep implementation aligned with quality and operational expectations

### Typical Communication
- Technical design reviews with Developers and QA
- Dependency and milestone planning with PM/PdM
- Risk and architecture updates to stakeholders when decisions shift scope or timeline

### Interaction with Existing Roles
- **Initiation:** helps PM and PdM shape solution options and initial technical risk profile.
- **Planning:** defines architecture milestones and dependency plans with Developers and Project Managers.
- **Execution:** mentors Developers and partners with QA on testability and defect root-cause analysis.
- **Release:** coordinates release technical checks with QA, Security, and Support/Ops.
- **Retrospective:** leads technical improvement actions with Developers and Engineering Managers.

---

## UX / Product Designers

### Role Summary
UX / Product Designers ensure solutions are usable, accessible, and consistent with customer needs and product intent.

### Responsibilities
- Conduct discovery and user research to validate problem understanding
- Produce user flows, wireframes, and design specs for delivery
- Define usability and accessibility expectations for acceptance criteria
- Collaborate with Developers and QA on implementation quality
- Validate shipped experiences against intended outcomes

### Goals
- Improve user adoption and task success
- Reduce usability defects and design rework
- Keep delivery aligned to customer context

### Typical Communication
- Discovery and design reviews with PdM and stakeholders
- Handoff sessions with Developers and QA
- Feedback loops from demos, user testing, and post-release insights

### Interaction with Existing Roles
- **Initiation:** supports PdM and stakeholders with problem framing and user context.
- **Planning:** aligns designs and acceptance criteria with PM, PdM, and Developers.
- **Execution:** partners with Developers and QA to clarify behavior and accessibility expectations.
- **Release:** validates final experience and communicates known UX constraints before launch.
- **Retrospective:** reviews user feedback trends with PdM and team to prioritize design improvements.

---

## Business Stakeholders / Executive Sponsors

### Role Summary
Business Stakeholders and Executive Sponsors provide strategic direction, prioritization input, and approval support for high-impact decisions.

### Responsibilities
- Clarify business outcomes, constraints, and strategic priorities
- Approve major scope, timeline, and investment decisions
- Support escalation handling for business-critical blockers
- Review milestone outcomes and release impact
- Champion adoption and cross-functional alignment

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between delivery and organizational priorities
- Reduce decision latency for critical trade-offs

### Typical Communication
- Milestone and monthly status reviews with PM/PdM
- Decision and escalation meetings for scope/timeline trade-offs
- Executive updates on outcomes, risks, and release readiness

### Interaction with Existing Roles
- **Initiation:** aligns goals, success metrics, and approval expectations with PM/PdM.
- **Planning:** validates milestone commitments and key dependencies.
- **Execution:** receives regular status and risk updates from Project Managers.
- **Release:** reviews release readiness, customer/business impacts, and communication plans.
- **Retrospective:** sponsors systemic improvements from lessons learned and outcome reviews.

---

## Customer Support / Operations Representatives

### Role Summary
Customer Support / Operations Representatives protect customer experience during rollout by preparing runbooks, readiness checks, and post-release response workflows.

### Responsibilities
- Provide frontline insights on recurring customer pain points
- Review release notes and prepare support/troubleshooting guidance
- Confirm operational readiness, on-call handoffs, and escalation paths
- Monitor incidents, customer tickets, and production signals after release
- Feed support and operations learnings into backlog prioritization

### Goals
- Minimize customer disruption during changes
- Shorten time to detect and resolve post-release issues
- Improve operational maturity release over release

### Typical Communication
- Release readiness syncs with PM, Tech Leads, and QA
- Incident/status updates through defined escalation channels
- Post-release summaries to Product and Project leadership

### Interaction with Existing Roles
- **Initiation:** shares customer impact patterns with PdM and PM to shape priorities.
- **Planning:** aligns support readiness needs and operational dependencies with Project Managers.
- **Execution:** collaborates with Developers and QA on known issues and support content.
- **Release:** coordinates announcements, monitoring, and escalation workflows with PM and Engineering.
- **Retrospective:** contributes incident and ticket trend data for continuous improvement actions.

---

## Security / Compliance Representatives

### Role Summary
Security / Compliance Representatives ensure delivery decisions meet security standards, policy obligations, and risk tolerance before and after release.

### Responsibilities
- Identify security and compliance requirements early in project scope
- Review architecture and implementation for security risks
- Support threat modeling and control validation
- Verify required security scans, controls, and sign-offs for release
- Guide incident response and post-incident corrective actions

### Goals
- Reduce security and compliance risk exposure
- Embed secure-by-design practices in delivery
- Ensure audit and policy expectations are met

### Typical Communication
- Risk and control discussions with Technical Leads and PM
- Security findings triage with Developers and QA
- Escalation support with leadership during security incidents

### Interaction with Existing Roles
- **Initiation:** aligns risk classification and compliance requirements with PM/PdM.
- **Planning:** works with Technical Leads to define controls, testing, and review checkpoints.
- **Execution:** partners with Developers and QA to remediate findings and validate fixes.
- **Release:** confirms security readiness with Project Managers before production deployment.
- **Retrospective:** reviews incidents/findings with the team and tracks prevention actions.

---

## Data Analysts / Analytics Partners

### Role Summary
Data Analysts / Analytics Partners define measurement plans and interpret delivery outcomes so teams can make evidence-based decisions.

### Responsibilities
- Define success metrics, baselines, and tracking requirements with PdM
- Validate instrumentation and data quality before release
- Build dashboards and reports for delivery and outcome monitoring
- Analyze experiment, adoption, and operational trend data
- Recommend adjustments based on observed results

### Goals
- Improve decision quality with trusted data
- Detect outcome and adoption risks early
- Strengthen continuous improvement with measurable evidence

### Typical Communication
- Metric definition sessions during initiation/planning
- Ongoing dashboard updates for PM, PdM, and delivery leads
- Post-release and retrospective readouts with actionable recommendations

### Interaction with Existing Roles
- **Initiation:** partners with PdM and PM to define measurable goals and baselines.
- **Planning:** aligns instrumentation dependencies with Developers and Technical Leads.
- **Execution:** monitors in-flight signals and shares trend insights with PM/PdM.
- **Release:** verifies launch measurement readiness and early outcome tracking.
- **Retrospective:** supports root-cause analysis and prioritization of improvements using data.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
