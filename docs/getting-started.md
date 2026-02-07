# Getting Started with CRISP-TAI

This document provides a **practical entry point** for engineers and teams who want to start applying **CRISP-TAI** in an AI project.

It assumes familiarity with AI development practices and focuses on *how to use CRISP-TAI in practice*, not on its theoretical foundations. For conceptual background, design rationale, and validation details, please refer to the associated research article.

---

## When to use CRISP-TAI

CRISP-TAI is particularly suitable when:

- AI systems are deployed in **regulated, high-stakes, or socio-technical contexts**
- Trustworthiness requirements go beyond model performance
- Governance, accountability, and operational concerns must be addressed **throughout the lifecycle**
- Existing AI workflows need to be extended without replacing the underlying SDLC

CRISP-TAI does **not** replace your development process or tooling.  
It **augments** an existing lifecycle (e.g., CRISP-DM–based workflows) with structured trustworthiness reasoning.

---

## Core idea in one paragraph

CRISP-TAI integrates **two complementary refinement mechanisms** across the AI lifecycle:

- **Contextual Refinement (CR)**: supports reflexive and governance-oriented reasoning (context, responsibilities, assumptions, priorities).
- **Functional Refinement (FR)**: translates refined interpretations into concrete artefacts, operational decisions, and feedback mechanisms.

These mechanisms operate **across all lifecycle phases**, enabling traceability, evaluability, and continuous governance without reducing trustworthiness to metrics or checklists.

---

## Minimal adoption workflow

The following steps describe a **minimal, non-disruptive way** to start using CRISP-TAI.

### Step 1 — Start with context

At project initiation (Business Understanding phase):

1. Copy the following templates from `/templates/contextual-refinement/`:
   - `context-description.md`
   - `responsibility-map.csv`
   - `principle-prioritisation.md`
2. Document:
   - Organisational and legal constraints
   - Stakeholders and responsibilities
   - Initial trustworthiness priorities and trade-offs

This corresponds primarily to **CR.1–CR.3**.

---

### Step 2 — Anchor decisions to lifecycle artefacts

As development proceeds:

1. For each trustworthiness-related decision:
   - Identify the lifecycle phase where it applies
   - Record it in an artefact (requirement, design note, evaluation criterion)
2. Use:
   - `artefact-derivation.md`
   - `traceability-matrix.csv`

This step activates **FR.1** and **FR.2**.

---

### Step 3 — Integrate operational considerations

Before and after deployment:

1. Identify operational implications of trustworthiness decisions:
   - Monitoring requirements
   - Oversight mechanisms
   - Deployment constraints
2. Update:
   - `monitoring-plan.md`
   - `feedback-log.md`

This corresponds to **FR.3–FR.6**.

---

### Step 4 — Plan for revision

Trustworthiness assumptions are not static.

1. Define triggers for reassessment:
   - Regulatory changes
   - New data sources
   - Observed system behaviour
2. Record them in:
   - `assumption-log.md`
   - `feedback-log.md`

This step operationalises **CR.5** and **FR.4**.

---

## What CRISP-TAI does *not* require

You do **not** need to:

- Introduce new metrics or scoring schemes
- Replace existing MLOps or DevOps pipelines
- Adopt new tooling
- Perform formal audits or certifications

CRISP-TAI focuses on **process structure and reasoning**, not automation.

---

## Using examples

The `/examples` directory contains **execution-based instantiations** of CRISP-TAI in heterogeneous contexts.

Each example shows:
- Which CR and FR rules were applied
- What artefacts were produced
- How decisions were revised over time

Examples are illustrative and may be incomplete by design.

---

## Recommended first experiment

For a first trial:

1. Select a **small but realistic AI project**
2. Apply only:
   - CR.1–CR.4
   - FR.1–FR.2
3. Focus on documentation and traceability, not completeness

This is sufficient to experience the core value of CRISP-TAI.

---

## Next steps

After completing a minimal instantiation, you may:

- Extend coverage to additional CR/FR rules
- Integrate CRISP-TAI artefacts into governance processes
- Contribute examples or templates back to the repository

See `CONTRIBUTING.md` for contribution guidelines.








