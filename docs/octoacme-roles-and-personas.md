# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Depending on project size and needs, one person may hold multiple roles, and not every project needs a separate person for each role. Teams should make ownership explicit for the responsibilities that apply to their work.

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

## UX / Product Designers and Researchers

### Role Summary
UX and product design roles research user needs and shape usable, accessible product experiences.

### Responsibilities
- Plan and conduct user research, and synthesize findings
- Create user flows, prototypes, and interaction designs
- Incorporate accessibility and usability considerations
- Validate designs with users and communicate findings

### Goals
- Ensure solutions address user needs and are understandable and accessible
- Reduce usability risks before implementation

### Typical Communication
- Research findings and design reviews
- Design specifications and prototypes
- Usability feedback and acceptance considerations

### Interactions with Existing Roles
- Partner with the Product Manager to connect user evidence to product goals, scope, and prioritization
- Collaborate with Developers and the Tech Lead on feasibility and implementation trade-offs
- Work with QA / Test Leads to include usability and accessibility in validation
- Share research insights with the Project Manager to inform dependencies, sequencing, and stakeholder updates

---

## Tech Leads / Solution Architects

### Role Summary
Tech Leads and Solution Architects guide technical design and help ensure that the solution fits the product needs and the broader system.

### Responsibilities
- Guide architecture, technical design, and integration decisions
- Identify technical dependencies, constraints, and risks
- Facilitate technical alignment and document consequential decisions
- Support maintainable implementation and appropriate quality practices

### Goals
- Deliver a coherent, reliable, and maintainable technical solution
- Surface technical risks and trade-offs early enough to inform planning

### Typical Communication
- Technical design documents and architecture reviews
- Engineering planning and dependency discussions
- Risk and decision updates to project stakeholders

### Interactions with Existing Roles
- Align with the Product Manager on technical options and scope trade-offs
- Coordinate with the Project Manager on sequencing, estimates, dependencies, and risks
- Guide Developers through design choices and implementation integration
- Work with QA / Test Leads and Security / Privacy Leads on testability, controls, and technical risk mitigation

---

## QA / Test Leads

### Role Summary
QA and Test Leads coordinate the test approach and help the team verify that the product meets its acceptance criteria and quality expectations.

### Responsibilities
- Define test strategy and coordinate relevant test coverage
- Clarify testable outcomes and edge cases with the team
- Support verification against acceptance criteria and the Definition of Done
- Communicate quality risks, gaps, and test results

### Goals
- Find important defects and quality risks before release
- Make verification expectations clear throughout delivery

### Typical Communication
- Test plans, test results, and defect reports
- Acceptance-criteria reviews and QA status updates
- Release-readiness discussions

### Interactions with Existing Roles
- Collaborate with Developers on testability, test coverage, and defect resolution
- Work with the Product Manager to clarify expected behavior and acceptance criteria
- Coordinate with the Project Manager on test dependencies, status, and escalations
- Partner with the Release / Operations Lead on release verification and unresolved quality risks

---

## Security / Privacy Leads

### Role Summary
Security and Privacy Leads help identify and address security, privacy, and compliance requirements and risks relevant to the project.

### Responsibilities
- Identify applicable security and privacy requirements and review needs
- Advise on risk assessment and appropriate mitigations
- Coordinate security and privacy reviews and track findings to resolution or explicit acceptance
- Help ensure relevant controls and incident paths are understood

### Goals
- Address security and privacy risks early and throughout delivery
- Make risk ownership and required release considerations explicit

### Typical Communication
- Security and privacy reviews and findings
- Risk register updates and mitigation plans
- Guidance for design, implementation, and release decisions

### Interactions with Existing Roles
- Work with the Tech Lead and Developers to incorporate controls into design and implementation
- Coordinate with QA / Test Leads to validate relevant security and privacy requirements
- Help the Product Manager understand user, regulatory, and product implications
- Partner with the Project Manager to track risks, owners, and escalations

---

## Data / Analytics Leads

### Role Summary
Data and Analytics Leads help define how the team will collect and interpret evidence that the project achieved its intended outcomes.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Define event, data-quality, and reporting needs with relevant partners
- Review metric definitions and identify limitations in interpreting results
- Help make outcome data available to decision-makers

### Goals
- Provide trustworthy evidence of product and project outcomes
- Enable informed decisions after launch and during iteration

### Typical Communication
- Metric definitions and instrumentation plans
- Data-quality checks and dashboards
- Outcome reports and analysis with product stakeholders

### Interactions with Existing Roles
- Partner with the Product Manager to define success measures and interpret results
- Coordinate with Developers on instrumentation and data collection
- Work with QA / Test Leads to validate event behavior and data quality
- Share measurement dependencies and reporting needs with the Project Manager for planning

---

## Release / Operations (SRE) Leads

### Role Summary
Release and Operations Leads coordinate operational readiness and help deliver changes safely with appropriate monitoring and recovery plans.

### Responsibilities
- Coordinate deployment readiness and operational dependencies
- Ensure monitoring, alerting, and post-deployment verification needs are addressed
- Prepare rollback or mitigation plans with the delivery team
- Communicate operational risks and readiness status

### Goals
- Make releases observable and recoverable
- Reduce avoidable deployment risk and improve service reliability

### Typical Communication
- Release plans and readiness reviews
- Deployment, monitoring, and rollback procedures
- Post-deployment verification and incident updates

### Interactions with Existing Roles
- Coordinate with Developers and QA / Test Leads on deployment needs and release verification
- Work with the Project Manager on release timing, dependencies, and status communication
- Consult the Product Manager on customer impact and release scope
- Coordinate with Customer Support / Enablement Leads on launch information and incident paths

---

## Customer Support / Enablement Leads

### Role Summary
Customer Support and Enablement Leads prepare customer-facing teams to support a change and bring customer feedback into product decisions.

### Responsibilities
- Prepare support guidance, training, and customer-facing materials as needed
- Communicate known issues, expected behavior, and escalation paths to support teams
- Surface customer questions and feedback to the delivery team
- Help assess customer readiness and support impact

### Goals
- Enable consistent, informed customer support during and after a release
- Ensure customer feedback and support needs inform future improvements

### Typical Communication
- Support briefs, FAQs, and enablement materials
- Customer feedback and recurring issue summaries
- Launch coordination and incident communications

### Interactions with Existing Roles
- Partner with the Product Manager on customer impact, product messaging, and feedback-driven priorities
- Coordinate with the Project Manager on stakeholder communications and readiness dependencies
- Work with the Release / Operations Lead on launch timing, known issues, and incident paths
- Share customer-reported issues with Developers and QA / Test Leads to support investigation and validation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Treat roles as adaptable responsibilities: teams should assign clear ownership while combining roles when appropriate for their size and context.
