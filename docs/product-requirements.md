# SkillLoop Product Requirements Document

## Problem

Employee work is scattered across projects, updates, and manager notes. During a review cycle, managers can miss important contributions or rely too heavily on recent work. Employees also need a clearer way to connect their work to demonstrated skills and career development.

## Product objective

Create one transparent workflow where employees submit work evidence, AI creates evidence-linked draft feedback, and managers make final review decisions.

## Users

### Employee

Creates goals, submits project summaries, views suggested skills, responds to evidence requests, and reads final feedback.

### Engineering Manager

Reviews direct-report submissions, verifies evidence, makes final feedback decisions, and views confirmed team skill coverage.

## MVP requirements

1. Employee and Manager authentication with role-based access control.
2. Employee profiles, target roles, and quarterly goals.
3. Project-summary drafts and submissions.
4. AI-generated skill suggestions with exact supporting excerpts.
5. AI-generated feedback draft based only on submitted text.
6. Manager approval, editing, rejection, and evidence-request actions.
7. An approval audit history.
8. A team skill map based only on manager-confirmed skills.
9. Review status tracking.

## Constraints

- No numerical performance score or automated employment decision.
- No access to private code, messages, or employee monitoring data.
- No real employee data in development or demonstrations.
- "Not Demonstrated" refers to missing evidence in the current submission, not the employee's ability.

## Success criteria

- A complete employee-to-manager review can be demonstrated end to end.
- Every AI skill suggestion contains a verifiable evidence excerpt.
- Confirmed team skills reflect only manager-approved evidence.
- Access-control tests prevent cross-team data access.
