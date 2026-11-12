# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Role Ownership and Shared Responsibilities

A project should make role ownership explicit. In smaller teams, one person may hold multiple responsibilities, but each function must still have a named accountable owner for decisions, quality, communication, or delivery outcomes.

Recommended practice:
- Document who is accountable for each major area: product decisions, delivery coordination, quality, user experience, and operational readiness.
- Keep one primary owner for each key decision or artifact to avoid duplicated work or unclear escalation.
- When responsibilities are shared, define the handoff points, review checkpoints, and escalation path clearly.
- Treat role assignments as team-specific and update them at kickoff or when staffing changes.

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

## Executive Sponsor

### Role Summary
The Executive Sponsor sets strategic direction, secures organizational support and resources, and helps resolve decisions that exceed the authority of the delivery team.

### Responsibilities
- Confirm business priorities and strategic fit
- Sponsor resource allocation, budget, and decision support
- Escalate cross-functional decisions, risks, or constraints that require leadership intervention
- Align project outcomes with broader organizational goals and commitments

### Goals
- Ensure the initiative remains aligned with business priorities
- Remove blockers that require executive authority or sponsorship
- Support a healthy balance between speed, risk, and stakeholder expectations

### Typical Communication
- Strategy reviews and milestone briefings
- Escalation updates during major risks, changes, or governance decisions
- Executive summaries of value, risks, and dependencies

### Collaboration with Other Roles
- Works with the Project Manager on scope, timeline, and escalations
- Partners with the Product Manager on outcomes, trade-offs, and strategic priorities
- Provides support to the delivery team by removing organizational barriers and confirming decision authority

---

## Business Analyst

### Role Summary
The Business Analyst translates stakeholder needs into clear requirements, accurate acceptance criteria, and traceable delivery outcomes.

### Responsibilities
- Elicit and document business, stakeholder, and user needs
- Clarify requirements, assumptions, and decision points
- Help define acceptance criteria and ensure they are testable
- Trace requirements to backlog items, work, and outcomes
- Support change impact analysis and prioritization discussions

### Goals
- Reduce ambiguity and rework in requirements
- Improve alignment between business needs and delivery
- Provide clarity for planning, QA, and stakeholder review

### Typical Communication
- Requirements workshops and stakeholder interviews
- Backlog refinement and acceptance criteria reviews
- Cross-functional alignment on scope, dependencies, and decisions

### Collaboration with Other Roles
- Works with the Product Manager to validate goals, priorities, and trade-offs
- Supports the Project Manager and delivery team by clarifying scope and resolving requirements questions
- Coordinates with QA/Test Lead and stakeholders on readiness, validation, and sign-off

---

## UX/UI Designer or User Researcher

### Role Summary
This role represents user needs through research, interaction design, and usability feedback so the product is useful, intuitive, and feasible to deliver.

### Responsibilities
- Conduct user research and synthesize insights
- Shape user journeys, workflows, and interaction patterns
- Create or refine visual design, interface patterns, and design system guidance
- Gather usability feedback and identify friction points
- Partner with engineers and QA to make design decisions testable and actionable

### Goals
- Improve customer experience and satisfaction
- Reduce misunderstandings between user needs and implementation
- Build products that are understandable, accessible, and easy to use

### Typical Communication
- Design reviews and user feedback sessions
- Product discovery and research synthesis discussions
- Collaboration with engineering and QA on interaction and usability validation

### Collaboration with Other Roles
- Works with the Product Manager to ensure the experience aligns with user value and product outcomes
- Partners with engineers and QA to confirm feasibility, accessibility, and testability
- Supports the Project Manager by clarifying dependencies, review needs, and design-related risks

---

## QA/Test Lead

### Role Summary
The QA/Test Lead defines the quality strategy, coordinates validation work, and provides evidence that the solution is ready for release.

### Responsibilities
- Define the testing approach, coverage strategy, and release readiness criteria
- Coordinate test planning, execution, defect tracking, and validation evidence
- Work with engineering teams to identify risk areas and improve coverage
- Support root-cause analysis for defects and regressions
- Provide recommendation on release readiness and quality risk

### Goals
- Build confidence in product quality and reliability
- Reduce the risk of production defects and regressions
- Provide clear evidence for delivery and release decisions

### Typical Communication
- Test planning and defect triage sessions
- Release readiness reviews and risk discussions
- Cross-functional quality checkpoints with PM, PdM, and engineering

### Collaboration with Other Roles
- Works closely with developers on test design, automation, and coverage
- Partners with the Product Manager and Project Manager on quality trade-offs, release risk, and communication
- Supports stakeholder and operations reviews with evidence of readiness and known issues

---

## Operations / Release Owner

### Role Summary
The Operations or Release Owner coordinates deployment readiness, monitoring, support, and handoff so releases are reliable and sustainable in production.

### Responsibilities
- Prepare release plans, deployment windows, and rollback or contingency steps
- Confirm operational readiness, monitoring, and alerting requirements
- Support production validation, release communications, and post-release follow-up
- Coordinate with support and stakeholders on incident response and known issue handling
- Track deployment health and operational impact after release

### Goals
- Reduce release risk and minimize disruption to customers or internal users
- Improve operational readiness and post-deployment confidence
- Ensure a clear handoff from project delivery to ongoing support

### Typical Communication
- Release readiness checks and deployment reviews
- Post-release operational check-ins and incident updates
- Coordination with Project Manager and support teams on communication and mitigation

### Collaboration with Other Roles
- Partners with engineering and QA on deployment criteria, smoke tests, and rollback planning
- Coordinates with the Project Manager on schedule, approvals, and stakeholder communications
- Works with the Product Manager to confirm product-impact communication and release notes

---

## Stakeholder Representative / Subject-Matter Expert

### Role Summary
The Stakeholder Representative or Subject-Matter Expert provides domain knowledge, validates assumptions, and helps ensure that project decisions reflect real operational or business needs.

### Responsibilities
- Share domain expertise and contextual knowledge about the business or process
- Validate requirements, assumptions, and deliverable quality against operational reality
- Communicate impacts to affected teams or customer groups
- Provide feedback during reviews, pilots, and milestone checks
- Support prioritization and trade-off decisions with practical context

### Goals
- Ensure the solution reflects real user and business needs
- Reduce costly rework from incorrect assumptions
- Improve acceptance and adoption of project outcomes

### Typical Communication
- Review sessions, workshops, and decision checkpoints
- Feedback on prototypes, requirements, and release readiness
- Informal and formal stakeholder updates as needed

### Collaboration with Other Roles
- Engages with the Product Manager on needs, priorities, and value trade-offs
- Works with the Project Manager on review cadence, decisions, and stakeholder management
- Provides context to engineering and QA to ensure the solution matches operational expectations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When a single person covers more than one responsibility, make the primary accountable owner explicit in the project plan, backlog, or team charter.
- Keep these role definitions lightweight and adaptable; project teams should adjust them to fit the size, complexity, and culture of the initiative.


