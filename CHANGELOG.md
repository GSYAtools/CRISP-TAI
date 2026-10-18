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
- Aligned the RAG-in-Data-Spaces retrospective reconstruction with
  **CR.1--CR.3**, **FR.1--FR.2**, and the case-level evidence for **P1** and
  **P2** reported in the revised manuscript.
- Aligned the Federated Learning retrospective reconstruction with
  **CR.3**, **FR.1**, and the case-level evidence for **P2**, distinguishing
  the paper-supported refinement chain from additional technical
  characteristics of the original study.
- Aligned the TrustAIoT retrospective reconstruction with
  **CR.4**, **CR.6**, **FR.4**, **FR.6**, and the case-level evidence for
  **P1**, **P2**, and **P3**.
- Clarified that **P4 — Cross-Domain Adaptability** is assessed through the
  cross-case comparison rather than attributed independently to any one
  retrospective application.
- Added explicit traceability summaries linking documentary case evidence,
  reconstructed CR and FR rules, process-independent Engineering
  Representations where applicable, documented Process Instantiation, and
  the assessment criteria supported by each case.
- Linked each retrospective application record to the reusable repository
  templates that can represent the reconstructed refinement and
  instantiation chain.
- Distinguished case-specific technical or lifecycle characteristics from
  evidence that a corresponding CR or FR rule was actually reconstructed.

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
  `engineering-representation.md`.
- Revised the worked examples to distinguish explicitly among:
  - **paper-supported retrospective reconstruction**,
  - **supporting repository representations**, and
  - **additional illustrative template usage**.
- Clarified that availability or completion of a reusable template does not
  imply that the CR or FR rule associated with that template was
  reconstructed for the corresponding case.
- Revised the worked examples to distinguish documentary case evidence from
  retrospectively reconstructed refinement records and to state explicitly
  that the completed artefacts are not original project records.
- Removed unsupported claims of prospective CRISP-TAI execution, complete
  CR/FR rule coverage, execution-based validation, and independent empirical
  validation from the example documentation.
- Removed or reformulated unsupported fixed priority rankings, review
  frequencies, dates, thresholds, organisational actors, and historical
  actions where the available documentary evidence did not justify them.
- Standardised example-level identifiers linking contextual records,
  assumptions, Engineering Representations, Process Instantiations,
  monitoring evidence, feedback, and traceability records.
- Removed obsolete or inferred identifiers where they were no longer required
  by the paper-supported reconstruction.
- Revised the worked traceability matrices so that repository-level
  traceability does not itself imply reconstruction of
  **FR.2 — Decision Traceability**.
- Clarified similarly that use of Engineering Representations in a worked
  example does not itself imply reconstruction of
  **FR.1 — Engineering Representation Derivation**.
- Separated `framework_instantiation` (`CRISP-TAI`) from `target_process`
  (`CRISP-DM`) in the worked traceability matrices.
- Preserved the distinction between process-independent Engineering
  Representations and the concrete architectural, statistical, lifecycle,
  or operational mechanisms through which they are retrospectively
  instantiated.

##### RAG in Federated Data Spaces worked example

- Aligned the paper-supported RAG reconstruction with:
  - **CR.1 — Context Interpretation**
  - **CR.2 — Responsibility Allocation**
  - **CR.3 — Principle Prioritisation**
  - **FR.1 — Engineering Representation Derivation**
  - **FR.2 — Decision Traceability**
  - **P1 — Lifecycle Anchoring**
  - **P2 — Coordinated Contextual and Functional Refinement**
- Reconstructed the documented distributed-governance, provenance,
  responsibility, source-identification, and architectural context without
  extending the rule coverage beyond that reported in the revised manuscript.
- Reconstructed the CR.3 decision around the documented architectural
  trade-off between **sovereignty, distributed control, and traceability**
  and **response latency**, rather than assigning unsupported fixed
  trustworthiness-principle rankings.
- Standardised the principal RAG Engineering Representations as:
  - `RAG-ER01` — distributed-control representation
  - `RAG-ER02` — provenance representation
  - `RAG-ER03` — traceability representation
- Distinguished those process-independent representations from their
  documented architectural enactment through role allocation, source
  metadata, provenance mechanisms, source-labelled retrieval, and
  architectural traceability mechanisms.
- Removed the inferred `RAG-R04` governance-function record and retained the
  documented Data Provider, Federator, and Data Consumer responsibility
  structure.
- Reclassified assumption, monitoring, and feedback artefacts as
  **additional illustrative template usage** where the associated article
  does not reconstruct CR.4, CR.5, FR.3, FR.4, FR.6, or P3 for the RAG case.
- Preserved conditional review paths without representing them as historical
  feedback, revision, or continuity events.

##### Federated Learning worked example

- Restricted the paper-supported Federated Learning reconstruction to:
  - **CR.3 — Principle Prioritisation**
  - **FR.1 — Engineering Representation Derivation**
  - **P2 — Coordinated Contextual and Functional Refinement**
- Reconstructed the CR.3 operational priority as the requirement for
  **lightweight early detection of strong and stealthy adversarial behaviour
  while remaining compatible with secure aggregation**.
- Standardised the principal Federated Learning Engineering Representations
  as:
  - `FL-ER01` — lightweight early-detection representation
  - `FL-ER02` — benign-reference calibration representation
  - `FL-ER03` — threshold-based monitoring representation
- Linked those representations retrospectively to documented technical
  mechanisms including pre-aggregation client-level early-warning detection,
  the benign reference distribution, bootstrap calibration, statistical
  distance measures, and per-feature detection thresholds.
- Added explicit links from the reconstructed Engineering Representations to
  experimental evidence including benign updates, strong and stealthy attack
  scenarios, independent experimental runs, and observed threshold
  exceedances.
- Treated pre-aggregation placement as documented technical-instantiation
  evidence rather than as independent reconstruction of CR.6, FR.5, or P1.
- Treated repeated technical monitoring across training rounds as distinct
  from FR.4, FR.6, and P3.
- Reclassified `context-description.md`, `responsibility-map.csv`,
  `assumption-log.md`, `monitoring-plan.md`, and `feedback-log.md` as
  supporting or additional illustrative template usage where they exceed the
  paper-supported CR.3 / FR.1 reconstruction.
- Removed obsolete contextual-decision and governance records associated with
  the earlier broader reconstruction, including `FL-CD02`, `FL-CD03`, and the
  inferred governance-board responsibility record.
- Removed claims of paper-supported operational adjustment, lifecycle
  anchoring, iterative feedback integration, and continuity enforcement from
  the Federated Learning worked example.

##### TrustAIoT worked example

- Aligned the paper-supported TrustAIoT reconstruction with:
  - **CR.4 — Assumption Documentation**
  - **CR.6 — Lifecycle Anchoring**
  - **FR.4 — Iterative Feedback Integration**
  - **FR.6 — Continuity Enforcement**
  - **P1 — Lifecycle Anchoring**
  - **P2 — Coordinated Contextual and Functional Refinement**
  - **P3 — Continuity and Iterative Feedback**
- Made the CR.4 reconstruction explicit through contextual assumptions and
  validity conditions grounded in stakeholder requirements, regulatory and
  governance conditions, platform/project relationships, monitoring,
  maintenance, and feedback evidence.
- Made the CR.6 reconstruction explicit through documented lifecycle
  dependencies associated with governance, testing and validation,
  deployment, monitoring, feedback, maintenance, change management, platform
  updates, and policy adaptation.
- Standardised the supporting TrustAIoT Engineering Representations as:
  - `TAIOT-ER01` — lifecycle governance and anchoring representation
  - `TAIOT-ER02` — monitoring and feedback representation
  - `TAIOT-ER03` — continuity and adaptation representation
- Clarified that these Engineering Representations are supporting repository
  representations and do not imply independent reconstruction of FR.1 for
  TrustAIoT.
- Reconstructed FR.4 through documented monitoring, validation, stakeholder,
  governance, and policy evidence linked back to existing contextual or
  engineering records.
- Reconstructed FR.6 through documented continuity of monitoring, review,
  maintenance, responsibility, update, change-management, and
  policy-adaptation obligations during platform evolution.
- Reclassified the responsibility and principle-prioritisation artefacts as
  supporting template representations rather than independent CR.2 or CR.3
  reconstruction.
- Removed obsolete intermediate contextual-decision identifiers
  `TAIOT-CD01`, `TAIOT-CD02`, and `TAIOT-CD03`.
- Retained CR.5 only as a **conditional framework path** where FR.4 evidence
  materially invalidates a CR.4 assumption; CR.5 is not claimed as an
  additional TrustAIoT case-level reconstruction.
- Removed FR.3 from the paper-supported TrustAIoT reconstruction and retained
  subsequent engineering or process-specific change only as a possible
  consequence of evidence review where justified.
- Linked FR.4 and FR.6 explicitly to the case-level evidence for P2 and P3,
  while preserving CR.6 and documented Process Instantiation as the basis for
  P1.

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
