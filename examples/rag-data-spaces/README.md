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

The case concerns RAG architectures operating over distributed information
sources within a federated Data Spaces setting.

The retrospective analysis reported in the associated article focuses on
documented evidence concerning:

- Distributed governance
- Responsibility boundaries
- Provenance
- Distributed control
- Traceability
- Source-labelled retrieval
- Architectural mechanisms through which these concerns are enacted
- Documented architectural trade-offs among alternative RAG configurations

Within the analytical evaluation reported in the article, this evidence
supports reconstruction of:

- **CR.1 — Context Interpretation**
- **CR.2 — Responsibility Allocation**
- **CR.3 — Principle Prioritisation**
- **FR.1 — Engineering Representation Derivation**
- **FR.2 — Decision Traceability**

The case provides analytical evidence for:

- **P1 — Lifecycle Anchoring**
- **P2 — Coordinated Contextual and Functional Refinement**

P1 is supported by the documented relationship between reconstructed
Engineering Representations and their architectural enactment. This does not
imply that CR.6 is independently reconstructed in this case.

P4 — Cross-Domain Adaptability is assessed through comparison of the three
retrospective applications rather than through this case alone.

---

## How to interpret the files in this directory

The files in this directory are **completed examples of the reusable
templates** provided under `/templates`.

They should be read as retrospective representations of documented case
evidence, not as original project records.

The paper-supported reconstruction chain is:

**Documented governance and architectural evidence  
→ contextual interpretation, responsibility allocation, and prioritisation
(CR.1–CR.3)  
→ process-independent provenance, distributed-control, and traceability
Engineering Representations (FR.1)  
→ traceability to the originating contextual decisions (FR.2)  
→ documented architectural instantiation**

Not every reusable template is equally exercised by this case.

Some templates in this directory are completed to illustrate how additional
contextual assumptions, monitoring evidence, or feedback conditions could be
represented using the repository structure. Their inclusion does **not** imply
that additional CR or FR rules were reconstructed as part of the analytical
evaluation reported in the associated article.

Where the available documentary evidence does not support a specific
historical monitoring event, feedback event, revision decision, or operational
adjustment, the worked example records that limitation rather than inventing
additional evidence.

---

## Contextual Refinement worked artefacts

### `context-description.md`

Represents the distributed governance, federation, provenance, and
information-use context documented in the case.

For the paper-supported retrospective analysis, this artefact primarily
illustrates **CR.1 — Context Interpretation**.

### `responsibility-map.csv`

Illustrates responsibility and accountability relations associated with Data
Providers, Federators, Data Consumers, information provision, retrieval, and
subsequent use.

For the paper-supported retrospective analysis, this artefact primarily
illustrates **CR.2 — Responsibility Allocation**.

### `principle-prioritisation.md`

Represents the context-dependent prioritisation supported by documented
architectural trade-offs.

In particular, the original evaluation shows that alternative distributions
of retrieval and generation responsibilities affect both operational
performance and trustworthiness properties. Greater centralisation can reduce
retrieval latency while limiting consumer-side transparency, whereas the
federated architecture incurs higher latency while preserving distributed
control and providing stronger traceability and semantic consistency.

This provides documentary evidence for reconstructing, through
**CR.3 — Principle Prioritisation**, a context-dependent preference for
sovereignty, distributed control, and traceability over lower response latency
where those concerns dominate the deployment context.

The worked example does not infer a universal ranking of trustworthiness
principles.

### `assumption-log.md`

Illustrates how contextual assumptions and validity conditions concerning
source metadata, provenance, governance, and actor relationships can be
represented using the reusable CRISP-TAI template.

This is an **additional worked-template representation**. Its inclusion does
not imply that CR.4 is part of the RAG retrospective reconstruction reported
in the associated article.

---

## Functional Refinement worked artefacts

### `engineering-representation.md`

Shows how the contextual decisions reconstructed through CR.1–CR.3 can be
expressed as **process-independent Engineering Representations** concerning:

- Provenance
- Distributed control
- Source identification
- Responsibility
- Traceability

For the paper-supported retrospective analysis, this artefact illustrates
**FR.1 — Engineering Representation Derivation**.

### `traceability-matrix.csv`

Provides the principal end-to-end mapping artefact for the worked example.

For the paper-supported retrospective analysis, it illustrates
**FR.2 — Decision Traceability** by preserving the relationship:

**contextual decision  
→ Engineering Representation  
→ documented Process Instantiation  
→ architectural enactment**

The matrix may contain additional fields for lifecycle anchoring, scope, or
placement because these belong to the reusable repository schema. The presence
of those fields does not by itself constitute evidence that the corresponding
CR or FR rules were reconstructed in this case.

### `monitoring-plan.md`

Illustrates how evidence affecting source metadata, provenance, governance, or
traceability conditions could be represented using the reusable monitoring
template.

It does not infer monitoring frequencies, thresholds, historical monitoring
events, or FR.6 execution that are not supported by the retrospective analysis.

### `feedback-log.md`

Illustrates conditional evidence-to-decision paths where source, governance,
provenance, or traceability evidence could require review.

It does not claim historical feedback events, CR.5 execution, FR.3 execution,
or revision outcomes that are not part of the paper-supported retrospective
reconstruction.

---

## Documented Process Instantiation

The original RAG-in-Data-Spaces material provides evidence of the subsequent
process-specific instantiation of the reconstructed Engineering
Representations.

Representative evidence includes:

- Role allocation across Data Providers, Federators, and Data Consumers
- Provenance mechanisms
- Source-labelled retrieval
- Architectural traceability mechanisms
- Publication and query-execution activities
- Architectural distribution of retrieval and generation responsibilities

These elements are treated as **documented instantiation evidence**, not as
artefacts generated prospectively by CR or FR.

---

## Canonical retrospective application record

The methodological reconstruction of this case is documented separately in:

`/logs/rag-data-spaces-retrospective-application.md`

That record defines the canonical analytical boundary for this case:

- CR reconstruction: **CR.1–CR.3**
- FR reconstruction: **FR.1–FR.2**
- Assessment criteria: **P1 and P2**

The files in this directory complement that record by showing how the
reconstruction, together with additional illustrative template usage, can be
represented using the reusable v0.2.0 artefacts.

Where an example-level template contains additional fields or illustrative
relations, the canonical retrospective application record and the associated
research article determine which rules and assessment criteria are actually
supported by the analytical evaluation.

---

## Relationship to the original case material

The original RAG-in-Data-Spaces study remains the evidential source for the
retrospective reconstruction.

The completed templates in this directory:

- Do not replace the original architectural or technical descriptions
- Do not constitute original project documentation
- Do not demonstrate prospective execution of CRISP-TAI
- Do not constitute independent empirical validation
- Do not infer undocumented lifecycle decisions or operational events
- Do not imply reconstruction of every CR or FR rule represented by the
  reusable template structure
- Do provide an illustrative, inspectable representation of how documented
  governance, responsibility, provenance, prioritisation, and traceability
  evidence can be structured using the current CRISP-TAI artefacts

---

## Purpose of the worked example

This example is intended primarily to illustrate:

1. Context interpretation in a distributed governance setting
2. Responsibility allocation across Data Providers, Federators, and Data
   Consumers
3. Context-dependent prioritisation based on documented architectural
   trade-offs
4. Derivation of process-independent provenance, distributed-control, and
   traceability Engineering Representations
5. Traceability from those representations to their originating contextual
   decisions
6. Separation of the reconstructed Engineering Representations from their
   documented architectural instantiation
7. Use of additional repository templates without converting template
   availability into unsupported rule-coverage claims

It should therefore be used as an **illustrative worked example**, not as a
reference implementation or as evidence that CRISP-TAI was prospectively
executed in the original case.
