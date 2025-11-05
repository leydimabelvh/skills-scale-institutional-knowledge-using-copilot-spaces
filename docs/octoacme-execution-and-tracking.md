# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups** (15 min) — facilitated by Scrum Master; focus on progress, blockers, dependencies
  - Participants: Developers, QA/Test, UX Designer, Engineering Lead (as needed)
- **Weekly delivery sync** — PM shows progress, updates, and flagged risks
  - Participants: PM, Product Manager, Engineering Lead, Scrum Master, stakeholders as needed
- **Demo/Review** at the end of each sprint or milestone
  - Scrum Master facilitates; UX Designer and Developers demo user-facing changes
  - QA/Test validates acceptance criteria; Product Manager provides feedback
  - Compliance/Regulatory reviews if applicable

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
  - Scrum Master maintains board hygiene and flow
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - **Code review** by peer Developer and Engineering Lead (for significant changes)
  - **Design review** by UX Designer (for user-facing changes)
  - Require at least one approval before merging (or team-defined policy)
  - After merge, moves to **QA** for validation by QA/Test Engineers

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup (Scrum Master facilitates)
  - Technical blockers: Engineering Lead engages
  - Design blockers: UX Designer resolves or escalates
  - Testing blockers: QA/Test Engineers coordinate with Developers
- **Level 2**: PM escalates to Product Manager and dependent teams
  - Cross-team dependencies or resource constraints
- **Level 3**: Sponsor-level escalation for business-impacting issues
  - PM and Product Manager engage executive stakeholders

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
