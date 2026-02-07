# Monitoring Plan

This document specifies how **trustworthiness-related considerations** are monitored and reviewed
during system deployment and operation, in accordance with **Functional Refinement rule FR.3
(Operational Adjustment)** and **FR.6 (Continuity Enforcement)**.

The purpose of this artefact is to ensure that trustworthiness-related decisions remain
**observable, revisable, and actionable over time**, without reducing trustworthiness
to fixed metrics or automated compliance checks.

---

## 1. Scope and context

- System or component:
- Deployment environment:
- Lifecycle phase(s):
- Responsible role:
- Date created:

---

## 2. Trustworthiness concerns to monitor

List the trustworthiness dimensions and concerns that require monitoring in this context.

Examples:
- Lawfulness (e.g., usage constraints, regulatory conditions)
- Fairness (e.g., drift affecting protected groups)
- Transparency (e.g., availability of explanations)
- Robustness and safety (e.g., anomalous behaviour)
- Accountability (e.g., responsibility handovers)

---

## 3. Monitoring signals and indicators

For each concern, identify **signals or indicators** that can inform review.

Indicators may be:
- Quantitative (metrics, thresholds, alerts)
- Qualitative (reviews, complaints, incident reports)
- Procedural (checkpoints, audits, governance reviews)

### Example table

| Trustworthiness concern | Signal / Indicator | Source | Review frequency | Responsible role |
|-------------------------|-------------------|--------|------------------|------------------|
| Fairness | Distribution shift in outcomes | Logs | Monthly | Operations Lead |
| Lawfulness | New regulatory guidance | Legal review | On update | Legal Officer |
| Transparency | User complaints | Support tickets | Quarterly | Product Owner |

---

## 4. Review and escalation process

Describe how monitoring results are reviewed and acted upon.

- Review forum or body:
- Escalation path:
- Decision authority:
- Documentation of outcomes:

Link this section to entries in:
- `feedback-log.md`
- `assumption-log.md`

---

## 5. Operational adjustments

Specify potential operational responses to monitoring outcomes.

Examples:
- Model retraining or rollback
- Update of usage constraints
- Changes in human oversight
- Revision of trustworthiness priorities

Operational adjustments should be traceable to decisions in:
- `traceability-matrix.csv`
- `artefact-derivation.md`

---

## 6. Continuity and lifecycle integration

Describe how monitoring is sustained across:
- System updates
- Organisational changes
- Long-term operation

Ensure that monitoring responsibilities and artefacts remain active and
are transferred appropriately when roles or teams change.

---

## 7. Versioning and review

- Document owner:
- Review frequency:
- Last review date:
- Next planned review:

---

## Notes

This monitoring plan is a **living artefact**.
Its role is to support continuous awareness and governance, not to enforce
static compliance or optimise isolated metrics.
