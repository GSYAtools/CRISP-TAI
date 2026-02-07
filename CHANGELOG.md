# Changelog

This changelog documents **structural and artefact-level changes** to the CRISP-TAI
technical repository. It focuses on changes relevant to **practical adoption,
reuse, and traceability**, rather than on the conceptual evolution described in
the associated research article.

The research article remains the authoritative source for theoretical,
methodological, and validation-related contributions.

---

## [0.1.0] — Initial public artefact release

### Added

#### Repository governance
- `README.md` clarifying the scope of the repository as a technical artefact
  complementary to the research article.
- `CITATION.cff` indicating the associated article (currently under review).
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

#### Execution-based example instantiations
- RAG in Federated Data Spaces.
- Federated Learning with early trustworthiness monitoring.
- TrustAIoT platform-level governance.

Each example includes contextual and functional artefacts, together with
pointers to canonical execution logs.

#### Canonical execution logs
- Centralised instantiation logs under `/logs`, documenting execution-based
  application of CRISP-TAI refinement rules for each example.
- Lightweight pointer files in `/examples` to avoid duplication while
  preserving example readability.

#### Technical appendix material
- `/appendix/figures/` containing expanded, practitioner-oriented lifecycle
  diagrams reused from prior work.
- `/appendix/activity-selection-trace/` documenting the traceability and
  rationale behind trustworthiness-related activity selection for each
  lifecycle phase.

### Notes
- This version provides **process-level artefacts, templates, and examples**.
- The repository does **not** include tooling, metrics, or certification
  mechanisms.
- Examples are illustrative and may evolve independently of the research
  article.

---

## Planned

- Minor documentation refinements based on practitioner feedback.
- Additional example instantiations in other domains.
- Clarifications and extensions to appendix material where needed.
