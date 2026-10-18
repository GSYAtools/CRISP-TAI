# Monitoring Plan

This template documents how **trustworthiness-related engineering
representations, controls, responsibilities, and contextual assumptions** are
observed and reviewed during system operation.

It primarily supports:

- **FR.6 — Continuity Enforcement**
- **FR.4 — Iterative Feedback Integration**

It may also provide operational evidence that activates:

- **FR.3 — Operational Adjustment**
- **CR.5 — Context Revision Trigger**

The purpose of this artefact is to ensure that relevant engineering
representations and their associated responsibilities remain **observable,
traceable, revisable, and maintained over time**, without reducing
trustworthiness to fixed metrics or automated compliance checks.

---

## 1. Monitoring record

- Monitoring plan ID:
- System or component:
- Operational environment:
- Responsible monitoring role(s):
- Accountable role:
- Date created:
- Last review date:
- Related contextual record(s):
- Related engineering representation(s):
- Related process-specific lifecycle artefact(s), where applicable:

---

## 2. Monitoring scope

Identify the trustworthiness-related elements that require continued
observation.

Monitoring may concern:

- Engineering requirements or controls
- Evaluation criteria
- Contextual assumptions
- Operational constraints
- Human-oversight conditions
- Responsibility or accountability conditions
- Explanation availability or adequacy
- Data or model behaviour
- Relevant regulatory or organisational changes
- Continuity of previously instantiated controls

| Monitoring item ID | Trustworthiness concern | Element monitored | Element type | Related representation / contextual record | Reason for monitoring |
|---|---|---|---|---|---|
| EXAMPLE-M01 | Transparency | Availability and suitability of explanations for human review | Engineering representation / operational condition | EXAMPLE-ER03 / EXAMPLE-CD01 | Detect whether the documented transparency expectation remains satisfied |

The example row is illustrative. Replace or remove it when using the template.

---

## 3. Monitoring evidence and signals

For each monitored element, identify the evidence required to support review.

Evidence may be:

- Quantitative — measurements, distributions, thresholds, alerts
- Qualitative — stakeholder feedback, complaints, review observations
- Operational — incidents, failures, changes in operating conditions
- Procedural — scheduled reviews, governance decisions, responsibility changes
- Contextual — regulatory, organisational, stakeholder, or use-context changes

| Monitoring item ID | Evidence / signal | Source | Collection or review condition | Responsible role | Evidence record |
|---|---|---|---|---|---|
| EXAMPLE-M01 | Explanation unavailable or judged unsuitable for the intended operator | Operational monitoring and user feedback | On occurrence and periodic review | Operations Owner | EXAMPLE-EV01 |

Monitoring signals provide evidence for reasoning and review. They do not
automatically determine trustworthiness or prescribe a decision.

---

## 4. Continuity requirements

Use this section to document how relevant engineering representations,
responsibilities, controls, and monitoring mechanisms remain active throughout
operation and system evolution.

| Element ID | Element requiring continuity | Owner | Monitoring obligation | Review obligation | Update condition | Continuity evidence |
|---|---|---|---|---|---|---|
| | | | | | | |

Consider:

- Continued ownership after deployment
- Responsibility handovers
- Persistence across system updates
- Monitoring after model or data changes
- Preservation of relevant controls
- Continued traceability
- Periodic or event-triggered review
- Conditions requiring update or retirement

This section primarily supports **FR.6 — Continuity Enforcement**.

---

## 5. Evidence review

When relevant monitoring evidence is obtained, assess it against the existing
contextual interpretations and engineering representations.

- Evidence record ID:
- Monitoring item ID:
- Date:
- Evidence observed:
- Existing contextual interpretation affected:
- Existing engineering representation affected:
- Existing assumption affected:
- Responsible reviewer(s):
- Assessment:
  - No relevant deviation
  - Engineering review required
  - Potential contextual change
  - Assumption potentially invalidated
  - Requirement or control potentially unmet
- Rationale:
- Follow-up required:

Where evidence indicates a relevant deviation, unmet requirement, invalidated
assumption, or contextual change, apply **FR.4 — Iterative Feedback
Integration**.

---

## 6. Feedback integration

Where FR.4 is activated, document the relationship between the operational
evidence and the existing refinement records.

- Feedback record ID:
- Evidence record ID:
- Affected contextual interpretation:
- Affected engineering representation:
- Affected assumption or constraint:
- FR.4 decision:
- Contextual reconsideration required:
  - Yes
  - No
- CR.5 invoked:
  - Yes
  - No
- Engineering re-refinement required:
  - Yes
  - No
- Related `feedback-log.md` entry:
- Supporting rationale:

If assumptions, constraints, priorities, or governance interpretations require
reconsideration, invoke **CR.5 — Context Revision Trigger**.

---

## 7. Operational adjustment

Where monitoring or contextual evidence indicates that an operational change
is required, document the required adjustment as an **engineering
representation** before changing its process-specific enactment.

- Adjustment record ID:
- Triggering evidence:
- Contextual or operational cause:
- Existing engineering representation affected:
- Required operational adjustment:
- New or revised engineering representation:
- Representation type:
- Responsible engineering or operational owner:
- Supporting rationale:
- Related `engineering-representation.md` record:
- Related traceability record:

This section supports **FR.3 — Operational Adjustment**.

FR.3 does not directly prescribe or execute a model retraining, rollback,
configuration change, oversight change, or other operational action. It derives
or revises the engineering representation specifying the required adjustment.
Its process-specific enactment is subsequently handled through Process
Instantiation.

---

## 8. Escalation and decision process

Describe how evidence requiring review or action is escalated.

- Review forum or responsible body:
- Escalation path:
- Decision authority:
- Expected response condition or timeframe:
- Required documentation:
- Related responsibility record:

Relevant decisions should be linked to:

- `feedback-log.md`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`

---

## 9. Process-specific monitoring instantiation

Where monitoring requirements have been instantiated through CRISP-TAI,
record the corresponding lifecycle enactment.

- Engineering representation ID:
- Instantiation ID:
- Target lifecycle location:
- Monitoring activity or control point:
- Instantiated monitoring artefact:
- Operational owner:
- Evidence produced:
- Traceability record:

This section records the result of Process Instantiation. The monitoring
requirement itself remains a process-independent engineering representation.

---

## 10. Versioning and ownership

- Document owner:
- Accountable role:
- Current version:
- Date created:
- Last review date:
- Next planned review:

### Revision history

| Version | Date | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|
| | | | | |

---

## Notes

This monitoring plan is a **living engineering artefact** supporting continuity
and feedback throughout system operation.

Its purpose is not to define universal trustworthiness metrics or automate
normative judgement. Monitoring evidence provides input to the refinement
cycle:

**Operational evidence → FR.4 → CR.5 where contextual reconsideration is
required → subsequent Functional Refinement → revised Engineering
Representation → updated Process Instantiation**

Where the required response concerns an operational adjustment, **FR.3**
expresses that adjustment as a new or revised Engineering Representation
before its process-specific enactment.
