# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may cover multiple roles on a small team; teams should name who is accountable for each responsibility during initiation and planning.

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

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator helps the team use its agreed delivery practices effectively, facilitates collaboration, and supports continuous improvement. This role complements rather than replaces the Project Manager's overall delivery coordination.

### Responsibilities
- Facilitate standups, planning, reviews, and retrospectives when agreed with the team
- Help surface and remove delivery blockers, coordinating with the PM when issues need wider escalation
- Coach the team on its working agreements and improve flow without prescribing a single methodology
- Capture retrospective actions and follow up with owners

### Goals
- Enable focused, predictable collaboration
- Reduce impediments and improve the team's delivery practices
- Foster an environment where concerns and learning are raised early

### Typical Communication and Interactions
- Works with the PM to coordinate ceremonies, dependencies, and blocker escalation
- Helps Developers and QA/Testing coordinate day-to-day work and raise impediments
- Partners with the Product Manager to keep refinement and planning conversations productive
- Shares improvement actions with the team and checks progress during regular syncs

### Accountability
Accountable for effective facilitation and surfacing impediments; the PM retains ownership of the integrated project plan and stakeholder status.

---

## UX/UI Designer

### Role Summary
The UX/UI Designer translates customer needs and product goals into accessible, usable experiences and validates design choices with users and the delivery team.

### Responsibilities
- Research user needs and map workflows with the Product Manager and stakeholders
- Create and validate interaction flows, prototypes, and interface specifications
- Consider accessibility and usability in design decisions
- Clarify design intent and edge cases during implementation

### Goals
- Deliver coherent, usable, accessible experiences
- Reduce uncertainty by validating concepts before or during implementation

### Typical Communication and Interactions
- Partners with the Product Manager on discovery, priorities, and acceptance criteria
- Reviews designs and implementation trade-offs with Developers and the Technical Lead
- Works with QA/Testing to identify usability and accessibility checks
- Shares research findings with the PM and stakeholders when they affect scope, risks, or milestones

### Accountability
Owns design recommendations and communicates evidence and trade-offs; the Product Manager remains accountable for product priorities and decisions.

---

## Data / Analytics Role

### Role Summary
The Data/Analytics role turns product and delivery questions into trustworthy measures, instrumentation, and insights that inform decisions.

### Responsibilities
- Help define measurable outcomes and event or reporting requirements with the Product Manager
- Advise Developers on instrumentation and data quality needs
- Build or coordinate dashboards and analyze usage, quality, and delivery signals
- Explain limitations, uncertainty, and privacy considerations in the data

### Goals
- Make outcome measures reliable and interpretable
- Help the team make evidence-informed product and delivery decisions

### Typical Communication and Interactions
- Works with the Product Manager to define success metrics and interpret customer outcomes
- Coordinates with Developers and the Technical Lead on event instrumentation and data quality
- Provides the PM with delivery signals and concise reporting for status and retrospectives
- Shares insights with stakeholders in context, distinguishing observations from recommendations

### Accountability
Accountable for analytical methods and communicating data limitations; the Product Manager owns product decisions and the PM owns project status reporting.

---

## Technical Lead / Engineering Lead

### Role Summary
The Technical Lead provides technical direction and helps the engineering team make sound implementation choices aligned with project goals and constraints.

### Responsibilities
- Guide architecture and technical design, identifying risks and dependencies early
- Support Developers with estimation, implementation choices, and technical reviews
- Mentor Developers and promote maintainability, testing, security, and observability
- Communicate engineering capacity, trade-offs, and technical blockers to the PM and Product Manager

### Goals
- Deliver a secure, reliable, maintainable technical solution
- Reduce technical uncertainty and unblock engineering decisions

### Typical Communication and Interactions
- Works with Developers on design, reviews, and technical problem solving
- Partners with the Product Manager on feasibility and trade-offs, and with the PM on dependencies and delivery impacts
- Coordinates with QA/Testing on testability and technical quality risks
- Consults Security/Compliance on controls and the Release Coordinator on technical readiness

### Accountability
Owns technical recommendations and engineering quality practices; scope and priority trade-offs are agreed with the Product Manager and delivery impacts with the PM.

---

## Release Manager / Release Coordinator

### Role Summary
The Release Manager or Release Coordinator organizes release readiness and deployment handoffs using the release process agreed by the team.

### Responsibilities
- Maintain the release checklist, schedule, and readiness record
- Coordinate environments, approvals, release notes, and stakeholder communications
- Confirm that CI, security checks, smoke tests, and rollback or mitigation plans are accounted for
- Track post-deployment verification and communicate release status

### Goals
- Make releases predictable, observable, and well communicated
- Ensure owners know readiness gaps and follow-up actions

### Typical Communication and Interactions
- Coordinates with QA/Testing on acceptance, smoke tests, and verification
- Works with Developers and the Technical Lead on deployment dependencies and rollback steps
- Confirms product readiness and release messaging with the Product Manager and customer-facing stakeholders
- Keeps the PM informed of schedule, risks, approvals, and go/no-go inputs

### Accountability
Accountable for coordinating the readiness process and recording status; the authorized release decision-maker follows the team's policy and is not assumed to be this role by default.

---

## Security / Compliance Role

### Role Summary
The Security/Compliance role advises on applicable security, privacy, and compliance requirements and helps teams identify and address related risks.

### Responsibilities
- Clarify relevant controls and requirements during initiation and planning
- Review risks, designs, and evidence at agreed points in delivery
- Advise on remediation, exceptions, and escalation paths
- Participate in release readiness and incident follow-up when security or compliance is implicated

### Goals
- Address security and compliance concerns early and proportionately
- Protect customers and the organization while enabling delivery

### Typical Communication and Interactions
- Works with Developers and the Technical Lead to embed controls and review design choices
- Coordinates with QA/Testing on security-related validation and evidence
- Advises the PM on risk-register entries, escalation, and schedule impacts
- Helps the Product Manager understand customer and product implications; follows the security incident runbook for incidents

### Accountability
Provides specialist guidance and identifies required escalations; designated security/compliance authorities retain approval or exception rights defined by organizational policy.

---

## Customer Support Representative

### Role Summary
The Customer Support Representative brings customer impact, supportability, and operational feedback into project decisions and release preparation.

### Responsibilities
- Share recurring customer questions, pain points, and issue trends
- Identify support documentation, training, and service-readiness needs
- Review customer-facing release communications for clarity and likely support impact
- Feed post-release issues and feedback into product discussions and retrospectives

### Goals
- Help customers adopt changes and get timely support
- Reduce avoidable support burden through readiness and feedback loops

### Typical Communication and Interactions
- Works with the Product Manager to prioritize customer feedback and understand impact
- Coordinates with the Release Coordinator on support readiness, release notes, and timing
- Shares incident and issue trends with the PM and Developers for triage and follow-up
- Collaborates with stakeholders on customer communications and escalation routes

### Accountability
Owns support-readiness input and customer issue trends; product prioritization remains with the Product Manager and incident response ownership follows the incident process.

---

## Sponsor / Executive Stakeholder

### Role Summary
The Sponsor or Executive Stakeholder provides strategic direction, sponsorship, and decisions that exceed the delivery team's delegated authority.

### Responsibilities
- Set strategic context, priority, and funding or capacity boundaries
- Confirm or resolve high-impact scope and priority conflicts
- Make or reinforce go/no-go decisions at agreed decision gates
- Resolve escalations the PM and Product Manager cannot settle within their authority

### Goals
- Ensure investment aligns with strategic outcomes
- Enable timely decisions and remove organizational barriers

### Typical Communication and Interactions
- Aligns with the PM and Product Manager on objectives, status, risks, and decisions needed
- Receives escalations with options, impacts, and a clear recommendation
- Confirms strategic decisions with stakeholders and communicates changes to priority or funding

### Accountability
Accountable for sponsorship and decisions explicitly delegated to the sponsor; day-to-day delivery coordination remains with the PM and product priorities with the Product Manager.

---

## Role Coverage Across the Project Lifecycle

The table is a lightweight accountability guide, not a substitute for named owners or organizational approval policies. Assign one accountable decision owner for each activity during initiation and planning; consult relevant specialists and record exceptions.

| Activity | Accountable lead | Key contributors and handoffs |
| --- | --- | --- |
| Initiation and outcome definition | Product Manager | PM coordinates the one-pager and stakeholders; Sponsor confirms strategic alignment; Data/Analytics advises on measurable outcomes; UX/UI Designer contributes user needs. |
| Planning, scope, and milestones | PM | Product Manager prioritizes; Technical Lead and Developers estimate and identify dependencies; UX/UI Designer, QA/Testing, Security/Compliance, and Data/Analytics identify needs and risks. |
| Execution and quality | Technical Lead (technical approach) | Developers implement; QA/Testing validates acceptance; Scrum Master facilitates team flow; PM tracks milestones and blockers; Product Manager clarifies scope. |
| Release readiness and deployment coordination | Release Coordinator | QA/Testing confirms validation; Technical Lead and Developers confirm technical readiness and rollback; Security/Compliance advises on required checks; Product Manager and Support prepare customer-facing readiness; PM communicates status. |
| Retrospective and improvement follow-up | PM | Scrum Master facilitates as agreed; all delivery roles contribute; Product Manager and Data/Analytics help assess outcome signals; named action owners follow through. |
| Strategic go/no-go or funding decision | Sponsor, when delegated | PM and Product Manager present status, risks, and options; Release Coordinator supplies readiness status; required security/compliance approval follows policy. |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
