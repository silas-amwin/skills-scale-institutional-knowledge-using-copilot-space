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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (proposed)

Below are recommended additional personas to improve clarity and handoffs across delivery, releases, operations, design, and customer adoption. Each entry shows responsibilities and how the role typically interacts with existing roles.

### Delivery Lead
- Role summary: Coordinates day-to-day cross-team delivery and removes impediments to meet milestone commitments.
- Responsibilities:
  - Track milestones and dependencies across teams.
  - Maintain release/cutover checklists and run pre-release readiness reviews.
  - Facilitate cross-team dependency resolution and scheduling.
- Interactions:
  - Works closely with Project Managers (PM) and Product Managers (PdM) to align timelines and priorities.
  - Coordinates with Developers and QA to ensure items meet the Definition of Done.
  - Escalates schedule or resource risks to the Project Manager as needed.

### Technical Program Manager (TPM)
- Role summary: Owns technical planning and sequencing for cross-team initiatives with significant technical dependencies.
- Responsibilities:
  - Translate product goals into technical workstreams and milestones.
  - Track technical dependencies, interfaces, and design trade-offs.
  - Coordinate design reviews and technical risk mitigations.
- Interactions:
  - Partners with Engineering Managers and Developers for estimates and design.
  - Keeps PdM informed of technical constraints and impacts to timelines.
  - Works with SRE/Observability to ensure operability and deployment requirements are met.

### Release Engineer / Build & Release Owner
- Role summary: Owns release pipelines, automation, and the mechanical aspects of shipping code.
- Responsibilities:
  - Maintain and improve CI/CD pipelines and release automation.
  - Coordinate staging, canary, and production cutovers and rollback procedures.
  - Ensure release readiness criteria (tests, artifacts, runbooks) are met.
- Interactions:
  - Works with Developers and QA to validate build artifacts and deployment steps.
  - Coordinates with SRE for production rollout and post-deploy verification.
  - Ensures release tasks are tracked on the project board and communicated to PM/PdM.

### Observability / SRE Representative
- Role summary: Ensures the system is observable and operable before and after release.
- Responsibilities:
  - Define monitoring, alerting, and runbook requirements.
  - Validate runbooks and on-call readiness for new functionality.
  - Support post-deploy verification and incident response.
- Interactions:
  - Collaborates with Developers, Release Engineer, and PM to prioritize reliability work.
  - Provides acceptance criteria for operability and assists in production troubleshooting.

### UX Researcher / Designer Representative
- Role summary: Represents user research and design needs through the delivery lifecycle.
- Responsibilities:
  - Own user research plans and synthesize findings into actionable requirements.
  - Validate UI/UX during prototypes, demos, and before release.
  - Provide design artifacts and usability acceptance criteria.
- Interactions:
  - Works with PdM to shape user-facing requirements and success metrics.
  - Partners with Developers and QA to ensure UI changes meet accessibility and usability standards.

### Customer Success Liaison
- Role summary: Bridges product delivery and customer-facing teams to ensure smooth adoption and support readiness.
- Responsibilities:
  - Capture customer feedback and adoption signals to inform prioritization.
  - Coordinate release communications, training materials, and onboarding needs.
  - Flag support risks and help prioritize documentation/training work.
- Interactions:
  - Works with PdM and PM on rollout plans and communications.
  - Ensures support and docs teams have the information needed for post-release support.

---

## How adding these personas helps
- Clarifies ownership for cross-cutting activities (releases, reliability, research, adoption).
- Reduces duplication and missed tasks by defining explicit role responsibilities.
- Speeds cross-team coordination and escalation paths.
- Improves onboarding by making expectations explicit.

(End of proposed content — this will be appended/merged into the existing roles doc under a new "Additional Personas" section.)
