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

### Interaction with Other Roles
- Work with **Technical Architect/Lead** on design reviews and technical guidance
- Collaborate with **QA/Testing Lead** on testability and acceptance criteria
- Report blockers to **Project Manager** and **Scrum Master**
- Implement requirements defined by **Product Managers**

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

### Interaction with Other Roles
- Partner with **Stakeholder/Sponsor** on business objectives and prioritization
- Work with **Project Manager** on timeline and release planning
- Collaborate with **UX/Design Lead** on user experience requirements
- Define acceptance criteria with **QA/Testing Lead**

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

### Interaction with Other Roles
- Escalate blockers and risks identified by **Developers** and **Scrum Master**
- Coordinate with **Stakeholder/Sponsor** on decisions and resource allocation
- Work with **Technical Architect/Lead** to understand technical risks and dependencies
- Align with **Product Manager** on priorities and milestones

---

## QA/Testing Lead

### Role Summary
The QA/Testing Lead owns quality assurance strategy, test planning, and acceptance criteria validation. They collaborate with product and engineering to define testability standards and ensure features meet quality gates before release.

### Responsibilities
- Develop and maintain test strategies and test plans for each release
- Define quality standards and acceptance criteria with product and engineering
- Execute manual QA and coordinate automated testing efforts
- Identify and triage quality issues; escalate blockers
- Participate in release readiness reviews

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce post-release defects and regressions
- Build testing efficiency through automation and process improvement

### Typical Communication
- Quality review gates in sprint planning and release checkouts
- Test plan and issue triage discussions
- Ad-hoc escalations for critical quality concerns

### Interaction with Other Roles
- Partner with **Developers** on testability and test implementation
- Work with **Product Managers** to validate feature acceptance criteria
- Collaborate with **DevOps/Release Engineer** on smoke testing and release verification
- Report quality metrics to **Project Manager**
- Review design specifications with **UX/Design Lead**

---

## Technical Architect/Lead

### Role Summary
The Technical Architect defines technical direction, conducts design reviews, and makes architectural decisions. They work with developers and product to ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Define technical approach and architecture for projects
- Conduct design reviews and provide technical guidance
- Identify technical risks and propose mitigations
- Mentor developers and establish technical standards
- Evaluate and recommend tools, libraries, and frameworks

### Goals
- Deliver scalable, maintainable, and secure solutions
- Reduce technical debt and rework
- Foster a culture of technical excellence

### Typical Communication
- Technical design discussions and architecture reviews
- Risk assessments and technology recommendations
- Code review guidance and technical mentoring

### Interaction with Other Roles
- Guide **Developers** on design and technical standards
- Collaborate with **Product Managers** on feasibility and technical trade-offs
- Work with **DevOps/Release Engineer** on deployment and infrastructure architecture
- Identify technical risks to escalate to **Project Manager**
- Support **QA/Testing Lead** on testability design

---

## Stakeholder/Sponsor

### Role Summary
The Stakeholder or Sponsor provides business context, strategic alignment, and resource oversight. They have decision authority and accountability for project success and business outcomes.

### Responsibilities
- Define business objectives and success metrics
- Provide resource allocation and prioritization guidance
- Review and approve major decisions and trade-offs
- Communicate project status to executive leadership
- Address blockers escalated from the team

### Goals
- Ensure project delivers measurable business value
- Maintain strategic alignment across initiatives
- Enable team success through timely decisions and support

### Typical Communication
- Monthly stakeholder updates and business reviews
- Decision gates at project milestones
- Escalation path for resource or priority conflicts

### Interaction with Other Roles
- Partner with **Product Managers** on business strategy and prioritization
- Receive escalations from **Project Manager** on blockers and major decisions
- Support team resource needs communicated by **Project Manager**
- Review business impact metrics reported by **Product Managers**

---

## Scrum Master/Agile Coach

### Role Summary
The Scrum Master or Agile Coach facilitates team processes, removes blockers, and coaches agile practices. They enable the team to work effectively and continuously improve their delivery approach.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and help resolve team blockers and impediments
- Coach team on agile practices and continuous improvement
- Monitor team health and velocity metrics
- Protect team focus and minimize distractions

### Goals
- Enable consistent, predictable delivery
- Foster a culture of collaboration and psychological safety
- Continuously improve team processes and efficiency

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members
- Coaching on agile practices and problem-solving

### Interaction with Other Roles
- Support all team members (**Developers**, **QA/Testing Lead**, **Technical Architect/Lead**)
- Escalate unresolvable blockers to **Project Manager**
- Facilitate collaboration between **Product Managers** and the delivery team
- Work with **Project Manager** to maintain project health and team capacity

---

## DevOps/Release Engineer

### Role Summary
The DevOps or Release Engineer manages CI/CD pipelines, production deployments, and infrastructure observability. They enable fast, reliable releases and maintain production stability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Execute production deployments and monitor releases
- Manage infrastructure and deployment automation
- Troubleshoot production issues and coordinate rollbacks
- Maintain deployment documentation and runbooks

### Goals
- Enable fast, reliable, and repeatable deployments
- Reduce deployment risk and time-to-recovery
- Maintain high availability and production observability

### Typical Communication
- Release planning and pre-deployment readiness reviews
- Deployment execution and incident response
- Infrastructure and automation improvement discussions

### Interaction with Other Roles
- Work with **Developers** on CI/CD pipeline integration and deployment strategies
- Partner with **QA/Testing Lead** on smoke testing and post-deployment verification
- Collaborate with **Technical Architect/Lead** on infrastructure and deployment architecture
- Report deployment metrics and incidents to **Project Manager**
- Support production stability reviewed in **Stakeholder/Sponsor** business reviews

---

## UX/Design Lead

### Role Summary
The UX/Design Lead defines user experience requirements and design standards. They work with product and engineering to ensure solutions are usable, accessible, and aligned with design principles.

### Responsibilities
- Define user experience requirements and design specifications
- Conduct user research and usability testing
- Establish and maintain design standards and guidelines
- Collaborate on feature design and user flow optimization
- Ensure accessibility and usability standards are met

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Maintain consistent, cohesive product design

### Typical Communication
- Design reviews and feedback sessions with product and engineering
- User research findings and design recommendations
- Design system documentation and standards

### Interaction with Other Roles
- Partner with **Product Managers** on user requirements and experience strategy
- Collaborate with **Developers** on design implementation and usability
- Work with **QA/Testing Lead** on usability and accessibility testing
- Support **Stakeholder/Sponsor** in communicating user-focused value

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Note how each role has defined interactions with other roles to show the interconnected nature of successful project delivery.
