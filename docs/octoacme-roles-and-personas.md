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

## QA / Testing

### Role Summary
QA Engineers validate that delivered features meet acceptance criteria and quality standards. They design test plans, execute manual and automated tests, and act as the last line of quality assurance before release.

### Responsibilities
- Author and maintain test plans, test cases, and acceptance checklists
- Execute functional, regression, and exploratory testing
- File, prioritize, and track defects through to resolution
- Partner with Developers on automated test coverage
- Sign off on release readiness from a quality perspective

### Goals
- Prevent defect escapes to production
- Increase confidence in each release through thorough test coverage
- Promote a quality-first mindset across the team

### Typical Communication
- Sprint review demos and sign-off confirmations
- Defect reports and test-result summaries
- Coordination with PM and Release Manager on release-readiness gates

### Interaction with Existing Roles
- Works with **Developers** to align on testability and co-author automated tests
- Works with **Product Managers** to clarify acceptance criteria and edge cases
- Works with **Project Managers** on quality status and release-readiness milestones
- Coordinates with **Release Manager** on deployment smoke tests and rollback triggers

---

## UX Designer

### Role Summary
UX Designers own the user experience of the product. They translate customer insights and product requirements into wireframes, prototypes, and design specs that guide development. They champion usability throughout the project lifecycle.

### Responsibilities
- Conduct user research, usability tests, and competitive analysis
- Produce wireframes, interactive prototypes, and detailed design specifications
- Maintain a consistent design system and component library
- Participate in sprint planning and backlog refinement to flag UX scope
- Review implemented features for design fidelity and usability compliance

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework caused by late-stage usability findings
- Bridge the gap between user needs and technical implementation

### Typical Communication
- Design reviews and prototype walkthroughs with Product and Engineering
- Usability test reports shared with Product Managers and stakeholders
- Design-spec handoffs to Developers via shared design tools (e.g., Figma)

### Interaction with Existing Roles
- Works with **Product Managers** to align design direction with product vision and success metrics
- Works with **Developers** to ensure faithful implementation and flag design deviations early
- Consults with **QA / Testing** on visual and accessibility acceptance criteria
- Shares user-research insights with **Project Managers** to inform scope and risk planning

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit, document, and clarify requirements, ensuring that the team builds the right solution for the right problem.

### Responsibilities
- Facilitate requirements workshops and stakeholder interviews
- Document business requirements, use cases, and process flows
- Translate business needs into actionable user stories and acceptance criteria
- Identify and document scope gaps, assumptions, and constraints
- Support change management and sign-off activities with stakeholders

### Goals
- Ensure requirements are complete, unambiguous, and traceable
- Reduce mid-sprint scope changes caused by misaligned expectations
- Improve communication efficiency between business and technical teams

### Typical Communication
- Requirements documentation and use-case diagrams shared with PM and PdM
- Scope-clarification sessions with stakeholders and development team
- Regular check-ins with Project Manager on requirement-driven risks

### Interaction with Existing Roles
- Works with **Product Managers** to refine problem statements, success metrics, and roadmap priorities
- Works with **Project Managers** to surface scope risks and resolve ambiguities before planning
- Works with **Developers** to provide detailed acceptance criteria and answer implementation questions
- Facilitates stakeholder alignment alongside **Project Managers** during initiation and planning phases

---

## Release Manager

### Role Summary
Release Managers plan and coordinate the deployment of software to production. They own release readiness, orchestrate the deployment process, and ensure rollback strategies are in place to minimize customer impact.

### Responsibilities
- Define and own the release calendar and go/no-go criteria
- Coordinate pre-release checks across QA, Development, and Operations
- Manage deployment steps, environment promotion, and configuration changes
- Maintain and test rollback plans for each release
- Communicate release status, timelines, and post-release health to stakeholders

### Goals
- Achieve reliable, low-risk releases with minimal customer disruption
- Reduce mean time to recovery (MTTR) when deployments encounter issues
- Build repeatable, auditable release processes

### Typical Communication
- Release readiness reports and go/no-go summaries for PM and stakeholders
- Deployment runbooks and rollback playbooks shared with DevOps and QA
- Post-release incident reports and retrospective inputs

### Interaction with Existing Roles
- Works with **Project Managers** to schedule releases against project milestones and communicate timelines
- Works with **QA / Testing** to confirm release-readiness gates and smoke-test results
- Works with **DevOps Engineers** to execute deployment pipelines and validate infrastructure readiness
- Coordinates with **Product Managers** on release notes and customer-facing communications
- Escalates blocking issues to **Project Managers** and relevant stakeholders

---

## Support / Customer Success

### Role Summary
Support and Customer Success professionals are the voice of the customer post-release. They capture feedback, triage reported issues, and advocate for customer needs inside the product organization.

### Responsibilities
- Triage, document, and escalate customer-reported bugs and feature requests
- Maintain a knowledge base of known issues and workarounds
- Track customer satisfaction metrics and surface trends to the product team
- Facilitate customer onboarding and adoption of new features
- Collaborate with Product Managers to prioritize customer-impacting fixes

### Goals
- Maximize customer satisfaction and product adoption
- Reduce time-to-resolution for customer-reported issues
- Provide the product team with a clear, continuous signal from real users

### Typical Communication
- Weekly support-health reports shared with Product and Project Managers
- Bug and feedback submissions directly to the project backlog
- Customer success calls and onboarding sessions coordinated with stakeholders

### Interaction with Existing Roles
- Works with **Product Managers** to advocate for customer-driven backlog priorities
- Works with **Project Managers** to ensure high-severity customer issues are tracked as project risks
- Provides **Developers** and **QA** with reproduction steps and supporting data for defects
- Coordinates release communications with **Release Manager** to prepare customers for upcoming changes

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, CI/CD pipelines, and tooling that enable rapid and reliable software delivery. They partner closely with development and operations teams to automate toil and improve system reliability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure using infrastructure-as-code (IaC) tooling
- Monitor system health, define alerting thresholds, and respond to incidents
- Enforce security, compliance, and access-control standards in the delivery pipeline
- Champion developer-experience improvements (local tooling, faster builds, better observability)

### Goals
- Minimize deployment lead time and increase deployment frequency
- Improve system availability and reduce mean time to recovery (MTTR)
- Automate repetitive operational work to free engineers for higher-value tasks

### Typical Communication
- Infrastructure and pipeline status updates to Project and Release Managers
- Incident post-mortems and action items shared with the broader team
- Collaboration with Developers via pull requests for pipeline and IaC changes

### Interaction with Existing Roles
- Works with **Release Manager** to design and execute deployment runbooks and rollback procedures
- Works with **Developers** to improve build/test pipelines and provide environment parity
- Works with **Project Managers** to surface infrastructure risks and capacity constraints
- Coordinates with **QA / Testing** to integrate automated test suites into CI/CD pipelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

