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

## QA Lead / Test Engineer

### Role Summary
The QA Lead owns the overall test strategy and quality gates for the project. They ensure features meet the Definition of Done before release and coordinate manual and automated testing across the team.

### Responsibilities
- Define and maintain the test strategy and test plans
- Write, own, and triage automated and manual test suites
- Enforce Definition of Done criteria at sprint and release boundaries
- Report test results, defect trends, and quality metrics
- Coordinate UAT with stakeholders and end-users
- Identify and escalate quality risks before release

### Goals
- Prevent defects from reaching production
- Shorten feedback loops between development and testing
- Ensure consistent quality standards across all releases

### Typical Communication
- Sprint planning and refinement to clarify acceptance criteria
- QA status updates in weekly delivery syncs
- Defect reports and test summary emails before releases

### Works closely with / Interactions
- **Developers**: Pair on test coverage gaps, review pull requests for testability, and triage failing tests together
- **Product Managers**: Clarify acceptance criteria and validate user-facing flows through UAT
- **Project Managers**: Report quality risks to the risk register; participate in release go/no-go decisions
- **Stakeholders / Sponsors**: Present UAT results and release-readiness summaries

---

## Scrum Master / Agile Facilitator

### Role Summary
The Scrum Master coaches the team in agile practices, facilitates ceremonies, and removes impediments so the team can maintain a sustainable delivery pace.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers at the team level; escalate when needed
- Track team health, velocity, and delivery cadence
- Shield the team from unplanned interruptions and scope creep
- Coach the team on agile principles and help improve ceremonies over time
- Maintain the sprint board and ensure workflow hygiene

### Goals
- Maximize team flow and reduce cycle time
- Create a safe space for continuous improvement and candid feedback
- Keep ceremonies focused, timely, and valuable

### Typical Communication
- Daily standup facilitation
- Retrospective outcomes and action-item tracking
- Escalations to Project Manager or Product Manager when blockers cannot be resolved at the team level

### Works closely with / Interactions
- **Developers**: Day-to-day facilitation of standups, sprint ceremonies, and blocker removal
- **Project Managers**: Align on project-level risks, dependencies, and escalation paths
- **Product Managers**: Ensure backlog is refined and sprint goals are well-defined before planning sessions

---

## UX/UI Designer

### Role Summary
The UX/UI Designer leads user experience research and design, producing wireframes, prototypes, and high-fidelity assets that guide development and ensure usability standards are met.

### Responsibilities
- Conduct user research, usability testing, and stakeholder workshops
- Create wireframes, mockups, and interactive prototypes
- Maintain the design system and component library
- Review implemented features against design specifications
- Ensure accessibility and usability standards are applied
- Participate in sprint planning to keep design one sprint ahead of development

### Goals
- Deliver intuitive, accessible user experiences
- Reduce development rework caused by unclear design requirements
- Ensure user feedback informs prioritization

### Typical Communication
- Design reviews and critique sessions with Developers and Product Managers
- Prototypes and annotated mockups shared in sprint planning
- Usability test readouts presented to Stakeholders

### Works closely with / Interactions
- **Developers**: Hand off design assets with annotations; review implementation for fidelity
- **Product Managers**: Align design work with product vision, user stories, and roadmap priorities
- **Stakeholders / Sponsors**: Present research findings and prototype reviews to gather feedback and validate direction

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business requirements and technical delivery. They ensure user stories are clear, complete, and aligned with business goals before development begins.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Write and refine user stories and acceptance criteria in the backlog
- Facilitate scope clarification sessions between stakeholders and the delivery team
- Analyze and map current and future-state processes
- Support UAT planning and sign-off coordination
- Identify scope changes and assess their impact

### Goals
- Ensure requirements are unambiguous and development-ready
- Reduce mid-sprint scope surprises and rework
- Bridge communication gaps between technical and non-technical audiences

### Typical Communication
- Backlog refinement sessions with Product Managers and Developers
- Requirements workshops with Stakeholders
- Impact assessments shared with Project Managers during planning

### Works closely with / Interactions
- **Product Managers**: Translate product vision into detailed, actionable user stories and acceptance criteria
- **Developers**: Clarify requirements during sprint; answer questions to unblock implementation
- **Project Managers**: Flag scope risks and change requests for impact assessment and planning adjustments
- **Stakeholders / Sponsors**: Facilitate requirements workshops and validate understanding of business needs

---

## Technical Writer

### Role Summary
The Technical Writer creates and maintains clear, accurate documentation for both internal processes and user-facing content, ensuring that knowledge is accessible to all audiences.

### Responsibilities
- Author, review, and update process documentation, API docs, and user guides
- Ensure documentation is consistent with the current state of the product and processes
- Coordinate with SMEs (Developers, QA, Product Managers) to validate accuracy
- Apply and maintain documentation style standards
- Publish documentation on release and flag outdated content for review

### Goals
- Reduce time lost to knowledge gaps and repeated questions
- Keep documentation current with each release
- Improve onboarding speed for new team members and users

### Typical Communication
- Documentation review cycles aligned with sprint reviews and releases
- Async collaboration via pull request reviews and document comments
- Coordination with QA to validate technical accuracy of user-facing content

### Works closely with / Interactions
- **Developers**: Review technical content for accuracy; obtain code examples and API details
- **QA Lead**: Validate that documented steps reflect tested and approved behavior
- **Product Managers**: Align documentation scope with feature releases and product priorities
- **Stakeholders / Sponsors**: Produce release-facing communications and executive summaries as needed

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent the business interests of the project. They provide strategic direction, approve major decisions, fund the initiative, and are accountable for the business outcomes.

### Responsibilities
- Define and communicate business goals, success criteria, and constraints
- Approve project scope, budget, and major change requests
- Provide timely decisions on escalated blockers and trade-offs
- Review and sign off on milestones, UAT, and release readiness
- Ensure organizational support and resource availability
- Act as executive escalation point for cross-team dependencies

### Goals
- Achieve measurable business outcomes from the project investment
- Maintain visibility into project health and risk without being in the day-to-day
- Enable the delivery team to move quickly by making clear, timely decisions

### Typical Communication
- Milestone readouts and steering committee updates (bi-weekly or monthly)
- Escalation notifications from Project Managers or Product Managers
- UAT review and sign-off checkpoints

### Works closely with / Interactions
- **Product Managers**: Align on product vision, roadmap trade-offs, and success metrics
- **Project Managers**: Receive status reports, risk escalations, and decision requests
- **QA Lead / Business Analyst**: Review UAT results and sign off on release readiness
- **UX/UI Designer**: Provide feedback on prototypes and design direction during reviews

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager or Tech Lead provides technical direction, owns the architecture decisions, and ensures the engineering team has the capacity, clarity, and standards to deliver quality software sustainably.

### Responsibilities
- Define and enforce coding standards, architectural patterns, and technical guidelines
- Own technical risk identification and mitigation planning
- Review and approve significant design documents and architecture decisions
- Support career growth and performance of engineers on the team
- Align technical roadmap with product roadmap and business goals
- Participate in release go/no-go decisions from a technical readiness perspective

### Goals
- Maintain a healthy, scalable, and maintainable codebase
- Reduce technical debt accumulation and unplanned outages
- Enable Developers to work autonomously within clear guardrails

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Engineering capacity and risk updates in weekly delivery syncs
- 1:1s and performance conversations with direct reports

### Works closely with / Interactions
- **Developers**: Provide code review guidance, unblock technical decisions, and mentor on best practices
- **Product Managers**: Translate feature requests into technical feasibility assessments and trade-off discussions
- **Project Managers**: Flag technical risks and capacity constraints for project planning and risk register updates
- **QA Lead**: Align on testability, CI standards, and release-readiness criteria

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-roles-and-personas-raci.md`](./octoacme-roles-and-personas-raci.md) for a RACI matrix mapping key project activities to these roles.

