# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions with Other Roles
- **Scrum Master**: Receives support in removing blockers and optimizing workflow
- **UX Designer**: Collaborates on implementation of user experience requirements
- **Business Analyst**: Works together to clarify edge cases and technical requirements
- **QA/Testing**: Partners on test strategies and acceptance criteria verification
- **Security Lead**: Consults on security implementation and code review concerns

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Ensure feature adoption and measure impact post-launch

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions with Other Roles
- **Project Manager**: Partners on timeline and resource planning
- **UX Designer**: Collaborates on customer research and user needs validation
- **Business Analyst**: Works together on requirements refinement and prioritization
- **Support Engineer**: Gathers customer feedback and support trends to inform backlog
- **Security Lead**: Ensures security requirements are factored into prioritization

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Track progress against milestones and escalate blockers

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions with Other Roles
- **Scrum Master**: Collaborates on sprint planning and process improvement
- **Product Manager**: Aligns on roadmap, timelines, and dependencies
- **Business Analyst**: Works together on scope clarification and stakeholder engagement
- **Support Engineer**: Coordinates release communication and customer impact assessment
- **Security Lead**: Ensures security reviews and compliance activities are scheduled

---

## Expanded Roles (Cross-Functional Support)

### Scrum Master

#### Role Summary
The Scrum Master facilitates agile ceremonies, removes impediments, and coaches the team on continuous improvement and process optimization. This role ensures the team operates efficiently within the agreed framework.

#### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Identify and help remove impediments blocking the team's progress
- Coach team members on agile practices and self-organization
- Protect the team from external distractions and scope creep
- Track team velocity and health metrics
- Drive process improvements based on retrospective feedback
- Ensure Definition of Done is consistently applied

#### Goals
- Enable the team to deliver predictably and sustainably
- Foster a culture of continuous improvement
- Remove obstacles to velocity and quality

#### Typical Communication
- Daily standup facilitation and blocker tracking
- Retrospective notes and action item tracking
- Metrics dashboards (velocity, cycle time, etc.)
- Ad-hoc coaching and process guidance

#### Interactions with Other Roles
- **Project Manager**: Collaborates on timeline management and escalation of external blockers
- **Developers**: Removes sprint-level impediments and coaches on technical practices
- **Product Manager**: Helps clarify priorities and manage backlog refinement cadence
- **UX Designer & Business Analyst**: Ensures their inputs are incorporated into sprint ceremonies
- **Security Lead**: Includes security reviews in DoD and sprint planning

---

### UX Designer

#### Role Summary
The UX Designer is responsible for designing user experiences, validating usability, and ensuring solutions are user-centered. This role bridges customer needs with technical implementation and brings a voice for end-users to the team.

#### Responsibilities
- Conduct user research and define user personas and journeys
- Create wireframes, prototypes, and design specifications
- Collaborate with developers to ensure design fidelity during implementation
- Participate in acceptance criteria definition, focusing on usability
- Conduct usability testing and gather user feedback
- Advocate for user experience throughout the project lifecycle
- Document design decisions and patterns for consistency

#### Goals
- Deliver intuitive, usable solutions that delight customers
- Reduce support burden through good UX
- Ensure consistency across product experiences

#### Typical Communication
- Design reviews and feedback sessions
- Usability test results and findings
- Acceptance criteria on user experience requirements
- Design documentation and component libraries

#### Interactions with Other Roles
- **Product Manager**: Partners on customer research and feature validation
- **Developers**: Collaborates on implementation feasibility and design details
- **Business Analyst**: Works together to translate requirements into user-centered designs
- **QA/Testing**: Provides input on usability test plans and acceptance criteria
- **Support Engineer**: Gathers user pain points and support feedback to inform design iterations

---

### Business Analyst

#### Role Summary
The Business Analyst gathers, analyzes, and clarifies requirements from stakeholders. This role bridges business and technical perspectives, ensuring clear understanding of what needs to be built and why.

#### Responsibilities
- Conduct stakeholder interviews and gather business requirements
- Analyze current processes and identify improvement opportunities
- Write detailed requirements and acceptance criteria
- Clarify edge cases, constraints, and dependencies
- Create requirement traceability matrices
- Facilitate workshops between business and technical teams
- Document and communicate complex business logic clearly

#### Goals
- Minimize rework due to unclear or missed requirements
- Align business stakeholders and technical teams on scope
- Ensure solutions meet intended business outcomes

#### Typical Communication
- Requirements documentation and specifications
- Stakeholder meeting notes and decision logs
- Use cases and acceptance criteria
- Process flow diagrams and business logic documentation

#### Interactions with Other Roles
- **Product Manager**: Collaborates on detailed requirements refinement and prioritization
- **Project Manager**: Works together on scope clarity and stakeholder alignment
- **UX Designer**: Partners to translate business requirements into user-centered designs
- **Developers**: Clarifies technical implications and edge cases during implementation
- **Security Lead**: Ensures compliance and security requirements are clearly documented

---

### Support Engineer

#### Role Summary
The Support Engineer represents the customer voice within the project team. This role brings customer insights, feedback, and pain points from support tickets into the product development process, ensuring solutions address real customer needs.

#### Responsibilities
- Gather and analyze customer feedback from support tickets and channels
- Identify patterns in customer pain points and feature requests
- Participate in acceptance criteria definition with a customer lens
- Provide testing and validation input from support perspective
- Document known issues and workarounds
- Participate in release planning and communication
- Help triage post-launch issues and incidents

#### Goals
- Ensure features solve real customer problems
- Reduce support volume through better product design
- Provide early warning of quality or usability issues

#### Typical Communication
- Support ticket trends and customer feedback summaries
- Input on acceptance criteria from customer perspective
- Release notes and customer communication
- Post-launch issue reports and trending analysis

#### Interactions with Other Roles
- **Product Manager**: Shares customer insights to inform prioritization
- **Project Manager**: Coordinates release communication and customer impact assessment
- **UX Designer**: Provides real-world user feedback to inform design iterations
- **Business Analyst**: Helps translate support patterns into business requirements
- **QA/Testing**: Partners on test scenarios based on customer usage patterns

---

### Security Lead

#### Role Summary
The Security Lead ensures that security considerations are integrated throughout the project lifecycle. This role works to identify, assess, and mitigate security risks and ensures compliance with organizational and regulatory requirements.

#### Responsibilities
- Conduct threat modeling and security assessments during planning
- Review architecture and design for security implications
- Provide security guidelines and best practices to the team
- Participate in code reviews with a security focus
- Ensure compliance with security policies and regulations
- Triage and coordinate incident response when needed
- Document security decisions and risk mitigations

#### Goals
- Deliver secure solutions that protect customer data and systems
- Identify and mitigate security risks early
- Ensure compliance with organizational and regulatory standards

#### Typical Communication
- Security threat models and risk assessments
- Security checklist items in Definition of Done
- Code review comments on security concerns
- Incident response coordination and post-mortems
- Security compliance documentation

#### Interactions with Other Roles
- **Project Manager**: Ensures security activities are scheduled in the timeline
- **Developers**: Reviews code and architecture with security expertise; provides guidance
- **Business Analyst**: Clarifies compliance and security requirements
- **UX Designer**: Advises on secure design patterns and user authentication flows
- **QA/Testing**: Includes security testing in test plans and acceptance criteria

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these role descriptions during planning and retrospectives to clarify ownership and accountability.
- Adapt these personas to your team's actual structure and responsibilities.
