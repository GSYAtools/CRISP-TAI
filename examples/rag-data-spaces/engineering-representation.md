# Engineering Representation — RAG in Federated Data Spaces Worked Example

This document is an **illustrative retrospective completion** of the
`engineering-representation.md` template using documentary evidence from the
RAG-in-Data-Spaces case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact illustrates **FR.1 — Engineering Representation
Derivation** by showing how reconstructed contextual decisions can be expressed
as **process-independent Engineering Representations** before their subsequent
architectural and lifecycle instantiation.

---

## 1. Representation record

- Record group ID: `RAG-ER`
- System or component: RAG in Federated Data Spaces
- Trustworthiness concerns: Governance, responsibility, source
  identification, provenance, and traceability
- Trigger for engineering representation: The reconstructed contextual
  decision `RAG-CD01` requires explicit engineering expression before its
  documented architectural enactment can be represented
- Responsible engineering role(s): Reconstructed federation, information
  provision, and information-use actors
- Supporting governance role(s): Relevant reconstructed governance actors
- Related context record: `RAG-CTX-01`
- Related prioritisation record: `RAG-PRIO-01`
- Related assumption records: `RAG-A01` to `RAG-A03`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Originating contextual decision

| Contextual decision ID | Contextual decision / interpretation | Applicable constraint, responsibility, or assumption | Source |
|---|---|---|---|
| RAG-CD01 | Relevant governance and responsibility information should remain connected to sufficient source-identification, provenance, and traceability information throughout governed retrieval and subsequent information use | Distributed source provision, federation, source-specific governance conditions, multi-actor responsibility, and assumptions `RAG-A01` to `RAG-A03` | `context-description.md`; `principle-prioritisation.md`; `responsibility-map.csv`; `assumption-log.md` |

This contextual decision is a retrospective reconstruction from the documented
RAG-in-Data-Spaces evidence.

---

## 3. Engineering Representation derivation

| Representation ID | Contextual decision ID | Representation type | Engineering Representation | Rationale | Responsible role |
|---|---|---|---|---|---|
| RAG-ER01 | RAG-CD01 | Responsibility and governance traceability requirement | Relevant information provision, federation, retrieval, and use responsibilities shall remain identifiable and traceable across the governed information chain | Preserves responsibility boundaries in a multi-actor federated setting without assigning end-to-end accountability to a single technical actor | Relevant provider, consumer, federation, and governance actors |
| RAG-ER02 | RAG-CD01 | Provenance and source-identification requirement | Retrieved information shall retain sufficient source-identification, metadata, and provenance information to support reconstruction of its relevant origin and governance context | Operationalises the contextual requirement to preserve source and provenance information independently of the final architectural mechanism | Data Provider / Federator |
| RAG-ER03 | RAG-CD01 | Information-use traceability requirement | Relevant relationships between retrieved information, its provenance context, and its subsequent use shall remain reconstructable where supported by the documented architecture | Extends traceability beyond source identification so that the relevant information-use chain can be inspected | Federator / Data Consumer |

These are **process-independent Engineering Representations**. They do not
prescribe a specific CRISP-DM phase, metadata technology, provenance format,
architectural component, logging mechanism, or lifecycle artefact.

---

## 4. Representation specification

### RAG-ER01 — Responsibility and governance traceability

- Representation type: Responsibility and governance traceability requirement
- Originating contextual decision: `RAG-CD01`
- Applicable constraints:
  - Distributed organisational actors
  - Source-specific governance conditions
  - Separation between information provision, federation, and use
- Relevant assumptions:
  - `RAG-A01`
  - `RAG-A03`
- Responsible role(s): Data Providers, Data Consumers, Federators, and
  relevant governance actors
- Verification condition: Relevant responsibilities and governance conditions
  can be related to the corresponding actors and information-use context
- Dependencies: Responsibility allocation and availability of relevant
  governance information
- Revision conditions: Material actor, source, governance, or organisational
  change

### RAG-ER02 — Provenance and source identification

- Representation type: Provenance and source-identification requirement
- Originating contextual decision: `RAG-CD01`
- Applicable constraints:
  - Distributed information sources
  - Federated retrieval
  - Need to preserve relevant source and governance context
- Relevant assumptions:
  - `RAG-A01`
  - `RAG-A02`
- Responsible role(s): Data Provider; Federator
- Verification condition: Retrieved information can be related to sufficient
  source-identification and provenance information to support the reconstructed
  traceability relation
- Dependencies: Source metadata and provenance mechanisms
- Revision conditions: Material loss, degradation, inconsistency, or change in
  source or provenance information

### RAG-ER03 — Information-use traceability

- Representation type: Information-use traceability requirement
- Originating contextual decision: `RAG-CD01`
- Applicable constraints:
  - Information may pass through multiple actors and architectural mechanisms
  - Relevant provenance information must remain usable for subsequent
    traceability
- Relevant assumptions:
  - `RAG-A01`
  - `RAG-A02`
  - `RAG-A03`
- Responsible role(s): Federator; Data Consumer; relevant governance actor
- Verification condition: The relevant relationship between retrieved
  information, provenance context, and subsequent information use can be
  reconstructed
- Dependencies: Source metadata, provenance, federation, and traceability
  structures
- Revision conditions: Material change in federation, retrieval, source,
  governance, or information-use conditions

---

## 5. Derivation rationale

The reconstructed Engineering Representations are derived from documented
governance and information-chain conditions rather than from a direct mapping
between a trustworthiness principle and a lifecycle artefact.

The derivation logic is:

**Documented governance / source evidence  
→ reconstructed contextual decision  
→ required engineering function  
→ process-independent Engineering Representation**

For example:

**Distributed sources + source metadata + documented provenance mechanisms  
→ source and governance information must remain connected to retrieved
information  
→ explicit provenance and source-identification capability is required  
→ `RAG-ER02`**

Similarly:

**Distributed responsibility across providers, federation actors, and
consumers  
→ responsibility boundaries must remain reconstructable  
→ explicit responsibility and governance traceability is required  
→ `RAG-ER01`**

This derivation remains separate from the architectural mechanisms through
which these requirements were documented as being enacted.

---

## 6. Traceability

| Representation ID | Trustworthiness concern | Contextual decision | Responsibility record | Assumption record(s) | Supporting documentary evidence |
|---|---|---|---|---|---|
| RAG-ER01 | Governance and distributed responsibility | RAG-CD01 | RAG-R01; RAG-R02; RAG-R03; RAG-R04 | RAG-A01; RAG-A03 | Documented actor roles, governance responsibilities, and distributed information-use structure |
| RAG-ER02 | Provenance and source identification | RAG-CD01 | RAG-R01; RAG-R03 | RAG-A01; RAG-A02 | Source metadata, provenance mechanisms, and governed retrieval structures |
| RAG-ER03 | End-to-end information-use traceability | RAG-CD01 | RAG-R02; RAG-R03; RAG-R04 | RAG-A01; RAG-A02; RAG-A03 | Traceability structures and architectural relationships among sources, retrieval, and information use |

The complete refinement-to-instantiation chain is represented in
`traceability-matrix.csv`.

---

## 7. Revision conditions

| Revision condition | Representation affected | Evidence source | Responsible role |
|---|---|---|---|
| Material change in actor or responsibility structure | RAG-ER01; RAG-ER03 | Governance / organisational evidence | Relevant governance actor |
| Material loss or change in source metadata | RAG-ER01; RAG-ER02 | Source / metadata evidence | Data Provider / Federator |
| Material loss or degradation of provenance information | RAG-ER02; RAG-ER03 | Provenance / traceability evidence | Federator / relevant technical actor |
| Material change in retrieval, federation, or information-use conditions | RAG-ER01; RAG-ER02; RAG-ER03 | Architectural / governance evidence | Relevant federation, consumer, or governance actor |

---

## 8. Subsequent Process Instantiation

The original RAG-in-Data-Spaces material documents architectural mechanisms
through which the reconstructed Engineering Representations can be
retrospectively mapped.

| Representation ID | Instantiation ID | Documented lifecycle location or mechanism | Documented process-specific enactment | Instantiation rationale |
|---|---|---|---|---|
| RAG-ER01 | RAG-PI01 | Governance and architectural responsibility structures | Documented governance roles, responsibility relations, and architectural actor boundaries | These elements provide the documented enactment through which responsibility and governance traceability can be reconstructed |
| RAG-ER02 | RAG-PI02 | Source metadata, retrieval, and provenance mechanisms | Source-identification metadata and documented provenance mechanisms associated with retrieved information | These mechanisms enact the provenance and source-identification requirement represented by RAG-ER02 |
| RAG-ER03 | RAG-PI03 | Traceability structures connecting sources, retrieval, and subsequent information use | Documented traceability structures and architectural relationships | These mechanisms provide the documented enactment through which the relevant information-use chain can be reconstructed |

These mappings are **retrospective Process Instantiations**. They do not imply
that `RAG-ER01` to `RAG-ER03` were explicitly formulated before the original
architecture was developed.

---

## 9. Process-instantiation boundary

This worked example is particularly useful for illustrating the distinction
between an Engineering Representation and its architectural enactment.

For example:

**RAG-ER02**

is the process-independent requirement:

> Retrieved information shall retain sufficient source-identification,
> metadata, and provenance information to support reconstruction of its
> relevant origin and governance context.

The documented source metadata and provenance mechanisms are **not FR.1
outputs**. They are the process-specific architectural mechanisms through
which that reconstructed requirement is retrospectively instantiated.

The relationship is therefore:

**Contextual decision  
→ FR.1  
→ Engineering Representation  
→ Process Instantiation  
→ documented architectural mechanism**

and not:

**Trustworthiness concern  
→ FR.1  
→ lifecycle or architectural artefact**

---

## 10. Verification and evidence

The retrospective FR.1 reconstruction is supported by documented:

- Data Provider, Data Consumer, and federation roles
- Governance responsibilities
- Source metadata
- Provenance mechanisms
- Traceability structures
- Governed retrieval mechanisms
- Architectural components connecting distributed sources with subsequent
  information use

Verification in this worked example means that each reconstructed Engineering
Representation can be related to:

1. A documented contextual or governance concern
2. `RAG-CD01`
3. Supporting documentary evidence
4. A documented architectural enactment

It does not mean that FR.1 was prospectively executed in the original study.

---

## 11. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: RAG in Federated Data Spaces
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This worked artefact demonstrates the revised methodological boundary:

**Contextual decision  
→ process-independent Engineering Representation  
→ Process Instantiation  
→ documented architectural enactment**

The previous repository version represented this relation directly as
`Contextual Interpretation → Derived Artefact`. The v0.2.0 example separates
these steps explicitly.

RAG in Federated Data Spaces is particularly useful for illustrating this
boundary because provenance and traceability requirements can be distinguished
clearly from the metadata, provenance, and architectural mechanisms through
which they are subsequently enacted.

