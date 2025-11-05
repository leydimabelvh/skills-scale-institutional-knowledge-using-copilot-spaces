# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs:
  - **Engineering stakeholders**: Engineering Lead, Developers, QA/Test
  - **Product stakeholders**: Product Manager, UX Designer
  - **Process stakeholders**: Scrum Master, PM
  - **External stakeholders**: Compliance/Regulatory, Support/Customer Success, Sales, Leadership
- Provide regular updates (weekly or milestone-based)
  - PM owns status communication to all stakeholder groups
  - Support/Customer Success receives early notification of customer-facing changes
  - Compliance/Regulatory included in reviews for regulated features
- Use a single source of truth (project README or release doc) for status

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
