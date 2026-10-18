# CRISP-TAI --- First Instantiation of the Lifecycle Refinement Framework

This repository contains the engineering artefacts supporting
**CRISP-TAI**, the **first instantiation** of the **Lifecycle
Refinement Framework (LRF)** introduced in the associated research
article.

The Lifecycle Refinement Framework defines a **process-independent
refinement method** for operationalising Trustworthy AI within
established software processes through two complementary refinement
mechanisms:

-   **Contextual Refinement (CR)**
-   **Functional Refinement (FR)**

CRISP-TAI demonstrates how this framework can be instantiated over the
CRISP-DM lifecycle while preserving the original process structure.

The repository preserves the distinction established in the framework
between **contextual interpretations**, **process-independent engineering
representations**, and their subsequent **process-specific instantiation**
as lifecycle artefacts.

This repository provides practical engineering artefacts supporting the
application of the refinement method and its process-specific
instantiation through CRISP-TAI in AI engineering projects.

> **Important scope note**
>
> This repository does **not** reproduce the paper, its figures, or its
> conceptual explanations. The associated article remains the
> authoritative source for the conceptual foundations, the Lifecycle
> Refinement Framework, and the scientific evaluation.
>
> This repository focuses exclusively on **implementation-oriented
> engineering artefacts**, reusable templates, execution traces, and
> practical guidance supporting the CRISP-TAI instantiation.

------------------------------------------------------------------------

# What this repository provides

-   Engineering artefacts supporting the CRISP-TAI instantiation
-   Reusable templates implementing Contextual Refinement (CR) and
    Functional Refinement (FR)
-   Practical examples showing applications of the framework through
    CRISP-TAI across heterogeneous AI domains
-   Traceability artefacts supporting lifecycle refinement
-   Practitioner guidance for adapting the refinement method to real
    projects

------------------------------------------------------------------------

# What this repository is *not*

-   ❌ Not a certification framework
-   ❌ Not an automated compliance or auditing tool
-   ❌ Not a Trustworthy AI checklist
-   ❌ Not a metrics or benchmarking library
-   ❌ Not a replacement for organisational governance or human
    decision-making

The repository supports **traceability, evaluability, and engineering
operationalisation**, not automated judgement or normative enforcement.

------------------------------------------------------------------------

# Repository structure

```text
/docs
    Practical guidance
/templates
    /contextual-refinement
    /functional-refinement
/examples
    Cross-domain illustrative applications
/logs
    Refinement and traceability records
/appendices
    Supplementary engineering material
```

------------------------------------------------------------------------

# /docs --- Practitioner Guidance

This directory contains practical documentation explaining how to apply
the CRISP-TAI instantiation in engineering projects.

This directory contains:

-   `getting-started.md`
-   `lifecycle-walkthrough.md`
-   `rule-application-guide.md

These documents explain **how** the refinement method is applied in
practice rather than the conceptual rationale behind the framework.

------------------------------------------------------------------------

# /templates --- Engineering Artefacts

The templates implement the two refinement mechanisms defined by the
Lifecycle Refinement Framework.

## Contextual Refinement (CR)

Supports governance-oriented reasoning through artefacts such as:

-   `context-description.md`
-   `responsibility-map.csv`
-   `principle-prioritisation.md`
-   `assumption-log.md`

## Functional Refinement (FR)

Supports engineering operationalisation through artefacts such as:

-   `artefact-derivation.md`
-   `traceability-matrix.csv`
-   `monitoring-plan.md`
-   `feedback-log.md`

## Optional phase-oriented guidance

-   `business-understanding.md`
-   `data-understanding.md`
-   `data-preparation.md`
-   `modeling.md`
-   `evaluation.md`
-   `deployment-monitoring.md`

All templates are intentionally:

-   technology-agnostic
-   domain-independent
-   reusable
-   adaptable to organisational engineering practices

------------------------------------------------------------------------

# /examples --- Illustrative Applications

This directory contains illustrative applications of the Lifecycle
Refinement Framework through its CRISP-TAI instantiation.

Examples may include:

-   Retrieval-Augmented Generation in Data Spaces
-   Federated Learning
-   AI-enabled Internet of Things (TrustAIoT)

Each example typically contains:

-   contextual description
-   refinement log
-   generated artefacts
-   traceability records
-   responsibility mappings

These examples are **illustrative applications of the framework through
its CRISP-TAI instantiation**, not production-ready reference
implementations.

------------------------------------------------------------------------

# /logs --- Refinement Records

Illustrative logs showing:

-   Context revision triggers
-   Refinement iterations
-   Monitoring feedback
-   Artefact evolution
-   Traceability updates

These records demonstrate lifecycle refinement and evaluability without
prescribing auditing procedures.

------------------------------------------------------------------------

# /appendices --- Supplementary Material

Contains extended engineering material supporting the examples when such
information exceeds the scope of the main repository.

------------------------------------------------------------------------

# Relationship to the Lifecycle Refinement Framework

The associated article introduces two complementary research
contributions.

1.  **The Lifecycle Refinement Framework**, a process-independent
    refinement method for operationalising Trustworthy AI.

2.  **CRISP-TAI**, the first instantiation of that framework
    over the CRISP-DM lifecycle.

This repository complements the second contribution by providing:

-   reusable engineering artefacts
-   implementation templates
-   refinement traces
-   practical guidance
-   illustrative applications

The repository intentionally focuses on implementation-oriented material
that exceeds the space available in the article.

------------------------------------------------------------------------

# Future Framework Instantiations

The Lifecycle Refinement Framework has been designed to remain
independent of any particular software process.

Although this repository currently contains only the CRISP-TAI
instantiation, future work may provide additional instantiations over
alternative software development processes.

------------------------------------------------------------------------

# Version and reproducibility

The repository is versioned to preserve traceability between the
engineering artefacts and the corresponding version of the Lifecycle
Refinement Framework described in the associated article.

The `CHANGELOG.md` records artefact-level changes across repository
versions. Releases associated with the article preserve the rule
definitions, templates, mappings, worked examples, and traceability
materials corresponding to that version of the framework.

For reproducibility, users should refer to the repository release or
version identified in `CITATION.cff` and `CHANGELOG.md`.

------------------------------------------------------------------------

# License and reuse

This repository is intended to support reuse and adaptation in both
research and industrial environments.

See `LICENSE` for licensing terms.

------------------------------------------------------------------------

# Citation

If you use CRISP-TAI or any artefacts contained in this repository,
please cite the associated research article.

Bibliographic information is provided in `CITATION.cff`.
