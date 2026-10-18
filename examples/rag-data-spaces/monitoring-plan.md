# Monitoring Plan — RAG in Federated Data Spaces Worked Example

This document is an **illustrative retrospective completion** of the
`monitoring-plan.md` template using documentary evidence from the
RAG-in-Data-Spaces case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

Unlike the Federated Learning and TrustAIoT worked examples, the documentary
evidence used for this case primarily supports reconstruction of governance,
provenance, source-identification, and traceability relationships.

This artefact therefore illustrates how evidence relevant to those
relationships can be represented without claiming a historical monitoring
process, fixed review frequency, or independent reconstruction of
**FR.6 — Continuity Enforcement**.

---

## 1. Monitoring record

- Monitoring plan ID: `RAG-MON-01`
- System or component: RAG in Federated Data Spaces
- Relevant environment: Multi-actor federated information setting
- Responsible role(s): Reconstructed Data Provider, Federator, Data Consumer,
  and governance actors according to the affected evidence
- Related context record: `RAG-CTX-01`
- Related contextual decision: `RAG-CD01`
- Related Engineering Representations:
  - `RAG-ER01`
  - `RAG-ER02`
  - `RAG-ER03`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Evidence scope

The retrospective reconstruction depends on source, governance, provenance,
and traceability information remaining sufficiently available to support the
relationships represented in this worked example.

Relevant evidence therefore includes:

| Evidence item ID | Trustworthiness concern | Element observed | Related assumption | Related Engineering Representation | Reason for review |
|---|---|---|---|---|---|
| RAG-M01 | Source governance | Availability and consistency of relevant source metadata and governance information | RAG-A01 | RAG-ER01; RAG-ER02 | Determine whether source and governance information remains sufficient for the reconstructed governance and provenance relations |
| RAG-M02 | Provenance | Availability and consistency of provenance information associated with retrieved information | RAG-A02 | RAG-ER02; RAG-ER03 | Determine whether the reconstructed provenance relation remains supportable |
| RAG-M03 | Distributed responsibility | Material change in participating actors, responsibility boundaries, or governance conditions | RAG-A03 | RAG-ER01; RAG-ER03 | Determine whether the existing governance and responsibility interpretation remains applicable |
| RAG-M04 | Information-use traceability | Availability of the relevant relationships among source information, retrieval, provenance, and subsequent use | RAG-A01; RAG-A02; RAG-A03 | RAG-ER03 | Determine whether the reconstructed information-use traceability relation remains supportable |

---

## 3. Evidence and review conditions

This worked example does not prescribe fixed monitoring frequencies or
thresholds.

Review is represented as **condition-driven** and should occur when relevant
evidence challenges an existing assumption, contextual decision, or
Engineering Representation.

| Evidence item ID | Evidence / signal | Source | Review condition | Responsible role | Evidence record |
|---|---|---|---|---|---|
| RAG-M01 | Missing, changed, or inconsistent source metadata or governance information | Source metadata / governance mechanisms | Evidence may affect the association between information and its source or governance context | Data Provider / Federator | RAG-EV01 |
| RAG-M02 | Missing, degraded, or inconsistent provenance information | Provenance / traceability mechanisms | Evidence may affect reconstruction of information origin or provenance context | Federator / relevant technical actor | RAG-EV02 |
| RAG-M03 | Material change in actors, responsibility relations, or governance conditions | Governance / federation evidence | Existing responsibility or governance interpretation may no longer remain applicable | Relevant governance actor | RAG-EV03 |
| RAG-M04 | Loss or inconsistency in the relationship between retrieved information, provenance, and subsequent use | Traceability / architectural evidence | Existing information-use traceability may no longer be reconstructable | Federator / Data Consumer | RAG-EV04 |

These signals are **evidence for review**. They are not automatic
trustworthiness judgements or revision decisions.

---

## 4. Evidence review

Where relevant evidence is observed, it should be assessed against the
existing retrospective records.

### Illustrative review structure

- Evidence record ID:
- Evidence item ID:
- Evidence observed:
- Contextual decision affected: `RAG-CD01`
- Assumption affected:
- Engineering Representation affected:
- Responsible reviewer(s):
- Assessment:
  - Existing relation remains supported
  - Additional evidence is required
  - Assumption may no longer remain valid
  - Engineering Representation requires review
  - Contextual reconsideration may be required
- Rationale:
- Follow-up required:

The available documentary evidence does not justify reconstructing specific
historical outcomes for each of these review conditions.

---

## 5. Relationship to contextual revision

Where evidence challenges `RAG-A01`, `RAG-A02`, `RAG-A03`, or the contextual
decision `RAG-CD01`, **CR.5 — Context Revision Trigger** may become applicable.

The conditional relation is:

**Source / governance / provenance evidence  
→ review against existing assumptions and RAG-CD01  
→ retain, update, or reconsider the contextual interpretation where required  
→ subsequent Functional Refinement where required**

This worked example does not claim that a specific CR.5 event occurred in the
original study.

---

## 6. Relationship to Engineering Representation review

Where evidence affects an existing Engineering Representation, the relevant
requirement may need to be reviewed.

| Evidence item ID | Engineering Representation potentially affected | Potential review |
|---|---|---|
| RAG-M01 | RAG-ER01; RAG-ER02 | Review responsibility/governance traceability or source-identification requirements |
| RAG-M02 | RAG-ER02; RAG-ER03 | Review provenance or information-use traceability requirements |
| RAG-M03 | RAG-ER01; RAG-ER03 | Review responsibility boundaries or downstream traceability requirements |
| RAG-M04 | RAG-ER03 | Review the information-use traceability requirement |

A resulting engineering change should be represented through subsequent
Functional Refinement before any process-specific or architectural update is
represented.

---

## 7. Relationship to documented architectural instantiation

The reconstructed Engineering Representations are retrospectively associated
with:

- `RAG-PI01` — governance roles and architectural responsibility structures
- `RAG-PI02` — source metadata and provenance mechanisms
- `RAG-PI03` — traceability structures connecting sources, retrieval, and
  subsequent information use

Where relevant evidence indicates that one of these documented mechanisms no
longer supports the corresponding Engineering Representation, the mapping
should be reviewed.

The relation is:

**Evidence  
→ contextual / engineering review  
→ revised Engineering Representation where required  
→ review of Process Instantiation**

This does not establish that such a revision historically occurred.

---

## 8. Scope limitation

This case does not provide the same explicit lifecycle-monitoring evidence as
the TrustAIoT or Federated Learning cases.

Accordingly, this worked artefact does **not** claim:

- A reconstructed historical monitoring schedule
- Fixed monitoring frequencies
- Universal provenance or traceability thresholds
- A specific historical operational adjustment
- Independent evidence of FR.6
- A documented continuous feedback cycle

The monitoring template is retained to demonstrate how evidence affecting the
reconstructed RAG refinement chain can be represented while preserving the
limits of the documentary evidence.

---

## 9. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: RAG in Federated Data Spaces
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This monitoring plan is intentionally more limited than those provided for the
Federated Learning and TrustAIoT worked examples.

Its purpose is to illustrate:

**Relevant evidence  
→ review of contextual assumptions and Engineering Representations  
→ subsequent refinement where justified**

without converting the existence of provenance or traceability mechanisms into
an unsupported claim of continuous monitoring or lifecycle feedback.

The primary contribution of the RAG-in-Data-Spaces case remains the
retrospective reconstruction of **governance, responsibility, provenance, and
traceability**, together with their documented architectural instantiation.
