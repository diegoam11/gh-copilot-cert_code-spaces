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

## UX/UI Designer or User Researcher

### Role Summary
UX/UI Designers and User Researchers represent user needs throughout discovery, design, and delivery. They ensure solutions are usable, accessible, and validated with evidence.

### Responsibilities
- Plan and run user research, usability tests, and discovery interviews
- Create and maintain user flows, wireframes, and design specifications
- Define accessibility and usability acceptance expectations
- Partner with Product Managers to refine requirements and outcomes
- Support Developers and QA/Testing with design clarifications and validation criteria

### Goals
- Increase user success, satisfaction, and accessibility compliance
- Reduce rework caused by unclear user requirements
- Ensure delivered experiences solve validated user problems

### Typical Communication
- Discovery readouts and usability findings
- Design reviews with Product Manager, Developers, and QA/Testing
- Annotated mockups and acceptance notes in planning artifacts

### Interaction Points with Existing Roles
- **Project Manager:** Align discovery activities with project timelines and risks
- **Product Manager:** Convert research insights into prioritized outcomes and requirements
- **Developers:** Clarify implementation intent, design edge cases, and feasibility trade-offs
- **QA/Testing:** Define usability/accessibility test expectations and acceptance criteria
- **Stakeholders:** Share user evidence that supports scope and priority decisions

---

## Technical Lead or Architect

### Role Summary
Technical Leads and Architects guide technical direction, solution design, and non-functional quality attributes across the project lifecycle.

### Responsibilities
- Define architecture and technical approach for features and integrations
- Set standards for reliability, scalability, maintainability, and performance
- Identify technical risks, dependencies, and mitigation plans
- Review implementation strategy and support engineering estimation
- Drive design decisions and document trade-offs in decision logs

### Goals
- Deliver technically sound solutions with manageable long-term maintenance cost
- Reduce implementation risk through early technical alignment
- Protect delivery predictability by resolving architecture decisions early

### Typical Communication
- Architecture reviews and design decision records
- Technical planning sessions with Developers and Project Manager
- Cross-functional readiness reviews with Security, QA/Testing, and DevOps/SRE

### Interaction Points with Existing Roles
- **Project Manager:** Translate technical dependencies and risks into schedule impacts
- **Product Manager:** Balance customer outcomes with technical feasibility and constraints
- **Developers:** Provide implementation guidance, patterns, and design guardrails
- **QA/Testing:** Align on non-functional test strategy and quality gates
- **Stakeholders:** Explain major technical trade-offs and decision implications

---

## Security and Privacy Partner

### Role Summary
Security and Privacy Partners ensure products and delivery plans meet security, privacy, and compliance expectations before release.

### Responsibilities
- Perform threat modeling and privacy impact input during planning
- Define required security controls, data handling rules, and review checkpoints
- Review high-risk changes for vulnerabilities and compliance concerns
- Support incident-preparedness planning and escalation paths
- Advise on remediation priorities for identified security/privacy risks

### Goals
- Prevent avoidable security and privacy incidents
- Ensure compliance obligations are addressed before release decisions
- Build security and privacy quality into delivery, not only post-release review

### Typical Communication
- Risk assessments and control recommendations
- Security/privacy review outcomes tied to release readiness
- Escalation updates for critical findings and mitigation status

### Interaction Points with Existing Roles
- **Project Manager:** Schedule mandatory review gates and manage risk escalation
- **Product Manager:** Clarify privacy-by-design and compliance requirements in scope
- **Developers:** Validate secure implementation approaches and mitigation actions
- **QA/Testing:** Align on security and privacy test coverage expectations
- **Stakeholders:** Communicate risk posture and decision requirements for go/no-go

---

## DevOps/SRE or Release Manager

### Role Summary
DevOps/SRE and Release Managers own deployment readiness, operational reliability, and safe release execution.

### Responsibilities
- Define and maintain deployment, rollback, and environment readiness checklists
- Ensure observability, alerting, and runbooks are in place for releases
- Coordinate release timing, cutover steps, and post-release verification
- Identify infrastructure and operational dependencies that affect delivery
- Partner with support/operations teams for production handoff readiness

### Goals
- Achieve reliable releases with minimal disruption
- Reduce time to detect and recover from production issues
- Improve repeatability of build, deploy, and rollback processes

### Typical Communication
- Release readiness reviews and deployment plans
- Operational status updates during release windows
- Post-release incident and reliability summaries

### Interaction Points with Existing Roles
- **Project Manager:** Align release milestones, dependencies, and contingency plans
- **Product Manager:** Confirm release scope, feature flags, and rollout sequencing
- **Developers:** Coordinate build/deploy requirements and production troubleshooting
- **QA/Testing:** Ensure test evidence and release criteria are met before go-live
- **Stakeholders:** Provide release status, risk visibility, and incident updates

---

## Data or Analytics Partner

### Role Summary
Data and Analytics Partners define how project outcomes are measured and ensure trustworthy data supports product and delivery decisions.

### Responsibilities
- Define instrumentation requirements and metric definitions with Product Manager
- Establish data quality expectations and validation checks
- Create or maintain dashboards for adoption, quality, and outcome tracking
- Support experiment design and analysis for product decisions
- Surface insights and risks that affect prioritization and project outcomes

### Goals
- Ensure decisions are based on reliable, relevant data
- Improve visibility into delivery outcomes and customer impact
- Reduce ambiguity around whether released changes met goals

### Typical Communication
- Metrics definitions and instrumentation plans
- Dashboard reviews and performance insights
- Outcome reporting in milestone and retrospective discussions

### Interaction Points with Existing Roles
- **Project Manager:** Align measurement milestones and reporting cadence
- **Product Manager:** Translate goals into measurable success criteria
- **Developers:** Specify and validate event tracking implementation details
- **QA/Testing:** Verify instrumentation behavior and data integrity in test scenarios
- **Stakeholders:** Report outcome performance and decision-support insights

---

## Customer Support or Operations Representative

### Role Summary
Customer Support and Operations Representatives provide frontline operational context to improve readiness, communication, and customer impact management.

### Responsibilities
- Identify support and operational risks for planned changes
- Define support-readiness needs (training, scripts, known-issue handling)
- Validate incident/escalation procedures and customer communication plans
- Feed post-release customer issues and trends back into planning
- Coordinate operational handoffs during launches and high-impact changes

### Goals
- Minimize customer disruption during and after release
- Improve speed and quality of issue triage and resolution
- Ensure operational teams are prepared for expected change impact

### Typical Communication
- Readiness check-ins and known-issue briefings
- Incident and escalation coordination updates
- Post-release feedback and trend summaries

### Interaction Points with Existing Roles
- **Project Manager:** Align support readiness tasks with project timelines
- **Product Manager:** Clarify customer impact messaging and policy decisions
- **Developers:** Share recurring issue patterns and troubleshooting needs
- **QA/Testing:** Contribute real-world scenarios and support-focused test cases
- **Stakeholders:** Communicate customer-impact risk and service performance signals

---

## Business Sponsor or Executive Stakeholder

### Role Summary
Business Sponsors and Executive Stakeholders provide strategic direction, priority alignment, and decision authority on business trade-offs beyond day-to-day team scope.

### Responsibilities
- Set strategic outcomes, constraints, and success expectations
- Approve major scope, budget, or priority shifts at defined decision gates
- Resolve escalated cross-team or cross-portfolio conflicts
- Sponsor critical dependencies and organizational unblockers
- Review outcome performance and authorize course corrections

### Goals
- Ensure project outcomes align to business strategy and value
- Improve decision speed for escalations that exceed team authority
- Maintain clear executive accountability for major business decisions

### Typical Communication
- Decision-gate reviews and executive status checkpoints
- Escalation discussions on scope, timing, and risk trade-offs
- Outcome reviews aligned to business KPIs

### Interaction Points with Existing Roles
- **Project Manager:** Receive structured status/risk escalations and confirm gate decisions
- **Product Manager:** Align strategic priorities, investment decisions, and outcome targets
- **Developers:** Engage indirectly through technical escalations requiring business trade-offs
- **QA/Testing:** Review critical quality risk escalations before release decisions
- **Stakeholders:** Coordinate cross-functional alignment and commitment on shared outcomes

---

## When to engage additional personas and clarify handoffs
- Engage personas based on project risk, complexity, regulatory exposure, customer impact, and operational change scope.
- Confirm **RACI-style ownership** at project kickoff and again before each lifecycle gate (initiation, planning, execution, release, retrospective).
- Define decision rights explicitly in project artifacts (who recommends, who decides, who must be consulted, who is informed).
- Document handoff checkpoints between Product, Project, Engineering, QA/Testing, and specialized partners (security review complete, release readiness approved, support readiness confirmed, metrics baseline validated).
- Escalate unresolved ownership or decision conflicts to the Business Sponsor/Executive Stakeholder using the Project Manager's decision log.
- Keep participation lightweight for low-risk efforts and increase required touchpoints for high-risk or cross-functional initiatives.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
