# Principle Prioritisation — Federated Learning Worked Example

This document is an **illustrative retrospective completion** of the
`principle-prioritisation.md` template using documentary evidence from the
Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

For the analytical evaluation reported in the associated article, this worked
artefact represents **CR.3 — Principle Prioritisation**.

The reconstruction is grounded in documented operational priorities and
constraints from the original Federated Learning study. It does not infer a
complete or universal ranking of trustworthiness principles.

---

## 1. Prioritisation record

- Record ID: `FL-PRIO-01`
- Contextual decision ID: `FL-CD01`
- Primary reconstructed rule: `CR.3 — Principle Prioritisation`
- System or component: Federated Learning setting
- Primary challenge: Partial observability, distributed control, and
  adversarial behaviour
- Trigger for prioritisation: The detection mechanism must address strong and
  stealthy adversarial behaviour while remaining compatible with the
  secure-aggregation constraints of the Federated Learning setting
- Decision context: Early detection of potentially adversarial client
  behaviour
- Relevant concerns:
  - Robustness against adversarial behaviour
  - Early detection
  - Lightweight operation
  - Compatibility with secure aggregation
- Related context record: `FL-CTX-01`
- Artefact status: Paper-supported retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Documented operational priorities and constraints

The original Federated Learning study provides documentary and experimental
evidence for several interrelated operational concerns.

| Concern / constraint | Why applicable | Documentary basis |
|---|---|---|
| Robustness against strong attacks | The system is evaluated under explicit adversarial attack conditions | Strong attack scenarios documented in the original study |
| Robustness against stealthy attacks | Detection must remain useful when adversarial behaviour is less directly observable | Stealthy attack scenarios documented in the original study |
| Early detection | The technical contribution is intended to identify relevant anomalous behaviour before aggregation | Client-level early-warning mechanism operating prior to aggregation |
| Lightweight operation | Detection must remain compatible with the operational characteristics of distributed Federated Learning | Lightweight detection approach documented in the original study |
| Compatibility with secure aggregation | The detection approach operates under restricted observability associated with secure aggregation | Secure-aggregation setting documented in the original study |

These concerns establish the context for prioritisation without requiring a
`High / Medium / Low` ranking.

---

## 3. Operational tension

The relevant prioritisation is not represented as a generic
security-versus-performance trade-off.

Instead, the documented setting imposes a combined engineering constraint:

> Adversarial behaviour should be detected early and with sufficient
> sensitivity to strong and stealthy attacks, while the detection approach
> remains lightweight and compatible with secure aggregation.

The relevant tension therefore concerns the need to preserve useful
adversarial detection under the observability and operational constraints of
the Federated Learning setting.

This is the documentary basis for the CR.3 reconstruction.

---

## 4. CR.3 — Prioritisation decision

The retrospective contextual decision is represented as:

> The engineering response should provide lightweight early detection of
> adversarial behaviour, including strong and stealthy attacks, while
> remaining compatible with the secure-aggregation constraints of the
> Federated Learning setting.

This decision is identified as:

`FL-CD01`

The decision prioritises:

- Robustness against documented adversarial behaviour
- Early detection

subject to:

- Lightweight operation
- Secure-aggregation compatibility
- Partial observability

This is a **context-dependent operational priority**.

It does not establish that robustness or security universally dominates other
trustworthiness concerns.

---

## 5. Decision rationale

The CR.3 reconstruction is supported by documented:

- Distributed Federated Learning
- Partial observability
- Secure aggregation
- Strong attack scenarios
- Stealthy attack scenarios
- Client-level early-warning detection
- Detection prior to aggregation
- Lightweight detection requirements

The original study additionally documents the technical and experimental
mechanisms used to satisfy and evaluate this operational priority.

These include:

- Benign reference distribution
- Bootstrap calibration
- Statistical distance measures
- Per-feature detection thresholds
- Experimental threshold exceedances

Those elements provide evidence for subsequent FR.1 reconstruction and
technical instantiation. They are not themselves CR.3 outputs.

---

## 6. Decisions not reconstructed

The available evidence does not require reconstruction of:

- A complete `High / Medium / Low` ranking of trustworthiness principles
- A universal priority of security over all other system objectives
- A governance-level escalation decision
- A context-revision decision
- A continuity decision across training rounds
- A fixed acceptable false-positive rate
- A universal intervention threshold
- An automatic response to every threshold exceedance

These would require additional contextual or methodological evidence beyond
the CR.3 reconstruction reported in the associated article.

---

## 7. Resulting contextual decision

- Contextual decision ID: `FL-CD01`
- Rule: `CR.3 — Principle Prioritisation`
- Decision: Provide lightweight early detection of adversarial behaviour,
  including strong and stealthy attacks, while preserving compatibility with
  secure aggregation
- Prioritised concerns:
  - Robustness against adversarial behaviour
  - Early detection
- Operational constraints:
  - Lightweight operation
  - Secure aggregation
  - Partial observability
- Supporting context record:
  - `FL-CTX-01`
- Downstream Functional Refinement:
  - `FR.1 — Engineering Representation Derivation`

The process-independent engineering consequences of this decision are
represented in `engineering-representation.md`.

---

## 8. Relationship to FR.1

The paper-supported CR.3 output provides input to
**FR.1 — Engineering Representation Derivation**.

The associated article reconstructs Engineering Representations requiring:

- `FL-ER01` — Lightweight early detection
- `FL-ER02` — Benign-reference calibration
- `FL-ER03` — Threshold-based monitoring

The relationship is:

**documented operational constraints  
→ CR.3  
→ FL-CD01  
→ FR.1  
→ FL-ER01 / FL-ER02 / FL-ER03**

The concrete statistical mechanisms used in the original study belong to
subsequent technical instantiation.

---

## 9. Documented technical and experimental evidence

The original study provides evidence through:

| Engineering concern | Documented evidence |
|---|---|
| Lightweight early detection | Client-level early-warning mechanism operating prior to aggregation |
| Calibration | Benign reference distribution and bootstrap calibration procedure |
| Detection criterion | Statistical distance measures and per-feature detection thresholds |
| Operational behaviour | Threshold exceedances observed under strong and stealthy attack scenarios |

This evidence supports the relationship between the contextual priority and
the reconstructed Engineering Representations.

It does not imply prospective execution of CR.3 or FR.1 during the original
study.

---

## 10. Additional illustrative review conditions

For purposes of demonstrating the reusable template, a prospective application
could review `FL-CD01` if the conditions supporting the prioritisation
materially changed.

| Illustrative review condition | Potentially affected element | Evidence source |
|---|---|---|
| Material change in adversarial behaviour | FL-CD01 | Threat / experimental evidence |
| Material change in secure-aggregation constraints | FL-CD01 | Technical / architectural evidence |
| Material change in lightweight-operation requirements | FL-CD01 | Operational evidence |
| Evidence that the existing detection approach no longer addresses the relevant attack conditions | FL-CD01 | Detection / experimental evidence |

In a prospective application, such evidence could provide input to
**CR.5 — Context Revision Trigger**.

This section is an **additional worked-template illustration**.

It does not claim paper-supported reconstruction or historical execution of
CR.5 in the Federated Learning case.

---

## 11. Verification and evidence

The paper-supported CR.3 reconstruction can be verified against documented:

- Adversarial threat conditions
- Strong attack scenarios
- Stealthy attack scenarios
- Partial observability
- Secure aggregation
- Lightweight early-warning detection
- Detection prior to aggregation

The downstream relationship with FR.1 can additionally be inspected through:

- Benign reference distribution
- Bootstrap calibration
- Statistical distance measures
- Per-feature detection thresholds
- Experimental threshold exceedances

Related paper-supported worked artefact:

- `engineering-representation.md`

Supporting repository artefacts:

- `context-description.md`
- `responsibility-map.csv`
- `traceability-matrix.csv`

Additional illustrative template artefacts:

- `assumption-log.md`
- `monitoring-plan.md`
- `feedback-log.md`

---

## 12. Assessment criterion

This contextual reconstruction contributes to:

**P2 — Coordinated Contextual and Functional Refinement**

through the relationship:

**CR.3 operational priority  
→ FR.1 Engineering Representations  
→ documented technical instantiation  
→ experimental operational evidence**

The Federated Learning case is not used in the associated article as
independent evidence of:

- P1 — Lifecycle Anchoring
- P3 — Continuity and Iterative Feedback

P4 — Cross-Domain Adaptability is assessed through cross-case comparison.

---

## 13. Analytical boundary

For this artefact, the paper-supported claim is:

**CR.3 — Principle Prioritisation**

The artefact does not establish reconstruction of:

- CR.1 — Context Interpretation
- CR.2 — Responsibility Allocation
- CR.4 — Assumption Documentation
- CR.5 — Context Revision Trigger
- CR.6 — Lifecycle Anchoring
- CR.7 — Scope Control

Pre-aggregation placement, repeated training rounds, and other documented
technical characteristics remain valid evidence about the original system but
do not independently extend the CR rule reconstruction.

---

## 14. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Paper-supported illustrative worked example
- Original project record: No
- Paper-supported CR reconstruction: CR.3

---

## Notes

This worked artefact represents the principal paper-supported Contextual
Refinement result for the Federated Learning case.

Its analytical relation is:

**documented adversarial and operational constraints  
→ CR.3 context-dependent prioritisation  
→ FL-CD01  
→ FR.1 Engineering Representation Derivation  
→ documented technical instantiation  
→ experimental evidence  
→ P2**

The example deliberately distinguishes the documented technical properties of
the original Federated Learning system from the specific refinement rule
reconstructed in the associated article.
