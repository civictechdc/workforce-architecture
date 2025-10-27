# Structure Schema Updates - Synthesis from FigJam Review

## Changes Made

### Domains (7 → 10)

**Added:**
- **Advisory Services** - Technical, UX, Product/PM, Marketing, Fundraising advisors providing project guidance
- **Financial Management & Compliance** - Taxes, filing, budgeting, forecasting, reimbursement (extracted from Board & Governance)
- **Fundraising & Development** - Grants, donations, sponsors, in-kind contributions (extracted from Board & Governance)

**Renamed:**
- "Member Coordination" → **"Member & Volunteer Coordination"** - Clarifies includes volunteer oversight
- "Project Incubation" → **"Project Incubation & Management"** - Captures both starting projects (kickoff, scope) and ongoing management (tracking, coaching, unblocking)

**Kept:**
- Partnerships & Outreach
- Operations & Events
- Infrastructure & SysAdmin
- Marketing & Communications
- Board & Governance (now focused on governance/strategy, not operations)

### Person Types (6 → 7)

**Added:**
- **"organizer"** - Core organizers with ongoing leadership responsibilities (distinct from occasional volunteers)

### Work Properties (6 → 9)

**Added:**
- **"tools"** - Platforms/services used (Slack, Lu.ma, AWS, GitHub) - helps identify tool dependencies and training needs
- **"knowledgeManagement"** - Involves documentation/standardization work (jargon docs, historical context, role definitions)
- **"dependencies"** - What other work this depends on - helps sequence tasks and identify blockers

### Gap Types (4 → 5)

**Added:**
- **"critical-need"** - Urgent gaps requiring immediate attention (distinct from general "unassigned")

## Key Findings from FigJam Review

### Heavy Workload Concentration
**Alma Trotter** appears 6+ times across partnerships, fundraising, financial compliance, member coordination.
**Helen** appears 8+ times in advisory roles, sustainability, project guidance.
**Kurian** appears 7+ times across financial, project guidelines, infrastructure.
**Michael Deeb** appears 5+ times in partnerships, project coaching, marketing, events.

→ Multiple single-points-of-failure detected.

### Work Distribution Patterns

**Operations are split:**
- Strategic/governance work (Board & Governance)
- Day-to-day financial operations (Financial Management & Compliance)
- Resource acquisition (Fundraising & Development)
- Community building (Partnerships & Outreach, Operations & Events)

**Projects have two distinct phases:**
- Starting projects: scope, guidelines, expectations, kickoff (Incubation)
- Running projects: tracking, coaching, unblocking, updates (Management)

**Advisory services are structured:**
- 5 advisor types identified: Technical, UX, Product/PM, Marketing, Fundraising
- Office hours mentioned (Tues 6-8pm Technical, Wed 6-8pm PM, Thu 6-8pm UX)
- Distinct from doing the work vs. guiding others

### Critical Infrastructure Dependencies

**Tools mentioned:**
- Slack (communication, moderation)
- Lu.ma (event management)
- AWS (infrastructure)
- GitHub (code, permissions, projects)
- Google Workspace (docs, drive)
- Meetup.org (events)
- Canva, Hugging Face (design, AI tools)

**Access/permission management is critical work** - ensuring multiple people can access critical systems.

### Automation Opportunities Identified

High-frequency, manual work suitable for AI pilots:
- Meeting notes and action item tracking
- Email inquiry response and triage
- Social media cross-posting
- Event RSVP insights
- Volunteer matching to projects
- Project activity tracking
- Documentation generation
- GitHub issue triage

## Next Steps

1. **Review updated structure** - Confirm 10 domains make sense
2. **Populate lattice** - Extract actual work items from docs/images
3. **Map people to work** - Build responsibility matrix
4. **Generate gap analysis** - Identify overload, single-points-of-failure, unassigned critical work
5. **Prioritize automation** - High-impact, low-effort quick wins

## People Identified (for lattice population)

- Alma Trotter/Trott
- Helen
- Michael Deeb (President)
- Kurian
- ejtung/ejlung
- Evan Tung
- Andrew
- Amy Trotter
- Nathan Arrington (AI pilot owner)

## Domain Definitions for Lattice

**Partnerships & Outreach** - External relationships, civic tech network, community building, partner org coordination

**Member & Volunteer Coordination** - Recruiting, skills matching, volunteer tracking, communication, retention

**Project Incubation & Management** - Starting new projects (scope, guidelines, kickoff) + ongoing management (tracking, coaching, unblocking)

**Advisory Services** - Expert guidance (technical, UX, product, marketing, fundraising) for projects, office hours

**Operations & Events** - Meetups, hackathons, workshops, alternative events (trivia, happy hours), event logistics

**Infrastructure & SysAdmin** - Website, Slack, GitHub, AWS, backups, access management, tool administration

**Marketing & Communications** - Social media, blog, branding, design assets, project outreach

**Financial Management & Compliance** - Taxes, business filing, budgeting, forecasting, reimbursement, financial records

**Fundraising & Development** - Grants, donations, corporate sponsors, in-kind contributions (food, venue)

**Board & Governance** - Strategy, sustainability planning, nonprofit visioning, governance oversight
