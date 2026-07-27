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

### Role Interactions
- **Product Managers**: receive acceptance criteria and feature specs; raise feasibility concerns and technical trade-offs.
- **Project Managers**: report progress, surface blockers, and confirm estimates during planning.
- **Tech Lead / Architect**: seek technical direction, participate in design reviews, and escalate architectural concerns.
- **Engineering Manager**: escalate team blockers or process issues that affect delivery capacity.
- **UX/UI Designer**: collaborate on implementation fidelity and flag design edge cases discovered during development.
- **DevOps / Platform Engineer**: coordinate on CI/CD pipeline requirements, environment issues, and deployment readiness.
- **Security / Compliance Specialist**: apply secure coding guidance and address findings from security reviews.

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

### Role Interactions
- **Project Managers**: align on timelines, scope changes, and release readiness; escalate blockers that affect delivery commitments.
- **Developers**: provide clear acceptance criteria and participate in refinement sessions to clarify requirements.
- **Tech Lead / Architect**: consult on technical constraints and evaluate feasibility of roadmap items.
- **UX/UI Designer**: co-define user flows, review prototypes, and validate usability outcomes.
- **Business Analyst**: work together to translate business needs into actionable requirements and acceptance criteria.
- **Customer Success / Support Representative**: incorporate customer feedback and support signals into prioritization decisions.
- **Security / Compliance Specialist**: ensure compliance implications are factored into product decisions.

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

### Role Interactions
- **Product Managers**: synchronize on scope changes, priority shifts, and release readiness decisions.
- **Engineering Manager**: align on team capacity, staffing changes, and delivery risk.
- **Tech Lead / Architect**: understand technical dependencies and validate milestone feasibility.
- **DevOps / Platform Engineer**: coordinate deployment windows, environment readiness, and release logistics.
- **Security / Compliance Specialist**: incorporate security milestones and compliance checkpoints into project plans.
- **Customer Success / Support Representative**: ensure support readiness and external communications are planned for each release.

---

## Engineering Manager

### Role Summary
Engineering Managers lead and develop engineering teams, own team capacity and health, and act as the bridge between delivery execution and organizational leadership.

### Responsibilities
- Own team capacity planning and headcount forecasting
- Coach and develop individual contributors on the team
- Remove systemic blockers that impede delivery
- Make staffing and role allocation decisions in partnership with Project Managers
- Represent engineering health and delivery risks to leadership
- Drive technical hiring decisions and onboarding

### Goals
- Build and maintain a high-performing, healthy engineering team
- Ensure sustainable delivery pace and minimize burnout
- Align team capabilities with roadmap demands

### Typical Communication
- 1:1s with direct reports; team retrospectives and health checks
- Capacity and headcount reviews with leadership
- Cross-functional syncs with Project Managers and Product Managers on delivery feasibility

### Role Interactions
- **Project Managers**: provide team capacity data to inform project plans; jointly manage delivery risk when resourcing is constrained.
- **Product Managers**: evaluate roadmap feasibility against team bandwidth and surface trade-off options.
- **Tech Lead / Architect**: partner on technical career development and organizational design; ensure engineering quality standards are upheld.
- **Developers**: support day-to-day execution by removing blockers, clarifying expectations, and providing coaching.
- **DevOps / Platform Engineer**: ensure platform and tooling investments align with team needs.

---

## Tech Lead / Architect

### Role Summary
Tech Leads and Architects provide technical direction, own system design decisions, and ensure non-functional requirements (scalability, reliability, security, performance) are addressed throughout the project lifecycle.

### Responsibilities
- Define and maintain technical architecture and design standards
- Lead technical design reviews and approve major architectural decisions
- Identify technical risks and dependencies early in the planning process
- Ensure non-functional requirements are captured and met
- Mentor Developers on engineering best practices
- Coordinate with DevOps and Security on infrastructure and compliance requirements

### Goals
- Deliver a technically sound, maintainable, and scalable solution
- Minimize technical debt introduced during delivery
- Ensure architectural decisions are well-understood and documented

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Design review sessions and PR reviews
- Technical risk input to the project risk register

### Role Interactions
- **Product Managers**: translate technical constraints and risks into product-understandable trade-offs; advise on feasibility of roadmap items.
- **Project Managers**: flag technical dependencies and blockers that affect timeline; provide effort estimates for architectural work.
- **Engineering Manager**: align on team technical direction and individual developer growth paths.
- **Developers**: provide direction and mentorship; review design proposals and code contributions for architectural correctness.
- **DevOps / Platform Engineer**: define infrastructure and deployment requirements; collaborate on CI/CD and observability standards.
- **Security / Compliance Specialist**: incorporate security architecture requirements and address findings from threat models.
- **UX/UI Designer**: align on technical feasibility of design proposals and API/data model constraints.

---

## UX/UI Designer

### Role Summary
UX/UI Designers own the user experience quality of product features. They translate user needs and business goals into clear, accessible, and implementable designs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity design specs
- Define user flows, interaction models, and accessibility standards
- Maintain and evolve the design system and component library
- Collaborate with Developers to ensure implementation fidelity
- Provide visual and interaction references for QA acceptance testing

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce ambiguity during development by providing clear design specifications
- Validate design assumptions with real user feedback before and after release

### Typical Communication
- Design reviews and prototype walkthroughs
- Design system documentation and component annotations
- Usability study reports shared with Product Managers

### Role Interactions
- **Product Managers**: co-define user outcomes and validate that designs achieve stated product goals.
- **Developers**: hand off design specs and assets; review implementation for fidelity; address design edge cases found during development.
- **Tech Lead / Architect**: confirm technical feasibility of interaction patterns and data requirements.
- **Business Analyst**: collaborate on user flows to ensure business rules and edge cases are represented.
- **Customer Success / Support Representative**: gather user pain points and support feedback to inform design improvements.

---

## Business Analyst

### Role Summary
Business Analysts bridge stakeholder needs and delivery teams by eliciting, documenting, and validating requirements. They ensure that project scope is well-defined and that acceptance criteria are unambiguous.

### Responsibilities
- Elicit and document functional and non-functional requirements
- Map current-state and future-state business processes
- Refine user stories and acceptance criteria in collaboration with Product Managers
- Identify and document edge cases, constraints, and business rules
- Support traceability between business goals and delivered features
- Facilitate requirements workshops with stakeholders and the delivery team

### Goals
- Ensure requirements are clear, complete, and testable before development begins
- Reduce rework caused by misunderstood or missing requirements
- Maintain a shared understanding of scope across all roles

### Typical Communication
- Requirements documentation and user story refinement sessions
- Process flow diagrams and business rule catalogs
- Acceptance criteria walkthroughs with Developers and QA

### Role Interactions
- **Product Managers**: translate business goals and stakeholder inputs into structured requirements; surface ambiguities and conflicts early.
- **Project Managers**: provide scope documentation that supports milestone and dependency planning.
- **Developers**: clarify requirements, business rules, and edge cases during development; review implementation against acceptance criteria.
- **UX/UI Designer**: jointly map user flows to ensure business rules are represented in designs.
- **Tech Lead / Architect**: confirm that technical constraints are reflected in requirements documentation.

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers own the reliability, efficiency, and security of the software delivery pipeline and production environment. They enable teams to deploy frequently with confidence.

### Responsibilities
- Design, maintain, and improve CI/CD pipelines and release automation
- Manage infrastructure provisioning, environment configuration, and secrets management
- Implement observability, monitoring, and alerting for production services
- Coordinate and execute production deployments and rollbacks
- Drive adoption of engineering best practices (infrastructure-as-code, containerization, etc.)
- Participate in incident response and post-incident reviews

### Goals
- Maximize deployment frequency and minimize lead time to production
- Ensure environment parity across development, staging, and production
- Reduce mean time to recovery (MTTR) when incidents occur

### Typical Communication
- Release readiness confirmations to Project Managers
- Infrastructure change notices and runbook documentation
- On-call handoff notes and incident post-mortems

### Role Interactions
- **Project Managers**: confirm deployment readiness, coordinate release windows, and flag infrastructure risks.
- **Developers**: support local development environments, CI/CD troubleshooting, and deployment automation.
- **Tech Lead / Architect**: collaborate on infrastructure design, service topology, and observability strategy.
- **Security / Compliance Specialist**: implement security controls in pipelines, apply vulnerability scanning, and enforce access policies.
- **Engineering Manager**: surface platform investment needs and tooling gaps that affect team productivity.

---

## Security / Compliance Specialist

### Role Summary
Security and Compliance Specialists protect the organization and its users by embedding security and regulatory requirements into the project lifecycle. They ensure features are built and shipped securely.

### Responsibilities
- Conduct threat modeling and security architecture reviews
- Define and enforce security acceptance criteria for features
- Perform or coordinate security testing (SAST, DAST, penetration testing)
- Advise on regulatory and compliance requirements (e.g., GDPR, SOC 2, HIPAA)
- Respond to and lead triage of security incidents
- Maintain security documentation, policies, and audit evidence

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure the product meets applicable compliance and regulatory standards
- Build security awareness across all roles in the team

### Typical Communication
- Security review findings and risk acceptance documentation
- Compliance requirement summaries for Product and Project Managers
- Security advisories and training for Developers

### Role Interactions
- **Product Managers**: advise on compliance implications of product decisions; ensure security requirements are reflected in acceptance criteria.
- **Project Managers**: add security milestones and checkpoints to project plans; escalate high-severity risks.
- **Tech Lead / Architect**: review architecture for security patterns and threat mitigation strategies.
- **Developers**: provide secure coding guidance, review code for vulnerabilities, and address security findings.
- **DevOps / Platform Engineer**: define pipeline security controls, supply-chain checks, and access management policies.

---

## Customer Success / Support Representative

### Role Summary
Customer Success and Support Representatives are the voice of the customer inside the organization. They capture real-world feedback, ensure customers can adopt new features successfully, and provide signal for prioritization and quality improvements.

### Responsibilities
- Capture, triage, and route customer feedback and bug reports to the right teams
- Contribute to support readiness planning for each release (documentation, FAQs, training)
- Communicate upcoming changes and release notes to customers
- Monitor post-release adoption and surface issues back to Product and Engineering
- Represent customer impact when risk and escalation decisions are made

### Goals
- Ensure customers can successfully use new features with minimal friction
- Reduce support ticket volume through proactive readiness and clear communication
- Provide a reliable feedback loop from production usage back to the delivery team

### Typical Communication
- Release readiness reviews with Project Managers
- Customer-facing release notes and change communications
- Feedback summaries and support trend reports to Product Managers

### Role Interactions
- **Product Managers**: provide customer feedback, usage signals, and support trends to inform backlog prioritization.
- **Project Managers**: confirm that support readiness activities (documentation, training, FAQs) are included in the release plan.
- **Developers**: report reproducible bugs with customer context and validate fixes from the customer's perspective.
- **UX/UI Designer**: share usability pain points observed in customer interactions to inform design improvements.
- **Security / Compliance Specialist**: report potential security concerns surfaced through customer channels.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to [RACI Matrix](octoacme-raci-matrix.md) to understand ownership and accountability across lifecycle phases.
- Refer to [Handoff Checklist](octoacme-handoff-checklist.md) for structured transition guidance between planning, execution, and release.

