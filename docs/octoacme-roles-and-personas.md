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

## Quality Assurance (QA) / Test Engineers

### Role Summary
QA / Test Engineers plan and coordinate validation so that delivered work meets its acceptance criteria and quality expectations. They provide an independent view of coverage and product readiness while collaborating with Developers throughout delivery.

### Responsibilities
- Define test approaches and coverage with Developers and Product Managers
- Validate features against acceptance criteria and report reproducible defects
- Track quality risks, gaps in coverage, and test results
- Help teams make testing part of development rather than a final handoff

### Goals
- Detect quality issues early and reduce preventable regressions
- Make validation status and remaining quality risks visible
- Ensure important user workflows are covered

### Typical Communication
- Test plans, test results, and defect reports
- Acceptance-criteria reviews with Product Managers
- Pairing and quality-risk discussions with Developers

### Interactions with Existing Roles
- **Developers:** agree on testability and coverage, coordinate defect triage, and verify fixes.
- **Product Managers:** clarify acceptance criteria and user-critical scenarios; report whether validation supports the intended outcomes.
- **Project Managers:** surface testing dependencies, quality risks, and readiness status for plans and status updates.

### Decision Boundaries
QA / Test Engineers recommend whether quality evidence is sufficient and identify unresolved risks. They do not change product priorities or acceptance criteria unilaterally; Product Managers own those decisions with relevant stakeholders.

---

## UX Designers / User Researchers

### Role Summary
UX Designers / User Researchers investigate user needs and shape accessible, usable experiences. They connect product intent with design decisions and help teams validate that implementation works for its intended users.

### Responsibilities
- Plan and conduct user research or usability evaluation appropriate to the work
- Translate findings into experience flows, designs, and accessibility considerations
- Collaborate on requirements and acceptance criteria for user-facing behavior
- Review implemented experiences and communicate usability issues and recommendations

### Goals
- Ensure product decisions are grounded in user needs
- Improve usability, accessibility, and consistency
- Identify experience risks before they become costly to address

### Typical Communication
- Research findings and design artifacts
- Design reviews and usability feedback
- Collaboration with Product Managers and Developers during refinement and implementation

### Interactions with Existing Roles
- **Product Managers:** share user evidence and shape requirements and priorities; Product Managers make product-priority decisions.
- **Developers:** clarify design intent, discuss technical trade-offs, and review implementation together.
- **Project Managers:** identify research, design, and review dependencies that affect milestones and communicate emerging risks.

### Decision Boundaries
UX Designers / User Researchers provide evidence and experience recommendations. Product Managers remain accountable for product scope and prioritization, while Developers determine implementation details in collaboration with the team.

---

## DevOps / Release Engineers

### Role Summary
DevOps / Release Engineers enable reliable build, deployment, and operation of software. They help teams plan for operational readiness and make delivery pipelines and service health visible.

### Responsibilities
- Maintain or improve build, deployment, and release automation
- Advise on observability, reliability, and operational readiness requirements
- Coordinate deployment dependencies and support release execution
- Surface infrastructure, environment, and operational risks

### Goals
- Make releases predictable and repeatable
- Improve service reliability and visibility after deployment
- Reduce avoidable deployment and operational issues

### Typical Communication
- Release plans, deployment status, and readiness checks
- Operational dashboards, alerts, and incident follow-ups
- Coordination with Developers and Project Managers on dependencies and timing

### Interactions with Existing Roles
- **Developers:** collaborate on deployment automation, service instrumentation, and reliability fixes.
- **Project Managers:** identify release dependencies and risks, provide readiness information, and coordinate timing against the project plan.
- **Product Managers:** communicate operational constraints that affect scope or release options and provide post-release service signals relevant to product outcomes.

### Decision Boundaries
DevOps / Release Engineers advise on operational readiness and execute or support releases under the team's release process. Project Managers coordinate project timing, and Product Managers decide product scope and priority; unresolved readiness risks should be made visible to the designated decision makers.

---

## Business Sponsors / Decision Makers

### Role Summary
Business Sponsors / Decision Makers connect project work to organizational strategy, provide sponsorship, and make or escalate decisions that require business-level authority.

### Responsibilities
- Communicate strategic objectives and expected business outcomes
- Help secure organizational support and resolve cross-team impediments
- Make or escalate business trade-offs outside the team's delegated authority
- Review outcome and progress information and respond to material changes

### Goals
- Ensure project outcomes support organizational priorities
- Enable timely decisions and remove barriers to delivery
- Maintain alignment between investment and expected value

### Typical Communication
- Project kickoff and milestone reviews
- Escalations, decision records, and material scope or risk updates
- Outcome reviews with Product Managers and Project Managers

### Interactions with Existing Roles
- **Product Managers:** align on strategic outcomes and resolve priority or value trade-offs; Product Managers continue to own the product roadmap and backlog.
- **Project Managers:** receive progress, risk, and dependency updates and help resolve escalations requiring sponsorship or authority.
- **Developers:** generally engage through the Product Manager or Project Manager, with direct discussion when a technical constraint informs a business decision.

### Decision Boundaries
Sponsors make decisions within their delegated business authority and resolve escalations beyond the team's remit. They do not replace the Product Manager's day-to-day product prioritization or the Project Manager's delivery coordination.

---

## Assigning Roles

Roles may be combined or shared on smaller projects, but each responsibility and decision should have a clearly identified owner. Teams should make handoffs, escalation paths, and approval boundaries explicit during project planning.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

