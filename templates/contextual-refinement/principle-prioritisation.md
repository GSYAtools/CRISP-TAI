# Principle Prioritisation

This document records how **trustworthiness principles are prioritised, balanced, and constrained**
for a specific AI system within its operational and organisational context.

It supports **Contextual Refinement rule CR.3** and is closely related to:
- `context-description.md`
- `responsibility-map.csv`
- `assumption-log.md`

The purpose of this artefact is **not** to define universal priorities, but to make
*context-dependent prioritisation decisions explicit, traceable, and revisable*.

---

## 1. Scope of prioritisation

Briefly describe the scope for which this prioritisation applies.

- System or component:
- Lifecycle phase(s):
- Decision context (e.g., deployment, evaluation, monitoring):
- Date of prioritisation:

---

## 2. Relevant trustworthiness dimensions

List the trustworthiness dimensions considered relevant in this context.
(Use the dimensions defined in the CRISP-TAI framework.)

For each dimension, specify:
- Priority level
- Rationale
- Dependencies or constraints
- Responsible role

### Example table

| Dimension | Priority | Rationale | Constraints / Dependencies | Responsible role |
|----------|----------|-----------|----------------------------|------------------|
| Lawfulness | High | Regulated environment | GDPR compliance required | Legal Officer |
| Fairness | Medium | Indirect user impact | Data availability | Data Owner |
| Transparency | High | Human oversight required | Model complexity | ML Engineer |
| Robustness | Medium | Operational stability | Monitoring capacity | Operations Lead |

---

## 3. Trade-offs and tensions

Describe known or anticipated tensions between trustworthiness dimensions.

For each identified trade-off:
- Dimensions involved
- Nature of the tension
- Decision taken
- Rationale
- Escalation path (if applicable)

Example:
- Fairness vs performance
- Transparency vs intellectual property
- Privacy vs data utility

---

## 4. Decision rationale

Summarise the reasoning behind the prioritisation decisions.

Consider:
- Organisational objectives
- Regulatory constraints
- Risk tolerance
- Stakeholder expectations

This section should provide enough detail to support **later review or audit-readiness**.

---

## 5. Review and revision triggers

Specify conditions under which this prioritisation must be revisited.

Examples:
- Regulatory updates
- New deployment contexts
- Significant changes in data or models
- Operational incidents or monitoring signals

Link these triggers to entries in `assumption-log.md` where appropriate.

---

## 6. Versioning and approval

- Document owner:
- Approving role or body:
- Date approved:
- Review frequency:
- Revision history summary:

---

## Notes

This artefact is intentionally **context-specific** and **non-normative**.
Different systems, domains, or lifecycle phases may legitimately lead to different
prioritisation outcomes.

The value of this document lies in **making prioritisation explicit**, not in enforcing
uniform priorities across projects.

