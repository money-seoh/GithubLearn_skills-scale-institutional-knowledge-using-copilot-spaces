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

## Release Manager

### Role Summary
Release Managers own the end-to-end release process, ensuring that software is packaged, validated, and deployed safely to production. They act as the coordination hub between development, operations, and stakeholders at release time.

### Responsibilities
- Define and maintain the release calendar and branching strategy
- Coordinate release readiness reviews with Developers, Project Managers, and Operations
- Gate deployments based on quality criteria and change-approval processes
- Communicate release notes and deployment windows to stakeholders
- Track post-release metrics and coordinate hotfixes with Developers if issues arise

### Goals
- Deliver stable, predictable releases with minimal disruption
- Reduce deployment risk through consistent release processes
- Maintain clear audit trails for every production change

### Typical Communication
- Release readiness meetings with Project Managers and Developers
- Go/no-go notifications to Product Managers and Support/Operations
- Post-release summaries distributed to all stakeholders

---

## Risk Owner

### Role Summary
Risk Owners are accountable for identifying, tracking, and mitigating specific risks throughout the project lifecycle. While Project Managers maintain the overall risk register, Risk Owners drive resolution for the risks assigned to them.

### Responsibilities
- Identify and articulate risks within their domain of expertise
- Define and execute mitigation or contingency plans
- Report risk status regularly to Project Managers and the Delivery Lead
- Collaborate with Security Champions on security-related risks and with Developers on technical risks
- Escalate blockers to the Project Manager when mitigation is stalled

### Goals
- Reduce the likelihood and impact of identified risks
- Ensure risks do not become unplanned work or escalations
- Maintain visibility on residual risk at all times

### Typical Communication
- Regular updates to the risk register maintained by Project Managers
- Escalation meetings when a risk materializes
- Coordination with Security Champions, Developers, and Project Managers

---

## Delivery Lead

### Role Summary
Delivery Leads ensure that teams have everything they need to execute and that delivery commitments are met. They bridge strategic priorities set by Product Managers and the tactical execution managed by Project Managers.

### Responsibilities
- Remove blockers and dependencies that prevent teams from delivering
- Track delivery health metrics and flag risks to Product and Project Managers
- Coordinate cross-team dependencies with other Delivery Leads and Project Managers
- Support capacity planning and resource allocation decisions
- Facilitate escalation and resolution of cross-team conflicts

### Goals
- Maintain a healthy, predictable delivery cadence
- Ensure teams are unblocked and focused on the highest-priority work
- Foster collaboration and reduce friction between Developers, PMs, and stakeholders

### Typical Communication
- Daily or weekly sync with Project Managers and team leads
- Escalation paths to senior leadership when needed
- Cross-team dependency tracking on shared project boards

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They translate stakeholder requirements into clear, actionable specifications that Developers and Product Managers can use.

### Responsibilities
- Elicit, document, and validate business and functional requirements
- Create user stories, acceptance criteria, and process flow diagrams
- Collaborate with Product Managers to prioritize requirements in the backlog
- Work with Developers to clarify requirements and resolve ambiguities during implementation
- Validate delivered functionality against original requirements

### Goals
- Ensure delivered solutions meet business needs and reduce rework
- Improve requirements clarity and reduce ambiguity for Developers
- Create shared understanding across business stakeholders and technical teams

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written specifications and acceptance criteria shared with Developers and Product Managers
- Review sessions with Product Managers and Project Managers during sprint planning

---

## Technical Writer

### Role Summary
Technical Writers create, maintain, and improve documentation so that users, Developers, and stakeholders can understand and effectively use the systems OctoAcme builds.

### Responsibilities
- Write and maintain user guides, API documentation, runbooks, and release notes
- Collaborate with Developers to document new features and changes accurately
- Work with Product Managers to ensure documentation aligns with product goals
- Coordinate with Support/Operations Representatives to address knowledge gaps surfaced by users
- Establish and enforce documentation standards and templates

### Goals
- Ensure all delivered features are accompanied by accurate, usable documentation
- Reduce support burden by making documentation self-service
- Maintain documentation quality and consistency across releases

### Typical Communication
- Feature reviews with Developers and Product Managers prior to release
- Coordination with Release Managers to publish documentation alongside releases
- Feedback loops with Support/Operations Representatives on documentation gaps

---

## Support/Operations Representative

### Role Summary
Support/Operations Representatives act as the voice of users and operational teams inside the project. They surface real-world issues, validate operability of new features, and ensure smooth transitions from development to production.

### Responsibilities
- Communicate user-facing issues and operational pain points to Product Managers and Developers
- Participate in release readiness reviews with Release Managers to validate operational impact
- Validate runbooks and escalation procedures with Technical Writers
- Monitor production health post-release and coordinate hotfixes with Developers and Release Managers
- Maintain knowledge-base articles and coordinate updates with Technical Writers

### Goals
- Minimize customer-facing incidents and reduce mean time to resolution
- Ensure new releases are operationally ready and well-documented
- Close the feedback loop between production operations and development teams

### Typical Communication
- Incident reports and post-mortems shared with Developers and Project Managers
- Participation in go/no-go decisions with Release Managers
- Regular syncs with Technical Writers to keep documentation current

---

## Security Champion

### Role Summary
Security Champions are embedded advocates for security best practices within the project team. They partner with Developers, Risk Owners, and Project Managers to identify and address security concerns throughout the development lifecycle.

### Responsibilities
- Conduct and facilitate threat modeling and security reviews for new features
- Guide Developers on secure coding practices and assist in remediating vulnerabilities
- Maintain awareness of relevant security advisories and communicate impact to the team
- Work with Risk Owners to track and mitigate security-related risks
- Coordinate with Project Managers to schedule security-related work within sprints
- Review release readiness from a security perspective alongside Release Managers

### Goals
- Reduce security risk in delivered software by shifting security left
- Build a security-aware engineering culture within the team
- Ensure security issues are identified and resolved before they reach production

### Typical Communication
- Security review sessions with Developers during design and implementation
- Risk register updates coordinated with Risk Owners and Project Managers
- Go/no-go input to Release Managers on security readiness

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

