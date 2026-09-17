# SkillLoop

SkillLoop is an AI-assisted employee skill-evidence and manager-review platform. Employees submit quarterly goals and project summaries. The system generates evidence-linked skill suggestions and a feedback draft, while managers remain responsible for all final review decisions.

## MVP workflow

```text
Employee goal + project summary
        → AI evidence-linked draft
        → manager review
        → confirmed feedback and team skill map
```

## Technology plan

- Frontend: React and TypeScript
- Backend: FastAPI and Python
- Database: PostgreSQL
- AI: LLM API with structured, evidence-linked responses
- Tests: Pytest, React Testing Library, and Playwright

## Project documentation

- [Product requirements](docs/product-requirements.md)
- [Sprint 1 product foundation](docs/sprint-01-product-foundation.md)
- [Development workflow](docs/development-workflow.md)
- [Product backlog](docs/product-backlog.md)

## Responsible-AI principles

- AI output is a draft, never an official performance decision.
- Every proposed skill must include source evidence from the employee submission.
- Managers approve, edit, reject, or request more evidence for every official claim.
- The MVP uses synthetic data only.

## Status

The project is in Sprint 1: product foundation and planning.
