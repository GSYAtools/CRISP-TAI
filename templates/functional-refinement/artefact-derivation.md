# Artefact Derivation

This document supports **Functional Refinement rule FR.1 (Artefact Derivation)** in CRISP-TAI.

Its purpose is to record how **contextual and governance-oriented trustworthiness interpretations**
are translated into **concrete engineering artefacts** during the system lifecycle.

This artefact does not prescribe specific formats or tools. Instead, it supports
traceability between **refined interpretations**, **engineering decisions**, and
**produced artefacts**.

---

## 1. Scope

- System or component:
- Lifecycle phase:
- Date:
- Responsible role:

---

## 2. Input interpretations

List the contextual interpretations that motivate artefact derivation.

Typical sources include:
- `context-description.md`
- `principle-prioritisation.md`
- `assumption-log.md`
- Governance or review decisions

### Example

| Interpretation ID | Description | Source artefact |
|------------------|-------------|-----------------|
| CI-01 | Data reuse constrained to purpose X | context-description.md |
| CI-02 | Transparency prioritised over performance | principle-prioritisation.md |

---

## 3. Derived artefacts

For each interpretation, document the artefacts that were produced or updated.

### Example

| Interpretation ID | Artefact | Type | Description |
|------------------|----------|------|-------------|
| CI-01 | data-usage-requirements.md | Requirement | Constraints on data reuse |
| CI-02 | model-design-rationale.md | Design rationale | Choice of interpretable model |

Artefact types may include:
- Requirements
- Design rationales
- Evaluation criteria
- Governance records
- Monitoring specifications

---

## 4. Rationale and traceability

Explain how each artefact implements or reflects the corresponding interpretation.

This section should allow an external reviewer to understand:
- Why the artefact exists
- Which trustworthiness concern it addresses
- How it relates to lifecycle decisions

---

## 5. Revision triggers

Specify conditions under which derived artefacts must be revisited.

Examples:
- Updated contextual assumptions
- Monitoring feedback
- Deployment changes
- Governance review outcomes

---

## 6. Versioning

- Artefact version:
- Date created:
- Last updated:
- Change summary:

---

## Notes

This document is a **bridging artefact**.
It connects reflexive reasoning with operational engineering outputs,
supporting evaluability and lifecycle coherence without enforcing fixed solutions.


