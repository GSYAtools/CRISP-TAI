# Assumption Log — RAG in Federated Data Spaces Worked Example

This document is an **illustrative completion** of the
`assumption-log.md` template using contextual conditions that can be derived
from documentary evidence in the RAG-in-Data-Spaces case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

The analytical evaluation reported in the associated article reconstructs
**CR.1–CR.3** for the RAG case. It does **not** identify
**CR.4 — Assumption Documentation** or **CR.5 — Context Revision Trigger**
as part of the paper-supported RAG reconstruction.

Accordingly, this file demonstrates how the reusable CRISP-TAI assumption
template can be populated consistently with the case evidence without
extending the analytical claims made in the associated article.

---

## 1. Log information

- System or component: RAG in Federated Data Spaces
- Log ID: `RAG-ASSUMPTIONS-01`
- Related context record: `RAG-CTX-01`
- Related prioritisation record: `RAG-PRIO-01`
- Paper-supported CR reconstruction: `CR.1–CR.3`
- Template function illustrated here: `CR.4 — Assumption Documentation`
- Artefact status: Additional illustrative worked-template representation
- Repository version: `0.2.0`

---

## 2. Assumption register

The assumptions below are **illustrative structured assumptions** derived from
contextual conditions documented in the RAG-in-Data-Spaces case.

They are not presented as assumptions explicitly reconstructed through CR.4
in the analytical evaluation reported in the associated article.

| Assumption ID | Assumption | Type | Validity condition | Rationale / evidence | Related contextual or engineering element | Responsible role | Illustrative review trigger | Status |
|---|---|---|---|---|---|---|---|---|
| RAG-A01 | Source and governance information remains sufficiently available to support governed retrieval and use | Governance / Information | Relevant source metadata and governance information remain available and associated with the information to which they apply | Documented source metadata, governance roles, and governed retrieval mechanisms | RAG-CTX-01; RAG-ER01; RAG-ER02 | Data Provider / Federator | Material loss, inconsistency, or change in source metadata or governance information | Illustrative |
| RAG-A02 | Provenance information remains sufficiently preserved to support the reconstructed traceability relation | Provenance / Traceability | Relevant provenance information remains available across retrieval and subsequent information use | Documented provenance and traceability mechanisms | RAG-CTX-01; RAG-ER02; RAG-ER03 | Federator / relevant technical actor | Material loss, degradation, or inconsistency of provenance or traceability information | Illustrative |
| RAG-A03 | Existing governance and responsibility interpretations remain applicable while the relevant federation conditions remain materially unchanged | Governance / Organisational | No material governance, actor, source, or organisational change invalidates the existing contextual interpretation | Documented distributed governance and responsibility structure | RAG-CTX-01; RAG-ER01; RAG-ER03 | Relevant responsible actors | Material governance, source, actor, or organisational change | Illustrative |

These assumptions make explicit conditions that are implicit in the worked
representation of the case. Their inclusion demonstrates template usage; it
does not add CR.4 to the set of rules reconstructed in the paper.

---

## 3. Assumption types

The worked example uses the following illustrative categories:

- **Governance / Information** — availability and association of source and
  governance information
- **Provenance / Traceability** — preservation of information required to
  reconstruct relevant source and retrieval relations
- **Governance / Organisational** — continued applicability of responsibility
  and governance interpretations in a federated setting

These categories are used for the worked example and do not constitute a
mandatory taxonomy or an additional analytical result.

---

## 4. Illustrative assumption review

In a prospective application of CRISP-TAI, evidence challenging one of these
assumptions could be reviewed against its validity condition.

### Illustrative review structure

- Assumption ID:
- Triggering evidence:
- Evidence source:
- Validity condition affected:
- Responsible reviewer(s):
- Assessment:
  - Remains valid
  - Potentially invalid
  - Invalid
  - Uncertain
- Related contextual interpretation:
- Related Engineering Representation(s):
- Supporting rationale:

Potential evidence could include:

- Missing or changed source metadata
- Missing or inconsistent governance information
- Loss or degradation of provenance information
- Changes in participating sources or actors
- Changes in governance conditions
- Evidence that an existing responsibility boundary no longer reflects the
  federated setting

This section demonstrates prospective use of the reusable template. It does
not reconstruct a historical review performed in the original case.

---

## 5. Illustrative context-revision path

In a prospective application, evidence invalidating an assumption could
provide input to **CR.5 — Context Revision Trigger**.

The generic relation would be:

**Triggering evidence  
→ review of the affected assumption or contextual interpretation  
→ retain / update / reconsider  
→ subsequent Functional Refinement where required**

### Illustrative revision record

- Revision record ID:
- Assumption ID:
- Triggering evidence:
- Affected contextual interpretation:
- Responsible role(s):
- Revision decision:
- Decision rationale:
- Updated assumption or validity condition, where applicable:
- Downstream Engineering Representation(s) potentially affected:
- Related feedback record:

No such CR.5 execution is claimed for the RAG retrospective application
reported in the associated article.

---

## 6. Illustrative evidence sources

| Assumption ID | Evidence / signal | Source | Review condition | Responsible role | Related Engineering Representation |
|---|---|---|---|---|---|
| RAG-A01 | Missing, changed, or inconsistent source metadata or governance information | Source metadata / governance mechanisms | Evidence affects the ability to connect information with its source or applicable governance conditions | Data Provider / Federator | RAG-ER01; RAG-ER02 |
| RAG-A02 | Missing, degraded, or inconsistent provenance information | Provenance / traceability mechanisms | Evidence affects the ability to reconstruct the relevant information chain | Federator / relevant technical actor | RAG-ER02; RAG-ER03 |
| RAG-A03 | Material change in governance conditions, participating actors, or source relationships | Governance / federation evidence | Change potentially invalidates an existing responsibility or governance interpretation | Relevant responsible actors | RAG-ER01; RAG-ER03 |

These rows demonstrate how evidence could be linked to assumption review in a
prospective application.

They are not historical monitoring records.

---

## 7. Relationship to the paper-supported reconstruction

The paper-supported RAG reconstruction is:

**documented case evidence  
→ CR.1 Context Interpretation  
→ CR.2 Responsibility Allocation  
→ CR.3 Principle Prioritisation  
→ FR.1 Engineering Representation Derivation  
→ FR.2 Decision Traceability  
→ documented Process Instantiation**

This `assumption-log.md` sits **outside that claimed rule set**.

Its relationship to the reconstruction is therefore:

**paper-supported contextual and architectural evidence  
→ additional illustrative assumption representation**

rather than:

**paper-supported evidence  
→ reconstructed CR.4**

This distinction is intentional.

---

## 8. Relationship to Engineering Representations

Although CR.4 is not claimed as part of the paper-supported RAG
reconstruction, the illustrative assumptions help demonstrate how the reusable
templates can expose validity conditions associated with the reconstructed
Engineering Representations.

For example:

- `RAG-A01` is relevant to responsibility/governance traceability and
  source-identification representations.
- `RAG-A02` is relevant to provenance and information-use traceability.
- `RAG-A03` is relevant to responsibility boundaries and their continued
  contextual applicability.

If one of these assumptions were invalidated in a prospective application, the
affected Engineering Representation could require subsequent review.

---

## 9. Relationship to RAG-CD01

`RAG-CD01` represents the **paper-supported CR.3 prioritisation decision**:

> Where sovereignty, distributed control, and traceability dominate the
> deployment context, preserving those properties may justify accepting the
> higher response latency documented for a more distributed RAG architecture.

The assumptions in this file are **not prerequisites used to establish that
documented architectural trade-off**.

They instead illustrate additional contextual validity conditions relevant to
the governance, provenance, and traceability representations in the worked
example.

This separation prevents the illustrative CR.4 template content from being
mistaken for part of the paper-supported CR.3 reconstruction.

---

## 10. Analytical boundary

For the RAG case, the associated article supports:

- **CR.1 — Context Interpretation**
- **CR.2 — Responsibility Allocation**
- **CR.3 — Principle Prioritisation**
- **FR.1 — Engineering Representation Derivation**
- **FR.2 — Decision Traceability**
- **P1 — Lifecycle Anchoring**
- **P2 — Coordinated Contextual and Functional Refinement**

This file additionally illustrates:

- **CR.4 — Assumption Documentation**
- A possible prospective path to **CR.5 — Context Revision Trigger**

Those additional template functions are **not** claimed as rules reconstructed
in the retrospective analytical evaluation.

---

## 11. Versioning and ownership

- Artefact type: Additional illustrative completion of a CRISP-TAI v0.2.0
  template
- Source case: RAG in Federated Data Spaces
- Repository version: `0.2.0`
- Status: Illustrative worked-template representation
- Original project record: No
- Paper-supported CR.4 reconstruction: No
- Paper-supported CR.5 reconstruction: No

---

## Notes

This log demonstrates how explicit assumptions can be represented using the
reusable CRISP-TAI template without extending the claims of the associated
research article.

The assumptions are not presented as verbatim historical project records or as
outputs of a CR.4 execution reconstructed in the paper.

Their illustrative relationship is:

**documented contextual condition  
→ explicit assumption  
→ validity condition  
→ related Engineering Representation  
→ potential review if the condition changes**

The authoritative analytical boundary for the RAG case remains the
CR.1–CR.3 / FR.1–FR.2 reconstruction reported in the associated article.
