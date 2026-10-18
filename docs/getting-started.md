# Getting Started with CRISP-TAI

This document provides a **practical entry point** for engineers and teams
who want to apply **CRISP-TAI**, the first instantiation of the Lifecycle
Refinement Framework over CRISP-DM, in an AI project.

It assumes familiarity with AI development practices and focuses on *how to
use CRISP-TAI in practice*, not on its theoretical foundations. For conceptual
background, design rationale, and evaluation details, please refer to the
associated research article.

---

## When to use CRISP-TAI

CRISP-TAI is particularly suitable when:

- AI systems are deployed in **regulated, high-stakes, or sociotechnical contexts**
- Trustworthiness requirements go beyond model performance
- Governance, accountability, and operational concerns must be addressed
  **throughout the lifecycle**
- Existing CRISP-DM-based workflows need to incorporate structured
  trustworthiness refinement without replacing their underlying lifecycle

CRISP-TAI does **not** replace CRISP-DM or existing engineering tooling.
It instantiates the process-independent Lifecycle Refinement Framework over
CRISP-DM while preserving the underlying lifecycle structure.

---

## Core idea in one paragraph

The Lifecycle Refinement Framework separates trustworthiness refinement from
its subsequent process-specific instantiation through two complementary
mechanisms:

- **Contextual Refinement (CR)** interprets trustworthiness knowledge according
  to the organisational, regulatory, social, and operational context, including
  responsibilities, assumptions, priorities, constraints, and revision
  conditions.
- **Functional Refinement (FR)** transforms the resulting contextualised
  decisions into **process-independent engineering representations**, such as
  requirements, controls, rationales, evaluation criteria, monitoring
  specifications, and traceability or revision requirements.

Within CRISP-TAI, these engineering representations are subsequently
**instantiated within the CRISP-DM lifecycle** as process-specific activities,
artefacts, responsibilities, control points, or monitoring mechanisms.

The resulting chain is therefore:

**Trustworthiness knowledge → Contextual Refinement → Contextual
interpretations → Functional Refinement → Process-independent engineering
representations → Process Instantiation → CRISP-DM lifecycle artefacts**

Traceability should be preserved across this chain.

---

## Minimal adoption workflow

The following steps describe a **minimal, non-disruptive way** to start using
the framework through CRISP-TAI.

### Step 1 — Contextualise the trustworthiness concern

Begin by identifying the relevant trustworthiness concerns and interpreting
them within the project context.

1. Use the relevant templates from `/templates/contextual-refinement/`:
   - `context-description.md`
   - `responsibility-map.csv`
   - `principle-prioritisation.md`
   - `assumption-log.md`
2. Document, as applicable:
   - Organisational, regulatory, social, and operational constraints
   - Stakeholders, responsibilities, and accountability boundaries
   - Trustworthiness priorities and trade-offs
   - Contextual assumptions and their validity conditions

This primarily supports **CR.1–CR.4**. Contextual revision conditions should
also be considered through **CR.5** where applicable.

---

### Step 2 — Derive process-independent engineering representations

Do not map contextual decisions directly to CRISP-DM artefacts.

For each contextualised trustworthiness decision:

1. Determine the engineering representation required to operationalise it.
2. Express it independently of its eventual CRISP-DM lifecycle location.
3. Preserve its relationship to the originating contextual decision.

Representative engineering representations include:

- Requirements
- Controls
- Design or decision rationales
- Evaluation criteria
- Monitoring specifications
- Traceability requirements
- Revision or continuity requirements

Use, where applicable:

- `engineering-representation.md`
- `traceability-matrix.csv`

This step primarily applies **FR.1** and **FR.2**.

---

### Step 3 — Instantiate the representations within CRISP-TAI

Once the required engineering representations have been defined, determine
where and how they should be enacted within the CRISP-DM lifecycle.

For each engineering representation:

1. Identify the lifecycle conditions and dependencies that must be preserved.
2. Determine the appropriate CRISP-DM phase, activity, artefact, responsibility,
   or control point.
3. Record the resulting process-specific instantiation.
4. Preserve traceability to the originating engineering representation and
   contextual decision.

**CR.6 (Lifecycle Anchoring)** and **CR.7 (Scope Control)** support the
boundary between refinement and process-specific instantiation without making
the final lifecycle mapping part of the process-independent refinement logic.

---

### Step 4 — Integrate operational considerations

Before and during operation:

1. Identify whether contextual or operational evidence requires:
   - New or revised engineering representations
   - Monitoring requirements
   - Oversight or configuration constraints
   - Feedback integration
   - Continuity requirements
2. Update the relevant engineering and lifecycle artefacts.

Use, where applicable:

- `monitoring-plan.md`
- `feedback-log.md`

This step primarily involves **FR.3**, **FR.4**, and **FR.6**.

Where an engineering representation should be addressed earlier in the
lifecycle, **FR.5** can establish the corresponding placement constraint for
subsequent process-specific instantiation.

---

### Step 5 — Plan for contextual revision

Trustworthiness assumptions and contextual interpretations are not static.

Define conditions that may require reconsideration, such as:

- Regulatory changes
- New data sources
- Changes in intended use or affected stakeholders
- Monitoring evidence
- Observed system behaviour
- Invalidated contextual assumptions

Record the relevant assumptions and operational evidence using:

- `assumption-log.md`
- `feedback-log.md`

When a revision condition occurs, **CR.5** determines whether contextual
reconsideration is required. **FR.4** integrates the resulting evidence into
the refinement cycle, and affected engineering representations should be
updated through subsequent refinement where necessary.

---

## What CRISP-TAI does *not* require

You do **not** need to:

- Introduce universal metrics or scoring schemes
- Replace existing MLOps or DevOps pipelines
- Adopt new tooling
- Perform formal audits or certifications
- Automate contextual or normative judgement

CRISP-TAI provides a structured refinement and instantiation method. Existing
engineering, DevOps, MLOps, governance, and monitoring infrastructures may be
used to enact the resulting lifecycle-specific artefacts and controls.

---

## Using examples

The `/examples` directory contains **illustrative applications of the
Lifecycle Refinement Framework through its CRISP-TAI instantiation** in
heterogeneous AI contexts.

Examples may show:

- Which CR and FR rules were applied
- Which contextual decisions or assumptions were reconstructed
- Which process-independent engineering representations were identified
- How those representations were instantiated within the lifecycle
- How traceability and revision were preserved

These examples are illustrative and may be incomplete by design. They are not
production-ready reference implementations or independent empirical
validations of the framework.

---

## Recommended first experiment

For a first trial:

1. Select a **small but realistic AI project**.
2. Identify one trustworthiness concern.
3. Apply the relevant contextual refinement rules to document its context,
   responsibilities, priorities, and assumptions.
4. Use **FR.1** to derive at least one process-independent engineering
   representation.
5. Use **FR.2** to preserve its traceability to the originating contextual
   decision.
6. Instantiate that representation within an appropriate CRISP-DM lifecycle
   element and record the resulting artefact.

Focus on preserving the complete chain:

**contextual decision → engineering representation → process-specific
instantiation**

rather than on achieving complete rule coverage in the first trial.

---

## Next steps

After completing a minimal application, you may:

- Extend coverage to additional CR/FR rules
- Introduce monitoring, feedback, and contextual revision
- Integrate CRISP-TAI artefacts into existing governance, DevOps, or MLOps
  practices
- Explore the illustrative applications in `/examples`
- Contribute CRISP-TAI examples, templates, or documentation back to the
  repository

See `rule-application-guide.md` for detailed rule-application guidance,
`lifecycle-walkthrough.md` for the CRISP-TAI lifecycle view, and
`CONTRIBUTING.md` for contribution guidelines.
