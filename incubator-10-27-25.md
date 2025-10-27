# Civic Tech DC Incubator Framework

## High-Level Framework

A volunteer-driven incubator for sustainable civic impact through **structured simplicity**. The framework matches community-identified problems with volunteer talent and ensures projects can outlive their original creators.

---

## Purpose & Principles

* **Problem-first:** Validated community needs before tech solutions  
* **Time-boxed iterations:** Quarterly cycles (\~12 weeks) with clear phases  
* **Built-in sustainability:** Plan the handoff from day one  
* **Minimal bureaucracy:** Just enough process to ensure quality  
* **Open by default:** Code, docs, and decisions are reusable and portable  
* **Burnout prevention:** Maximum 10 hrs/week guideline with rotation opportunities

---

## Participation Pathways

1. **NP-Open** — Nonprofit has a problem; needs volunteers  
2. **NP-Date** — Nonprofit has specific request with deadline/acceptance test (e.g., ElectrifyDMV grant)  
3. **VOL-Idea** — Volunteer has an idea; needs a sponsor/partner  
4. **VOL-Partnered** — Volunteer already has sponsor and manages that relationship

Each project declares **leadership mode** (Volunteer-led or Nonprofit-led). Pathways can switch via brief decision memo as conditions change.

---

## Entry Criteria

* Named nonprofit (or sponsor) point of contact with weekly availability  
* One-page **Project Brief** (problem, users, success metric, risks, realistic timeline)  
* **MoU-lite** defining roles and commitments  
* Repo scaffolded in org; agreement to open source \+ public updates  
* Data access understood (synthetic allowed early)  
* Historical check: Has anyone worked on this before?

---

## Quarterly Cycle (Lifecycle)

### Discovery (Weeks 1–2)

* Validate problem; map stakeholders and users  
* Technical feasibility check (data, integrations, constraints)  
* **Timeline triage:** Reality check on deadlines vs. volunteer availability  
* Review historical projects and volunteer expertise

### Incubation (Weeks 3–10)

* Present project and available roles needed  
* Run sprints with **scheduled review sessions:**  
  * Technical review (weekly)  
  * Product/UX review (bi-weekly)  
  * Project management check-in (weekly)  
* Testing protocols for production readiness  
* Analytics implementation where needed

### Transition (Weeks 11–12)

* Meet **review checklist** (documentation, testing, deployment)  
* Sustainability assessment (owner, runbooks, support window)  
* Leadership succession planning  
* Short retrospective (keep/change/stop)

---

## Roles & Responsibilities

### Project Level

* **Nonprofit POC (Product Owner):** Domain expertise, weekly decisions, user access  
* **Volunteer Lead (Delivery):** Technical or product leadership, cadence steward  
* **Delivery Coach:** Facilitation, unblockers, quality bar, incubator support  
* **Contributors:** Clear delineation between volunteer and org staff roles

### Support Infrastructure (with Office Hours)

* **Technical Consulting Lead**  
  * Office hours: Tuesdays 6-8pm  
  * Architecture, code review, deployment, WordPress integration  
* **Project Management Lead**  
  * Office hours: Wednesdays 6-8pm  
  * Agile coaching, timeline reality checks  
* **Product Management Lead**  
  * Monthly strategy sessions  
  * Feature prioritization, user story development  
* **UX/Design Lead**  
  * Office hours: Thursdays 6-8pm  
  * Design systems, user research, accessibility

**All leads maintain email in Slack bio and are listed in pinned channel messages**

---

## Culture & Guardrails

* **Project Code of Conduct \+ CONTRIBUTING.md** in every repo  
* Ethos: **Be kind. Don't be a jerk. Ask questions. Discussion first. Push what you have.**  
* **Governance:** Light org-level **RACI**; per-project **Maintainer Guide** (maintainers, decision process, release rules)  
* **Volunteer wellbeing:** Mandatory breaks between projects, rotation opportunities

---

## Communication Infrastructure

### Slack Standards

* Channel naming: `#proj-[name]-[year]`  
* Pinned message with all POC contacts and emails  
* Required channels per project:  
  * `#proj-[name]-general`  
  * `#proj-[name]-dev` (if technical)  
  * `#proj-[name]-design` (if applicable)

### First-Timer Path

* Dedicated **\#first-time-contributors** channel  
* Pinned **Start Here** thread in every project channel  
* Buddy system for first PR  
* **Everything counts** (docs, UX, testing, data, PM)

### Issue Labels

`good-first-issue`, `help-wanted`, `size-S/M/L`, `needs-design`, `needs-PM`, `needs-nonprofit-input`, `needs-translation`, `partner-led`, `deadline`, `acceptance-test`, `discovery`, `needs-sponsor`, `needs-testing`, `production-ready`

---

## Non-Technical Visibility

* Website **project cards** (plain language):  
  * Problem statement  
  * Who benefits  
  * Top tasks needed  
  * Roles needed with time commitment  
  * Links to repo/docs/Slack  
* Mirror essentials in each README \+ **FAQ** section  
* Consistent GitHub topics and naming  
* Cross-post help-wanted to meetups/fests/hackathons

---

## Support Infrastructure

### Technical Resources

* Shared hosting/cloud credits pool  
* Standard stack recommendations (WordPress for CMS when applicable)  
* CI/CD pipeline templates  
* Testing framework templates

### Non-Technical Resources

* PM templates and agile boards  
* User research protocols  
* Design system components  
* Grant writing technical sections support

### Project Templates

* Web apps  
* Data pipelines  
* Integration/connector  
* Static site/visualization  
* WordPress plugins/themes

---

## Required Artifacts

### Start

* Project Brief with realistic timeline assessment  
* **MoU-lite** (roles/commitments)  
* Repo scaffold with documentation structure  
* Initial roadmap  
* CONTRIBUTORS.md template

### During

* Weekly public update  
* `research/user-log.md` (historical user info)  
* Architecture sketch \+ Architecture Decision Records (ADRs)  
* Testing documentation  
* Who-worked-on-what log

### Finish

* Production readiness checklist  
* Runbook & rollback procedures  
* **Adopt in Your Org** documentation  
* 90-second demo video  
* Leadership transfer checklist \+ 10-minute repo tour  
* Handoff documentation for contractors/staff

---

## Volunteer Management System

### Onboarding

* Skills inventory form with availability  
* Time commitment agreement (max 10 hrs/week)  
* Paired first contribution  
* Access to historical project/volunteer database

### Retention & Recognition

* LinkedIn recommendations  
* Portfolio pieces and references  
* Volunteer contribution history maintained  
* Alumni network for emergency support  
* Rotation between technical and non-technical roles

### Knowledge Management

* **Volunteer history database:** Who worked on what, when  
* Skills matrix updated quarterly  
* Documentation of all code decisions  
* Repository quality standards enforced

---

## Adoption & Exit

* Name post-incubator owner (nonprofit, agency, or community maintainers)  
* Production deployment support for partner organizations  
* If not adopted, **archive cleanly** with deprecation note and revival path  
* Grant/funding transition planning where applicable

---

## Risk & Continuity

* **Volunteer management:** Time-boxed commitments; rotate reviewers; track burnout indicators  
* **Single point of failure:** Minimum two maintainers; credential management system  
* **Scope creep:** Lightweight change log; re-baseline at midpoint  
* **Partner no-show:** Escalate protocol; pause or move to umbrella mode  
* **Grant deadlines:** Buffer time built into all estimates; clear go/no-go decisions  
* **Data/privacy:** Document PII status and handling in README  
* **Production issues:** On-call rotation for first 30 days post-launch

---

## Metrics That Matter

### Conversion Funnel (per project)

Card views → repo clicks → Slack joins → first issue comment → first PR opened → first PR merged → retained at 30/60 days

### Outcome Metrics

* Partner attendance & satisfaction scores  
* Midpoint gate pass rate  
* Production deployments achieved  
* Adoption within \~60 days  
* Grant funding secured with our support  
* Reuse by other communities  
* Volunteer hours retained post-project

### Motivation Tracking

Capture **"Why are you contributing?"** on signup to segment motivations and improve retention strategies

---

## Templates & Tools

### Core Templates

* Project proposal with timeline reality check  
* Weekly check-in format  
* Handoff & adoption checklist  
* Retrospective guide  
* MoU-lite & partnership agreement templates

### Production Support

* Database cleaning protocols  
* WordPress integration guides  
* Analytics implementation checklist  
* Testing plan templates  
* Contractor handoff documentation

---

## Quick Reference

### For Non-profit Partners

1. Submit Project Brief with clear deadlines  
2. Attend weekly check-ins  
3. Provide user access and domain expertise  
4. Review deliverables at scheduled sessions  
5. Take ownership at transition

### For Volunteers

1. Check project cards for opportunities  
2. Join Slack channel and introduce yourself  
3. Pick labeled issue matching your skills/time  
4. Get buddy for first contribution  
5. Respect 10hr/week maximum

### For Delivery Coaches

1. Facilitate discovery and planning  
2. Run weekly standups  
3. Ensure documentation standards  
4. Monitor volunteer wellbeing  
5. Manage stakeholder expectations

---

*Version 1.0 \- Last Updated: \[Date\]* *Next Review: \[Quarterly\]*  
