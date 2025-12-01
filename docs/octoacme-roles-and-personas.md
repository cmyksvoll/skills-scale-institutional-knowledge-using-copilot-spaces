# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. For each role, we provide a summary, key responsibilities, goals, and typical communication patterns with other personas.

> **See also:** For workflow details and how these roles interact across project phases, refer to [Project Management Overview](octoacme-project-management-overview.md) and [Execution & Tracking](octoacme-execution-and-tracking.md).

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

### Touchpoints with Other Personas
- **Product Managers:** Clarify requirements and acceptance criteria; provide technical feasibility feedback
- **Project Managers:** Report progress and blockers; participate in planning and estimation
- **QA:** Collaborate on test coverage, defect resolution, and acceptance testing
- **Scrum Master:** Participate in agile ceremonies; raise impediments
- **UX Designer:** Implement UI/UX designs; provide feedback on technical constraints
- **Technical Writer:** Provide technical details for documentation; review accuracy
- **Solution Architect:** Follow architectural guidance; contribute to design reviews

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

### Touchpoints with Other Personas
- **Developers:** Provide requirements, prioritize features; clarify acceptance criteria
- **Project Managers:** Align on timelines and dependencies; coordinate release plans
- **QA:** Define acceptance criteria; validate delivered features meet requirements
- **Business Analyst:** Receive analyzed requirements and business insights; validate solution fit
- **UX Designer:** Collaborate on user flows and design decisions; validate usability
- **Technical Writer:** Provide context for documentation; review product messaging
- **Stakeholders:** Gather feedback and requirements; present roadmap and progress

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

### Touchpoints with Other Personas
- **Product Managers:** Align on priorities and timelines; coordinate deliverables
- **Developers:** Track progress and blockers; facilitate planning sessions
- **QA:** Coordinate testing schedules; track quality metrics and defect resolution
- **Scrum Master:** Collaborate on process improvements; coordinate agile ceremonies
- **Solution Architect:** Understand technical dependencies; manage architecture-related risks
- **Business Analyst:** Incorporate business requirements into project plans
- **Stakeholders:** Provide regular status updates; manage expectations and escalations

---

## QA / Testing

### Role Summary
QA Engineers validate that software meets quality standards and acceptance criteria. They design test strategies, execute tests, and collaborate with the team to ensure reliable, high-quality releases.

### Responsibilities
- Create and maintain test plans and test cases
- Execute manual and automated tests
- Report and track defects
- Validate acceptance criteria before release
- Collaborate with Developers on testability and coverage

### Goals
- Ensure product quality and reliability
- Catch defects early in the development cycle
- Maintain comprehensive test coverage

### Typical Communication
- Daily standups to report testing progress
- Defect reviews and triage meetings
- Release readiness assessments

### Touchpoints with Other Personas
- **Developers:** Collaborate on defect resolution; provide feedback on testability
- **Product Managers:** Validate features meet acceptance criteria
- **Project Managers:** Report quality metrics; participate in release planning
- **Technical Writer:** Provide testing insights for documentation
- **Scrum Master:** Participate in retrospectives; raise quality-related impediments

---

## Stakeholders

### Role Summary
Stakeholders are business representatives, sponsors, or customers who provide inputs, requirements, and approvals throughout the project lifecycle. They ensure the project aligns with business goals.

### Responsibilities
- Provide business requirements and context
- Approve project scope, timelines, and deliverables
- Participate in key decision gates
- Provide feedback during demos and reviews

### Goals
- Ensure project delivers expected business value
- Maintain alignment with organizational strategy
- Manage risk to business operations

### Typical Communication
- Monthly stakeholder updates
- Milestone reviews and demo sessions
- Escalation discussions as needed

### Touchpoints with Other Personas
- **Product Managers:** Provide requirements; approve priorities and roadmap
- **Project Managers:** Receive status updates; approve scope changes
- **Business Analyst:** Provide business context and validate requirements
- **Solution Architect:** Approve major architectural decisions
- **UX Designer:** Provide feedback on user experience and design

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile practices and ceremonies, remove impediments, and coach the team on continuous improvement. They serve as process champions and enablers for delivery teams.

### Responsibilities
- Facilitate agile ceremonies (sprint planning, daily standups, retrospectives, demos)
- Remove blockers and impediments for the team
- Coach team members on agile principles and practices
- Track and improve team velocity and process metrics
- Shield the team from external distractions

### Goals
- Enable the team to deliver consistently and predictably
- Foster a culture of continuous improvement
- Ensure agile practices are followed effectively

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members on process issues
- Retrospective facilitation and action item tracking

### Touchpoints with Other Personas
- **Developers:** Remove blockers; facilitate ceremonies; coach on agile practices
- **Project Managers:** Coordinate on delivery schedules; share process insights
- **Product Managers:** Ensure backlog readiness; facilitate prioritization discussions
- **QA:** Include testing activities in sprint planning; address quality impediments
- **Solution Architect:** Ensure architectural considerations are addressed in planning

---

## UX Designer

### Role Summary
UX Designers create user-centered designs for products, focusing on usability, accessibility, and user satisfaction. They translate user needs into intuitive interfaces and experiences.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers to define user flows
- Work with Developers to ensure design implementation accuracy
- Maintain design systems and style guides

### Goals
- Deliver intuitive, accessible user experiences
- Improve user satisfaction and engagement
- Ensure design consistency across the product

### Typical Communication
- Design reviews and critique sessions
- User research findings presentations
- Collaboration sessions with Developers and Product Managers

### Touchpoints with Other Personas
- **Product Managers:** Collaborate on user needs and feature definitions; validate design decisions
- **Developers:** Hand off designs; provide guidance during implementation; review UI accuracy
- **Stakeholders:** Present design concepts; gather feedback on user experience
- **Technical Writer:** Coordinate on in-product help and UI copy
- **Business Analyst:** Understand user requirements and business context

---

## Technical Writer

### Role Summary
Technical Writers create clear, accurate documentation for products, including user guides, API documentation, release notes, and onboarding materials. They make complex information accessible to diverse audiences.

### Responsibilities
- Write and maintain product documentation and user guides
- Create release notes and changelog entries
- Develop onboarding and training materials
- Collaborate with Developers and QA to ensure documentation accuracy
- Maintain documentation standards and style guides

### Goals
- Produce clear, accurate, and user-friendly documentation
- Reduce support burden through self-service documentation
- Ensure documentation stays current with product releases

### Typical Communication
- Documentation review sessions with subject matter experts
- Release coordination meetings for release notes
- Feedback collection from users and support teams

### Touchpoints with Other Personas
- **Developers:** Gather technical details; review documentation for accuracy
- **Product Managers:** Understand features and positioning; align messaging
- **QA:** Validate documentation accuracy; incorporate testing insights
- **UX Designer:** Coordinate on in-product copy and help content
- **Support Teams:** Gather feedback on documentation gaps

---

## Solution Architect

### Role Summary
Solution Architects define the technical vision and architecture for solutions. They ensure systems are scalable, maintainable, secure, and aligned with business requirements.

### Responsibilities
- Define and document system architecture and technical standards
- Evaluate technology choices and make recommendations
- Guide Developers on architectural patterns and best practices
- Review designs for scalability, security, and maintainability
- Collaborate with stakeholders on technical feasibility

### Goals
- Ensure systems are well-architected and future-proof
- Reduce technical debt and complexity
- Enable teams to build scalable, secure solutions

### Typical Communication
- Architecture review meetings
- Technical design document reviews
- Consultation sessions with project teams

### Touchpoints with Other Personas
- **Developers:** Provide architectural guidance; review designs; mentor on best practices
- **Project Managers:** Advise on technical risks and dependencies; support estimation
- **Product Managers:** Assess technical feasibility of features; advise on trade-offs
- **Stakeholders:** Present architectural decisions; obtain approval for major changes
- **Business Analyst:** Understand business requirements; ensure technical alignment

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and delivery teams. They gather, analyze, and document business requirements to ensure solutions meet business needs.

### Responsibilities
- Gather and document business requirements
- Analyze current processes and identify improvement opportunities
- Create user stories and acceptance criteria
- Facilitate requirements workshops and stakeholder interviews
- Validate that delivered solutions meet business requirements

### Goals
- Ensure clear understanding of business needs
- Translate business requirements into actionable specifications
- Improve alignment between business and technical teams

### Typical Communication
- Requirements workshops and stakeholder interviews
- Business process documentation reviews
- Collaboration sessions with Product Managers and Developers

### Touchpoints with Other Personas
- **Stakeholders:** Gather business requirements; validate solutions meet needs
- **Product Managers:** Provide analyzed requirements; support prioritization decisions
- **Project Managers:** Contribute to project planning; provide requirements estimates
- **Developers:** Clarify requirements; answer questions during implementation
- **UX Designer:** Share user research insights; validate user needs

---

## Role Interaction Matrix

The following matrix summarizes key interactions between roles across project phases:

| Phase | Primary Roles | Supporting Roles |
|-------|---------------|------------------|
| **Initiation** | PM, PdM, Stakeholders | Business Analyst, Solution Architect |
| **Planning** | PM, PdM, Scrum Master | Developers, QA, UX Designer, Solution Architect, Business Analyst |
| **Execution** | Developers, QA, Scrum Master | PM, PdM, UX Designer, Technical Writer, Solution Architect |
| **Release** | PM, Developers, QA | Technical Writer, Stakeholders |
| **Retrospective** | Scrum Master, PM, Developers | QA, PdM, all team members |

---

## How these personas are used in OctoAcme projects

- Use these persona definitions to frame scenarios and sample interactions in OctoAcme projects.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference this document during project initiation to identify required roles for your project.
- Use the Role Interaction Matrix above to understand handoffs and collaboration points between phases.

## Related Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Core principles and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — Starting a new project
- [Project Planning](octoacme-project-planning.md) — Planning and backlog management
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day delivery
- [Risks & Communication](octoacme-risks-and-communication.md) — Risk and stakeholder management
- [Release & Deployment](octoacme-release-and-deployment.md) — Release processes
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Learning and improving
- [Cross-Functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) — Collaboration best practices
- [Onboarding Guide](octoacme-onboarding-guide.md) — New team member onboarding

