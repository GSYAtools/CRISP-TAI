# Principle Prioritisation — RAG in Federated Data Spaces Worked Example

This document is an **illustrative retrospective completion** of the
`principle-prioritisation.md` template using documentary evidence from the
RAG-in-Data-Spaces case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact illustrates how **CR.3 — Principle Prioritisation** can
represent a context-dependent priority or constraint where the documentary
evidence supports one.

The retrospective reconstruction does not infer a complete ranking of
trustworthiness principles.

---

## 1. Prioritisation record

- Record ID: `RAG-PRIO-01`
- System or component: RAG in Federated Data Spaces
- Trigger for prioritisation: Information from distributed sources must be
  retrieved and used while preserving relevant governance, provenance, and
  responsibility information
- Decision context: Governed retrieval and subsequent use of information in a
  multi-actor federated setting
- Responsible role(s): Reconstructed Data Provider, Data Consumer,
  Federator, and governance actors
- Related context record: `RAG-CTX-01`
- Related responsibility records: `RAG-R01` to `RAG-R04`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Applicable trustworthiness principles or concerns

The documentary evidence supports several interrelated concerns relevant to
the federated RAG setting.

| Principle / concern | Why applicable | Contextual constraint or expectation | Relevant actor(s) |
|---|---|---|---|
| Governance and responsibility | Information provision, federation, retrieval, and use involve different actors | Responsibility boundaries associated with source provision, federation, and information use should remain explicit | Data Provider; Data Consumer; Federator; Governance Function |
| Provenance | Retrieved information originates from distributed governed sources | Relevant source and provenance information should remain associated with retrieved information where supported by the documented architecture | Data Provider; Federator |
| Traceability | The relationship between information sources, retrieval, and subsequent use must remain reconstructable | Sufficient metadata and provenance information should be preserved to support traceability | Federator; Data Consumer |
| Transparency of information origin | Users or responsible actors may need to understand the origin of information used by the RAG system | Source-identification information should remain available where required by the documented use context | Data Provider; Federator; Data Consumer |
| Governed information use | Distributed information sources are subject to source-specific governance conditions | Retrieval and use should remain connected to the applicable governance information represented in the federated setting | Data Provider; Data Consumer; Governance Function |

The presence of these concerns does not establish a universal ordering among
trustworthiness principles.

---

## 3. Tensions and dependencies

The retrospective reconstruction supports dependencies among governance,
provenance, traceability, and system operation.

| Tension / dependency | Concerns involved | Contextual consideration | Retrospective interpretation |
|---|---|---|---|
| Retrieval utility vs. provenance preservation | Retrieval utility; provenance; traceability | Additional source and provenance information may introduce operational or architectural overhead | Provenance should not be discarded solely to simplify retrieval or subsequent information use |
| Distributed autonomy vs. end-to-end traceability | Source governance; federation; traceability | Different actors control different parts of the information chain | Traceability must preserve actor and responsibility boundaries rather than collapse them into a single central responsibility |
| Information use vs. source-specific governance conditions | Governed information use; responsibility | Retrieved information may originate under different governance conditions | Relevant governance information should remain connected to the information to which it applies |
| Generated output vs. source identification | Transparency; provenance | Generated information may combine material retrieved from multiple sources | The architecture should preserve sufficient source and provenance information to reconstruct the relevant information chain |

These dependencies are retrospective representations of the documented
federated setting and are not quantified trade-offs.

---

## 4. Prioritisation or constraint decision

The available documentary evidence does not justify reconstructing a complete
`High / Medium / Low` ordering across trustworthiness principles.

Instead, the supported contextual constraint is represented as:

> In the federated RAG setting, governance and responsibility information
> associated with distributed sources should remain connected to sufficient
> source-identification, provenance, and traceability information to support
> governed retrieval and subsequent information use.

This constraint reflects the role of provenance and traceability in the
documented architecture without claiming that they universally dominate other
trustworthiness concerns.

---

## 5. Decision rationale

The reconstructed constraint is supported by:

- Distributed Data Provider, Data Consumer, and federation roles
- Documented governance responsibilities
- Source metadata
- Provenance mechanisms
- Traceability structures
- Governed retrieval mechanisms
- Architectural elements connecting distributed information sources with
  subsequent information use

### Alternatives not reconstructed

The available evidence does not justify:

- Assigning fixed `High / Medium / Low` levels to the relevant concerns
- Reconstructing a universal priority of lawfulness, transparency, or
  traceability over all other principles
- Introducing a fairness priority solely from the existence of downstream
  information use
- Assigning a numerical cost to provenance or traceability overhead
- Reconstructing fixed review frequencies or approval procedures

These decisions would require additional documentary or empirical evidence.

---

## 6. Resulting contextual decision

- Contextual decision ID: `RAG-CD01`
- Affected concerns: Governance, responsibility, provenance, source
  identification, traceability, and governed information use
- Adopted contextual decision: Relevant governance and responsibility
  information should remain connected to sufficient source-identification,
  provenance, and traceability information throughout governed retrieval and
  subsequent information use
- Applicable constraints: Distributed source provision, federation,
  source-specific governance conditions, and multi-actor responsibility
- Responsible actors: Data Providers, Data Consumers, Federators, and relevant
  governance actors
- Related assumptions:
  - `RAG-A01`
  - `RAG-A02`
  - `RAG-A03`
- Related context record: `RAG-CTX-01`

The engineering response required by this contextual decision is represented
separately through `engineering-representation.md`.

---

## 7. Review and revision conditions

| Revision condition | Affected decision | Evidence source | Responsible role |
|---|---|---|---|
| Material loss or change in source-identification information | RAG-CD01 | Source / metadata evidence | Data Provider / Federator |
| Material degradation of provenance or traceability information | RAG-CD01 | Provenance / traceability evidence | Federator |
| Material change in source-specific governance conditions | RAG-CD01 | Governance / policy evidence | Data Provider / Governance Function |
| Addition or material change of participating sources or actors | RAG-CD01 | Federation / governance evidence | Relevant provider, federation, or governance actor |

Where such evidence challenges the contextual decision or its assumptions,
**CR.5 — Context Revision Trigger** may determine whether the decision should
be retained, updated, or reconsidered.

This worked example does not claim that such a CR.5 decision historically
occurred.

---

## 8. Verification and evidence

Supporting documentary evidence includes:

- Documented actor roles and governance responsibilities
- Source metadata
- Provenance mechanisms
- Traceability structures
- Governed retrieval mechanisms
- Architectural elements supporting federated information access and use

Related worked artefacts:

- `context-description.md`
- `responsibility-map.csv`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`

---

## 9. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: RAG in Federated Data Spaces
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This worked artefact distinguishes **documented contextual constraints** from
an inferred ordinal ranking.

The earlier repository version assigned `High` or `Medium` priorities to
Lawfulness, Traceability, Transparency, and Fairness. The v0.2.0 example does
not retain those levels because the retrospective reconstruction does not
require or independently establish such a formal ranking.

The resulting contextual decision remains process-independent. Its engineering
operationalisation is represented through Functional Refinement before
subsequent Process Instantiation.
