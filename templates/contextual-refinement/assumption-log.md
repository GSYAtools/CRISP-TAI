# Assumption Log

This document records **contextual and operational assumptions** underlying trustworthiness-related
decisions made during the AI system lifecycle.

It supports **Contextual Refinement rules CR.4 (Assumption Documentation)** and **CR.5 (Context Revision Trigger)**
by making assumptions explicit, traceable, and revisable over time.

Assumptions documented here should be reviewed periodically and updated whenever relevant
revision triggers occur.

---

## 1. Purpose and scope

- System or component:
- Lifecycle phase(s):
- Date created:
- Document owner:

---

## 2. Assumption register

Each assumption should be documented as a discrete entry.
Use one row per assumption.

### Example table

| Assumption ID | Description | Assumption Type | Rationale | Related Decisions / Artefacts | Risk if Invalid | Review Trigger | Status |
|--------------|-------------|-----------------|-----------|-------------------------------|-----------------|----------------|--------|
| A-01 | Training data remains representative | Data | Historical stability of source | model-design.md | Bias, performance degradation | Data drift detected | Active |
| A-02 | Human operators will review alerts | Human / Organisational | SOP mandates review | monitoring-plan.md | Missed incidents | Operator workload change | Active |
| A-03 | Legal interpretation remains valid | Legal / Regulatory | Current guidance | context-description.md | Non-compliance | Regulatory update | Active |

---

## 3. Assumption types (guidance)

Typical assumption categories include:

- **Data-related** (e.g., data quality, stability, representativeness)
- **Model-related** (e.g., performance stability, explainability sufficiency)
- **Human and organisational** (e.g., user behaviour, oversight capacity)
- **Legal and regulatory** (e.g., interpretation of applicable laws)
- **Operational** (e.g., monitoring effectiveness, incident response)

This categorisation is indicative and may be adapted to local contexts.

---

## 4. Review and revision process

For each assumption, specify:

- How the assumption is monitored or reviewed
- What signals indicate potential invalidation
- Who is responsible for reassessment
- Which artefacts must be updated if the assumption changes

Assumption revisions should be logged with timestamps and justification.

---

## 5. Revision history

| Date | Assumption ID | Change description | Reason | Approved by |
|------|---------------|-------------------|--------|-------------|

---

## Notes

This log is a **living artefact**.
Its role is not to eliminate uncertainty, but to make uncertainty visible and manageable.

Explicit assumptions support:
- Traceability of trustworthiness decisions
- Evaluability and audit-readiness
- Timely adaptation to contextual and operational change


