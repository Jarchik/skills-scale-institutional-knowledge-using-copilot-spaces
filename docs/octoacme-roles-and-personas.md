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

## UX/UI Designer

### Role Summary
UX/UI Designers create intuitive, accessible, and visually appealing user experiences. They conduct user research, design wireframes and prototypes, and collaborate with developers and product managers to ensure designs are implemented correctly.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user interfaces that align with brand guidelines and accessibility standards
- Collaborate with developers to ensure design implementation fidelity
- Maintain and evolve design systems and component libraries
- Advocate for user needs throughout the development process

### Goals
- Deliver user-centered designs that improve usability and satisfaction
- Reduce friction in user workflows and increase task completion rates
- Maintain design consistency across products
- Ensure accessibility compliance (WCAG standards)

### Typical Communication
- Design reviews and critiques with stakeholders
- Daily collaboration with developers during implementation
- User research findings and usability test reports
- Design specs and handoff documentation via Figma/Sketch
- Participation in sprint planning and demos

### Interactions with Existing Roles
- **Product Managers**: Collaborate on feature requirements, success metrics, and user flows; validate designs align with business goals
- **Developers**: Provide design specifications, assets, and guidance during implementation; review UI/UX in pull requests
- **Project Managers**: Coordinate on timelines for design deliverables; flag design-related risks and dependencies
- **QA/Testing**: Partner on usability testing and UI validation in various environments

---

## Technical Writer / Documentation Lead

### Role Summary
Technical Writers create and maintain clear, accurate documentation that helps users, developers, and stakeholders understand products, APIs, and processes. They ensure documentation is accessible, up-to-date, and aligned with product changes.

### Responsibilities
- Write and maintain user guides, API documentation, and technical specifications
- Create onboarding materials and tutorials
- Ensure documentation accuracy and consistency across all platforms
- Collaborate with developers to document new features and changes
- Manage documentation repositories and publishing workflows
- Establish and enforce documentation standards and style guides

### Goals
- Reduce support burden through comprehensive, searchable documentation
- Enable self-service for users and developers
- Maintain documentation that stays current with product evolution
- Improve developer experience through clear API and integration guides

### Typical Communication
- Documentation reviews with subject matter experts
- Weekly sync with product and engineering on upcoming features
- Style guide and template updates
- Documentation release notes coordinated with product releases
- User feedback analysis to improve content clarity

### Interactions with Existing Roles
- **Developers**: Gather technical details for API docs and feature documentation; review pull requests for user-facing changes
- **Product Managers**: Align documentation with product roadmap; ensure feature announcements have supporting docs
- **Project Managers**: Track documentation milestones and dependencies; coordinate doc releases with product launches
- **Customer/Support Advocate**: Gather feedback on documentation gaps and frequently asked questions

---

## DevOps / Platform Engineer

### Role Summary
DevOps/Platform Engineers build and maintain the infrastructure, tooling, and automation that enable reliable software delivery. They focus on CI/CD pipelines, observability, infrastructure as code, and platform stability.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Manage cloud infrastructure and infrastructure as code (IaC)
- Implement monitoring, logging, and alerting systems
- Automate deployment processes and environment provisioning
- Ensure platform security, scalability, and reliability
- Support incident response and post-incident reviews
- Maintain developer tooling and platform documentation

### Goals
- Reduce deployment time and increase deployment frequency
- Minimize downtime and improve system reliability (SLAs/SLOs)
- Enable developer self-service through automation and tooling
- Improve observability and mean time to recovery (MTTR)

### Typical Communication
- Infrastructure change notifications and maintenance windows
- Post-incident reports and root cause analysis
- Platform status updates and capacity planning reports
- Runbooks and operational documentation
- Participation in architecture and security reviews

### Interactions with Existing Roles
- **Developers**: Provide CI/CD support and troubleshooting; enable automated testing and deployments; collaborate on performance optimization
- **Project Managers**: Coordinate infrastructure changes and deployment schedules; communicate platform risks
- **Security Lead**: Implement security scanning in pipelines; ensure infrastructure security best practices
- **Product Managers**: Align platform improvements with product reliability and performance goals

---

## Security Lead / Champion

### Role Summary
Security Leads champion security practices across the development lifecycle. They conduct threat modeling, security reviews, and vulnerability assessments while enabling teams to build secure software through education and tooling.

### Responsibilities
- Conduct security reviews of designs, code, and infrastructure
- Perform threat modeling and risk assessments
- Implement and maintain security scanning tools (SAST, DAST, dependency scanning)
- Respond to security incidents and coordinate remediation
- Establish security policies, standards, and best practices
- Provide security training and guidance to development teams
- Monitor vulnerability disclosures and coordinate patching

### Goals
- Reduce security vulnerabilities in production systems
- Enable secure-by-default development practices
- Minimize time to detect and remediate security issues
- Maintain compliance with security standards and regulations

### Typical Communication
- Security review findings and recommendations
- Vulnerability reports and remediation tracking
- Security awareness training and guidelines
- Incident response communications and post-mortems
- Compliance audit reports and security metrics

### Interactions with Existing Roles
- **Developers**: Conduct code security reviews; provide guidance on secure coding practices; assist with vulnerability remediation
- **DevOps/Platform Engineer**: Collaborate on infrastructure security, secrets management, and security automation in CI/CD
- **Product Managers**: Advise on security implications of features; balance security requirements with product timelines
- **Project Managers**: Communicate security risks and dependencies; coordinate security-related work in project plans

---

## Customer/Support Advocate

### Role Summary
Customer/Support Advocates represent the voice of the customer throughout the product development process. They gather feedback, track issues, and ensure customer needs are addressed in product planning and prioritization.

### Responsibilities
- Collect and analyze customer feedback and support tickets
- Identify and escalate critical customer issues and trends
- Advocate for customer needs in product planning discussions
- Create and maintain customer-facing knowledge base content
- Coordinate beta programs and early access feedback
- Track customer satisfaction metrics (NPS, CSAT)
- Bridge communication between customers and product/engineering teams

### Goals
- Improve customer satisfaction and reduce support burden
- Ensure customer pain points inform product roadmap
- Reduce time to resolution for customer issues
- Enable customer success through proactive communication

### Typical Communication
- Weekly customer insights reports and trend analysis
- Critical issue escalations and resolution updates
- Customer feedback sessions and beta program summaries
- Support documentation and FAQ updates
- Customer health reviews and retention discussions

### Interactions with Existing Roles
- **Product Managers**: Share customer insights to inform prioritization; validate feature ideas with customer feedback
- **Developers**: Escalate bugs and feature requests; provide context on customer use cases and edge cases
- **Technical Writer**: Collaborate on support documentation and knowledge base content; identify documentation gaps
- **Project Managers**: Communicate customer commitments and deadlines; track customer-facing deliverables

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

