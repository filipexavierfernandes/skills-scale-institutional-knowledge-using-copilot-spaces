# OctoAcme — Communication Matrix Template

## Purpose
Establish clear, consistent communication patterns across all project roles to ensure information flows efficiently, reduce miscommunication, and keep everyone aligned on project progress.

## How to Use This Template
1. Customize for your specific project at kickoff
2. Share with all team members and stakeholders
3. Review and update during retrospectives
4. Reference when communication issues arise

---

## Regular Communication Cadence

### Daily Communications

#### Daily Standup
- **Participants**: Developers, Scrum Master, (optional: PM, PdM, UX Designer, QA)
- **Frequency**: Daily, 15 minutes
- **Format**: Each person shares: yesterday's progress, today's plan, blockers
- **Owner**: Scrum Master (facilitates)
- **Documentation**: Blockers logged in project tracking tool
- **Async Alternative**: Written update in team channel for distributed teams

### Weekly Communications

#### PM + Product Manager Sync
- **Participants**: Project Manager, Product Manager
- **Frequency**: Weekly, 30-60 minutes
- **Format**: Review priorities, scope changes, risks, timeline adjustments
- **Owner**: Project Manager (schedules and documents)
- **Documentation**: Decision log, updated risk register
- **Key Outcomes**: Aligned priorities, resolved scope questions, risk mitigation plans

#### Delivery Team Sync
- **Participants**: PM, PdM, Scrum Master, Tech Lead, UX Lead, QA Lead
- **Frequency**: Weekly, 45-60 minutes
- **Format**: Progress review, demo readiness, upcoming priorities, risk review
- **Owner**: Project Manager
- **Documentation**: Status summary, action items
- **Key Outcomes**: Visibility across functions, early risk identification

#### Design Review
- **Participants**: UX Designer, Product Manager, Developers (implementing feature)
- **Frequency**: Weekly or as needed per sprint
- **Format**: Review designs, discuss feasibility, align on implementation approach
- **Owner**: UX Designer (presents), Product Manager (prioritizes feedback)
- **Documentation**: Design decisions, implementation notes
- **Key Outcomes**: Approved designs, clear implementation guidance

#### Backlog Refinement
- **Participants**: Product Manager, Scrum Master, Developers, UX Designer
- **Frequency**: Weekly, 60-90 minutes
- **Format**: Review upcoming stories, clarify requirements, estimate, identify dependencies
- **Owner**: Product Manager (prioritizes), Scrum Master (facilitates)
- **Documentation**: Updated stories with acceptance criteria and estimates
- **Key Outcomes**: Ready backlog for upcoming sprint

### Sprint/Iteration Cadence

#### Sprint Planning
- **Participants**: Scrum Master, Developers, Product Manager, UX Designer, QA
- **Frequency**: Start of each sprint (e.g., bi-weekly)
- **Format**: Commit to sprint backlog, define sprint goal, clarify requirements
- **Owner**: Scrum Master (facilitates), Product Manager (clarifies requirements)
- **Documentation**: Sprint backlog, sprint goal
- **Key Outcomes**: Team commitment to sprint deliverables

#### Sprint Review/Demo
- **Participants**: All team members, External Stakeholders (as appropriate)
- **Frequency**: End of each sprint (e.g., bi-weekly)
- **Format**: Demonstrate completed work, gather feedback
- **Owner**: Scrum Master (facilitates), Developers (demo features)
- **Documentation**: Demo notes, stakeholder feedback
- **Key Outcomes**: Stakeholder alignment, feedback for backlog

#### Sprint Retrospective
- **Participants**: Developers, Scrum Master, PM, PdM, UX Designer, QA
- **Frequency**: End of each sprint (e.g., bi-weekly)
- **Format**: What went well, what to improve, action items
- **Owner**: Scrum Master (facilitates)
- **Documentation**: Retrospective notes, action items with owners
- **Key Outcomes**: Process improvements, team health insights

### Monthly Communications

#### Stakeholder Update
- **Participants**: External Stakeholders, PM, PdM
- **Frequency**: Monthly or at major milestones
- **Format**: Written status report + optional meeting for questions
- **Owner**: Project Manager (prepares), Product Manager (presents outcomes)
- **Documentation**: Status report archived in project repo
- **Key Outcomes**: Stakeholder confidence, early escalation of concerns

**Status Report Template**:
- Executive Summary
- Progress This Period (completed milestones)
- Upcoming Milestones
- Success Metrics Update
- Risks and Issues (RAG status)
- Decisions Needed
- Ask/Support Required

### Ad-Hoc/Event-Driven Communications

#### Project Kickoff
- **Participants**: All team members, External Stakeholders
- **Frequency**: Once at project start
- **Format**: Review charter, align on goals, introduce team, establish communication norms
- **Owner**: Project Manager
- **Documentation**: Kickoff deck, meeting notes, RACI matrix
- **Key Outcomes**: Shared understanding, team alignment, clear roles

#### Blocker Escalation
- **Participants**: Varies by blocker (typically PM, affected team members, stakeholder with decision authority)
- **Frequency**: As needed
- **Format**: Describe blocker, impact, options, recommendation
- **Owner**: Person encountering blocker (raises), Project Manager (escalates if needed)
- **Documentation**: Blocker log with resolution
- **Key Outcomes**: Quick resolution, minimal disruption

#### Incident Communication
- **Participants**: On-call team, PM, PdM, affected stakeholders
- **Frequency**: During production incidents
- **Format**: Follow incident response runbook
- **Owner**: On-call lead
- **Documentation**: Incident report, post-mortem
- **Key Outcomes**: Quick resolution, transparent communication, learnings captured

---

## Communication Channels by Type

### Synchronous Channels
- **Video meetings**: For ceremonies, kickoffs, complex discussions requiring back-and-forth
- **Huddles/Quick calls**: For urgent blockers or quick clarifications (< 15 min)
- **Pair programming sessions**: For collaborative problem-solving and knowledge sharing

### Asynchronous Channels
- **Project board comments**: For updates on specific work items
- **Pull request comments**: For code review and technical discussions
- **Team chat channel**: For quick questions, daily updates, team coordination
- **Email**: For formal communications, stakeholder updates, decision documentation
- **Documentation/Wiki**: For persistent knowledge, processes, architectural decisions

### Documentation Repositories
- **Project repository**: Charter, plans, status reports
- **Design repository**: Wireframes, prototypes, design specs
- **Technical docs**: Architecture decisions, API specs, runbooks
- **Team wiki**: Process docs, onboarding guides, FAQs

---

## Role-Specific Communication Patterns

### Project Manager
- **Outbound**: Status reports, meeting notes, decision logs, risk updates
- **Inbound**: Progress updates, blocker notifications, stakeholder requests
- **Key Relationships**: PM ↔ PdM (daily/weekly), PM ↔ Scrum Master (weekly), PM ↔ Stakeholders (weekly/monthly)

### Product Manager
- **Outbound**: Requirements, acceptance criteria, prioritization decisions, roadmap updates
- **Inbound**: Technical feasibility input, user feedback, market insights
- **Key Relationships**: PdM ↔ PM (weekly), PdM ↔ UX Designer (frequent), PdM ↔ Stakeholders (frequent)

### Scrum Master
- **Outbound**: Metrics reports, blocker escalations, ceremony invites, retrospective summaries
- **Inbound**: Impediments, process questions, ceremony prep requests
- **Key Relationships**: SM ↔ Developers (daily), SM ↔ PM (weekly), SM ↔ PdM (backlog refinement)

### Developers
- **Outbound**: Code, PR descriptions, technical proposals, status updates
- **Inbound**: Requirements, code review feedback, design specs
- **Key Relationships**: Dev ↔ Dev (daily), Dev ↔ UX Designer (frequent), Dev ↔ QA (continuous)

### UX Designer
- **Outbound**: Design specs, research findings, usability recommendations
- **Inbound**: Requirements, technical constraints, user feedback
- **Key Relationships**: UX ↔ PdM (frequent), UX ↔ Developers (frequent), UX ↔ Users (research)

### QA/Testing
- **Outbound**: Test reports, bug reports, release readiness assessments
- **Inbound**: Features to test, acceptance criteria, deployment notifications
- **Key Relationships**: QA ↔ Developers (continuous), QA ↔ PM (release planning), QA ↔ PdM (acceptance validation)

### External Stakeholders
- **Outbound**: Requirements, constraints, approvals, feedback
- **Inbound**: Status updates, demos, approval requests, escalations
- **Key Relationships**: Stakeholder ↔ PM (primary), Stakeholder ↔ PdM (product direction)

---

## Communication Escalation Paths

### Level 1: Team-Level Resolution
- **Timeframe**: Immediate to 1 business day
- **Process**: Raised in daily standup or team chat
- **Resolver**: Scrum Master, Tech Lead, or peer team members
- **Examples**: Technical blockers, clarification questions, minor process issues

### Level 2: Project Leadership
- **Timeframe**: 1-3 business days
- **Process**: Escalated to Project Manager or Product Manager
- **Resolver**: PM (for scope, timeline, resources) or PdM (for product decisions)
- **Examples**: Cross-team dependencies, scope questions, priority conflicts

### Level 3: Stakeholder/Executive
- **Timeframe**: 3-5 business days
- **Process**: Formal escalation with business impact analysis
- **Resolver**: External Stakeholders, executive sponsors
- **Examples**: Budget overruns, major timeline risks, strategic direction changes

### Emergency Escalation
- **Timeframe**: Immediate
- **Process**: Follow incident response runbook
- **Resolver**: On-call team, incident commander, PM
- **Examples**: Production outages, security incidents, critical bugs

---

## Communication Best Practices

### General Guidelines
- Default to transparency: share information broadly unless confidential
- Use public channels when possible to maximize visibility
- Document important decisions and share links
- Respect communication preferences and time zones
- Provide context in all communications (link to relevant docs/tickets)
- Use @mentions thoughtfully (don't overuse)

### Meeting Effectiveness
- Always have an agenda shared in advance
- Start and end on time
- Document decisions and action items
- Send notes within 24 hours
- Record meetings when possible for distributed teams
- Default to smaller meetings when possible

### Written Communication
- Use clear subject lines/titles
- Lead with summary/key points (executive summary style)
- Use formatting (bullets, headers) for readability
- Include relevant links and context
- Specify if action is needed and by when
- Use threading to keep conversations organized

### Async-First Mindset
- Prefer async communication when possible
- Don't expect immediate responses outside working hours
- Use synchronous time for complex discussions and decision-making
- Document synchronous discussions for async participants
- Set clear expectations for response times

---

## Troubleshooting Communication Issues

### Symptom: Information Silos
**Solution**: Increase use of public channels, document decisions in shared locations, implement regular cross-functional syncs

### Symptom: Meeting Overload
**Solution**: Audit meeting necessity, combine overlapping meetings, implement async alternatives, enforce strict time limits

### Symptom: Unclear Decisions
**Solution**: Use decision log, document decision-makers (RACI), send explicit decision summaries after key meetings

### Symptom: Stakeholder Misalignment
**Solution**: Increase update frequency, solicit explicit feedback/approval, clarify expectations and success criteria

### Symptom: Blocker Delays
**Solution**: Clarify escalation paths, reduce escalation timeframes, empower team-level decision-making

### Symptom: Missing Context
**Solution**: Require linked issues/docs in communications, improve onboarding docs, implement better documentation practices

---

## Review and Improvement

### Quarterly Review Questions
1. Are all regular meetings still necessary and effective?
2. Are communication channels working well for all team members?
3. Are there gaps in information flow?
4. Is documentation keeping pace with changes?
5. Are escalation paths working efficiently?
6. Do team members feel over- or under-communicated with?

### Update This Matrix When:
- Team composition changes significantly
- Project phase transitions occur
- Communication issues arise repeatedly
- Team feedback suggests improvements
- New tools or channels are adopted

---

## Customization Checklist

When adapting this template for your project:
- [ ] Adjust meeting frequency based on project pace and team size
- [ ] Define specific meeting times and locations/links
- [ ] Identify actual names for key roles (not just role titles)
- [ ] Specify communication tools used (Slack vs Teams, Zoom vs Meet, etc.)
- [ ] Add project-specific ceremonies or communication needs
- [ ] Define working hours and timezone considerations
- [ ] Establish response time expectations
- [ ] Create project-specific channels/spaces
- [ ] Document any exceptions or special cases
- [ ] Share finalized matrix with all participants
