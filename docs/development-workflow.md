# Development Workflow

## Delivery model

SkillLoop uses Scrum with two-week sprints. GitHub is the canonical place for requirements, issues, source code, reviews, releases, and project documentation.

## GitHub workflow

1. Create or select a backlog issue before implementation.
2. Assign the issue to a sprint and add acceptance criteria.
3. Create a focused branch from `develop` using `feature/<issue-number>-short-name`, `fix/<issue-number>-short-name`, or `docs/<issue-number>-short-name`.
4. Make small, clear commits that reference the issue, for example `feat: add quarterly goal form (#12)`.
5. Open a pull request using the repository template.
6. Ensure automated checks pass and review acceptance criteria before merging.
7. Squash merge the pull request into `develop`, close the issue, and update the GitHub Project board.
8. At the end of a tested sprint or release cycle, open a release pull request from `develop` to `main`.

## Branch model

```text
main (stable, releasable code)
  └── develop (sprint integration branch)
        └── feature/<issue-number>-short-name (one focused issue)
```

Never commit directly to `main` or `develop`. Feature branches merge into `develop` through pull requests. `develop` merges into `main` through a reviewed release pull request.

## Branch protection

Configure these GitHub repository rules for both `main` and `develop`:

- Require a pull request before merging.
- Require at least one approval when working with collaborators.
- Require passing CI checks.
- Require resolved review conversations.
- Block force pushes and direct pushes.

## Definition of Done

- Acceptance criteria are met.
- Relevant unit, API, or end-to-end tests pass.
- Code has been reviewed through a pull request.
- Documentation is updated when behavior or setup changes.
- No secrets, real employee data, or sensitive sample data are committed.

## Repository structure

```text
docs/          Product, architecture, and delivery documents
frontend/      React application (Sprint 2)
backend/       FastAPI application (Sprint 2)
infra/         Local development and deployment configuration (later)
.github/       Issue templates, pull-request template, and CI workflows
```
