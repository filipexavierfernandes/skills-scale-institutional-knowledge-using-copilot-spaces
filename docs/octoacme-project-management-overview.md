# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risk, communications, and cross-team dependencies.
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success, and ensures product-market fit.
- **Developers**: Implement features, write tests, participate in code reviews, and collaborate on design decisions.
- **Scrum Master**: Facilitates agile ceremonies, removes impediments, tracks team metrics, and coaches on agile practices.
- **UX Designer**: Conducts user research, creates designs, validates usability, and ensures intuitive user experiences.
- **QA/Testing**: Validates quality, tests acceptance criteria, and ensures product reliability.
- **External Stakeholders**: Provide business requirements, approve deliverables, and ensure organizational alignment.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Role Accountability by Project Phase

### 1. Initiation Phase
**Primary Accountability**: Product Manager & Project Manager
- **Product Manager**: Defines problem statement, success metrics, business value
- **Project Manager**: Creates project charter, identifies stakeholders, initial timeline
- **External Stakeholders**: Approve charter and business case
- **Developers**: Provide technical feasibility assessment
- **UX Designer**: Contribute user research insights
- **Scrum Master**: Estimate team capacity

**Key Handoff**: Approved charter → Planning phase kickoff

### 2. Planning Phase
**Primary Accountability**: Project Manager with input from all roles
- **Project Manager**: Facilitates kickoff, creates project plan, manages dependencies
- **Product Manager**: Prioritizes backlog, defines acceptance criteria
- **Scrum Master**: Facilitates sprint planning, ensures realistic commitments
- **Developers**: Break down work, provide estimates, identify technical dependencies
- **UX Designer**: Create design concepts, define UX acceptance criteria
- **QA/Testing**: Define test strategy and quality gates
- **External Stakeholders**: Review and approve scope and timeline

**Key Handoff**: Prioritized backlog + project plan → Execution phase

### 3. Execution Phase
**Primary Accountability**: Developers & Scrum Master (delivery), Project Manager (coordination)
- **Developers**: Implement features, write tests, review code
- **Scrum Master**: Facilitate daily standups, remove blockers, track metrics
- **UX Designer**: Deliver designs iteratively, validate implementation
- **QA/Testing**: Execute test plans, validate acceptance criteria
- **Product Manager**: Make trade-off decisions, adjust priorities
- **Project Manager**: Track progress, manage risks, coordinate communication
- **External Stakeholders**: Receive status updates, provide feedback at milestones

**Key Handoff**: Completed, tested features → Release readiness review

### 4. Release Phase
**Primary Accountability**: Project Manager & Developers
- **Developers**: Deploy to production, monitor systems, address critical issues
- **Project Manager**: Coordinate deployment schedule, manage stakeholder communication
- **Product Manager**: Approve go-live, validate success metrics
- **QA/Testing**: Execute release verification tests
- **Scrum Master**: Ensure release process improvements are captured
- **UX Designer**: Validate production implementation meets design standards
- **External Stakeholders**: Approve go-live decision, receive release announcement

**Key Handoff**: Production deployment → Post-release monitoring and retrospective

### 5. Close & Retrospective Phase
**Primary Accountability**: Scrum Master & Project Manager
- **Scrum Master**: Facilitate retrospective, document improvement actions
- **Project Manager**: Document project learnings, close administrative tasks
- **All Team Members**: Participate in retrospective, share insights
- **Product Manager**: Review success metrics, identify next iteration opportunities
- **External Stakeholders**: Review final outcomes and learnings

**Key Handoff**: Documented learnings → Future project improvements

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
