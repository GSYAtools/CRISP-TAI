## Lifecycle Walkthrough — Applying CRISP-TAI in Practice

This document provides a **phase-by-phase walkthrough** of how CRISP-TAI is applied
across the AI system development lifecycle.

It is intended for practitioners who want to understand **how Contextual Refinement (CR)**
and **Functional Refinement (FR)** artefacts are used together as development progresses,
and how trustworthiness-related reasoning is sustained over time.

This walkthrough complements:
- `docs/getting-started.md`
- `docs/rule-application-guide.md`
- The example instantiations in `/examples`

Figures referenced below are provided in `/appendix/figures` as expanded, practitioner-oriented views.

---

## Overview of the lifecycle

CRISP-TAI follows the structure of an established, iterative lifecycle
(CRISP-DM), while embedding trustworthiness reasoning as a cross-cutting concern.

The lifecycle comprises the following phases:
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Continuous Deployment & Monitoring

Trustworthiness is treated as an **emergent lifecycle property**, supported by
CR and FR artefacts throughout all phases.

---

## 1. Business Understanding

**Purpose:** Establish project objectives, scope, and trustworthiness context.

### Key activities
- Identify stakeholders and governance structures
- Interpret regulatory and organisational constraints
- Define trustworthiness priorities and responsibilities

### Primary artefacts
- `context-description.md`
- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`

### Relevant refinement rules
- CR.1 (Context Interpretation)
- CR.2 (Responsibility Allocation)
- CR.3 (Principle Prioritisation)
- CR.4 (Assumption Documentation)

### Supporting figure
- `appendix/figures/TAI-CRISP-DM-BU.png`

---

## 2. Data Understanding

**Purpose:** Understand data sources, meaning, and limitations in context.

### Key activities
- Identify data sources and lineage
- Assess data quality and representativeness
- Revisit assumptions related to data availability and stability

### Primary artefacts
- `assumption-log.md`
- `traceability-matrix.csv`

### Relevant refinement rules
- CR.4 (Assumption Documentation)
- FR.2 (Decision Traceability)

### Supporting figure
- `appendix/figures/TAI-CRISP-DM-DU.png`

---

## 3. Data Preparation

**Purpose:** Prepare data while preserving trustworthiness constraints.

### Key activities
- Apply privacy-preserving transformations
- Address bias and representation issues
- Document rationale for inclusion/exclusion decisions

### Primary artefacts
- `artefact-derivation.md`
- `traceability-matrix.csv`

### Relevant refinement rules
- FR.1 (Artefact Derivation)
- FR.2 (Decision Traceability)

### Supporting figure
- `appendix/figures/TAI-CRISP-DM-DP.png`

---

## 4. Modeling

**Purpose:** Build and assess models under trustworthiness constraints.

### Key activities
- Select modeling techniques aligned with priorities
- Document modeling assumptions and design rationales
- Assess explainability and robustness

### Primary artefacts
- `artefact-derivation.md`
- `traceability-matrix.csv`
- `assumption-log.md`

### Relevant refinement rules
- FR.1 (Artefact Derivation)
- FR.2 (Decision Traceability)

### Supporting figure
- `appendix/figures/TAI-CRISP-DM-M.png`

---

## 5. Evaluation

**Purpose:** Evaluate results in relation to business goals and trustworthiness concerns.

### Key activities
- Interpret results in context
- Validate assumptions and priorities
- Decide on deployment or revision

### Primary artefacts
- `traceability-matrix.csv`
- `feedback-log.md`

### Relevant refinement rules
- FR.4 (Iterative Feedback Integration)
- CR.5 (Context Revision Triggers)

### Supporting figure
- `appendix/figures/TAI-CRISP-DM-E.png`

---

## 6. Continuous Deployment & Monitoring

**Purpose:** Sustain trustworthiness during operation and evolution.

### Key activities
- Monitor trustworthiness-related signals
- Review operational feedback
- Trigger contextual or operational revisions

### Primary artefacts
- `monitoring-plan.md`
- `feedback-log.md`
- `assumption-log.md`
- `instantiation-log.md`

### Relevant refinement rules
- FR.3 (Operational Adjustment)
- FR.4 (Iterative Feedback Integration)
- FR.6 (Continuity Enforcement)

### Supporting figure
- `appendix/figures/TAI-CRISP-DM-D.png`

---

## Iteration and refinement

The lifecycle is **iterative by design**.

Feedback collected during Evaluation or Operation may trigger:
- Revision of assumptions
- Reprioritisation of trustworthiness dimensions
- Updates to artefacts or monitoring strategies

CRISP-TAI supports entering the lifecycle at different phases,
depending on system maturity and organisational context.

---

## Using the examples

The examples in `/examples` demonstrate how this lifecycle walkthrough
is instantiated in different settings:

- RAG in Federated Data Spaces
- Federated Learning with early monitoring
- TrustAIoT platform governance

Use the walkthrough as a **navigation guide**, not as a prescriptive sequence.

---

## Notes
CRISP-TAI does not enforce a single workflow.
Its value lies in **structuring reasoning, coordination, and traceability**
across heterogeneous AI systems and organisational settings.
