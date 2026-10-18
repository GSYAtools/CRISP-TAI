# Changelog

This changelog documents **structural and artefact-level changes** to the
CRISP-TAI technical repository. It focuses on changes relevant to
**practical adoption, reuse, traceability, and reproducibility**, rather
than on the conceptual evolution described in the associated research
article.

The research article remains the authoritative source for theoretical,
methodological, and validation-related contributions.

---

## [0.2.0] — Revised manuscript alignment

Version 0.2.0 aligns the CRISP-TAI technical repository with the revised
version of the associated research article and with the process-independent
Lifecycle Refinement Framework defined therein.

This release preserves the distinction between the **Lifecycle Refinement
Framework**, which defines the process-independent refinement method, and
**CRISP-TAI**, its first instantiation over the CRISP-DM lifecycle.

### Changed

#### Repository scope and terminology

- Updated `README.md` to distinguish explicitly between the
  process-independent Lifecycle Refinement Framework and its first
  process-specific instantiation, CRISP-TAI.
- Clarified the distinction between **contextual interpretations**,
  **process-independent engineering representations**, and their subsequent
  **process-specific instantiation** as lifecycle artefacts.
- Revised terminology for the cross-domain examples to describe them as
  illustrative applications of the framework through CRISP-TAI rather than
  as independent framework instantiations.
- Updated repository structure references to use `/appendices`.

#### Contribution governance

- Updated `CONTRIBUTING.md` to clarify that ordinary contributions concern
  the CRISP-TAI technical instantiation and its supporting artefacts.
- Added explicit requirements to preserve the separation between
  process-independent refinement and process-specific lifecycle
  instantiation.
- Added versioning expectations for proposed methodological changes to the
  canonical CR and FR rule definitions.
- Added traceability expectations connecting contextual decisions,
  engineering representations, and lifecycle artefacts.

#### Practitioner documentation

- Updated `docs/getting-started.md` to distinguish Contextual Refinement,
  Functional Refinement, process-independent engineering representations,
  and subsequent Process Instantiation.
- Updated `docs/rule-application-guide.md` to reflect the canonical
  CR.1--CR.7 and FR.1--FR.6 rule definitions and their common operational
  structure of input, trigger, responsible role(s), procedure, expected
  output, and verification/evidence.
- Updated `docs/lifecycle-walkthrough.md` to present phase-level associations
  as CRISP-TAI instantiation mappings rather than as intrinsic lifecycle
  locations of the process-independent CR and FR rules.

#### Refinement templates and traceability

- Updated the Contextual Refinement templates to align their documented
  inputs, triggers, responsibilities, outputs, revision conditions, and
  supporting evidence with the revised CR rule definitions.
- Renamed `templates/functional-refinement/artefact-derivation.md` to
  `templates/functional-refinement/engineering-representation.md` to align
  with **FR.1 — Engineering Representation Derivation** and distinguish
  process-independent engineering representations from subsequently
  instantiated lifecycle artefacts.
- Updated the Functional Refinement templates to distinguish engineering
  representation, operational evidence, feedback integration, continuity,
  and subsequent process-specific instantiation.
- Expanded `traceability-matrix.csv` to preserve explicit links between
  contextual decisions, process-independent engineering representations,
  lifecycle anchoring and placement constraints, process-specific
  instantiation, and instantiated lifecycle artefacts.
- Updated monitoring and feedback templates to preserve the
  evidence-to-decision chain across FR.4, CR.5, subsequent re-refinement,
  and process-specific re-instantiation where required.

#### Retrospective application records

- Reframed the former execution-based instantiation logs as
  **retrospective application records** to align repository claims with the
  retrospective analytical evaluation reported in the revised manuscript.
- Renamed `logs/rag-data-spaces-instantiation-log.md` to
  `logs/rag-data-spaces-retrospective-application.md`.
- Renamed `logs/federated-learning--instantiation-log.md` to
  `logs/federated-learning-retrospective-application.md`.
- Renamed `logs/trustaiot-instantiation-log.md` to
  `logs/trustaiot-retrospective-application.md`.
- Removed claims implying prospective execution, execution-based validation,
  or independent empirical validation of CRISP-TAI in the three original
  case studies.
- Updated the RAG-in-Data-Spaces record to distinguish documented governance
  and provenance evidence, reconstructed Contextual Refinement, reconstructed
  process-independent engineering representations, and documented
  process-specific instantiation.
- Updated the Federated Learning record to distinguish operational and
  contextual constraints, reconstructed detection, monitoring, adjustment,
  and continuity representations, and their documented technical enactment.
- Updated the TrustAIoT record to distinguish contextual assumptions and
  lifecycle anchoring from reconstructed feedback and continuity
  representations and their documented process-specific enactment.
- Added explicit traceability summaries linking documentary case evidence,
  reconstructed CR and FR rules, process-independent engineering
  representations, and documented instantiation evidence.
- Linked each retrospective application record to the reusable repository
  templates that can represent the reconstructed refinement and
  instantiation chain.

#### Citation and version information

- Updated `CITATION.cff` to identify repository version `0.2.0`.
- Added explicit repository metadata and Apache-2.0 license information.
- Linked the repository version to the revised manuscript
  *A Process-Independent Framework for Lifecycle Refinement in Trustworthy AI*.

### Repository alignment under review

The remaining illustrative applications and supplementary materials in
`/examples` and `/appendices` are being reviewed for consistency with the
revised framework specification. Their corresponding changes will be recorded
in this section before version 0.2.0 is released.

---

## [0.1.0] — Initial public artefact release

### Added

#### Repository governance

- `README.md` clarifying the scope of the repository as a technical artefact
  complementary to the research article.
- `CITATION.cff` indicating the associated article.
- `LICENSE` (Apache 2.0).
- `CONTRIBUTING.md` defining the scope and rules for contributions.
- `CHANGELOG.md` documenting artefact-level evolution.

#### Practitioner documentation

- `docs/getting-started.md` providing a minimal, non-disruptive entry point
  for adopting CRISP-TAI.
- `docs/rule-application-guide.md` explaining how Contextual Refinement (CR)
  and Functional Refinement (FR) rules are applied in practice.
- `docs/lifecycle-walkthrough.md` offering a phase-by-phase walkthrough of
  CRISP-TAI across the lifecycle.

#### Contextual Refinement (CR) templates

- `templates/contextual-refinement/context-description.md`
- `templates/contextual-refinement/responsibility-map.csv`
- `templates/contextual-refinement/principle-prioritisation.md`
- `templates/contextual-refinement/assumption-log.md`

#### Functional Refinement (FR) templates

- `templates/functional-refinement/artefact-derivation.md`
- `templates/functional-refinement/traceability-matrix.csv`
- `templates/functional-refinement/monitoring-plan.md`
- `templates/functional-refinement/feedback-log.md`

#### Illustrative applications

- RAG in Federated Data Spaces.
- Federated Learning with early trustworthiness monitoring.
- TrustAIoT platform-level governance.

Each example includes contextual and functional artefacts, together with
pointers to canonical execution logs.

#### Canonical execution logs

- Centralised execution logs under `/logs`, documenting application of
  CRISP-TAI refinement rules for each example.
- Lightweight pointer files in `/examples` to avoid duplication while
  preserving example readability.

#### Technical appendix material

- `/appendices/figures/` containing expanded, practitioner-oriented lifecycle
  diagrams reused from prior work.
- `/appendices/activity-selection-trace/` documenting the traceability and
  rationale behind trustworthiness-related activity selection for each
  lifecycle phase.

### Notes

- This version provides **process-level artefacts, templates, and examples**.
- The repository does **not** include tooling, metrics, or certification
  mechanisms.
- The examples are illustrative applications and are not production-ready
  reference implementations or independent empirical validations.

---

## Planned

- Additional framework instantiations over alternative software development
  processes.
- Additional illustrative applications in other domains.
- Practitioner-driven documentation and template refinements.
- Further lifecycle-aware tooling and integration guidance where appropriate.
