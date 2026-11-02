# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A persona describes a set of responsibilities, not necessarily a separate person; teams may combine or adapt roles to suit project size and context while ensuring each responsibility has a clear owner.

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

## Engineering or Technical Leads

### Role Summary
Engineering or Technical Leads guide technical direction and help the team deliver a coherent, maintainable solution. Depending on the team, this may be a dedicated lead or a responsibility shared by senior Developers.

### Responsibilities
- Guide technical design and document significant decisions
- Help Developers estimate work and identify technical dependencies
- Surface technical risks, constraints, and mitigation options
- Promote engineering standards, review practices, and sustainable architecture

### Goals
- Keep implementation aligned with product needs and technical standards
- Make technical trade-offs visible early
- Reduce delivery risk from unclear design or dependencies

### Typical Communication
- Design discussions and architecture decision records
- Technical estimates and dependency reviews during planning
- Updates on technical milestones, risks, and trade-offs

### Collaboration with Existing Roles
- Partners with Developers on design, implementation, and reviews; the lead guides rather than replacing developer ownership of their work.
- Advises the Product Manager on feasibility, options, and technical trade-offs so prioritization reflects impact and effort.
- Shares estimates, dependencies, and technical risks with the Project Manager for schedule and risk planning.

---

## UX Designers or User Researchers

### Role Summary
UX Designers and User Researchers build understanding of user needs and translate it into usable, accessible experiences. One person or team may cover both research and design responsibilities.

### Responsibilities
- Plan and conduct user research appropriate to the project
- Create and validate user flows, prototypes, and interaction designs
- Identify usability and accessibility needs and recommend improvements
- Share evidence and design intent so implementation can be evaluated against user needs

### Goals
- Ensure solutions address real user needs
- Make experiences understandable, usable, and inclusive
- Reduce rework by validating assumptions early

### Typical Communication
- Research findings and user journey documentation
- Design reviews, prototypes, and usability test results
- Collaboration with product and engineering during refinement and delivery

### Collaboration with Existing Roles
- Works with the Product Manager to connect user evidence to problem statements, priorities, and acceptance criteria.
- Collaborates with Developers and the Engineering or Technical Lead on feasibility and implementation details while preserving the intent of validated designs.
- Shares research activities, design decisions, and validation milestones with the Project Manager so they can be reflected in the plan and dependencies.

---

## QA or Test Leads

### Role Summary
QA or Test Leads coordinate quality strategy and provide visibility into whether the product meets agreed requirements and is ready for release. Testing may be a dedicated role or shared across the team.

### Responsibilities
- Define an appropriate test strategy and quality criteria with the team
- Coordinate test coverage across functional, integration, and other relevant risks
- Track defects, communicate their impact, and verify resolutions
- Report quality risks and readiness evidence before release

### Goals
- Detect important issues early and reduce preventable defects
- Make quality status and release risks transparent
- Ensure verification aligns with product expectations

### Typical Communication
- Test plans, quality reports, and defect tracking
- Test results and readiness reviews
- Ongoing coordination with Developers and release stakeholders

### Collaboration with Existing Roles
- Works with Developers on testability, coverage, defect investigation, and prevention; quality remains a shared team responsibility.
- Aligns with the Product Manager on acceptance criteria and the significance of defects against user and business outcomes.
- Provides the Project Manager with test progress, unresolved risks, and readiness information to support delivery and release coordination.

---

## Executive Sponsors or Business Owners

### Role Summary
Executive Sponsors or Business Owners connect a project to organizational goals and provide direction, authority, or resources for significant decisions. Their level of involvement should match the project's impact and governance needs.

### Responsibilities
- Clarify strategic outcomes and constraints for the project
- Help secure sponsorship, resources, or cross-team alignment
- Make or escalate material scope, priority, and investment decisions within their authority
- Resolve escalations that the delivery team cannot settle

### Goals
- Realize the intended business outcomes
- Ensure the project has appropriate direction and support
- Make timely decisions when delivery is blocked by organizational constraints

### Typical Communication
- Sponsor checkpoints and decision briefings
- Escalations and documented scope or investment decisions
- Outcome reviews with product and project leadership

### Collaboration with Existing Roles
- Aligns with the Product Manager on strategic outcomes and priorities without taking over day-to-day backlog management.
- Works with the Project Manager on progress, constraints, resource needs, and decisions requiring sponsorship.
- Relies on Developers and technical leads for clear explanations of technical options and impacts when making business-level decisions.

---

## Release or Operations Owners

### Role Summary
Release or Operations Owners coordinate the transition of a change into a supported, observable production environment. This may be a dedicated operations role or a responsibility shared with the delivery team.

### Responsibilities
- Coordinate deployment planning and operational readiness
- Confirm monitoring, support, rollback, and handoff plans are in place
- Surface operational constraints and dependencies before release
- Track release issues and coordinate response with the appropriate owners

### Goals
- Make releases predictable and supportable
- Reduce operational risk and disruption to users
- Ensure teams can detect and respond to issues after launch

### Typical Communication
- Release checklists and readiness reviews
- Deployment schedules, runbooks, and operational handoff notes
- Monitoring and incident updates with delivery and stakeholder teams

### Collaboration with Existing Roles
- Coordinates with Developers and the Engineering or Technical Lead on deployment requirements, observability, and rollback options.
- Works with QA or Test Leads to confirm verification and release criteria are met.
- Aligns with the Product Manager on launch expectations and with the Project Manager on release dependencies, schedule, and communications.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Assign or combine persona responsibilities according to project context; make ownership and handoffs explicit even when one person covers multiple roles.
