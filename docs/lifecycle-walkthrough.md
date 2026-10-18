## Lifecycle Walkthrough — Applying CRISP-TAI in Practice

This document provides a **phase-by-phase walkthrough** of how the
process-independent engineering representations produced through the Lifecycle
Refinement Framework can be instantiated across the CRISP-DM lifecycle through
**CRISP-TAI**.

It is intended for practitioners who want to understand how **Contextual
Refinement (CR)** and **Functional Refinement (FR)** inform engineering
representations, how those representations are subsequently mapped to
CRISP-DM lifecycle elements, and how trustworthiness-related reasoning is
sustained over time.

This walkthrough complements:

- `docs/getting-started.md`
- `docs/rule-application-guide.md`
- The illustrative applications in `/examples`

Figures referenced below are provided in `/appendices/figures` as expanded,
practitioner-oriented views.

---

## Overview of the lifecycle

CRISP-TAI is the first instantiation of the Lifecycle Refinement Framework over
the CRISP-DM lifecycle. It preserves the underlying lifecycle structure while
providing a process-specific mapping for engineering representations produced
through CR and FR.

For the purposes of this CRISP-TAI walkthrough, the lifecycle is organised
around the following phase-level locations:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Continuous Deployment & Monitoring

The phase-level associations below are **illustrative instantiation mappings**.
They do not make CR or FR phase-specific: the refinement rules remain
process-independent and may be activated whenever their inputs and triggering
conditions apply.

The general relationship is:

**Contextual interpretation → Process-independent engineering representation
→ CRISP-DM process instantiation → Lifecycle artefact**

---

## 1. Business Understanding

**Instantiation focus:** Contextual priorities, responsibilities, assumptions,
and governance constraints.

### Representative activities

- Identify stakeholders and governance structures
- Interpret organisational, regulatory, social, and operational constraints
- Establish trustworthiness priorities and responsibility boundaries
- Document assumptions relevant to subsequent engineering decisions

### Refinement support

Relevant rules may include:

- CR.1 — Context Interpretation
- CR.2 — Responsibility Allocation
- CR.3 — Principle Prioritisation
- CR.4 — Assumption Documentation

These rules produce contextual decisions and constraints rather than
CRISP-DM-specific artefacts.

### Representative process-specific artefacts

During CRISP-TAI instantiation, the resulting contextual decisions and
engineering representations may be reflected in:

- Responsibility records or maps
- Assumption records
- Accountability records
- Principle-prioritisation records
- Governance constraints

### Supporting repository templates

- `context-description.md`
- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`

### Supporting figure

- `appendices/figures/TAI-CRISP-DM-BU.png`

---

## 2. Data Understanding

**Instantiation focus:** Data provenance, lineage, contextual usage, and
limitations.

### Representative activities

- Identify data sources and provenance
- Examine lineage and contextual meaning
- Identify relevant data limitations
- Revisit assumptions concerning data availability, representativeness, or
  stability

### Refinement support

Relevant rules may include:

- CR.4 — Assumption Documentation
- FR.1 — Engineering Representation Derivation
- FR.2 — Decision Traceability

For example, a contextual decision concerning data legitimacy or transparency
may be represented through provenance, lineage, contextual-usage, or
data-limitation requirements before being mapped to CRISP-DM artefacts.

### Representative process-specific artefacts

- Data description reports
- Provenance and lineage records
- Contextual usage records
- Data limitation records

### Supporting repository templates

- `assumption-log.md`
- `artefact-derivation.md`
- `traceability-matrix.csv`

### Supporting figure

- `appendices/figures/TAI-CRISP-DM-DU.png`

---

## 3. Data Preparation

**Instantiation focus:** Transformation rationale, preprocessing traceability,
and trustworthiness constraints affecting data preparation.

### Representative activities

- Identify trustworthiness constraints affecting data transformations
- Document preprocessing decisions and their rationale
- Preserve traceability across transformations
- Represent relevant mitigation or preparation requirements

### Refinement support

Relevant rules may include:

- FR.1 — Engineering Representation Derivation
- FR.2 — Decision Traceability
- FR.3 — Operational Adjustment, where an engineering representation must be
  revised or introduced in response to contextual or operational evidence

The corresponding engineering representations should be defined before their
final placement as CRISP-DM-specific artefacts.

### Representative process-specific artefacts

- Dataset rationale
- Preprocessing traceability records
- Bias-mitigation records, where applicable
- Data-preparation decision logs

### Supporting repository templates

- `artefact-derivation.md`
- `traceability-matrix.csv`

### Supporting figure

- `appendices/figures/TAI-CRISP-DM-DP.png`

---

## 4. Modeling

**Instantiation focus:** Model rationale, explanation, oversight, and
configuration requirements.

### Representative activities

- Represent trustworthiness constraints affecting model design
- Document model and configuration rationale
- Define explanation or oversight requirements where applicable
- Preserve traceability to the contextual decisions that motivated those
  requirements

### Refinement support

Relevant rules may include:

- FR.1 — Engineering Representation Derivation
- FR.2 — Decision Traceability
- FR.3 — Operational Adjustment
- FR.5 — Shift-Left Integration, where an engineering representation should be
  addressed at the earliest meaningful lifecycle point

### Representative process-specific artefacts

- Model rationale records
- Explainability artefacts
- Oversight records
- Configuration justification records

### Supporting repository templates

- `artefact-derivation.md`
- `traceability-matrix.csv`
- `assumption-log.md`

### Supporting figure

- `appendices/figures/TAI-CRISP-DM-M.png`

---

## 5. Evaluation

**Instantiation focus:** Verification, review, traceability, escalation, and
revision requirements.

### Representative activities

- Evaluate instantiated requirements and controls
- Review whether engineering outcomes remain aligned with contextual decisions
- Examine whether assumptions remain valid
- Record unresolved issues or escalation decisions
- Determine whether evidence requires engineering or contextual revision

### Refinement support

Relevant rules may include:

- FR.2 — Decision Traceability
- FR.4 — Iterative Feedback Integration
- CR.5 — Context Revision Trigger

FR.4 relates evaluation evidence to existing contextual interpretations and
engineering representations. CR.5 is invoked where that evidence challenges
an assumption, constraint, priority, or governance interpretation.

### Representative process-specific artefacts

- Review reports
- Justification records
- Escalation records
- Unresolved-issue logs

### Supporting repository templates

- `traceability-matrix.csv`
- `feedback-log.md`
- `assumption-log.md`

### Supporting figure

- `appendices/figures/TAI-CRISP-DM-E.png`

---

## 6. Continuous Deployment & Monitoring

**Instantiation focus:** Monitoring, feedback, continuity, and contextual
revision requirements.

### Representative activities

- Monitor trustworthiness-related operational evidence
- Preserve relevant responsibilities, controls, and monitoring obligations
- Record feedback and changes in operating conditions
- Identify required engineering adjustments
- Trigger contextual reconsideration where assumptions or governance
  interpretations no longer remain valid

### Refinement support

Relevant rules may include:

- FR.3 — Operational Adjustment
- FR.4 — Iterative Feedback Integration
- CR.5 — Context Revision Trigger
- FR.6 — Continuity Enforcement

### Representative process-specific artefacts

- Monitoring plans and specifications
- Monitoring and review records
- Feedback records
- Contextual revision records
- Continuity and maintenance records

### Supporting repository templates

- `monitoring-plan.md`
- `feedback-log.md`
- `assumption-log.md`
- `traceability-matrix.csv`

### Supporting figure

- `appendices/figures/TAI-CRISP-DM-D.png`

---

## Lifecycle anchoring and scope control

CRISP-TAI requires an explicit boundary between process-independent refinement
and process-specific lifecycle instantiation.

Two Contextual Refinement rules support this boundary:

- **CR.6 — Lifecycle Anchoring** identifies the lifecycle conditions,
  dependencies, and candidate process locations that must be considered when
  an engineering representation is subsequently instantiated.
- **CR.7 — Scope Control** determines whether the selected process can
  accommodate the required refinement through existing elements or whether
  retention, adaptation, or extension is required.

Neither rule performs the final process-specific mapping. Their role is to
preserve the conditions and rationale that the subsequent CRISP-TAI
instantiation must satisfy.

Similarly, **FR.5 — Shift-Left Integration** may establish a placement
constraint defining the earliest meaningful lifecycle point at which an
engineering representation should be addressed, while leaving its final
CRISP-DM mapping to Process Instantiation.

---

## Iteration and refinement

The lifecycle is **iterative by design**, and refinement may be reactivated as
the system and its context evolve.

Evidence collected during Evaluation, Deployment, or Monitoring may trigger:

- Revision of engineering representations
- Reconsideration of contextual assumptions
- Reprioritisation of trustworthiness concerns
- Updates to process-specific lifecycle artefacts
- Changes to monitoring or continuity requirements

A typical feedback path is:

**Operational evidence → FR.4 → CR.5, where contextual reconsideration is
required → updated contextual interpretation → subsequent FR → revised
engineering representation → updated process-specific instantiation**

This feedback path preserves the distinction between refinement and lifecycle
enactment while supporting continuous evolution.

---

## Using the examples

The examples in `/examples` illustrate how the Lifecycle Refinement Framework
can be applied retrospectively or practically through CRISP-TAI in different
settings:

- RAG in Data Spaces
- Federated Learning with early monitoring
- TrustAIoT platform governance

When using these examples, distinguish between:

1. Contextual decisions reconstructed through CR
2. Process-independent engineering representations reconstructed through FR
3. Their documented process-specific instantiation
4. Operational evidence and subsequent feedback or revision, where available

Use the walkthrough as a **navigation guide**, not as a prescriptive sequence
or as evidence that CR and FR are intrinsically tied to particular CRISP-DM
phases.

---

## Notes

CRISP-TAI does not define a new lifecycle and does not require every
refinement rule to be applied in every phase.

Its value lies in providing a structured way to instantiate
trustworthiness-related engineering representations within CRISP-DM while
preserving their relationship to the contextual decisions from which they were
derived.

The Lifecycle Refinement Framework remains process-independent; this
walkthrough describes its **first process-specific instantiation through
CRISP-TAI**.
