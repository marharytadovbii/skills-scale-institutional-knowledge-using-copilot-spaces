# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers both core delivery roles and supporting/governance roles to ensure clear ownership, reduce handoff gaps, and enable cross-functional collaboration across the full project lifecycle.

See also:
- [RACI Matrix](./octoacme-roles-raci-matrix.md) — responsibility assignments across lifecycle phases
- [Handoff Checklist](./octoacme-handoff-checklist.md) — structured handoff guide between roles and phases

---

## Core Delivery Roles

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

### Key Decisions Owned
- Implementation approach and technical patterns within agreed architecture
- Test strategy for individual components

### Interactions with Other Roles
- Receives acceptance criteria and feature specs from Product Managers
- Coordinates on architecture and technical trade-offs with the Technical Lead
- Flags blockers and risks to the Project Manager
- Works with QA/Testing Lead to agree on test coverage and handoff criteria

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

### Key Decisions Owned
- Feature prioritization and backlog ordering
- Acceptance criteria and definition of done for product outcomes
- Go/no-go on feature readiness from a product perspective

### Interactions with Other Roles
- Collaborates with the Project Manager on timeline, scope, and dependency management
- Partners with the Technical Lead on feasibility and sequencing
- Works with the Stakeholder Representative to align on business priorities
- Coordinates with the Change Management Lead on rollout readiness and communications

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

### Key Decisions Owned
- Project schedule and milestone sequencing
- Escalation paths and risk mitigation priorities
- Meeting cadence and facilitation

### Interactions with Other Roles
- Drives coordination between Product Managers, Developers, and the Technical Lead
- Escalates blockers to the Risk and Compliance Partner when governance or policy is involved
- Works with the Delivery Lead on cross-team dependency management and status reporting
- Coordinates with the Change Management Lead on communication planning

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Technical Lead / Solution Owner

### Role Summary
The Technical Lead owns the technical direction, architecture decisions, and implementation trade-offs for the project. They ensure that engineering choices are sustainable, aligned with standards, and feasible within the agreed scope and timeline.

### Responsibilities
- Define and communicate the technical approach and architecture
- Review and approve significant design and implementation decisions
- Identify and escalate technical risks and dependencies
- Guide developers on patterns, standards, and quality expectations
- Partner with Product Managers on feasibility and sequencing trade-offs

### Goals
- Deliver technically sound, maintainable solutions
- Reduce re-work caused by late-stage architectural decisions
- Ensure alignment between implementation and product intent

### Key Decisions Owned
- Architecture and system design choices
- Technology selection and deprecation within the project scope
- Resolution of conflicting technical approaches among developers

### Interactions with Other Roles
- Works closely with Developers on implementation guidance and code review
- Partners with Product Managers on scope feasibility and risk communication
- Coordinates with the Project Manager on technical milestones and dependency tracking
- Consults with the Risk and Compliance Partner on technical compliance requirements

### Example Scenarios
- Calling a design review when a proposed implementation creates significant complexity
- Flagging to the Project Manager that an external API dependency is at risk of delay
- Advising the Product Manager that a requested feature requires significant rework and proposing an incremental alternative

### Typical Communication
- Architecture decision records (ADRs) or technical design docs
- Code review feedback and pairing sessions
- Technical risk items in the risk register

---

## QA / Testing Lead

### Role Summary
The QA / Testing Lead owns the quality strategy for the project, ensuring that features meet acceptance criteria, that testing is integrated throughout delivery (not deferred to the end), and that release readiness is verified.

### Responsibilities
- Define the test strategy, including unit, integration, and acceptance test coverage expectations
- Coordinate test execution and triage defects with Developers
- Validate that acceptance criteria are met before promoting work to done
- Maintain the Definition of Done and verify it is applied consistently
- Produce release readiness sign-off based on test results

### Goals
- Prevent defects from reaching production
- Embed quality earlier in the delivery cycle
- Provide clear, evidence-based release readiness assessments

### Key Decisions Owned
- Test strategy and coverage thresholds
- Defect severity classification and escalation
- Release readiness sign-off (quality gate)

### Interactions with Other Roles
- Works with Developers to agree on test ownership and coverage per feature
- Coordinates with Product Managers to validate acceptance criteria are testable
- Reports quality status and blockers to the Project Manager
- Supports the Delivery Lead with test status as part of milestone reviews

### Example Scenarios
- Blocking a release candidate because a critical acceptance test is failing
- Raising a quality risk when test coverage has been reduced due to schedule pressure
- Collaborating with Developers to define integration test scenarios during planning

### Typical Communication
- Test plans and test result summaries
- Defect reports and triage sessions
- Release readiness checklist sign-off

---

## Delivery Lead / Program Coordinator

### Role Summary
The Delivery Lead owns cross-team coordination, milestone tracking, dependency management, and executive status reporting. This role operates above the individual project level and is engaged when delivery spans multiple teams, workstreams, or release trains.

### Responsibilities
- Track cross-team dependencies and surface blockers to the relevant Project Managers
- Maintain program-level milestone views and status dashboards
- Facilitate cross-team planning, alignment, and escalation forums
- Report program status to senior stakeholders and leadership

### Goals
- Keep multiple concurrent workstreams aligned and progressing
- Prevent delivery failures caused by unresolved cross-team dependencies
- Provide leadership with accurate, timely visibility into program health

### Key Decisions Owned
- Cross-team dependency prioritization
- Program-level timeline adjustments when individual project timelines conflict
- Escalation routing when a blocker affects multiple teams

### Interactions with Other Roles
- Works with individual Project Managers to aggregate status and surface cross-project risks
- Coordinates with the Change Management Lead on cross-team communications
- Escalates systemic blockers to the Risk and Compliance Partner or leadership
- Supports Product Managers on roadmap sequencing across teams

### Example Scenarios
- Facilitating a cross-team dependency review when two teams share a platform component
- Escalating a missed milestone that affects a downstream release to senior leadership
- Coordinating a joint planning session when two programs need to align on shared infrastructure

### Typical Communication
- Program status dashboards and executive summaries
- Dependency registers and cross-team risk logs
- Cross-team alignment meetings and escalation forums

---

## Supporting and Governance Roles

---

## Change Management / Adoption Lead

### Role Summary
The Change Management Lead owns rollout readiness, communications planning, enablement, and adoption tracking for significant process or product changes. They ensure that impacted teams and users are prepared before and after delivery.

### Responsibilities
- Develop and execute change communications plans
- Coordinate enablement and training activities for new features or processes
- Track adoption metrics and surface adoption risks post-release
- Partner with Product Managers and Project Managers on go-live readiness

### Goals
- Minimize disruption caused by changes
- Accelerate adoption of new features and processes
- Ensure stakeholders and end users are informed and prepared

### Key Decisions Owned
- Communications timing and messaging strategy
- Enablement plan scope and prioritization
- Adoption success criteria

### Interactions with Other Roles
- Works with Product Managers to understand the scope and impact of changes
- Coordinates with the Project Manager on communications milestones in the project plan
- Partners with the Documentation Owner to ensure user-facing documentation is ready at launch
- Reports adoption risks to the Stakeholder Representative and leadership

### Example Scenarios
- Developing a communications plan when a major feature changes an existing user workflow
- Coordinating a training rollout before a process change goes live
- Flagging low adoption post-release and recommending targeted enablement actions

### Typical Communication
- Change communications and announcements
- Training materials and enablement guides
- Adoption dashboards and post-launch reviews

---

## Risk and Compliance Partner

### Role Summary
The Risk and Compliance Partner supports risk identification, mitigation planning, governance checkpoints, and policy alignment. They ensure that delivery decisions are evaluated against organizational risk appetite and compliance requirements.

### Responsibilities
- Facilitate risk identification and scoring across projects
- Maintain the risk register and track mitigation actions to closure
- Advise on governance checkpoints and approval requirements
- Escalate compliance or policy concerns to leadership when needed
- Coordinate with external audit or regulatory stakeholders where applicable

### Goals
- Reduce project delivery risk through proactive identification and mitigation
- Ensure compliance requirements are understood and met before release
- Provide leadership with an accurate risk posture across the portfolio

### Key Decisions Owned
- Risk severity ratings and escalation thresholds
- Compliance sign-off requirements before release
- Governance checkpoint pass/fail recommendations

### Interactions with Other Roles
- Works with Project Managers to maintain accurate risk registers
- Advises the Technical Lead on compliance requirements for architecture decisions
- Coordinates with the Delivery Lead on program-level risk reporting
- Escalates unresolved risks to the Stakeholder Representative or leadership

### Example Scenarios
- Flagging that a planned integration requires a security review before deployment
- Facilitating a governance checkpoint review prior to a major release
- Escalating a risk that has exceeded its mitigation deadline to senior leadership

### Typical Communication
- Risk register updates and mitigation status reports
- Governance checkpoint summaries
- Escalation memos and compliance sign-off records

---

## Documentation Owner / Knowledge Manager

### Role Summary
The Documentation Owner maintains the quality and completeness of process documentation, ensures that updates are reflected across related docs, and helps standardize terminology and references across the project.

### Responsibilities
- Review and publish documentation updates aligned with project changes
- Maintain a documentation index and ensure cross-references are accurate
- Standardize terminology and templates across process docs
- Flag documentation gaps identified during delivery or retrospectives
- Support onboarding by ensuring documentation is discoverable and up to date

### Goals
- Ensure documentation accurately reflects current processes and roles
- Reduce onboarding friction through clear, well-organized documentation
- Prevent outdated documentation from causing delivery errors

### Key Decisions Owned
- Documentation structure, taxonomy, and naming conventions
- Prioritization of documentation updates and gap-filling
- Approval of new templates and process aids

### Interactions with Other Roles
- Works with Project Managers and Product Managers to capture process changes
- Coordinates with the Change Management Lead to publish user-facing documentation at launch
- Supports the Technical Lead by maintaining technical design doc standards
- Partners with the Delivery Lead to keep program-level artifacts current

### Example Scenarios
- Updating the roles and personas document after a new role is introduced
- Flagging in a retrospective that the handoff checklist has become outdated
- Creating a new template to standardize a recurring process across teams

### Typical Communication
- Documentation updates and changelogs
- Template reviews and style guides
- Documentation health reports during retrospectives

---

## Stakeholder Representative / Business Owner

### Role Summary
The Stakeholder Representative provides business context, prioritization input, acceptance guidance, and feedback on whether project outcomes meet business needs. They represent the interests of the business unit or customer segment most affected by the project.

### Responsibilities
- Communicate business priorities and constraints to the delivery team
- Participate in milestone reviews and provide acceptance sign-off
- Escalate business risks or concerns through the appropriate channels
- Validate that delivered outcomes align with business goals and user needs

### Goals
- Ensure delivery investment is directed at the highest-value business outcomes
- Provide timely, clear input so the team can make confident decisions
- Maintain alignment between delivery and business strategy

### Key Decisions Owned
- Business priority and urgency of features or changes
- Acceptance sign-off on delivered outcomes
- Escalation of business impact risks

### Interactions with Other Roles
- Partners with Product Managers to define and validate success metrics
- Provides direction to the Project Manager on business priorities and scheduling trade-offs
- Works with the Change Management Lead on change readiness from a business perspective
- Approves release readiness from the business side alongside the QA / Testing Lead

### Example Scenarios
- Attending a milestone demo and providing acceptance sign-off
- Raising a business risk when a delivery delay would affect a contractual commitment
- Working with the Product Manager to reprioritize the backlog after a strategic shift

### Typical Communication
- Milestone review attendance and sign-off
- Business requirement updates and priority changes
- Stakeholder briefings and executive updates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The [RACI Matrix](./octoacme-roles-raci-matrix.md) shows how responsibilities are distributed across lifecycle phases.
- The [Handoff Checklist](./octoacme-handoff-checklist.md) provides structured guidance on transitions between phases and roles.

