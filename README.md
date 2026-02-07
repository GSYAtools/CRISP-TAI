# CRISP-TAI — Technical Artefact for Practical Adoption

This repository provides a **technical artefact that complements the CRISP-TAI process model** presented in the associated research article.  
Its purpose is to support **practical adoption, instantiation, and reuse** of CRISP-TAI in real-world AI engineering projects.

> **Important scope note**  
> This repository does **not** reproduce the paper, its figures, or its conceptual explanations.  
> The article remains the authoritative source for the motivation, theoretical foundations, and validation of CRISP-TAI.  
> This repository focuses exclusively on **practical engineering artefacts**, templates, and example instantiations that cannot be fully detailed in an academic paper.

---

## What this repository is

- A **technical companion** to the CRISP-TAI article  
- A collection of **engineering artefacts** that operationalise the process model  
- A set of **templates and examples** to help practitioners apply CRISP-TAI  
- A reference for **traceability, evaluability, and governance-ready lifecycle documentation**

---

## What this repository is *not*

- ❌ Not a certification framework  
- ❌ Not an automated compliance or auditing tool  
- ❌ Not a checklist for Trustworthy AI  
- ❌ Not a metrics or benchmarking library  
- ❌ Not a replacement for human governance or organisational decision-making  

CRISP-TAI supports **evaluability and traceability**, not automated judgement or normative enforcement.

---

## Repository structure

```
/docs        Practical guidance for applying CRISP-TAI
/templates   Reusable engineering templates (CR / FR artefacts)
/examples    Cross-domain instantiations and execution traces
/logs        Illustrative rule-usage and refinement logs
/appendix    Extended tables and detailed traces referenced by examples
```

---

## /docs — Practitioner-oriented guidance

This directory contains **hands-on documentation** aimed at engineers and teams applying CRISP-TAI in practice.

Typical contents include:

- `getting-started.md`  
  How to start applying CRISP-TAI in an AI project

- `lifecycle-walkthrough.md`  
  A phase-by-phase walkthrough showing how trustworthiness considerations evolve across the lifecycle

- `rule-application-guide.md`  
  How Contextual Refinement (CR) and Functional Refinement (FR) rules are used in practice

- `governance-notes.md`  
  Practical notes on roles, responsibilities, reviews, and organisational integration

These documents **extend** the paper by focusing on *how* CRISP-TAI is applied, not *why* it is valid.

---

## /templates — Core engineering artefacts

This directory contains **reusable templates** that implement the CRISP-TAI refinement mechanisms.

### Contextual Refinement templates
Used to support reflexive and governance-oriented reasoning:

- `context-description.md`
- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`

### Functional Refinement templates
Used to translate refined interpretations into concrete artefacts:

- `artefact-derivation.md`
- `traceability-matrix.csv`
- `monitoring-plan.md`
- `feedback-log.md`

### Phase-oriented checklists
Optional lightweight guidance per lifecycle phase:

- `business-understanding.md`
- `data-understanding.md`
- `data-preparation.md`
- `modeling.md`
- `evaluation.md`
- `deployment-monitoring.md`

All templates are **technology-agnostic**, **domain-independent**, and intended to be adapted to local engineering practices.

---

## /examples — Execution-based instantiations

This directory contains **illustrative instantiations of CRISP-TAI** in heterogeneous settings, reflecting the execution-based validation discussed in the paper.

Examples may include:

- Retrieval-Augmented Generation in Data Spaces  
- Federated Learning environments  
- AI-enabled Internet of Things (TrustAIoT)  

Each example typically includes:

- A short contextual description (`README.md`)  
- An `instantiation-log.md` documenting applied CR/FR rules  
- Selected artefacts derived during execution (anonymised or synthetic)  
- Traceability and responsibility records  

These examples are **not reference implementations**, but **evidence of instantiability and practical use**.

---

## /logs — Refinement and traceability records

This directory provides **illustrative logs** showing how refinement rules may be activated and revisited over time, for example:

- Context revision triggers  
- Artefact updates  
- Monitoring feedback loops  

These logs support **evaluability and audit-readiness** without prescribing auditing procedures.

---

## /appendix — Supplementary material

Contains extended tables, detailed traces, or supporting material referenced by examples, when such detail would clutter the main repository structure.

---

## Relationship to the research article

The CRISP-TAI article presents:

- The motivation and problem framing  
- The design rationale of the process model  
- The distinction between operational and reflexive reasoning  
- The execution-based validation across domains  

This repository provides:

- The **engineering artefacts** that make CRISP-TAI usable in practice  
- The **templates and traces** that operationalise the model  
- Additional material that supports adoption but exceeds article length constraints  

For conceptual, methodological, and validation details, **refer to the article**.

---

## License and reuse

This repository is intended to support reuse and adaptation in both research and industrial contexts.  
See `LICENSE` for terms of use.

---

## Citation

If you use CRISP-TAI or artefacts from this repository in academic work, please cite the associated article.

Citation details are provided in `CITATION.cff`.


