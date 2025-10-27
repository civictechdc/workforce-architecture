# Volunteer Workforce Synthesis

Two-phase approach to aggregate workforce architecture from messy sources.

## What It Does

Takes fragmented info (meeting notes, FigJam boards, Slack, screenshots) → produces unified workforce map.

Shows who does what, where work lives, what's unassigned/overloaded, what's automatable.

## Two Phases

### Phase 1: Structure (Taxonomy)
Define the buckets and categories. What types of things exist?

File: `structure-schema.json`

Establishes:
- Domain categories (Operations, Projects, etc.)
- Work attributes (name, frequency, criticality, etc.)
- Person types (volunteer, staff, partner)
- Gap types (unassigned, single-point-of-failure, overload)
- Automation criteria (impact/effort)

### Phase 2: Lattice (Data)
Populate with actual facts. Who, what, when.

File: `lattice-schema.json`

Contains:
- Actual domains with descriptions
- Work items with assignments
- People with contact info
- Detected gaps
- Automation opportunities

## Workflow

1. **Review each source doc** (incubator-10-27-25.md, ai-working-group-10-27-25.md, figjam screenshots)
2. **Update structure schema** as new categories emerge
3. **Agree on structure** before filling lattice
4. **Populate lattice** with actual roles/tasks/people
5. **Generate gap analysis** (unassigned, overloaded, single-owner critical work)
6. **Flag automation candidates** (high-frequency, low-skill, high-impact)

## Five Buckets

**Domains**: Functional areas (Operations, Projects, Infrastructure, Partnerships)

**Work**: Tasks, responsibilities, roles. Who's assigned, frequency, hours, critical?, automatable?

**People**: Names and types (volunteer, staff, partner, contractor)

**Gaps**: Unassigned critical work, single points of failure, overloaded people

**Automation**: AI/automation pilots with impact/effort estimates

## Anti-Patterns Detected

- Critical work with one person (single point of failure)
- Person with multiple critical assignments (burnout risk)
- High-frequency manual work (automation candidate)
- Work with no owner (orphaned)

## Related Docs

- `ai-working-group-10-27-25.md`: AI pilot ideas
- `incubator-10-27-25.md`: Project framework
- `figjam/`: Visual responsibility maps
