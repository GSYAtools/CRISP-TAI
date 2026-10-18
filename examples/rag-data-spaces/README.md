# Worked Example — RAG in Federated Data Spaces

This directory provides an **illustrative worked example** showing how the
reusable CRISP-TAI repository templates can be populated retrospectively using
documentary evidence from the RAG-in-Data-Spaces case examined in the
associated research article.

The example concerns Retrieval-Augmented Generation in a federated Data Spaces
setting and represents the available case evidence using the **v0.2.0
CRISP-TAI artefact structure**.

This example does **not** imply that the Lifecycle Refinement Framework or
CRISP-TAI was prospectively applied during the original study. The completed
artefacts are retrospective representations intended to illustrate how the
current templates can be used.

---

## Example scope

The case concerns a RAG architecture operating over distributed information
sources within a federated Data Spaces setting.

The retrospective analysis focuses primarily on documented evidence concerning:

- Governance roles and responsibilities
- Source identification and metadata
- Provenance
- Traceability
- Governed retrieval and information use
- Architectural mechanisms through which these concerns are enacted

These characteristics make the case particularly useful for illustrating the
relationship between contextual governance decisions, process-independent
provenance and traceability requirements, and their documented architectural
instantiation.

---

## How to interpret the files in this directory

The files in this directory are **completed examples of the reusable
templates** provided under `/templates`.

They should be read as retrospective representations of documented case
evidence, not as original project records.

The principal reconstruction chain is:

**Documented governance and source evidence  
→ reconstructed contextual decision  
→ reconstructed process-independent Engineering Representation  
→ documented architectural instantiation**

Not every reusable template is equally exercised by this case. Where the
available documentary evidence does not support a specific refinement
decision, monitoring relation, feedback event, or revision outcome, the worked
example records that limitation rather than inventing additional evidence.

---

## Contextual Refinement worked artefacts

### `context-description.md`

Represents the governance, federation, source-use, and provenance context that
can be reconstructed from the documented case material.

### `responsibility-map.csv`

Illustrates responsibility and accountability relations associated with
information provision, governance, retrieval, and use.

### `principle-prioritisation.md`

Records only those contextual priorities or constraints that can be supported
by the available documentary evidence. It does not infer a complete ranking of
trustworthiness principles.

### `assumption-log.md`

Represents contextual assumptions and validity conditions concerning governed
information use, source metadata, provenance, and related contextual
conditions.

---

## Functional Refinement worked artefacts

### `engineering-representation.md`

Shows how reconstructed contextual decisions can be represented as
**process-independent Engineering Representations**, particularly provenance,
source-identification, responsibility, and traceability requirements.

### `traceability-matrix.csv`

Provides the principal end-to-end mapping artefact for this worked example,
linking:

**contextual decision  
→ Engineering Representation  
→ instantiation constraints  
→ Process Instantiation  
→ documented architectural enactment**

### `monitoring-plan.md`

Where the documentary evidence supports continued observation of provenance,
metadata, governance, or traceability conditions, this file illustrates how
such evidence could be represented using the current monitoring template.

It does not infer monitoring frequencies, thresholds, or operational
procedures that are not documented in the case.

### `feedback-log.md`

Where documented evidence supports review or revision, this file illustrates
the corresponding evidence-to-decision structure.

It does not invent historical feedback events or revision outcomes.

---

## Canonical retrospective application record

The methodological reconstruction of this case is documented separately in:

`/logs/rag-data-spaces-retrospective-application.md`

That record explains:

- The documentary evidence used
- Which CR and FR functions can be reconstructed from that evidence
- The reconstructed Engineering Representations
- The documented architectural instantiation
- The process-level properties for which the case provides analytical evidence

The files in this directory complement that record by showing **how the
reconstruction can be represented using the reusable v0.2.0 templates**.

---

## Relationship to the original case material

The original RAG-in-Data-Spaces material remains the evidential source for the
retrospective reconstruction.

The completed templates in this directory:

- Do not replace the original architectural or technical descriptions
- Do not constitute original project documentation
- Do not demonstrate prospective execution of CRISP-TAI
- Do not constitute independent empirical validation
- Do not infer undocumented lifecycle decisions or operational events
- Do provide an illustrative, inspectable representation of how documented
  governance, provenance, and traceability evidence can be structured using
  the current CRISP-TAI artefacts

---

## Purpose of the worked example

This example is intended primarily to illustrate:

1. Reconstruction of contextual governance and responsibility decisions
2. Derivation of process-independent provenance and traceability Engineering
   Representations
3. Separation of those representations from their documented architectural
   enactment
4. End-to-end traceability across the reconstructed chain

It should therefore be used as an **illustrative worked example**, not as a
reference implementation or as evidence that CRISP-TAI was prospectively
executed in the original case.
