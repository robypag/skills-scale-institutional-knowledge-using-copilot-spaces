# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone — include UX Designer for design reviews, Data Analyst for metrics review
- Sprint retrospectives — facilitated by Scrum Master, all roles participate

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers)
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- UX/Usability testing for user-facing features (UX Designer)
- Design review and implementation validation (UX Designer with Developers)
- Analytics verification to ensure metrics are instrumented correctly (Data Analyst)

## Reporting & Metrics
- Track velocity and burndown (Scrum Master)
- Monitor success metrics identified in the Project One-pager (Data Analyst)
- Use dashboards for key signals (errors, latency, usage) - maintained by Data Analyst
- Regular metric reviews with Product Manager and stakeholders
- Documentation progress tracking (Technical Writer)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates resolution)
- Level 2: Project Manager or Scrum Master escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Design blockers: UX Designer works with Product Manager to resolve
- Analytics/data blockers: Data Analyst coordinates with engineering and stakeholders

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled with all stakeholders
- [ ] Risk register updated weekly (Project Manager or Scrum Master)
- [ ] Sprint ceremonies running smoothly (Scrum Master)
- [ ] Design reviews conducted for user-facing features (UX Designer)
- [ ] Analytics dashboards set up and monitored (Data Analyst)
- [ ] Documentation updated with each release (Technical Writer)
- [ ] Team velocity and burndown tracked (Scrum Master)
