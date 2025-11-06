# OctoAcme — Compliance Review Checklist

## Purpose
Ensure product changes comply with legal, regulatory, and company policy requirements before release to production.

## When to Use
Compliance review is required for:
- Features that collect, store, or process customer data
- Changes to authentication, authorization, or security controls
- Features subject to industry regulations (GDPR, HIPAA, SOC2, etc.)
- Changes to terms of service, privacy policies, or consent flows
- Features that may have legal or regulatory implications

## Compliance Review Process

### 1. Early Identification
- [ ] PM identifies compliance requirements during project initiation
- [ ] Compliance/Regulatory Stakeholder added to project team
- [ ] Compliance requirements documented in project one-pager

### 2. Pre-Review Preparation
- [ ] Feature specification and technical design completed
- [ ] Data flow diagrams created (if handling sensitive data)
- [ ] Security and privacy impact assessment conducted
- [ ] Relevant policies and regulations identified

### 3. Review Participants
Required:
- Compliance/Regulatory Stakeholder (lead reviewer)
- PM (context provider)
- Engineering Lead (technical details)

Optional (as needed):
- Product Manager (business requirements)
- Security team representative
- Legal counsel (for legal questions)

### 4. Compliance Review Checklist

#### Data Privacy & Protection
- [ ] Personal data collection is necessary and documented
- [ ] User consent mechanisms in place (where required)
- [ ] Data retention policies followed
- [ ] Data deletion/export capabilities provided (where required)
- [ ] Privacy policy updated to reflect new data practices
- [ ] Cross-border data transfer requirements met

#### Security & Access Control
- [ ] Authentication and authorization properly implemented
- [ ] Sensitive data encrypted in transit and at rest
- [ ] Access controls follow principle of least privilege
- [ ] Audit logging in place for sensitive operations
- [ ] Security vulnerabilities addressed

#### Regulatory Compliance
- [ ] Industry-specific regulations identified and addressed
- [ ] Required disclosures and notices implemented
- [ ] Compliance documentation updated
- [ ] Training materials prepared for compliance-sensitive features

#### Documentation & Audit Trail
- [ ] Compliance decisions documented
- [ ] Risk assessment completed and approved
- [ ] Audit trail maintained for compliance-related changes
- [ ] Evidence collected for compliance audits

### 5. Review Outcomes
- **Approved**: Change meets all compliance requirements
- **Approved with conditions**: Minor adjustments needed, documented as requirements
- **Not approved**: Significant compliance issues, requires redesign or mitigation

### 6. Post-Release Compliance
- [ ] Monitor for compliance-related issues or incidents
- [ ] Update compliance documentation as needed
- [ ] Track compliance metrics (if applicable)
- [ ] Schedule periodic compliance reviews

## Compliance Review Template

**Feature/Change**: [Name and link to issue/PR]

**Release Date**: [Planned release date]

**Compliance Reviewer**: [Name]

**Review Date**: [Date]

### Applicable Regulations/Policies
- [ ] GDPR
- [ ] HIPAA
- [ ] SOC2
- [ ] CCPA
- [ ] [Company Policy Name]
- [ ] [Other]

### Data Handling
**Types of data collected/processed**: [List data types]

**Data storage location**: [Where data is stored]

**Data retention period**: [How long data is kept]

**Data access controls**: [Who can access and how]

### Compliance Findings
| Issue ID | Severity | Description | Mitigation | Status |
|----------|----------|-------------|------------|--------|
| [ID]     | [H/M/L]  | [Issue]     | [Action]   | [Open/Resolved] |

### Approval Decision
- [ ] Approved
- [ ] Approved with conditions (see findings above)
- [ ] Not approved (requires changes)

**Reviewer Signature**: [Name, Date]

**Additional Comments**: [Any additional notes or recommendations]

---

_This checklist supports the Compliance Review process introduced with the Compliance/Regulatory Stakeholder role. See [Roles and Personas](octoacme-roles-and-personas.md) for more details. Related to [Issue #6](https://github.com/leydimabelvh/skills-scale-institutional-knowledge-using-copilot-spaces/issues/6)._
