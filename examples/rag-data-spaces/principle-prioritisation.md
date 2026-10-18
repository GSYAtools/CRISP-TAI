# Principle Prioritisation — RAG in Federated Data Spaces Worked Example

This document is an **illustrative retrospective completion** of the
`principle-prioritisation.md` template using documentary evidence from the
RAG-in-Data-Spaces case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

For the analytical evaluation reported in the associated article, this worked
artefact represents **CR.3 — Principle Prioritisation**.

The reconstruction is grounded in documented architectural trade-offs among
the RAG variants examined in the original study. It does not infer a complete
or universal ranking of trustworthiness principles.

---

## 1. Prioritisation record

- Record ID: `RAG-PRIO-01`
- Contextual decision ID: `RAG-CD01`
- Primary reconstructed rule: `CR.3 — Principle Prioritisation`
- System or component: RAG in Federated Data Spaces
- Trigger for prioritisation: Alternative distributions of retrieval and
  generation responsibilities produce documented differences in operational
  performance and trustworthiness properties
- Decision context: Selection or interpretation of an architectural
  configuration for governed RAG over federated Data Spaces
- Relevant concerns:
  - Data sovereignty
  - Distributed control
  - Traceability
  - Transparency
  - Response latency
  - Semantic consistency
- Responsible role(s): Reconstructed Data Provider, Federator, and Data
  Consumer actors associated with the affected architectural and governance
  decisions
- Related context record: `RAG-CTX-01`
- Related responsibility records:
  - `RAG-R01`
  - `RAG-R02`
  - `RAG-R03`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Applicable trustworthiness concerns

The original case documents architectural differences relevant to both
operational performance and trustworthiness.

| Concern | Why applicable | Documented contextual relevance | Relevant actor(s) |
|---|---|---|---|
| Data sovereignty | The federated setting preserves distributed control over information sources and retrieval responsibilities | Architectural centralisation or distribution affects the degree of control retained across participating actors | Data Provider; Federator; Data Consumer |
| Distributed control | Retrieval and generation responsibilities can be allocated differently across the documented RAG architectures | Greater centralisation and greater distribution produce different governance and operational characteristics | Data Provider; Federator; Data Consumer |
| Traceability | Retrieved information and its relevant provenance relations must remain inspectable | The evaluated architectures differ in the degree of traceability they provide | Federator; Data Consumer |
| Transparency | The distribution of retrieval and generation responsibilities affects visibility available to participating actors | The original evaluation identifies differences in consumer-side transparency | Data Consumer; Federator |
| Response latency | Architectural distribution affects operational performance | The original evaluation documents different retrieval-latency characteristics across architectural variants | Data Consumer; Federator |
| Semantic consistency | Generated responses depend on retrieval and coordination across distributed sources | The original evaluation reports semantic-consistency differences among the architectural configurations | Data Consumer; Federator |

These concerns are not assigned universal `High / Medium / Low` values.

Their relevance is established through the architectural trade-offs documented
in the original case.

---

## 3. Documented architectural trade-off

The original evaluation provides the principal documentary basis for the CR.3
reconstruction.

The documented comparison indicates that:

- **Custodian RAG** reduces retrieval latency through greater centralisation,
  while providing more limited consumer-side transparency.
- **Federated RAG** incurs higher latency while preserving distributed control
  and providing stronger traceability and semantic consistency.

The case therefore documents a genuine tension between:

**lower response latency / greater centralisation**

and

**sovereignty / distributed control / traceability / semantic consistency**.

This trade-off provides the contextual evidence required for reconstructing
CR.3.

---

## 4. CR.3 — Prioritisation decision

The retrospective prioritisation is represented as:

> Where the deployment context gives greater importance to data sovereignty,
> distributed control, and traceability than to minimising response latency,
> an architectural configuration preserving those properties may be preferred
> despite its higher documented latency.

This is a **context-dependent prioritisation**, not a claim that Federated RAG
is universally preferable or that sovereignty and traceability should always
dominate operational performance.

The reconstructed decision establishes:

- **Prioritised concerns:** Data sovereignty, distributed control, and
  traceability
- **Accepted trade-off:** Higher response latency where required to preserve
  the prioritised concerns
- **Supporting consideration:** Stronger semantic consistency documented for
  the federated configuration
- **Context dependency:** The decision applies only where these
  trustworthiness concerns dominate the relevant deployment context

---

## 5. Decision rationale

The CR.3 reconstruction is supported by documented differences among the
architectural variants concerning:

- Retrieval latency
- Centralisation and distribution of control
- Consumer-side transparency
- Traceability
- Semantic consistency
- Distribution of retrieval and generation responsibilities

The reconstruction therefore does not derive prioritisation from an abstract
list of trustworthiness principles.

Instead, it follows the CR.3 relation:

**documented contextual constraints  
+ affected trustworthiness concerns  
+ observed architectural trade-off  
→ context-dependent prioritisation decision**

### Decisions not reconstructed

The available evidence does not justify:

- Assigning fixed `High / Medium / Low` values to the concerns
- Claiming that Federated RAG is universally preferable
- Establishing a universal priority of traceability over latency
- Defining an acceptable numerical latency penalty
- Introducing a fairness priority not used in the paper-supported
  reconstruction
- Inferring fixed review frequencies or approval procedures

---

## 6. Resulting contextual decision

- Contextual decision ID: `RAG-CD01`
- Rule: `CR.3 — Principle Prioritisation`
- Decision: Where sovereignty, distributed control, and traceability dominate
  the deployment context, preserving those properties may justify accepting
  the higher response latency documented for a more distributed RAG
  architecture
- Prioritised concerns:
  - Data sovereignty
  - Distributed control
  - Traceability
- Trade-off concern:
  - Response latency
- Supporting concern:
  - Semantic consistency
- Applicable context:
  - Federated information access
  - Distributed responsibility
  - Provenance-sensitive information use
- Responsible actors:
  - Data Provider
  - Federator
  - Data Consumer
- Related context record: `RAG-CTX-01`
- Related responsibility records:
  - `RAG-R01`
  - `RAG-R02`
  - `RAG-R03`

The process-independent engineering consequences of this contextual decision
are represented separately in `engineering-representation.md`.

---

## 7. Relationship to CR.1 and CR.2

The prioritisation reconstructed here depends on the preceding contextual
information represented by the other worked artefacts.

### CR.1 — Context Interpretation

`context-description.md` reconstructs the distributed governance, provenance,
actor, and architectural context within which the trade-off is meaningful.

### CR.2 — Responsibility Allocation

`responsibility-map.csv` reconstructs the differentiated responsibilities of
Data Providers, Federators, and Data Consumers.

### CR.3 — Principle Prioritisation

This artefact reconstructs the context-dependent priority decision supported
by the documented architectural trade-off.

Together, these represent the paper-supported Contextual Refinement for the
RAG case:

**CR.1 → CR.2 → CR.3**

This notation describes the analytical reconstruction and does not prescribe a
rigid sequential workflow for every framework application.

---

## 8. Relationship to Functional Refinement

The contextual decision `RAG-CD01` provides input to the paper-supported
Functional Refinement reconstruction.

Through **FR.1 — Engineering Representation Derivation**, the contextual
decision is represented through process-independent engineering requirements
concerning:

- Provenance
- Distributed control
- Source identification
- Responsibility
- Traceability

Through **FR.2 — Decision Traceability**, those representations remain linked
to the contextual decisions and rationale from which they were reconstructed.

The subsequent mapping to documented RAG architectural mechanisms belongs to
Process Instantiation rather than to CR.3 or FR.1.

---

## 9. Additional worked-template review conditions

For purposes of demonstrating the reusable template, the prioritisation could
require review in a prospective application if the conditions supporting the
trade-off materially change.

| Review condition | Potentially affected decision | Evidence source | Relevant actor |
|---|---|---|---|
| Material change in architectural latency characteristics | RAG-CD01 | Performance / architectural evidence | Federator / Data Consumer |
| Material change in provenance or traceability capability | RAG-CD01 | Provenance / traceability evidence | Federator |
| Material change in distributed-control requirements | RAG-CD01 | Governance / architectural evidence | Data Provider / Federator / Data Consumer |
| Material change in deployment priorities | RAG-CD01 | Governance / stakeholder evidence | Relevant responsible actors |

In a prospective application, such evidence could provide input to
**CR.5 — Context Revision Trigger**.

This section is an **additional worked-template illustration**. It does not
claim that CR.5 was reconstructed or historically executed in the RAG
retrospective application reported in the associated article.

---

## 10. Verification and evidence

The paper-supported CR.3 reconstruction is verified against documented:

- Alternative RAG architectural configurations
- Distribution of retrieval and generation responsibilities
- Retrieval-latency differences
- Consumer-side transparency differences
- Distributed-control characteristics
- Traceability results
- Semantic-consistency results

Related paper-supported worked artefacts:

- `context-description.md`
- `responsibility-map.csv`
- `engineering-representation.md`
- `traceability-matrix.csv`

Additional illustrative template artefacts:

- `assumption-log.md`
- `monitoring-plan.md`
- `feedback-log.md`

---

## 11. Analytical boundary

For this artefact, the paper-supported claim is:

**CR.3 — Principle Prioritisation**

supported by the documented architectural trade-off.

The artefact does not establish:

- CR.4 assumption reconstruction
- CR.5 contextual revision
- CR.6 lifecycle anchoring
- CR.7 scope control

P1 — Lifecycle Anchoring is supported at case level through the documented
Process Instantiation of the reconstructed Engineering Representations, not
through a claim that CR.6 was reconstructed here.

---

## 12. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: RAG in Federated Data Spaces
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This worked artefact represents a **documented context-dependent
prioritisation**, not an inferred ordinal ranking.

Its principal retrospective relation is:

**documented architectural trade-off  
→ CR.3 context-dependent prioritisation  
→ RAG-CD01  
→ FR.1 Engineering Representation Derivation  
→ FR.2 Decision Traceability  
→ documented Process Instantiation**

The decision remains context-dependent and process-independent until its
subsequent instantiation within the selected lifecycle and architecture.
