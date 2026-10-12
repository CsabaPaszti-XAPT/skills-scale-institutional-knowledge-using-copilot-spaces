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

## Delivery Leads

### Role Summary
Delivery Leads coordinate day-to-day execution and team handoffs. They work with Project Managers (PMs) on delivery progress while PMs retain ownership of project plans, risks, and stakeholder reporting.

### Responsibilities
- Coordinate work sequencing and dependencies with developers and QA/testing
- Keep the project board current and identify blockers during daily standups
- Work with Product Managers (PdMs) to clarify priorities and acceptance criteria
- Escalate unresolved blockers and schedule risks to the PM
- Coordinate handoffs to the QA Lead and Release Coordinator

### Goals
- Maintain a predictable flow of work from planning through release
- Reduce blocked work and missed handoffs
- Keep delivery commitments visible and realistic

### Typical Communication
- Daily standups with developers and QA/testing
- Weekly delivery syncs with PM and PdM
- Project board updates and blocker escalations

---

## QA Leads

### Role Summary
QA Leads own the test strategy and coordinate quality assessment across the project lifecycle. They provide acceptance-readiness evidence to PMs, PdMs, and the Release Coordinator.

### Responsibilities
- Define test coverage and quality checks with developers and QA/testing
- Clarify testable acceptance criteria with the PdM
- Coordinate automated testing, manual QA, and pre-release smoke tests
- Triage defects with developers and QA/testing, involving the PdM in prioritization
- Report quality risks to the PM and unresolved defects to the Release Coordinator

### Goals
- Detect defects early and prevent regressions
- Provide clear evidence that acceptance criteria and quality standards are met
- Make remaining quality risks visible before release decisions

### Typical Communication
- Test plans and results shared with developers and QA/testing
- Defect triage sessions with developers and PdM
- Readiness summaries for PM and Release Coordinator

---

## Stakeholder Liaisons

### Role Summary
Stakeholder Liaisons consolidate stakeholder inputs, updates, and approval requests. They support PM-led project communication and PdM-led product decisions without taking over those responsibilities.

### Responsibilities
- Identify stakeholder groups, including support, and their communication needs
- Gather feedback and route scope or priority requests to the PM and PdM
- Translate delivery and quality updates from developers and QA/testing into stakeholder briefings
- Track decisions and approval requests, including owners and due dates
- Escalate conflicting expectations or delayed approvals to the PM and PdM

### Goals
- Maintain shared expectations across the team and stakeholders
- Ensure feedback reaches the right decision-makers
- Reduce communication gaps and delays in approvals

### Typical Communication
- Weekly or milestone-based stakeholder briefings aligned with PM status reports
- Feedback summaries and decision logs shared with PM and PdM
- Release communications coordinated with the Release Coordinator and support

---

## Release Coordinators

### Role Summary
Release Coordinators manage release readiness, deployment coordination, and post-release verification. They bring together PMs, PdMs, developers, QA/testing, and support to ensure release handoffs are complete.

### Responsibilities
- Maintain the release checklist and coordinate deployment windows with PM and developers
- Confirm acceptance readiness with PdM and QA Lead, including passing CI and security scans
- Ensure developers document rollback or mitigation plans and prepare smoke tests with QA/testing
- Coordinate release notes and announcements with the Stakeholder Liaison, stakeholders, and support
- Track post-deployment verification with developers and QA/testing, escalating failures to the PM and on-call team
- Hand over known issues and follow-up actions to support and the delivery team

### Goals
- Make release readiness and outstanding risks explicit
- Reduce deployment disruption and incomplete support handoffs
- Ensure releases are verified and communicated promptly

### Typical Communication
- Release-readiness reviews with PM, PdM, developers, and QA Lead
- Deployment checklist updates and coordination with developers and support
- Post-release verification summaries and incident notifications when needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
