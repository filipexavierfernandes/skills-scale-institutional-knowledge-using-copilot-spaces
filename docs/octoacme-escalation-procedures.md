# OctoAcme — Escalation Procedures

## Purpose
Define clear, efficient escalation paths for blockers, risks, and issues to ensure rapid resolution and minimize project disruption. This document empowers team members to know when and how to escalate appropriately.

## Guiding Principles
- **Escalate early**: Don't wait until problems become critical
- **Provide context**: Always include impact, options, and recommendations
- **Clear ownership**: Every escalation has a named owner and timeframe
- **No blame culture**: Escalation is a problem-solving tool, not a failure
- **Track and learn**: Document escalations to improve processes

---

## Escalation Decision Framework

### When to Escalate

#### ✅ DO Escalate When:
- Blocker unresolved after reasonable team-level effort (typically 1-2 days)
- Dependencies on other teams or external parties causing delays
- Risk probability or impact increases beyond acceptable levels
- Scope change requests that affect timeline or resources
- Technical decisions requiring architectural or strategic input
- Quality issues that cannot be resolved within current sprint
- Resource constraints (capacity, tooling, access) blocking progress
- Stakeholder requirements conflicting or unclear
- Timeline slippage that will affect committed milestones
- Budget concerns or unexpected cost increases
- Security or compliance concerns requiring immediate attention

#### ⚠️ DON'T Escalate When:
- Issue can be resolved within the team with existing resources
- Problem is normal course of troubleshooting (< 1 day investigation)
- Clear workaround exists and can be implemented quickly
- Issue has no material impact on deliverables or timeline
- Escalation is meant to avoid ownership or accountability
- Problem hasn't been attempted to be resolved at appropriate level first

### How to Decide the Right Level

**Ask yourself:**
1. Can my immediate team resolve this? → Team-level resolution
2. Does this require PM/PdM decision-making authority? → Level 2
3. Does this require stakeholder approval or resources? → Level 3
4. Is this a production emergency or security incident? → Emergency path

---

## Escalation Levels

### Level 0: Peer-to-Peer Resolution (Immediate)
**Timeframe**: Immediate to few hours  
**Who**: Team members, peers in same function  
**Examples**: Code review questions, technical clarifications, tool usage help

**Process**:
1. Ask in team chat or direct message
2. Schedule quick huddle if needed (< 15 min)
3. Document resolution in relevant ticket or doc
4. No formal escalation tracking needed

**When to escalate to Level 1**: If unresolved after a few hours and blocking work

---

### Level 1: Team-Level Resolution (Same Day to 1 Business Day)
**Timeframe**: Same day to 1 business day  
**Who Resolves**: Scrum Master, Tech Lead, UX Lead, QA Lead  
**Who to Contact**: Raise in daily standup or team channel

**Examples**:
- Technical blockers within team's control
- Test environment issues
- Internal process questions
- Sprint scope clarification
- Team coordination problems
- Minor dependency clarifications
- Tool or access issues within team's purview

**Process**:
1. **Identify**: Team member identifies blocker
2. **Raise**: Mention in daily standup or team channel
3. **Triage**: Scrum Master or Lead assesses and assigns
4. **Resolve**: Work with team to resolve quickly
5. **Document**: Update ticket with resolution
6. **Follow-up**: Verify resolution in next standup

**Escalation Template** (Team Channel):
```
🚧 Blocker Alert
**Issue**: [Brief description]
**Impact**: [What's blocked, who's affected]
**Attempted solutions**: [What's been tried]
**Help needed**: [Specific ask]
**Urgency**: [Can wait for standup / Need attention today / Urgent]
```

**When to escalate to Level 2**: 
- Unresolved after 1 business day
- Requires PM/PdM decision-making
- Cross-team coordination needed
- Resource or scope decisions required

---

### Level 2: Project Leadership (1-3 Business Days)
**Timeframe**: 1-3 business days  
**Who Resolves**: Project Manager, Product Manager  
**Who to Contact**: Project Manager (for delivery/scope/resources), Product Manager (for product decisions)

**Examples**:
- Cross-team dependencies blocking progress
- Scope change requests or clarifications
- Priority conflicts or re-prioritization needs
- Resource constraints (team capacity, budget)
- Vendor or external partner delays
- Technical architecture decisions requiring broader input
- Definition of Done or acceptance criteria disputes
- Risk mitigation requiring PM coordination
- Timeline adjustments needed
- Design vs. implementation feasibility conflicts

**Process**:
1. **Document**: Create escalation with full context (see template below)
2. **Notify**: Tag PM or PdM in ticket and send summary
3. **Provide options**: Include 2-3 options with pros/cons and recommendation
4. **Schedule decision meeting**: If needed, PM schedules within 24 hours
5. **Communicate decision**: PM documents and communicates decision
6. **Track**: PM adds to decision log and risk register if applicable
7. **Follow-up**: PM ensures resolution is implemented

**Escalation Template** (Written):
```
🚨 Escalation to Project Leadership

**Issue**: [Clear description]
**Impact**: 
- Timeline impact: [Days/sprints affected]
- Scope impact: [Features/stories affected]
- Team impact: [Who's blocked]
- Risk level: [High/Medium/Low]

**Background/Context**: [How we got here]

**Options Considered**:
1. [Option 1]: [Pros/Cons]
2. [Option 2]: [Pros/Cons]
3. [Option 3]: [Pros/Cons]

**Recommendation**: [Your recommended approach and why]

**Decision Needed By**: [Date/Time]
**Escalated By**: [Name]
**Date**: [Date]
```

**When to escalate to Level 3**:
- Requires stakeholder approval or resources outside PM authority
- Budget implications beyond project contingency
- Strategic direction changes needed
- Major timeline or scope changes
- Unresolved after 3 business days at Level 2
- Legal, compliance, or security concerns

---

### Level 3: Stakeholder/Executive (3-5 Business Days)
**Timeframe**: 3-5 business days (or faster for critical issues)  
**Who Resolves**: External Stakeholders, Executive Sponsors, Department Heads  
**Who to Contact**: Project Manager escalates formally to designated stakeholder

**Examples**:
- Major scope changes requiring additional budget
- Timeline delays affecting business commitments
- Strategic direction or priority shifts
- Cross-organizational dependencies or conflicts
- Resource allocation requiring executive approval
- Risk materialization with significant business impact
- Contract or vendor escalations
- Legal or compliance approvals
- Market or competitive pressures requiring pivot

**Process**:
1. **Prepare escalation package**: PM creates comprehensive summary with business impact analysis
2. **Review with PdM**: Align on ask and recommendation
3. **Schedule stakeholder meeting**: PM arranges meeting within 2 business days
4. **Present formally**: Use escalation template with exec summary
5. **Document decision**: PM creates decision record and communicates broadly
6. **Update plans**: Adjust project plan, risk register, and stakeholder communications
7. **Track implementation**: PM ensures decision is executed and reports progress

**Escalation Package Template**:
```
🔴 Executive Escalation Required

**Executive Summary**: [2-3 sentence summary of issue and ask]

**Business Impact**:
- Revenue/Customer impact: [Quantified if possible]
- Timeline impact: [Original date → New date]
- Resource impact: [Additional resources needed]
- Reputation/Market impact: [External considerations]
- Risk if not addressed: [Consequences of inaction]

**Root Cause**: [How did we get here]

**Options Analysis**:
| Option | Cost | Timeline | Pros | Cons | Risk |
|--------|------|----------|------|------|------|
| [1]    | [$]  | [Time]   | []   | []   | []   |
| [2]    | [$]  | [Time]   | []   | []   | []   |
| [3]    | [$]  | [Time]   | []   | []   | []   |

**Recommendation**: [Chosen option with clear rationale]

**Decision Required**: [Specific approval or resource needed]
**Decision Needed By**: [Date - explain why]
**Next Steps After Approval**: [Implementation plan]
**Communication Plan**: [Who needs to know, when, how]

**Prepared by**: [PM Name]
**Reviewed by**: [PdM Name]
**Date**: [Date]
```

**When to escalate beyond Level 3**: 
Typically this is the highest level. If unresolved, PM works with stakeholder to identify the appropriate decision-maker or escalation path within the organization.

---

### Emergency Escalation (Immediate)
**Timeframe**: Immediate response required  
**Who Resolves**: Incident Commander, On-call team, PM, Security team  
**Who to Contact**: Follow incident response runbook, notify on-call

**Examples**:
- Production outage affecting customers
- Security breach or vulnerability
- Data loss or corruption
- Critical bug in production
- Service degradation below SLA
- Compliance violation discovered
- Safety or security threat

**Process**:
1. **Trigger incident response**: Follow incident runbook
2. **Declare incident**: Incident Commander declared
3. **Assemble response team**: Page relevant on-call personnel
4. **Establish communication channel**: Create dedicated incident channel
5. **Frequent updates**: Status updates every 30-60 minutes to stakeholders
6. **Focus on mitigation**: Prioritize service restoration over root cause analysis
7. **Document actions**: Maintain incident timeline
8. **Resolve**: Restore service and verify resolution
9. **Post-incident review**: Schedule blameless post-mortem within 48 hours
10. **Action items**: Track and implement preventive measures

**Emergency Notification Template**:
```
🚨🚨🚨 INCIDENT DECLARED 🚨🚨🚨

**Severity**: [P0/P1/P2]
**Status**: [Investigating / Mitigating / Resolved]
**Impact**: [What's affected, how many users/systems]
**Incident Commander**: [Name]
**Started**: [Time]

**Latest Update**: [Brief status]
**Next Update**: [Time]

**War Room**: [Channel/Meeting link]
**On-call**: [Tagged]
```

---

## Cross-Team Dependency Escalation

### Scenario: Another Team is Blocking Your Work

**Step 1: Direct Coordination (Same Day)**
- Your team member reaches out directly to counterpart on other team
- Attempt to resolve at engineer-to-engineer or peer level

**Step 2: Scrum Master to Scrum Master (1 Business Day)**
- If unresolved, your Scrum Master contacts their Scrum Master
- Attempt to find workaround or expedite dependency

**Step 3: PM to PM (2-3 Business Days)**
- If still unresolved, your PM contacts their PM
- Discuss priority alignment, resource constraints, options
- Document dependency in both teams' risk registers

**Step 4: Joint Escalation to Leadership (3-5 Business Days)**
- If teams cannot align, both PMs escalate jointly to shared leadership
- Present as a prioritization or resource decision
- Executive decides priority and resources

---

## Role-Specific Escalation Guidance

### For Developers
**Your first escalation point**: Scrum Master or Tech Lead  
**When to escalate**:
- Blocked > 4 hours with no workaround
- Technical decision requires architectural input
- Code review or PR process stalled
- Test environment issues blocking work
- Dependencies on other teams

**Don't escalate to PM for**: Normal debugging, code reviews pending < 24hrs, questions answerable by team

---

### For Scrum Master
**Your escalation points**: Project Manager (scope/resources), Product Manager (product decisions)  
**When to escalate**:
- Team blocker unresolved after 1 day
- Velocity trending off target for sprint commitment
- Team capacity constraints affecting deliverables
- Process issues requiring PM involvement
- External dependencies blocking multiple team members

**Don't escalate to PM for**: Normal team-level issues, ceremonies facilitation, metrics reporting

---

### For UX Designer
**Your escalation points**: Product Manager (product decisions), Project Manager (timeline/resources)  
**When to escalate**:
- Design feedback conflicting or unclear
- Design timeline incompatible with dev timeline
- Technical constraints preventing desired UX
- User research results requiring product direction change
- Design resources insufficient for project needs

**Don't escalate to PM for**: Normal design iterations, tool issues, peer design feedback

---

### For QA/Testing
**Your escalation points**: Project Manager (release decisions), Product Manager (quality standards)  
**When to escalate**:
- Quality issues blocking release
- Testing environment unavailable
- Test coverage gaps requiring scope decision
- Bug priority disputes
- Testing timeline insufficient

**Don't escalate to PM for**: Normal bug reports, test case questions, environment setup delays < 1 day

---

### For Product Manager
**Your escalation points**: External Stakeholders, Product Leadership  
**When to escalate**:
- Scope change requests requiring stakeholder approval
- Conflicting stakeholder requirements
- Success metrics or business case in question
- Market changes affecting product direction
- Resource constraints preventing roadmap delivery

**Don't escalate to stakeholders for**: Normal prioritization decisions, acceptance criteria clarifications, backlog refinement

---

### For Project Manager
**Your escalation points**: External Stakeholders, PMO, Executive Sponsors  
**When to escalate**:
- Timeline slippage affecting committed dates
- Budget overruns or resource constraints
- Cross-organizational dependencies unresolved
- Risk materialization with significant impact
- Scope changes requiring executive approval

**Don't escalate to executives for**: Normal project coordination, team-level blockers, routine status updates

---

## Escalation Tracking

### Track All Level 2+ Escalations
**Use escalation log with**:
- Escalation ID
- Date raised
- Raised by
- Issue description
- Level
- Assigned to
- Target resolution date
- Status (Open/In Progress/Resolved/Closed)
- Resolution summary
- Resolution date

### Review in Weekly PM Sync
- Review open escalations
- Identify patterns (are we escalating too much/too little?)
- Adjust processes to prevent recurrence
- Celebrate successful escalations that drove good outcomes

---

## Escalation Anti-Patterns (Avoid These)

### ❌ "Escalation as Blame"
**Don't**: Escalate to point fingers or avoid responsibility  
**Do**: Escalate to solve problems collaboratively

### ❌ "Premature Escalation"
**Don't**: Skip levels or escalate before team-level resolution attempt  
**Do**: Follow escalation levels and exhaust appropriate options first

### ❌ "Vague Escalation"
**Don't**: "This isn't working, please fix"  
**Do**: Provide context, impact, options, and recommendations

### ❌ "Escalation Hoarding"
**Don't**: Wait until crisis before escalating known issues  
**Do**: Escalate early when you see impact trajectory

### ❌ "Drive-by Escalation"
**Don't**: Tag someone in chat and expect them to solve it without context  
**Do**: Use proper escalation format and provide all necessary information

### ❌ "Escalation Shopping"
**Don't**: Escalate to multiple people simultaneously hoping someone will solve it  
**Do**: Escalate to appropriate level and follow up if needed

---

## Escalation Success Metrics

Track and improve:
- **Time to resolution** by level
- **Escalation volume** over time (trending up may indicate process issues)
- **Repeat escalations** (same issue multiple times)
- **Escalation patterns** (which types, which teams)
- **Escalation satisfaction** (was it resolved effectively?)

---

## When the Escalation Process Isn't Working

If escalations are consistently slow, ineffective, or causing frustration:
1. Raise in retrospective
2. Review escalation log for patterns
3. Adjust timeframes or escalation paths
4. Clarify decision-making authority
5. Improve escalation training for team
6. Consider if underlying process issues need addressing

**Remember**: The goal is to solve problems efficiently, not to create bureaucracy. If the process becomes a blocker itself, adapt it.

---

## Quick Reference Card

```
┌─────────────────────────────────────────────────────┐
│            ESCALATION QUICK REFERENCE               │
├─────────────────────────────────────────────────────┤
│ Level 0: Peer-to-Peer (Immediate)                  │
│ → Team chat or quick huddle                        │
│                                                     │
│ Level 1: Team Leadership (Same Day - 1 Day)        │
│ → Scrum Master, Tech Lead                          │
│ → Daily standup or team channel                    │
│                                                     │
│ Level 2: Project Leadership (1-3 Days)             │
│ → Project Manager, Product Manager                 │
│ → Use escalation template                          │
│                                                     │
│ Level 3: Stakeholder/Executive (3-5 Days)          │
│ → PM escalates with business impact analysis       │
│                                                     │
│ Emergency: IMMEDIATE                                │
│ → Follow incident response runbook                 │
│ → Notify on-call                                   │
└─────────────────────────────────────────────────────┘
```

---

## FAQs

**Q: Will I get in trouble for escalating?**  
A: No. Appropriate escalation is encouraged and shows good judgment. It's far better to escalate early than to let issues fester.

**Q: How do I know if I'm escalating too much?**  
A: If you're escalating multiple times per day or skipping peer/team-level resolution, you might be over-escalating. Check with your Scrum Master or PM.

**Q: What if I escalate and nothing happens?**  
A: Follow up after the expected timeframe. If still no response, escalate to the next level with a note that previous escalation was not addressed.

**Q: Can I escalate directly to Level 3 if it's urgent?**  
A: Only for true emergencies. Otherwise, going through levels ensures proper context and empowers decision-makers at appropriate levels.

**Q: What if I escalated to the wrong person?**  
A: They should redirect you to the right person. Learn from it and adjust for next time.

**Q: Do I need to use the formal templates for Level 1 escalations?**  
A: No, Level 1 can be informal (standup mention, chat message). Use templates for Level 2+.
