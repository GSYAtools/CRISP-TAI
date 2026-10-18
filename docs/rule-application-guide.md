# Rule Application Guide

This guide explains **how to apply Contextual Refinement (CR) and Functional
Refinement (FR) rules** in practice when using **CRISP-TAI**, the first
instantiation of the Lifecycle Refinement Framework over CRISP-DM.

It is intended for practitioners who want to understand **how to navigate the
artefacts** provided in this repository, how refinement rules interact, and how
their outputs are subsequently instantiated within the CRISP-DM lifecycle.

This document complements the associated research article by focusing on
*practical usage*, not on theoretical justification.

---

## 1. How to read CR and FR rules

CR and FR rules are **not**:

- Mandatory checklists
- Sequential lifecycle steps
- Automated enforcement mechanisms
- CRISP-DM phases or activities

Instead, they are **process-independent refinement mechanisms** that structure
contextual interpretation and the derivation, traceability, and evolution of
engineering representations related to trustworthiness.

Not all rules need to be applied in every project or at every lifecycle phase.
Their application depends on the trustworthiness concern, available evidence,
contextual conditions, and current state of the system.

Each canonical CR and FR rule is operationally specified through:

- **Input (I)** — information required to apply the rule
- **Trigger (T)** — condition under which the rule becomes applicable
- **Responsible role(s) (R)** — functional responsibility for its application
- **Procedure (P)** — transformation or decision procedure
- **Expected output (O)** — result that should be produced
- **Verification / evidence (V)** — evidence retained to make application
  traceable and inspectable

The complete canonical rule specification is provided in the associated
research article. Repository templates support practical application of these
rules but do not redefine them.

---

## 2. Applying Contextual Refinement (CR) rules

CR supports the interpretation of structured trustworthiness knowledge
according to the organisational, regulatory, social, and operational context
of the system.

### Typical entry points

CR may be activated during:

- Initial project or system scoping
- Governance and planning activities
- Interpretation of new trustworthiness concerns
- Changes in regulation, organisational conditions, intended use, or affected
  stakeholders
- Evaluation or operational feedback requiring contextual reconsideration

CR is therefore not restricted to the beginning of the lifecycle.

### Artefacts involved

Repository templates supporting CR include:

- `context-description.md`
- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`

### Practical guidance

- Use **CR.1 — Context Interpretation** to identify the organisational,
  regulatory, social, and operational factors relevant to a trustworthiness
  concern.
- Use **CR.2 — Responsibility Allocation** when a trustworthiness-related
  decision, trade-off, artefact, or outcome requires identifiable
  responsibility or accountability.
- Use **CR.3 — Principle Prioritisation** when applicable trustworthiness
  objectives impose competing requirements or require an explicit
  context-specific trade-off.
- Use **CR.4 — Assumption Documentation** when a contextual interpretation or
  decision depends on conditions that are assumed rather than established or
  invariant.
- Use **CR.5 — Context Revision Trigger** when new evidence or a predefined
  revision condition challenges an existing assumption, constraint, priority,
  or governance interpretation.
- Use **CR.6 — Lifecycle Anchoring** to identify the lifecycle conditions,
  dependencies, and candidate process locations that must be considered during
  subsequent process-specific instantiation without prescribing the final
  lifecycle mapping.
- Use **CR.7 — Scope Control** to determine whether the selected software
  process can accommodate the required refinement through existing elements or
  whether subsequent instantiation requires retention, adaptation, or extension
  of the process.

CR.1–CR.5 primarily support contextual interpretation. CR.6 and CR.7 operate
at the **boundary with Process Instantiation**, preserving the separation
between process-independent refinement and the final process-specific mapping.

---

## 3. Applying Functional Refinement (FR) rules

FR transforms contextualised trustworthiness decisions into
**process-independent engineering representations** suitable for subsequent
lifecycle instantiation.

Representative engineering representations include requirements, controls,
design or decision rationales, evaluation criteria, monitoring specifications,
responsibility structures, and traceability or revision requirements.

### Typical entry points

FR may be activated when:

- A contextual interpretation requires explicit engineering representation
- A trustworthiness-related decision requires traceability
- Contextual or operational evidence requires an engineering adjustment
- Evaluation, monitoring, auditing, or review produces relevant feedback
- An engineering representation should be addressed earlier in the lifecycle
- A representation, responsibility, control, or monitoring requirement must
  persist during operation and system evolution

### Artefacts involved

Repository templates supporting FR include:

- `artefact-derivation.md`
- `traceability-matrix.csv`
- `monitoring-plan.md`
- `feedback-log.md`

### Practical guidance

- Use **FR.1 — Engineering Representation Derivation** to transform a
  contextual interpretation into one or more process-independent engineering
  representations.
- Use **FR.2 — Decision Traceability** to preserve explicit links between the
  originating trustworthiness concern, contextual decision, engineering
  representation, and subsequent process-specific enactment where applicable.
- Use **FR.3 — Operational Adjustment** when contextual or operational evidence
  requires a new or revised engineering representation specifying an
  operational adjustment.
- Use **FR.4 — Iterative Feedback Integration** to evaluate operational or
  evaluation evidence against existing contextual interpretations and
  engineering representations and to invoke CR.5 where contextual
  reconsideration is required.
- Use **FR.5 — Shift-Left Integration** to establish a placement constraint
  identifying the earliest meaningful lifecycle point at which an engineering
  representation should be addressed during subsequent process-specific
  instantiation.
- Use **FR.6 — Continuity Enforcement** when engineering representations,
  responsibilities, controls, monitoring mechanisms, or revision obligations
  must persist throughout operation and system evolution.

FR produces and maintains engineering representations. Their final placement
within CRISP-DM is determined during **Process Instantiation**, not by FR
itself.

---

## 4. Process Instantiation in CRISP-TAI

Process Instantiation is distinct from CR and FR.

Once process-independent engineering representations have been produced,
CRISP-TAI maps them to the phases, activities, artefacts, responsibilities,
control points, and monitoring mechanisms of the CRISP-DM lifecycle.

A practical instantiation should therefore preserve the following chain:

**Trustworthiness concern  
→ Contextual interpretation or decision  
→ Engineering representation  
→ CRISP-DM lifecycle instantiation  
→ Lifecycle artefact or operational configuration**

The process-specific mapping should preserve the meaning, rationale,
responsibility, and traceability established during refinement.

CR.6 and CR.7 support this boundary by identifying anchoring and scope
conditions, while FR.5 may constrain the earliest meaningful lifecycle
placement. The final CRISP-DM mapping nevertheless remains part of Process
Instantiation.

---

## 5. Navigating the refinement cycle

A typical application may involve:

1. **Contextual Refinement** — interpret the trustworthiness concern and
   establish responsibilities, priorities, assumptions, and relevant
   constraints.
2. **Functional Refinement** — derive and maintain process-independent
   engineering representations.
3. **Process Instantiation** — map those representations to appropriate
   CRISP-DM lifecycle elements and artefacts.
4. **Operation and monitoring** — collect evidence through the instantiated
   engineering and monitoring mechanisms.
5. **Feedback integration** — use FR.4 to relate operational evidence to
   existing engineering representations.
6. **Contextual revision** — invoke CR.5 where evidence challenges contextual
   assumptions, constraints, priorities, or governance interpretations.
7. **Re-refinement and re-instantiation** — update affected engineering
   representations and their lifecycle-specific enactment where required.

The refinement cycle is iterative and may be entered or reactivated at
different points as the system and its context evolve.

---

## 6. Common pitfalls

Avoid:

- Treating CR and FR rules as mandatory checklists
- Treating CR or FR rules as CRISP-DM phases
- Mapping contextual decisions directly to lifecycle artefacts without first
  identifying the required engineering representation
- Treating an Engineering Representation as if it were already a
  process-specific lifecycle artefact
- Allowing lifecycle placement decisions to become embedded in the
  process-independent refinement logic
- Ignoring assumptions after deployment
- Failing to connect monitoring evidence back to engineering and contextual
  decisions
- Allowing trustworthiness-related representations or lifecycle artefacts to
  become stale
- Assuming that every rule must be applied in every project

---

## 7. Using the examples

The examples in `/examples` illustrate retrospective or practical applications
of the Lifecycle Refinement Framework through CRISP-TAI in heterogeneous
contexts:

- RAG in Data Spaces — distributed governance, provenance, and traceability
- Federated Learning — distributed monitoring and operational constraints
- TrustAIoT — lifecycle governance, monitoring, feedback, and contextual
  revision

When examining an example, identify:

1. The original trustworthiness concern
2. The contextual decision or interpretation reconstructed through CR
3. The process-independent engineering representation reconstructed through FR
4. Its documented process-specific instantiation
5. Any operational evidence, feedback, or subsequent revision

Use these examples as guidance rather than as prescriptive templates. They are
illustrative applications and should not be interpreted as production-ready
reference implementations or independent empirical validations.

---

## 8. Relationship to repository templates

The templates in `/templates` provide reusable structures for documenting
practical applications of CR and FR.

Templates are supporting artefacts. They do not replace the canonical rule
definitions and do not imply that a particular template must be used whenever
a corresponding rule is applied.

Where possible, completed templates should preserve traceability between:

- The applicable CR or FR rule
- Its relevant input or trigger
- The responsible actor
- The resulting contextual decision or engineering representation
- Supporting evidence
- Any subsequent process-specific lifecycle instantiation

This makes refinement decisions inspectable while allowing organisations to
adapt the documentation format to their existing engineering practices.

---

## Notes

CRISP-TAI is intentionally adaptable to organisational and engineering
contexts while preserving the methodological separation defined by the
Lifecycle Refinement Framework.

Its value lies in **structuring contextual interpretation, engineering
representation, traceability, process-specific instantiation, monitoring, and
revision**, not in enforcing uniform practices across systems or organisations.
