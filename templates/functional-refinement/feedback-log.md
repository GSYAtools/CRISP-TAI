# Feedback Log

This document records **feedback signals, review outcomes, and resulting actions**
related to trustworthiness throughout the system lifecycle.

It supports **Functional Refinement rule FR.4 (Iterative Feedback Integration)**
and provides the operational link between monitoring, evaluation, and contextual revision.

The purpose of this artefact is to ensure that trustworthiness-related insights
obtained during evaluation, deployment, or operation are **systematically captured,
interpreted, and propagated** into subsequent refinement cycles.

---

## 1. Scope and ownership

- System or component:
- Lifecycle phase(s):
- Document owner:
- Responsible role:
- Date created:

---

## 2. Feedback sources

List the sources from which feedback may originate.

Examples include:
- Monitoring signals (see `monitoring-plan.md`)
- Evaluation results
- Audit or review findings
- Incident reports
- User or stakeholder feedback
- Regulatory or policy updates

---

## 3. Feedback entries

Each feedback item should be recorded as a discrete entry.

### Example table

| Feedback ID | Source | Description | Trustworthiness concern | Triggered by | Date |
|-------------|--------|-------------|--------------------------|--------------|------|
| F-01 | Monitoring | Drift detected in subgroup outcomes | Fairness | Monthly review | 2025-03-10 |
| F-02 | Legal review | New regulatory guidance issued | Lawfulness | Regulation update | 2025-04-02 |
| F-03 | User feedback | Lack of explanation clarity | Transparency | Support tickets | 2025-04-15 |

---

## 4. Assessment and interpretation

For each feedback entry, document:

- Initial assessment
- Potential impact on trustworthiness priorities or assumptions
- Need for escalation or immediate action

This assessment should involve the roles identified in `responsibility-map.csv`.

---

## 5. Resulting actions

Record actions taken in response to feedback.

Examples:
- Revision of contextual assumptions (`assumption-log.md`)
- Update of trustworthiness priorities (`principle-prioritisation.md`)
- Modification of artefacts (`artefact-derivation.md`)
- Operational adjustment (`monitoring-plan.md`)

### Example table

| Feedback ID | Action taken | Artefact updated | Responsible role | Date |
|-------------|--------------|------------------|------------------|------|
| F-01 | Triggered bias review | assumption-log.md | Data Owner | 2025-03-20 |
| F-02 | Updated legal interpretation | context-description.md | Legal Officer | 2025-04-05 |

---

## 6. Closure and follow-up

Indicate how feedback items are closed and tracked.

- Closure criteria:
- Follow-up required:
- Status (Open / In progress / Closed):
- Review notes:

---

## 7. Revision history

| Date | Change description | Approved by |
|------|--------------------|-------------|

---

## Notes

This feedback log is a **living artefact**.
Its purpose is not to optimise individual metrics, but to support
continuous learning, accountability, and lifecycle-level governance.
