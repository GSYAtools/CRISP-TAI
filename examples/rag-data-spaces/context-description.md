# Context Description — RAG in Federated Data Spaces Worked Example

This document is an **illustrative retrospective completion** of the
`context-description.md` template using documentary evidence from the
RAG-in-Data-Spaces case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact primarily illustrates contextual information supporting
**CR.2 — Responsibility Allocation** and **CR.4 — Assumption Documentation**
in the retrospective reconstruction described in
`/logs/rag-data-spaces-retrospective-application.md`.

---

## 1. Refinement record

- Record ID: `RAG-CTX-01`
- Trustworthiness concern or principle: Governed information use, provenance,
  responsibility, and traceability in a federated RAG setting
- Trigger for contextual interpretation: Retrospective reconstruction of the
  governance and source-use conditions documented in the case
- Responsible role(s): Reconstructed data-provider, data-consumer,
  federation, and governance actors
- Supporting stakeholders: Actors participating in information provision,
  retrieval, governance, and use
- Related record(s): `RAG-A01`, `RAG-A02`, `RAG-A03`, `RAG-ER01`,
  `RAG-ER02`, `RAG-ER03`

---

## 2. System overview

- System name: RAG in Federated Data Spaces
- High-level purpose: Support retrieval and generation using information
  distributed across governed data sources
- Relevant actors: Data Providers, Data Consumers, federation or
  interoperability actors, and governance functions
- Intended use considered in this reconstruction: Governed retrieval and use
  of information from distributed sources
- Deployment environment: Multi-actor federated Data Spaces setting
- Relevant contextual variation: Changes in participating sources,
  governance conditions, metadata, access or usage constraints, and
  information-use context

---

## 3. Organisational and governance context

The documented case involves distributed actors with differentiated roles in
information provision, federation, retrieval, and use.

Relevant actor categories include:

- **Data Providers** — provide information sources under applicable
  governance and usage conditions
- **Data Consumers** — request or use information through the RAG setting
- **Federation / interoperability actors** — support metadata, source
  coordination, interoperability, or governed access
- **Governance actors** — establish or review applicable governance
  conditions and responsibilities

This distributed setting makes explicit responsibility and accountability
relations relevant to the interpretation and use of retrieved information.

Detailed reconstructed responsibility relations are represented in
`responsibility-map.csv`.

---

## 4. Governance and policy context

The retrospective reconstruction focuses on documented governance, source-use,
metadata, provenance, and traceability conditions.

Relevant contextual constraints include:

- Governed use of distributed information sources
- Source and metadata identification
- Provenance preservation
- Responsibility for information provision and use
- Applicable access or usage conditions
- Traceability between retrieved information and its subsequent use

The worked example does not infer a complete legal or compliance assessment
beyond the governance conditions supported by the documentary evidence.

---

## 5. Social and stakeholder context

The available case material supports reconstruction of multiple organisational
actors participating in governed information exchange and use.

The retrospective analysis does not require additional claims concerning
specific affected social groups or societal impacts unless those claims are
explicitly supported by the source material.

Relevant stakeholder considerations for this worked example therefore focus on:

- Responsibility for information provision
- Responsibility for governed information use
- Ability to identify information sources
- Ability to reconstruct provenance and traceability relations

---

## 6. Operational context

Relevant operational characteristics include:

- Distributed information sources
- Retrieval-Augmented Generation
- Federated information access
- Source metadata
- Provenance mechanisms
- Traceability structures
- Governance conditions associated with information retrieval and use
- Architectural components supporting governed retrieval

These conditions provide the principal documentary basis for the
retrospective reconstruction.

---

## 7. Contextual interpretation

- Trustworthiness concern: Governed and traceable use of distributed
  information in a federated RAG setting
- Applicable contextual constraints:
  - Distributed information ownership or provision
  - Multiple organisational actors
  - Source-specific governance conditions
  - Need to preserve source identification and provenance
- Relevant expectation: Information used through the RAG architecture should
  remain connected to sufficient source, provenance, governance, and
  responsibility information to support subsequent traceability
- Contextual interpretation: The federated setting requires governance and
  responsibility decisions concerning information provision and use to remain
  explicitly connected to source-identification, provenance, and traceability
  information
- Supporting rationale: Documented governance roles, source metadata,
  provenance mechanisms, traceability structures, and architectural elements
- Supporting evidence: Original RAG-in-Data-Spaces case material

This interpretation provides contextual input to the reconstructed
Engineering Representations documented in
`engineering-representation.md`.

---

## 8. Trustworthiness priorities and trade-offs

The original case material identifies governance, provenance, traceability,
source control, and related transparency concerns as relevant to the
federated RAG setting.

Their presence does not by itself establish a formal `High / Medium / Low`
ordering.

Where a contextual priority, constraint, or trade-off can be supported by the
documentary evidence, it is represented separately in
`principle-prioritisation.md`.

---

## 9. Contextual assumptions

| Assumption ID | Assumption | Validity condition | Affected contextual decision / interpretation | Evidence or rationale |
|---|---|---|---|---|
| RAG-A01 | Source and governance information remains sufficiently available to support governed retrieval and use | Relevant source metadata and governance information remain available and associated with the information used by the system | Governance and responsibility decisions can remain connected to the relevant information sources | Documented source metadata and governance mechanisms |
| RAG-A02 | Provenance information remains sufficiently preserved to support the reconstructed traceability relation | Relevant provenance information remains available across retrieval and subsequent information use | Retrieved information can remain traceable to its documented source or provenance context | Documented provenance and traceability mechanisms |
| RAG-A03 | The applicable governance conditions remain sufficiently stable for existing contextual interpretations to remain applicable | No material governance, policy, source, or organisational change invalidates the existing interpretation | Existing contextual governance and responsibility decisions remain applicable | Documented governance conditions and distributed actor structure |

Detailed assumption management is represented in `assumption-log.md`.

---

## 10. Revision conditions

| Revision condition | Affected contextual element | Evidence source | Responsible role |
|---|---|---|---|
| Material change in source metadata or source-identification capability | RAG-A01 and source-governance interpretation | Metadata / source evidence | Relevant provider / federation actor |
| Material loss or degradation of provenance information | RAG-A02 and traceability interpretation | Provenance / traceability evidence | Relevant federation / technical actor |
| Material governance, policy, or organisational change | RAG-A03 and governance interpretation | Governance / policy evidence | Relevant governance actor |
| Addition or material change of participating information sources or actors | Existing responsibility or governance interpretation | Federation / governance evidence | Relevant provider, federation, or governance actor |

Where such evidence challenges an existing assumption or contextual
interpretation, **CR.5 — Context Revision Trigger** may determine whether the
affected element should be retained, updated, or reconsidered.

This does not imply that CR.5 was historically executed in the original case.

---

## 11. Context revision record

The documentary evidence used in this worked example primarily supports the
reconstruction of governance, provenance, responsibility, and traceability
relationships.

It does not justify inventing specific historical contextual-revision events.

Where relevant evidence becomes available, the refinement relation would be:

**Governance / source / provenance evidence  
→ review of existing contextual assumption or interpretation  
→ retain, update, or reconsider where required  
→ subsequent Functional Refinement**

Any such relation represented in `feedback-log.md` should remain explicitly
conditional unless a specific historical revision is supported by the source
material.

---

## 12. Verification and evidence

Evidence supporting this retrospective contextual reconstruction includes:

- Documented governance roles
- Distributed actor responsibilities
- Source metadata
- Provenance information
- Traceability structures
- Governed retrieval mechanisms
- Architectural components associated with information access and use

Related worked artefacts:

- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`
- `monitoring-plan.md`
- `feedback-log.md`

---

## 13. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: RAG in Federated Data Spaces
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This document represents **documented RAG-in-Data-Spaces evidence using the
current CRISP-TAI contextual-refinement structure**.

It should not be interpreted as evidence that CRISP-TAI was used prospectively
during the original study.

Its principal purpose is to demonstrate the relationship:

**Governance and source context  
→ contextual responsibility and assumption records  
→ process-independent provenance and traceability Engineering
Representations  
→ documented architectural instantiation**

The worked example deliberately avoids inferring undocumented priority
rankings, legal conclusions, monitoring frequencies, or historical revision
events.
