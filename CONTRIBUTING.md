# Contributing to CRISP-TAI

Thank you for your interest in contributing to the CRISP-TAI technical
repository.

This repository accompanies the research article introducing the
**Lifecycle Refinement Framework (LRF)** and its first instantiation,
**CRISP-TAI**, over the CRISP-DM lifecycle. It provides practical
engineering artefacts, templates, illustrative applications, refinement
records, and practitioner-oriented guidance supporting the application
and adaptation of CRISP-TAI in real-world settings.

Contributions to this repository therefore concern the **CRISP-TAI
technical instantiation and its supporting artefacts**. They should
remain aligned with the process-independent Lifecycle Refinement
Framework defined in the associated article.

Contributions are welcome, provided they align with the scope and
principles outlined below.

---

## Scope of contributions

This repository accepts contributions that:

- Extend or refine **engineering templates** supporting the application
  of CR and FR within CRISP-TAI
- Add **illustrative applications** demonstrating how the framework can
  be applied through CRISP-TAI in concrete contexts
- Improve **practitioner-oriented documentation**
- Clarify or enhance **traceability, evaluability, or governance-related
  artefacts**
- Improve the documentation of **process-specific instantiation** from
  process-independent engineering representations to CRISP-DM lifecycle
  elements and artefacts
- Improve refinement records, worked examples, or other supporting
  materials without altering the methodological meaning of the
  underlying Lifecycle Refinement Framework

Contributions should focus on **process-level support and practical
application of CRISP-TAI**, not on specific tools, algorithms, or
metrics.

---

## Relationship to the Lifecycle Refinement Framework

The Lifecycle Refinement Framework and CRISP-TAI operate at different
levels.

- The **Lifecycle Refinement Framework** defines the process-independent
  refinement method, including Contextual Refinement (CR), Functional
  Refinement (FR), and the separation between refinement outputs and
  subsequent process-specific instantiation.
- **CRISP-TAI** is the first instantiation of that framework over the
  CRISP-DM lifecycle.

Contributions to this repository may extend, clarify, or improve the
technical artefacts supporting CRISP-TAI, but should preserve this
architectural separation.

The canonical CR and FR rule definitions associated with a released
version of the repository should remain aligned with the corresponding
version of the Lifecycle Refinement Framework described in the
associated article. Changes that modify the methodological definition of
the framework or the canonical CR/FR rule catalogue require explicit
methodological justification and corresponding versioning rather than
being treated as ordinary CRISP-TAI artefact updates.

---

## What is out of scope

To preserve the integrity and intent of the Lifecycle Refinement
Framework and its CRISP-TAI instantiation, the following types of
contributions are **out of scope** as ordinary CRISP-TAI artefact
contributions:

- Certification schemes or compliance checklists
- Automated auditing or trustworthiness scoring tools
- Prescriptive or normative policy frameworks
- Domain-specific hard-coded metrics or thresholds
- Implementations that replace human judgement with automated decisions
- Unversioned changes to the canonical CR or FR rule definitions
- Changes that collapse process-independent refinement into
  process-specific lifecycle mapping

CRISP-TAI is designed to support **reasoned decision-making,
traceability, engineering operationalisation, and evaluability**, not
automated compliance or normative enforcement.

---

## Types of contributions

### 1. Templates and artefacts

Contributions may include:

- New or improved templates in `/templates`
- Additional traceability or documentation artefacts
- Artefacts supporting process-specific instantiation within CRISP-TAI
- Enhancements that improve clarity, reuse, or adaptability

Each template contribution should include:

- A short description of its purpose
- An example of how it would be used in practice
- Clear alignment with the applicable CR or FR refinement mechanism or
  rule
- Where applicable, an indication of whether the artefact represents a
  contextual interpretation, a process-independent engineering
  representation, or a process-specific lifecycle artefact

Templates should support the application of the framework without
redefining the canonical CR or FR rules themselves.

---

### 2. Illustrative applications

Contributions to `/examples` are particularly welcome.

Examples should:

- Describe the **context and system scope**
- Indicate which **CR and FR rules** were applied
- Identify the relevant **contextual decisions or interpretations**
- Identify the resulting **process-independent engineering
  representations**
- Document their subsequent **process-specific instantiation** within
  CRISP-TAI, where applicable
- Include representative artefacts (anonymised or synthetic)
- Document decisions, assumptions, traceability relations, and revision
  triggers

Examples do not need to be complete implementations. Their purpose is to
demonstrate **practical application, traceability, and instantiation
reasoning** rather than to constitute production-ready reference
implementations or independent empirical validation.

---

### 3. Documentation

Improvements to documentation in `/docs` may include:

- Clarifications for practitioners
- Step-by-step walkthroughs
- Explanations of how CR and FR rules are applied in practice
- Guidance on the transition from process-independent refinement outputs
  to process-specific lifecycle instantiation
- Notes on governance integration or organisational adoption

Documentation should complement the associated article, not replicate
its conceptual or scientific content.

---

## Contribution process

1. Fork the repository.
2. Create a branch describing your contribution.
3. Make your changes following the repository structure.
4. Open a pull request with:
   - A clear description of the contribution
   - The motivation for the change
   - Any relevant context or examples
   - The CR or FR rules affected, where applicable
   - Any implications for repository versioning or compatibility with
     existing artefacts

Where applicable, contributions should indicate whether the affected
material concerns contextual interpretation, process-independent
engineering representation, process-specific instantiation, or a
lifecycle artefact.

Any proposed change to the canonical definition of a CR or FR rule
should be explicitly identified as a methodological change rather than
as an ordinary artefact contribution.

---

## Review criteria

Contributions will be reviewed based on:

- Alignment with the Lifecycle Refinement Framework and its CRISP-TAI
  instantiation
- Preservation of the distinction between process-independent refinement
  and process-specific lifecycle instantiation
- Traceability between contextual decisions, engineering
  representations, and lifecycle artefacts where applicable
- Consistency with the canonical CR and FR rule definitions associated
  with the repository version
- Clarity and usefulness for practitioners
- Preservation of a non-normative, process-oriented approach
- Avoidance of hard-coded metrics or automated judgement
- Appropriate versioning where a contribution affects methodological or
  structural artefacts

---

## Use of prior material

If your contribution is derived from prior publications, industrial
projects, or internal documentation:

- Ensure that you have the right to share the material
- Anonymise sensitive information
- Clearly indicate the origin of the artefacts

---

## Questions and discussion

If you are unsure whether a contribution fits the scope, please open an
issue for discussion before submitting a pull request.

---

By contributing to this repository, you agree that your contributions
will be licensed under the same license as the rest of the repository.
