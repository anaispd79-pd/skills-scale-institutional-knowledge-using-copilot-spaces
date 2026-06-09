# OctoAcme Project Management Documentation

This README serves as the entry point for all OctoAcme project management process docs. It summarizes the core project management practices and provides links to detailed guidance for each area.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need and align stakeholders around a lightweight One-pager that captures the problem, objective, success metrics, and resource needs. Once approved at a decision gate, the project moves into Planning, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done.

Execution and delivery are managed through a disciplined team rhythm and project board workflow. Daily standups focus on progress and blockers, while weekly delivery syncs track advancement toward milestones. Work flows through a GitHub Projects board with columns spanning Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines when possible) with automated CI/CD testing and linting before review. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, and security scanning. The team also conducts regular demos and maintains a risk register, escalating blockers through a three-level system: team triage, PM escalation to Product Lead, and sponsor-level involvement for business-impacting issues.

Clear roles and responsibilities drive accountability across OctoAcme projects. The **Project Manager** coordinates delivery, schedules, risks, and communications; the **Product Manager** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features while collaborating on design and testability; and **QA/Testing** validates quality and acceptance criteria. Communication is formalized through weekly PM-to-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Risk management is continuous—risks are identified during planning and execution, assessed for impact and likelihood, monitored weekly, and mitigated through documented action plans. After release, teams conduct blameless retrospectives to capture learnings and convert action items into backlog improvements, reinforcing a culture of psychological safety and iterative improvement.

## Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate, authorize work, and align stakeholders
- [Project Planning](./octoacme-project-planning.md) — Turn approved initiatives into actionable plans and backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, and progress tracking
- [Risks & Communication](./octoacme-risks-and-communication.md) — Risk management, escalation, and stakeholder communication
- [Release & Deployment](./octoacme-release-and-deployment.md) — Standardized release processes and deployment checklists
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive actionable improvements
- [Roles & Personas](./octoacme-roles-and-personas.md) — Detailed descriptions of core roles and responsibilities

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) for context on our principles and key roles.
2. **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate and plan your work.
3. **In execution?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for our team rhythm and workflows.
4. **Need guidance on a specific area?** Use the Documentation Index above to find the relevant guide.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

For questions or suggestions about these processes, please open an issue or discussion in the repository.
