# Engineering Representation

This template supports **FR.1 — Engineering Representation Derivation** when
applying the Lifecycle Refinement Framework through CRISP-TAI.

Its purpose is to document how a **contextualised trustworthiness decision** is
transformed into one or more **process-independent engineering
representations** suitable for subsequent lifecycle instantiation.

Engineering representations may include requirements, controls, design or
decision rationales, evaluation criteria, governance records, monitoring
specifications, responsibility structures, and traceability or revision
requirements.

This template documents the output of Functional Refinement. It does **not**
perform the final mapping of that output to a CRISP-DM phase, activity, or
lifecycle artefact.

---

## 1. Representation record

- Record ID:
- System or component:
- Trustworthiness concern:
- Trigger for engineering representation:
- Responsible engineering role(s):
- Supporting governance or domain role(s):
- Date created:
- Last revision date:

The trigger should identify why the contextual interpretation requires explicit
engineering representation.

---

## 2. Originating contextual decision

Identify the contextual interpretation or decision from which the engineering
representation is derived.

Typical sources include:

- `context-description.md`
- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`
- Other documented contextual or governance decisions

| Contextual record ID | Contextual decision / interpretation | Applicable constraint, priority, responsibility, or assumption | Source |
|---|---|---|---|
| EXAMPLE-CI01 | Explanations must be meaningful to the affected human operator | Intended users and expected operator knowledge constrain the required explanation | context-description.md |

The example row is illustrative. Replace or remove it when using the template.

---

## 3. Engineering representation derivation

Determine the engineering representation required to operationalise the
contextual decision without prescribing its final location within the target
software process.

| Representation ID | Contextual record ID | Representation type | Engineering representation | Rationale | Responsible role |
|---|---|---|---|---|---|
| EXAMPLE-ER01 | EXAMPLE-CI01 | Requirement | The system shall provide an explanation suitable for the intended operator for each decision requiring human review | Operationalises the contextual transparency expectation while preserving its user-related constraints | ML Engineering Owner |

Representative types include:

- Requirement
- Control
- Design rationale
- Decision rationale
- Evaluation criterion
- Governance record
- Monitoring specification
- Responsibility structure
- Traceability requirement
- Revision requirement
- Continuity requirement
- Configuration constraint
- Other engineering representation

The example row is illustrative. Replace or remove it when using the template.

---

## 4. Representation specification

For each engineering representation, provide sufficient information for it to
be subsequently instantiated without losing the meaning of the originating
contextual decision.

- Representation ID:
- Representation statement:
- Representation type:
- Originating contextual record:
- Applicable constraints:
- Relevant assumption(s):
- Responsible role(s):
- Verification or evaluation condition:
- Dependencies:
- Related engineering representation(s):
- Revision condition(s):

Do not specify a CRISP-DM phase or lifecycle artefact here unless documenting
a separate subsequent Process Instantiation record.

---

## 5. Derivation rationale

Explain why the selected engineering representation is an appropriate
operational expression of the originating contextual decision.

Document:

- Trustworthiness concern addressed:
- Contextual interpretation or decision:
- Engineering response required:
- Alternatives considered, where relevant:
- Derivation rationale:
- Supporting evidence:
- Responsible actor(s):

The rationale should allow the relationship between the contextual decision
and the engineering representation to be independently reconstructed.

---

## 6. Traceability

Record the links required to preserve the refinement chain.

- Representation ID:
- Originating trustworthiness concern:
- Contextual interpretation or decision ID:
- Responsibility record:
- Prioritisation record, where applicable:
- Assumption record(s), where applicable:
- Supporting evidence:
- Related representation(s):

Where more detailed traceability is required, use
`traceability-matrix.csv`.

Process-specific lifecycle mappings should be added to the traceability chain
only after Process Instantiation has occurred.

---

## 7. Revision conditions

Specify conditions under which the engineering representation may require
review or revision.

Examples include:

- Updated contextual interpretation
- Revised prioritisation or trade-off decision
- Invalidated assumption
- Evaluation or monitoring evidence
- Operational feedback
- Changes in relevant constraints
- Changes propagated through FR.4

| Revision condition | Representation affected | Evidence source | Responsible role |
|---|---|---|---|
| | | | |

---

## 8. Subsequent Process Instantiation

Complete this section only after the engineering representation has been
mapped through CRISP-TAI.

The purpose of this section is to record the result of Process Instantiation,
not to make lifecycle placement part of FR.1.

- Representation ID:
- Instantiation record ID:
- Target CRISP-DM phase or lifecycle location:
- Process-specific activity or control point:
- Instantiated lifecycle artefact or operational configuration:
- Responsible lifecycle role:
- Anchoring requirement or constraint:
- Placement constraint, where applicable:
- Instantiation rationale:
- Traceability record:

Where Process Instantiation is documented through a dedicated mapping
artefact, reference that artefact here instead of duplicating its contents.

---

## 9. Verification and evidence

Identify the evidence retained for the application of FR.1.

- Originating contextual interpretation:
- Supporting rationale:
- Responsible actor(s):
- Engineering representation produced:
- Related traceability record:
- Supporting evidence:
- Subsequent instantiation evidence, where available:

Verification should demonstrate that the engineering representation can be
traced to its originating contextual interpretation and supporting rationale.

---

## 10. Versioning and ownership

- Document owner:
- Current version:
- Date created:
- Last updated:

### Revision history

| Version | Date | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|
| | | | | |

---

## Notes

This template documents a **process-independent engineering representation**.

Its purpose is to bridge contextual trustworthiness reasoning and subsequent
software-process enactment without collapsing those two methodological steps.

The expected sequence is:

**Contextual decision → Engineering representation → Process Instantiation →
Lifecycle artefact or operational configuration**

FR.1 produces the engineering representation. The subsequent mapping to a
CRISP-DM lifecycle element belongs to Process Instantiation within CRISP-TAI.
