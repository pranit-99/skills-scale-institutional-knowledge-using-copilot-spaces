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
- Collaborate with UX/UI Designers on implementation details

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Collaboration with Release Manager on deployment readiness
- Security discussions with Security Champion

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Work with UX/UI Designers on user research and feature validation
- Coordinate with Release Manager on launch timing and communications

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Design review sessions with UX/UI team

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
- Work with Release Manager to coordinate deployment windows
- Escalate security and infrastructure concerns identified by Security Champion and DevOps Engineer
- Ensure Documentation Specialist has content ready for release

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Release planning meetings with Release Manager

---

## UX/UI Designer

### Role Summary
UX/UI Designers focus on creating intuitive, accessible, and visually coherent user experiences. They collaborate with Product Managers and Developers to ensure features are usable and meet customer needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with Developers on implementation feasibility and best practices
- Define and maintain design system and component libraries
- Review acceptance criteria from a usability perspective
- Iterate on designs based on user feedback and data
- Ensure accessibility standards are met (WCAG compliance)

### Goals
- Deliver intuitive and delightful user experiences
- Reduce user friction and support burden
- Ensure consistent, accessible design across products

### Typical Communication
- Design review sessions with Developers and Product Managers
- User testing sessions and feedback synthesis
- Design documentation and component specifications
- Collaboration on acceptance criteria refinement

---

## Release Manager

### Role Summary
Release Managers coordinate the planning, scheduling, and execution of product releases. They ensure smooth deployments, manage release communications, and minimize risk during transitions to production.

### Responsibilities
- Plan and schedule release windows in coordination with Product and Engineering teams
- Verify all acceptance criteria are met before release approval
- Coordinate with DevOps/Platform Engineer on deployment infrastructure and rollback plans
- Ensure release notes and communications are complete and accurate
- Manage communication to stakeholders, customers, and support teams
- Conduct pre-release verification and smoke tests
- Lead incident response if issues arise post-deployment
- Track release metrics and post-release metrics
- Maintain release documentation and checklists

### Goals
- Minimize release risk and downtime
- Ensure clear, timely communication to all stakeholders
- Enable fast recovery from issues through documented rollback procedures

### Typical Communication
- Release planning meetings with Product and Engineering leads
- Pre-release verification checklists with Developers and QA
- Post-release status updates to stakeholders and support teams
- Incident response coordination

---

## DevOps/Platform Engineer

### Role Summary
DevOps and Platform Engineers build and maintain infrastructure, CI/CD pipelines, and deployment automation. They enable the team to ship code safely and observe system health in production.

### Responsibilities
- Design and maintain CI/CD pipelines
- Build and manage infrastructure (staging, production, disaster recovery)
- Implement monitoring, logging, and alerting systems
- Support Developers in troubleshooting production issues
- Work with Release Manager to plan deployments and rollback strategies
- Manage secrets, credentials, and access control
- Document infrastructure and operational procedures
- Perform capacity planning and performance optimization
- Support security scanning and compliance automation

### Goals
- Enable fast, safe, and repeatable deployments
- Maintain high availability and observability
- Reduce operational toil through automation

### Typical Communication
- Infrastructure design reviews with Developers
- Deployment planning with Release Manager
- On-call rotations and incident response
- Documentation of runbooks and operational procedures

---

## Security Champion

### Role Summary
Security Champions embed security practices into the development lifecycle. They collaborate with the team to identify risks, enforce best practices, and ensure compliance.

### Responsibilities
- Identify and assess security risks during planning and design phases
- Review code and architecture for security vulnerabilities
- Recommend security scanning tools and practices for CI/CD
- Stay updated on security threats and best practices
- Facilitate security training and awareness sessions
- Coordinate with DevOps/Platform Engineer on secure infrastructure practices
- Escalate critical security issues to Project Manager and stakeholders
- Maintain a security risk register and mitigation plans
- Ensure secure handling of secrets and access controls

### Goals
- Prevent security breaches and data loss
- Build a culture of security awareness across the team
- Ensure compliance with security policies and standards

### Typical Communication
- Security design reviews during planning
- Code review comments with security focus
- Security incident response and post-mortems
- Quarterly security training and awareness updates
- Risk escalation to Project Manager and leadership

---

## Documentation Specialist

### Role Summary
Documentation Specialists create clear, accurate, and comprehensive documentation that helps users, operators, and new team members understand and use products and processes.

### Responsibilities
- Create and maintain user-facing documentation and help content
- Document API specifications and technical integrations
- Develop runbooks and operational procedures for support and ops teams
- Participate in design and planning to understand features early
- Review acceptance criteria to ensure completeness and clarity
- Collaborate with UX/UI Designers on embedded help and guidance
- Manage documentation release cycles with Release Manager
- Maintain documentation standards and style guides
- Incorporate user feedback to improve documentation quality

### Goals
- Reduce support burden through clear self-service documentation
- Accelerate onboarding and reduce time-to-productivity
- Ensure consistency and accuracy across all documentation

### Typical Communication
- Documentation kickoff meetings during project planning
- Content reviews with Developers and Product Managers
- User feedback synthesis and documentation iterations
- Release note collaboration with Release Manager

---

## Role Interaction Matrix

| Role | Key Collaborators | Primary Touch Points |
|------|-------------------|----------------------|
| Developer | Product Manager, UX/UI Designer, DevOps Engineer, Security Champion | Code reviews, design reviews, deployment readiness |
| Product Manager | Developers, UX/UI Designer, Project Manager, Release Manager | Roadmap planning, acceptance criteria, launch readiness |
| Project Manager | All roles | Planning, daily standups, risk management, stakeholder communication |
| UX/UI Designer | Product Manager, Developers, Documentation Specialist | Design reviews, usability testing, feature specs |
| Release Manager | Developers, DevOps Engineer, Product Manager, Documentation Specialist | Deployment planning, release verification, post-release communication |
| DevOps/Platform Engineer | Developers, Release Manager, Security Champion | Infrastructure design, CI/CD, incident response |
| Security Champion | Developers, DevOps Engineer, Project Manager | Risk assessment, code review, security training |
| Documentation Specialist | Product Manager, Developers, UX/UI Designer, Release Manager | Content planning, feature documentation, release notes |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Role Interaction Matrix to understand dependencies and communication patterns.
