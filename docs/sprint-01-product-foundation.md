# SkillLoop — Sprint 1: Product Foundation

## MVP outcome

An employee submits a quarterly goal and project summary. SkillLoop generates evidence-linked skill suggestions and a feedback draft. A manager reviews the evidence, then approves, edits, rejects, or requests more evidence. Only manager-confirmed skills appear in the team skill map.

## MVP scope

### Included

- Employee and Manager authentication
- Quarterly goals
- Project-summary submission
- AI skill suggestions with supporting excerpts
- AI feedback draft
- Manager review actions
- Team skill map
- Synthetic demo data

### Excluded

- HR Admin portal
- GitHub, Slack, or other integrations
- Peer feedback
- Learning recommendations
- Numeric performance scores
- Real employee data

## User roles

### Employee

An individual contributor who records goals and project work, reviews AI suggestions, and responds when a manager requests more evidence.

**Primary needs:** make work visible, understand the skills demonstrated, and receive clear review feedback.

### Engineering Manager

A manager responsible for reviewing direct-report submissions and confirming evidence before it is used in team-level views.

**Primary needs:** review work efficiently, retain decision control, and understand confirmed team skill coverage.

## Primary user journeys

### Employee journey

1. Signs in to the employee workspace.
2. Creates or updates a quarterly goal.
3. Adds a project summary, personal contribution, and outcome.
4. Submits the summary for review.
5. Views AI-generated skill suggestions, evidence excerpts, and draft feedback.
6. If requested, adds further evidence.
7. Views manager-approved feedback.

### Manager journey

1. Signs in to the manager workspace.
2. Opens the review queue for direct reports.
3. Reads an employee's submitted project summary.
4. Inspects the evidence excerpt for each AI-suggested skill.
5. Approves, edits, rejects, or requests more evidence.
6. Finalizes feedback.
7. Views confirmed skills in the team skill map.

## Workflow rules

- AI may only use employee-submitted project-summary text in the MVP.
- Every suggested skill must include a supporting excerpt.
- A manager must review every official feedback claim.
- "Not Demonstrated" means the current submission lacks evidence; it does not mean the employee lacks the skill.
- Only confirmed skills appear in the team skill map.

## Definition of Done for Sprint 1

- MVP scope, roles, workflow, and exclusions are documented.
- A prioritized backlog exists with acceptance criteria for the initial stories.
- Initial wireframes cover the employee and manager core workflows.
- The development repository and baseline project structure are ready for Sprint 2.
