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

## Technical Lead (new)

### Role Summary
The Technical Lead drives technical direction and ensures the solution meets architectural, scalability, and maintainability goals.

### Responsibilities
- Own system and solution architecture decisions for the project
- Author and review technical design documents
- Mentor engineers and guide code-quality standards
- Make trade-off calls during implementation and scope changes
- Identify technical risks and mitigation strategies

### Interactions
- Works with Developers on designs, estimates, and implementation
- Partners with Product Manager and Project Manager on feasibility and technical risk
- Escalates platform or infrastructure needs to Platform teams or PM as needed

---

## Delivery Lead (new)

### Role Summary
The Delivery Lead focuses on execution cadence and removing impediments to keep the delivery on track.

### Responsibilities
- Coordinate day-to-day delivery activities and sprint commitments
- Track cross-team dependencies and schedule alignment
- Facilitate removal of impediments and unblock teams
- Keep release timeline and status up-to-date

### Interactions
- Pairs with Project Manager on schedules and risk mitigation
- Syncs with Product Manager on scope changes
- Acts as primary escalation contact at the team level for delivery issues

---

## Release Manager (new)

### Role Summary
The Release Manager owns the release process and ensures safe, observable rollouts.

### Responsibilities
- Define release windows and coordinate release plans
- Verify release readiness (CI status, smoke tests, runbooks)
- Coordinate staging and production rollouts and post-deploy verifications
- Own rollback plans and communicate contingency steps

### Interactions
- Coordinates with Developers, QA, Platform/DevOps, and PM
- Communicates release status to Stakeholders and Support
- Works with Observability Owner and Security Lead to ensure monitoring and controls are in place

---

## Security Lead (new)

### Role Summary
The Security Lead ensures features and releases meet security requirements and responds to security-related incidents.

### Responsibilities
- Review security implications and perform threat modeling for features
- Ensure required scans, dependencies, and controls are applied
- Lead or coordinate security incident triage when needed
- Document security-related mitigations in the risk register

### Interactions
- Advises Developers and Product Manager during planning and design
- Escalates issues to Security on-call and coordinates follow-up
- Works with Release Manager on release gating related to security fixes

---

## Observability / Monitoring Owner (new)

### Role Summary
The Observability Owner ensures the project has the telemetry, dashboards, and alerts required to operate and measure success.

### Responsibilities
- Define key metrics and alerting thresholds for the project
- Ensure logs, metrics, and traces are instrumented and dashboards built
- Own post-deploy monitoring and alert-response playbooks
- Work with SRE/on-call engineers to tune alerts and runbooks

### Interactions
- Works with Developers to implement telemetry and instrumentation
- Partners with Product Manager and Data Analyst to define success metrics
- Coordinates with Release Manager to ensure monitoring is validated pre- and post-deploy

---

## Data Analyst (new)

### Role Summary
The Data Analyst defines instrumentation and analyzes usage and impact to support evidence-based decisions.

### Responsibilities
- Specify instrumentation needs and metrics to track feature impact
- Create dashboards and reports for stakeholders
- Analyze experiments and product metrics, provide recommendations
- Partner on A/B testing and interpretation of results

### Interactions
- Partners with Product Manager on success metrics and measurement plans
- Works with Developers to ensure proper instrumentation is added
- Shares findings with Stakeholders and the delivery team to guide prioritization

---

## UX Researcher (new)

### Role Summary
The UX Researcher validates user assumptions and guides product design using qualitative and quantitative user research.

### Responsibilities
- Plan and conduct user interviews, usability tests, and research studies
- Synthesize research findings and present user insights
- Recommend design changes based on evidence and user needs
- Collaborate on acceptance criteria that reflect user validation

### Interactions
- Collaborates with Product Manager on research goals and scope
- Works with Designers and Developers to implement validated changes
- Presents findings to Stakeholders to influence decisions

---

## Customer Success / Support Representative (new)

### Role Summary
The Customer Success / Support Representative brings customer feedback into planning and helps manage communications around releases.

### Responsibilities
- Surface recurring customer issues and feedback into backlog
- Validate acceptance criteria against real-world usage and support cases
- Assist in release communications and runbooks for support teams
- Help prioritize bug fixes or usability issues based on customer impact

### Interactions
- Feeds issues into backlog and prioritization discussions with Product Manager
- Coordinates with Release Manager and PM for release communications
- Works with Data Analyst to quantify customer impact

---

## Change Manager (new; for larger initiatives)

### Role Summary
The Change Manager designs adoption and communication plans to ensure smooth organizational transitions.

### Responsibilities
- Identify impacted teams and stakeholders for larger initiatives
- Develop communication, training, and rollout plans to support adoption
- Track adoption metrics and capture feedback for continuous improvement

### Interactions
- Coordinates with PM, Product, and Stakeholders to plan adoption activities
- Works with Customer Success and Support for training and post-release support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
