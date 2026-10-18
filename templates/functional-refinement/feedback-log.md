# Feedback Log

This template records **evaluation, monitoring, review, and operational evidence**
that may require reconsideration of existing contextual interpretations or
engineering representations.

It primarily supports:

- **FR.4 — Iterative Feedback Integration**

It also provides traceable input to:

- **CR.5 — Context Revision Trigger**, where assumptions, constraints,
  priorities, or governance interpretations require reconsideration
- Subsequent Functional Refinement, where affected engineering
  representations must be revised following contextual reconsideration

The purpose of this artefact is to preserve an explicit
**evidence-to-decision chain** connecting observed evidence, affected
contextual interpretations and engineering representations, revision
decisions, and resulting engineering updates.

---

## 1. Log information

- Feedback log ID:
- System or component:
- Document owner:
- Responsible operational or monitoring role(s):
- Accountable role:
- Date created:
- Last revision date:
- Related monitoring plan:
- Related context record(s):

---

## 2. Evidence sources

Feedback may originate from:

- Monitoring evidence (`monitoring-plan.md`)
- Evaluation results
- Review findings
- Incident reports
- User or stakeholder feedback
- Changes in operating conditions
- Changes in data or system behaviour
- Regulatory or policy changes
- Organisational changes
- Evidence challenging a documented assumption

The presence of feedback does not by itself imply that contextual or
engineering revision is required. The evidence must first be assessed against
the existing refinement records.

---

## 3. Feedback entries

Record each relevant item of evidence as a discrete entry.

| Feedback ID | Evidence source | Evidence / observation | Trustworthiness concern | Trigger / collection condition | Date | Responsible role | Status |
|---|---|---|---|---|---|---|---|
| EXAMPLE-F01 | Operational monitoring and user feedback | Explanations are unavailable or considered unsuitable for some outputs requiring human review | Transparency | Explanation monitoring condition | YYYY-MM-DD | Operations Owner | Open |
| EXAMPLE-F02 | Regulatory review | New authoritative guidance may affect the existing contextual interpretation | Lawfulness | Regulatory change | YYYY-MM-DD | Governance / Legal Owner | Open |

The example rows are illustrative. Replace or remove them when using the
template.

---

## 4. Assessment against existing refinement records

For each feedback entry, identify the existing contextual and engineering
elements potentially affected by the evidence.

- Feedback ID:
- Existing contextual interpretation or decision:
- Related contextual record ID:
- Existing assumption(s):
- Existing priority or trade-off decision:
- Existing engineering representation(s):
- Related process-specific instantiation(s), where applicable:
- Responsible reviewer(s):

### Assessment

Indicate whether the evidence suggests:

- No relevant deviation
- An unmet engineering requirement
- A required engineering adjustment
- A potentially invalid assumption
- A changed contextual constraint
- A priority or trade-off requiring reconsideration
- A governance interpretation requiring reconsideration
- A continuity or monitoring issue

- Assessment rationale:
- Supporting evidence:

This assessment constitutes the first step of **FR.4 — Iterative Feedback
Integration**.

---

## 5. Context revision decision

Where the evidence challenges an assumption, constraint, priority, or
governance interpretation, record whether **CR.5 — Context Revision Trigger**
is invoked.

- Feedback ID:
- CR.5 invoked:
  - Yes
  - No
- Contextual element affected:
- Related assumption record:
- Related prioritisation record:
- Responsible contextual owner:
- Revision decision:
  - Retain
  - Update
  - Reconsider through a new refinement cycle
  - Not applicable
- Decision rationale:
- Updated contextual interpretation or decision, where applicable:
- Related context revision record:

FR.4 does not itself redefine the contextual interpretation. Where contextual
reconsideration is required, that decision is handled through CR.5 and the
relevant Contextual Refinement records.

---

## 6. Engineering update decision

Determine whether the evidence or resulting contextual revision requires an
engineering representation to be introduced or changed.

- Feedback ID:
- Engineering update required:
  - Yes
  - No
- Engineering representation ID(s) affected:
- New representation required:
  - Yes
  - No
- Representation to be revised:
- Required engineering response:
- Applicable FR rule(s):
- Responsible engineering role:
- Related `engineering-representation.md` record:
- Decision rationale:

Where an operational adjustment is required, apply **FR.3 — Operational
Adjustment** to derive or revise the Engineering Representation specifying the
required change.

Where contextual reconsideration has occurred, affected Engineering
Representations should be updated through subsequent Functional Refinement.

---

## 7. Process-specific propagation

Where an Engineering Representation has been added or revised, identify any
existing process-specific instantiation that may require corresponding update.

- Feedback ID:
- Engineering representation ID:
- Existing instantiation ID:
- Existing lifecycle artefact or operational configuration:
- Re-instantiation required:
  - Yes
  - No
- Updated instantiation ID:
- Updated lifecycle artefact or operational configuration:
- Responsible lifecycle owner:
- Related traceability record:

This section records the propagation of a revised Engineering Representation
to its process-specific enactment. It does not make the lifecycle mapping part
of FR.4 itself.

---

## 8. Evidence-to-decision trace

Summarise the complete feedback chain.

| Feedback ID | Evidence | Affected contextual element | Affected engineering representation | CR.5 decision | Engineering update | Instantiation update | Traceability record |
|---|---|---|---|---|---|---|---|
| | | | | | | | |

This table should allow reconstruction of the relationship between the
observed evidence, the resulting revision decision, affected contextual
interpretations, and downstream engineering updates.

---

## 9. Closure and follow-up

A feedback item should be closed only when the required assessment and
resulting decisions have been documented.

- Feedback ID:
- Closure criteria:
- Required contextual revision completed:
- Required engineering update completed:
- Required process-specific update completed:
- Follow-up monitoring required:
- Responsible role:
- Closure date:
- Status:
  - Open
  - In progress
  - Closed
- Closure evidence:
- Review notes:

---

## 10. Versioning and ownership

- Document owner:
- Accountable role:
- Current version:
- Date created:
- Last revision date:

### Revision history

| Version | Date | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|
| | | | | |

---

## Notes

This feedback log is a **living refinement artefact**.

Its purpose is not to optimise individual metrics or automatically determine
whether the system is trustworthy. It preserves the relationship between
operational or evaluation evidence and the refinement decisions that follow.

The expected feedback path is:

**Evidence → FR.4 assessment → CR.5 where contextual reconsideration is
required → updated contextual decision → subsequent Functional Refinement →
revised Engineering Representation → updated Process Instantiation**

Where contextual reconsideration is not required, evidence may still result in
an engineering adjustment through FR.3 or in continuity-related action through
FR.6.

The log should preserve enough evidence to make this chain traceable and
independently inspectable.
