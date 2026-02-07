# Rule Application Guide

This guide explains **how to apply Contextual Refinement (CR) and Functional Refinement (FR) rules**
in practice when using **CRISP-TAI**.

It is intended for practitioners who want to understand **how to navigate the artefacts**
provided in this repository and how refinement rules interact across the lifecycle.

This document complements the research article by focusing on *practical usage*,
not on theoretical justification.

---

## 1. How to read CR and FR rules

CR and FR rules are **not**:
- Mandatory checklists
- Sequential steps
- Automated enforcement mechanisms

Instead, they are **process-level reasoning mechanisms** that structure decisions,
artefacts, and reviews related to trustworthiness.

Not all rules need to be applied in every project or at every lifecycle phase.

---

## 2. Applying Contextual Refinement (CR) rules

CR rules support **reflexive and governance-oriented reasoning**.

### Typical entry points
- Business Understanding
- Early system scoping
- Governance and planning activities

### Artefacts involved
- `context-description.md`
- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`

### Practical guidance
- Use **CR.1–CR.3** to clarify context, responsibilities, and priorities.
- Apply **CR.4** to make assumptions explicit.
- Define **CR.5** revision triggers early.
- Use **CR.6–CR.7** to avoid unnecessary lifecycle restructuring or scope creep.

---

## 3. Applying Functional Refinement (FR) rules

FR rules translate refined interpretations into **concrete engineering outputs**.

### Typical entry points
- Requirements and design activities
- Definition of monitoring and operational procedures
- Review of feedback from system operation

### Artefacts involved
- `artefact-derivation.md`
- `traceability-matrix.csv`
- `monitoring-plan.md`
- `feedback-log.md`

### Practical guidance
- Apply **FR.1** when interpretations lead to new or updated artefacts.
- Use **FR.2** to maintain traceability across lifecycle phases.
- Activate **FR.3** for operational adjustments.
- Use **FR.4** to propagate feedback into revised assumptions or priorities.
- Apply **FR.5** for shift-left integration.
- Use **FR.6** to ensure lifecycle continuity.

---

## 4. Navigating the refinement cycle

A typical CRISP-TAI refinement cycle:

1. Contextual interpretation and prioritisation (CR)
2. Artefact derivation and traceability (FR)
3. Monitoring and operation (FR)
4. Feedback and revision (FR → CR)

This cycle can be entered at different points depending on system maturity.

---

## 5. Common pitfalls

- Treating rules as checklists rather than reasoning support
- Ignoring assumptions once deployment begins
- Failing to connect monitoring signals back to governance decisions
- Allowing trustworthiness artefacts to become stale

---

## 6. Using the examples

The examples in `/examples` illustrate how CR and FR rules are applied in practice:

- RAG in Data Spaces — distributed governance and provenance
- Federated Learning — early operational monitoring and feedback
- TrustAIoT — platform-level lifecycle governance

Use these examples as guidance, not as prescriptive templates.

---

## Notes

CRISP-TAI is intentionally flexible.
Its value lies in **structuring coordination and reasoning**, not in enforcing
uniform practices across systems or organisations.
