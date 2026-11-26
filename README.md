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

## Delivery Lead / Scrum Master

### Purpose and accountability
Facilitates the delivery process, protects team flow, and helps remove impediments. The Delivery Lead is accountable for ceremony effectiveness and transparent team delivery, while the Project Manager remains accountable for the integrated project plan, dependencies, risks, and stakeholder reporting.

### Responsibilities
- Facilitate standups, planning, reviews, retrospectives, and other delivery ceremonies
- Track impediments and coordinate their resolution
- Surface cross-team dependencies and help teams manage work in progress
- Coach teams toward predictable, sustainable delivery
- Provide delivery health and flow information to the Project Manager

### Key interactions and handoffs
- Works with the **Project Manager** on dependencies, plans, risks, and escalations.
- Aligns priorities with the **Product Manager** and validates that work is ready for implementation.
- Coordinates with **Developers** and **QA/Testing** on readiness, blockers, and acceptance criteria.
- Shares dependency or delivery risks with **stakeholders** when timely input or decisions are needed.

### Decision authority and escalation
The Delivery Lead may prioritize ceremony outcomes and team process actions. Scope, roadmap, budget, and cross-project tradeoffs are escalated to the Project Manager or Product Manager. Organizational or cross-team blockers that exceed delivery-team authority go to the Project Manager and Executive Sponsor.

### Typical inputs and outputs
- Inputs: backlog status, team capacity, impediments, dependency maps, and acceptance criteria
- Outputs: facilitated decisions, updated flow metrics, impediment actions, and readiness signals

---

## Release Manager

### Purpose and accountability
Owns the end-to-end release plan and coordinates the final steps required to deploy safely. The Release Manager is accountable for release timing, readiness evidence, and rollback coordination.

### Responsibilities
- Plan deployment windows and release sequencing
- Verify that documented readiness gates have been met
- Coordinate go/no-go decisions, communications, and rollback plans
- Maintain release records and post-release handoffs

### Key interactions and handoffs
- Aligns timing and risks with the **Project Manager**.
- Confirms implementation and validation with **Developers** and **QA/Testing**.
- Provides operational and customer readiness information to **Operations/Site Reliability**, **Support**, and stakeholders.
- Partners with the **Change and Adoption Lead** on release communications and user impact.

### Decision authority and escalation
May approve deployment execution after required gates are satisfied under established policy. A missed gate, unresolved critical defect, or elevated operational risk is escalated for go/no-go decision by the Project Manager, appropriate approvers, and Executive Sponsor when organization-level impact warrants it.

### Typical inputs and outputs
- Inputs: release checklist, test evidence, deployment plan, rollback procedure, and support coverage
- Outputs: release calendar, readiness decision, stakeholder announcement, and deployment record

---

## Security/Compliance Reviewer

### Purpose and accountability
Defines and verifies applicable security, privacy, legal, and regulatory requirements. The reviewer is accountable for identifying control requirements and confirming whether evidence supports approval.

### Responsibilities
- Interpret applicable policies and regulatory obligations
- Identify required controls, threat risks, evidence, and approval conditions
- Review designs and release evidence for compliance gaps
- Advise on remediation and residual risk

### Key interactions and handoffs
- Advises the **Product Manager** on required constraints and the **Project Manager** on schedule and approval risk.
- Works with **Developers** and **QA/Testing** to implement and validate controls.
- Coordinates release approval evidence with the **Release Manager** and operational assurances with **Operations/Site Reliability**.
- Raises material stakeholder impacts or unresolved obligations to leadership.

### Decision authority and escalation
May accept or reject controls based on its documented compliance mandate and stop work when required approval or evidence is missing. Scope or residual-risk exceptions are escalated through designated compliance, legal, and executive approval paths.

### Typical inputs and outputs
- Inputs: architecture, data flows, threat models, test evidence, policies, and regulatory requirements
- Outputs: control requirements, findings, approval conditions, exception requests, and compliance sign-off

---

## Data/Analytics Partner

### Purpose and accountability
Defines how project outcomes will be measured and converts project data into actionable decisions. The partner is accountable for measurement quality and clear interpretation, not for product prioritization.

### Responsibilities
- Define success metrics and measurement plans
- Specify required instrumentation and data-quality checks
- Analyze delivery and outcome data
- Communicate findings, limitations, and recommendations

### Key interactions and handoffs
- Collaborates with the **Product Manager** on outcomes and success criteria.
- Works with **Developers** and **QA/Testing** on telemetry, instrumentation, and validation.
- Provides status and outcome reporting to the **Project Manager**, stakeholders, and Executive Sponsor.
- Supports the **Change and Adoption Lead** with adoption and usage metrics.

### Decision authority and escalation
May determine approved definitions and the validity of reported measures. Product tradeoffs, scope decisions, and unresolved metric disputes are escalated to the Product Manager, Project Manager, or Executive Sponsor according to organizational authority.

### Typical inputs and outputs
- Inputs: business goals, event or usage requirements, baselines, and stakeholder questions
- Outputs: metric definitions, dashboards, experiment plans, analyses, and decision recommendations

---

## Change and Adoption Lead

### Purpose and accountability
Plans communications, training, and adoption support and identifies impacts to users and teams. The lead is accountable for adoption readiness and user feedback, while the Product Manager owns product intent and prioritization.

### Responsibilities
- Assess user and stakeholder impact
- Plan communications, training, enablement, and adoption measures
- Coordinate readiness activities with affected groups
- Collect feedback and identify adoption risks

### Key interactions and handoffs
- Partners with the **Product Manager** on product intent and intended outcomes.
- Coordinates timing and dependencies with the **Project Manager** and Delivery Lead.
- Works with **Release Manager** and **Operations/Site Reliability** on readiness and post-release support.
- Builds help materials and coverage plans with **Support** and communicates impacts to stakeholders.

### Decision authority and escalation
May approve communication and training artifacts within agreed messaging and timing. Changes to scope, policy, or product behavior are escalated to the Product Manager and Project Manager; adoption shortfalls or unresolved organizational barriers are escalated to the Executive Sponsor.

### Typical inputs and outputs
- Inputs: release plan, stakeholder list, user research, process changes, and training needs
- Outputs: communications, training plan, adoption measures, feedback summary, and readiness checklist

---

## Operations/Site Reliability Partner

### Purpose and accountability
Defines operational readiness, monitoring, service ownership, and incident practices. The partner is accountable for production operability and reliable handoff from delivery to operations.

### Responsibilities
- Define service-level objectives, ownership, monitoring, and alerting
- Review capacity and failure scenarios
- Establish incident, escalation, and post-release follow-up processes
- Validate runbooks and rollback readiness

### Key interactions and handoffs
- Coordinates reliability implementation and test scenarios with **Developers** and **QA/Testing**.
- Reviews deployment readiness with the **Release Manager** and project schedule with the **Project Manager**.
- Shares operating impacts with **Support** and adoption implications with the Change and Adoption Lead.
- Reports unresolved operational risk to the Executive Sponsor when organizational escalation is required.

### Decision authority and escalation
May veto production release for unmet operational gates and initiate incident response according to service policy. Operational tradeoffs or exceptional releases are escalated to the Project Manager, Release Manager, Security/Compliance Reviewer, and Executive Sponsor as applicable.

### Typical inputs and outputs
- Inputs: architecture, capacity projections, monitoring requirements, test results, and runbooks
- Outputs: operational readiness decision, dashboards and alerts, service ownership, and incident procedures

---

## Support Lead

### Purpose and accountability
Represents customer and operational issues and prepares the support organization for launch. The Support Lead is accountable for support readiness and for feeding recurring feedback into the backlog prioritization process.

### Responsibilities
- Identify likely customer questions and support impacts
- Establish coverage, triage, escalation, and reporting processes
- Contribute to readiness planning and release communications
- Aggregate recurring issues and recommend backlog themes

### Key interactions and handoffs
- Provides customer evidence to **Product Managers** and recurring-issue priorities to the Project Manager and Delivery Lead.
- Works with **Developers** and **QA/Testing** on troubleshooting and defect reproduction.
- Partners with the **Change and Adoption Lead** on help content and the Release Manager on go-live readiness.
- Coordinates urgent incidents or systemic issues with Operations/Site Reliability and stakeholders.

### Decision authority and escalation
May determine support coverage and escalate customer-facing severity according to agreed procedures. Product, scope, release, and response decisions are escalated to the appropriate Product Manager, Release Manager, Project Manager, or Executive Sponsor.

### Typical inputs and outputs
- Inputs: known issues, customer feedback, FAQs, release notes, and operating procedures
- Outputs: support plans, known-issue guidance, escalations, defect evidence, and backlog recommendations

---

## Executive Sponsor

### Purpose and accountability
Provides organizational mandate and removes blockers that exceed delivery-team authority. The sponsor is accountable for major business alignment and final tradeoffs that affect strategic goals, risk, or investment.

### Responsibilities
- Champion project goals and remove organizational barriers
- Approve major scope, budget, timing, or policy tradeoffs
- Resolve escalations beyond delivery-team authority
- Communicate strategic context and reinforce stakeholder alignment

### Key interactions and handoffs
- Reviews goals, progress, risks, and key decisions with the **Project Manager** and **Product Manager**.
- Receives decision requests from specialist roles and delivery leads when established authority is insufficient.
- Uses stakeholder and organizational context to set priorities and unblock cross-functional work.
- Supports go/no-go decisions for material business or organizational risk.

### Decision authority and escalation
Owns decisions delegated by the organization, including major scope, investment, and risk acceptance. Matters outside that delegated authority follow the organization's executive or governance process.

### Typical inputs and outputs
- Inputs: project briefs, decision requests, risk and financial summaries, and stakeholder concerns
- Outputs: mandate, prioritization, approved tradeoffs, escalation decisions, and organizational support

---

## Cross-role collaboration principles

- **Accountability stays explicit:** specialist approval or sign-off does not replace delivery ownership. The Project Manager coordinates delivery, the Product Manager owns product direction, and each specialist owns the authority and evidence assigned to their role.
- **Handoffs are decision-ready:** transfers include the owner, due date, required inputs, acceptance criteria, and escalation path.
- **Risks escalate by impact:** delivery risks move to the Project Manager or Delivery Lead, product tradeoffs to the Product Manager, and organization-wide or strategic risks to the Executive Sponsor.
- **Readiness is shared:** Developers, QA/Testing, Operations/Site Reliability, Release Manager, Security/Compliance, Support, and Change/Adoption roles contribute evidence toward an informed release decision.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
