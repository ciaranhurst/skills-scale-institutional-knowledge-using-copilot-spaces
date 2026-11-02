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

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors provide business context, funding, and top-level approvals for projects. Sponsors authorize initiation, resolve business-impacting escalations, and confirm that delivered outcomes meet strategic goals.

### Responsibilities
- Approve project initiation and major scope or budget changes
- Provide business context, priorities, and success criteria
- Serve as the final escalation point for business-impacting issues
- Review and approve release announcements affecting the business

### Goals
- Ensure projects align with business strategy and deliver expected value
- Make timely decisions on escalations and trade-offs
- Maintain confidence in delivery teams through transparency

### Typical Communication
- Sponsor/stakeholder alignment meetings at initiation
- Monthly or milestone-based status updates
- Sponsor-level escalation discussions for critical issues

### Interaction with Other Roles
- Receive status reports and escalations from Project Managers
- Provide prioritization input and approvals to Product Managers and Product Lead
- Approve initiation one-pagers alongside the Product Lead

---

## Product Lead

### Role Summary
The Product Lead reviews and approves product direction at a level above individual Product Managers, resolving cross-team product conflicts and approving key artifacts such as initiation one-pagers.

### Responsibilities
- Review and approve one-pagers and major product decisions
- Resolve product-direction conflicts escalated by Product Managers or Project Managers
- Act as the second-level escalation point before Sponsor involvement
- Align product priorities across teams

### Goals
- Ensure product decisions are consistent across teams and projects
- Reduce escalations reaching Sponsors by resolving conflicts early
- Support Product Managers in maintaining a coherent product vision

### Typical Communication
- Review sessions for one-pagers and specs
- Escalation discussions with Project Managers and Product Managers
- Periodic alignment syncs with Sponsors

### Interaction with Other Roles
- Reviews and approves work from Product Managers
- Receives escalations from Project Managers (Level 2) before involving Sponsors (Level 3)
- Coordinates with Stakeholders/Sponsors on business alignment

---

## QA / Testing

### Role Summary
QA/Testing validates that features and fixes meet acceptance criteria and quality standards before release, through manual and automated testing.

### Responsibilities
- Validate acceptance criteria and quality standards
- Perform manual testing for feature acceptance when needed
- Own and manage the "QA" stage of the project board
- Report defects and verify fixes with Developers

### Goals
- Catch defects before release
- Maintain confidence in release quality
- Reduce post-release incidents and rework

### Typical Communication
- Test plans and QA approach documentation
- Defect reports and triage discussions
- Quality gate status updates to Project Managers before release

### Interaction with Other Roles
- Receives completed work from Developers for validation and returns defects for rework
- Reports quality status to Project Managers as part of release go/no-go decisions
- Coordinates with Security on combined quality and security gates before release

---

## Security

### Role Summary
Security owns security scanning gates in CI and the security incident response process, ensuring releases and operations meet security standards.

### Responsibilities
- Maintain and monitor security scanning in CI pipelines
- Own the security incident runbook and on-call rotation
- Participate in go/no-go release decisions related to security risk
- Advise on secure design and remediation of vulnerabilities

### Goals
- Prevent security vulnerabilities from reaching production
- Minimize time to detect and resolve security incidents
- Maintain compliance with security standards and best practices

### Typical Communication
- Security scan results and CI gate reports
- Security incident notifications and on-call escalations
- Participation in release readiness and risk reviews

### Interaction with Other Roles
- Notifies Developers of vulnerabilities requiring remediation
- Provides input to Project Managers/release owners for go/no-go decisions
- Coordinates with QA/Testing on combined release quality gates

---

## Support / Customer Success

### Role Summary
Support/Customer Success is the first point of contact for customers after release, communicating customer impact back to the delivery team and relaying release information to customers.

### Responsibilities
- Receive and communicate release announcements to customers
- Triage and report customer-impacting issues post-release
- Provide customer feedback and impact data to the delivery team
- Act as the first point of contact for post-release support issues

### Goals
- Ensure customers are informed of changes and issues
- Minimize time to resolution for customer-impacting problems
- Provide accurate, timely feedback to improve future releases

### Typical Communication
- Release announcement notifications
- Customer issue triage and reproduction reports
- Post-release feedback summaries to the delivery team

### Interaction with Other Roles
- Receives release announcements from Project Managers for customer communication
- Reports customer-impacting issues to Developers and QA/Testing for triage and reproduction
- Escalates significant business impact to Stakeholders/Sponsors when needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

