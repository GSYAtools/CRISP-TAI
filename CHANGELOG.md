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
  **process-independent Engineering Representations**, and their subsequent
  **process-specific instantiation** as lifecycle artefacts or operational
  mechanisms.
- Revised terminology for the cross-domain cases to describe them as
  retrospective applications of the framework through CRISP-TAI rather than
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
  Engineering Representations, Process Instantiation, and lifecycle
  artefacts.

#### Practitioner documentation

- Updated `docs/getting-started.md` to distinguish Contextual Refinement,
  Functional Refinement, process-independent Engineering Representations,
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
  process-independent Engineering Representations from subsequently
  instantiated lifecycle artefacts.
- Updated the Functional Refinement templates to distinguish Engineering
  Representation, operational evidence, feedback integration, continuity,
  and subsequent process-specific instantiation.
- Expanded `traceability-matrix.csv` to preserve explicit links between
  contextual decisions, process-independent Engineering Representations,
  lifecycle anchoring and placement constraints, Process Instantiation, and
  instantiated lifecycle artefacts.
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
  process-independent Engineering Representations, and documented
  process-specific instantiation.
- Updated the Federated Learning record to distinguish operational and
  contextual constraints, reconstructed detection, monitoring, adjustment,
  and continuity representations, and their documented technical enactment.
- Updated the TrustAIoT record to distinguish contextual assumptions and
  lifecycle anchoring from reconstructed feedback and continuity
  representations and their documented process-specific enactment.
- Added explicit traceability summaries linking documentary case evidence,
  reconstructed CR and FR rules, process-independent Engineering
  Representations, and documented instantiation evidence.
- Linked each retrospective application record to the reusable repository
  templates that can represent the reconstructed refinement and
  instantiation chain.

#### Worked retrospective examples

- Reworked the three `/examples` cases as **retrospectively completed worked
  examples** of the v0.2.0 reusable templates rather than as records of
  prospective CRISP-TAI execution.
- Standardised the TrustAIoT, Federated Learning, and RAG-in-Data-Spaces
  example directories around a common structure containing:
  - `README.md`
  - `context-description.md`
  - `responsibility-map.csv`
  - `principle-prioritisation.md`
  - `assumption-log.md`
  - `engineering-representation.md`
  - `traceability-matrix.csv`
  - `monitoring-plan.md`
  - `feedback-log.md`
- Removed the redundant example-level `instantiation-log.md` pointer files;
  the canonical methodological reconstructions are now maintained under
  `/logs` as retrospective application records.
- Renamed example-level `artefact-derivation.md` files to
  `engineering-representation.md` and revised their contents to distinguish
  contextual decisions, process-independent Engineering Representations, and
  subsequent Process Instantiation.
- Revised the worked examples to distinguish documentary case evidence from
  retrospectively reconstructed refinement records and to state explicitly
  that the completed artefacts are not original project records.
- Removed unsupported claims of prospective CRISP-TAI execution, complete
  CR/FR rule coverage, execution-based validation, and independent empirical
  validation from the example documentation.
- Removed or reformulated unsupported fixed priority rankings, review
  frequencies, dates, thresholds, and historical actions where the available
  documentary evidence did not justify them.
- Standardised example-level identifiers linking contextual decisions,
  assumptions, Engineering Representations, Process Instantiations, monitoring
  evidence, feedback, and traceability records.
- Expanded the worked traceability matrices to represent the chain:
  **contextual decision → Engineering Representation → instantiation
  constraints → Process Instantiation → documented process-specific
  enactment**.
- Separated `framework_instantiation` (`CRISP-TAI`) from `target_process`
  (`CRISP-DM`) in the worked traceability matrices.
- Treated availability of a traceability field as distinct from evidence that
  a corresponding CR or FR rule was reconstructed, avoiding artificial rule
  coverage.

##### TrustAIoT worked example

- Reconstructed contextual assumptions, governance conditions, lifecycle
  anchoring, monitoring, feedback, continuity, and contextual adaptation from
  documented TrustAIoT material.
- Introduced explicit Engineering Representations for governance/lifecycle
  traceability, monitoring/continuity, and contextual revision.
- Linked those representations retrospectively to documented BPMN lifecycle
  activities, governance mechanisms, continuous monitoring, user feedback,
  maintenance, change management, and policy-adaptation mechanisms.
- Represented monitoring and feedback as evidence-to-decision paths rather
  than as automatic revision mechanisms.

##### Federated Learning worked example

- Reconstructed the distributed, partially observable Federated Learning
  context, including secure aggregation, repeated training rounds, adversarial
  risk, and early pre-aggregation detection.
- Introduced explicit Engineering Representations for early detection and
  monitoring, operational review and adjustment, and continuity across
  successive training rounds.
- Represented **lifecycle anchoring before aggregation** explicitly while
  preserving the distinction between anchoring constraints and final
  process-specific technical placement.
- Separated detection evidence from operational or governance decisions and
  removed direct `alert → action` relationships from the earlier example.
- Clarified that FR.3 represents a required operational adjustment through a
  new or revised Engineering Representation and does not itself execute
  client exclusion, threshold changes, configuration changes, or other
  interventions.

##### RAG in Federated Data Spaces worked example

- Refocused the worked example on the documentary evidence most strongly
  supported by the retrospective assessment: distributed governance,
  responsibility, source identification, provenance, and traceability.
- Introduced explicit Engineering Representations for responsibility and
  governance traceability, provenance and source identification, and
  information-use traceability.
- Distinguished these process-independent representations from the documented
  source metadata, provenance mechanisms, traceability structures, and
  architectural relationships through which they are retrospectively
  instantiated.
- Kept monitoring and feedback artefacts deliberately conditional and limited
  where the documentary evidence did not support reconstruction of historical
  monitoring schedules, feedback events, operational adjustments, or
  continuity mechanisms.
- Demonstrated that reusable templates do not require artificial completion of
  every refinement rule or lifecycle property in every application setting.

#### Design provenance and supplementary material

- Updated `/appendices/activity-selection-trace/` to identify the phase-level
  activity-selection records explicitly as **design-provenance material**
  documenting the construction of the CRISP-TAI instantiation.
- Clarified that the phase associations in the activity-selection traces are
  process-specific and do not imply that CR or FR rules are intrinsically
  tied to particular CRISP-DM lifecycle phases.
- Clarified that references between historical phase-level activities and
  current CR or FR rules represent **retrospective correspondences**, while
  final lifecycle placement belongs to Process Instantiation.
- Updated the Business Understanding trace to relate its historical design
  concerns retrospectively to contextual interpretation, responsibility
  allocation, and principle prioritisation without treating CR.1--CR.3 as
  phase-specific rules.
- Updated the Data Preparation trace to distinguish historical preprocessing
  activities from the process-independent Engineering Representation and
  traceability functions subsequently formalised through FR.1 and FR.2.
- Updated the Evaluation trace to distinguish its process-specific evaluation
  activities from the iterative feedback function subsequently formalised
  through FR.4.
- Updated the Data Understanding, Modeling, and Continuous Deployment &
  Monitoring traces to clarify their role as CRISP-TAI design provenance and
  preserve the distinction between historical activity selection and the
  process-independent refinement mechanisms.
- Corrected phase-level trace filenames for consistency, including
  `business-understanding.md` and `data-preparation.md`.
- Retained the six expanded lifecycle figures under `/appendices/figures/` as
  supplementary design-provenance material documenting the detailed
  phase-level construction of CRISP-TAI.
- Clarified that the supplementary figures and activity-selection traces do
  not introduce new refinement rules, requirements, or validation claims.

#### Citation and version information

- Updated `CITATION.cff` to identify repository version `0.2.0`.
- Added explicit repository metadata and Apache-2.0 license information.
- Linked the repository version to the revised manuscript
  *A Process-Independent Framework for Lifecycle Refinement in Trustworthy AI*.

### Release scope

Version 0.2.0 completes repository-wide alignment with the revised manuscript
across the root governance files, practitioner documentation, reusable
templates, retrospective application records, worked examples, and
supplementary design-provenance material.

The release is intended to support **inspectability, reuse, traceability, and
reproducibility of the refinement and instantiation structure**. It does not
claim prospective empirical validation of the Lifecycle Refinement Framework
or CRISP-TAI.

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
