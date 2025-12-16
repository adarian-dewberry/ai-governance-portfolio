# AI Risk Classification Model  
Aligned to NIST AI RMF and EU AI Act

## Overview
This project provides a structured method for classifying AI use cases based on risk, impact, and regulatory exposure.  
Clear risk tiers enable proportionate governance, consistent approvals, and defensible oversight.

The model is designed to integrate with existing legal, security, risk, and compliance processes rather than replace them.

---

## Why This Model Exists
As AI adoption increases, organizations struggle with inconsistent decisions about which systems require heightened scrutiny.

This model creates a shared risk language that allows teams to move quickly while maintaining accountability and auditability.

---

## How the Model Is Used
1. AI use cases are classified early in the lifecycle.
2. Each classification maps directly to governance actions.
3. Risk levels are revisited when material changes occur.
4. Decisions and rationale are documented for assurance and review.

---

## AI Risk Tiers

### Tier 1 — Low Risk
**Characteristics**
- Internal or productivity-focused use
- No automated decisions
- No sensitive or regulated data

**Example Use Cases**
- Internal summarization tools
- Non-customer-facing analytics

**Governance Requirements**
- Business owner approval
- Basic documentation
- Periodic review

---

### Tier 2 — Medium Risk
**Characteristics**
- Customer-facing or decision-support systems
- Limited personal or regulated data
- Human-in-the-loop oversight

**Example Use Cases**
- Customer service copilots
- HR screening support tools

**Governance Requirements**
- Legal and security review
- Documented safeguards
- Defined monitoring cadence

---

### Tier 3 — High Risk
**Characteristics**
- Automated or materially impactful decisions
- Regulated or sensitive data
- Financial, customer, or safety implications

**Example Use Cases**
- Eligibility determinations
- Financial recommendations or scoring

**Governance Requirements**
- Executive and risk approval
- Formal risk assessment
- Ongoing monitoring and escalation

---

### Tier 4 — Prohibited or Restricted
**Characteristics**
- Unacceptable risk under policy or regulation

**Example Use Cases**
- Uses explicitly restricted by law or internal policy

**Governance Requirements**
- Deployment blocked
- Exception process documented if applicable

---

## Alignment to Governance Standards

### NIST AI Risk Management Framework
- Govern: Risk ownership and accountability
- Map: Context and impact assessment
- Measure: Risk indicators and monitoring
- Manage: Controls, escalation, and response

### EU AI Act (Operational Alignment)
- Supports early identification of high-risk systems
- Enables readiness for conformity assessment planning
- Does not replace legal interpretation

---

## Regulated Finance Overlay
In regulated financial environments, additional considerations apply:
- Customer impact and suitability risk
- Data retention and auditability
- Second-line review for high-risk classifications
- Documentation sufficient for regulatory examination

---

## Core Artifact
**AI Risk Tiering Rubric**

| Risk Tier | Decision Impact | Data Sensitivity | Required Review | Monitoring |
|----------|-----------------|------------------|-----------------|------------|
| Low | None | Public or internal | Business owner | Periodic |
| Medium | Assisted | Limited PII | Legal and Security | Scheduled |
| High | Automated | Regulated | Executive and Risk | Continuous |
| Prohibited | N/A | N/A | Blocked | N/A |

See `ai-risk-tiering-rubric.md` for the full classification logic.

---

## Why This Matters
Clear risk classification reduces ambiguity, accelerates responsible approvals, and ensures governance decisions are defensible under audit and regulatory review.

This model enables AI adoption that is intentional, scalable, and accountable.
