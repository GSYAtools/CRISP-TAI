# Context Description — Federated Learning Worked Example

This document is an **additional illustrative completion** of the
`context-description.md` template using documentary evidence from the
Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

The analytical evaluation reported in the associated article reconstructs
**CR.3 — Principle Prioritisation** and
**FR.1 — Engineering Representation Derivation** for the Federated Learning
case.

It does **not** reconstruct CR.1, CR.4, CR.5, or CR.6 for this case.

Accordingly, this file provides a structured contextual description that helps
interpret the paper-supported CR.3 reconstruction without extending the
analytical claims made in the associated article.

---

## 1. Context record

- Record ID: `FL-CTX-01`
- System or component: Federated Learning setting
- Primary challenge: Partial observability, distributed control, and
  adversarial behaviour
- Purpose of this record: Provide supporting contextual information for the
  paper-supported CR.3 reconstruction
- Paper-supported CR reconstruction:
  - `CR.3 — Principle Prioritisation`
- Paper-supported FR reconstruction:
  - `FR.1 — Engineering Representation Derivation`
- Assessment criterion:
  - `P2 — Coordinated Contextual and Functional Refinement`
- Artefact status: Additional illustrative worked-template representation
- Repository version: `0.2.0`

---

## 2. System overview

- System name: Federated Learning setting with secure aggregation
- High-level purpose: Train a shared model through distributed client
  participation without centralising local training data
- Relevant actors: Distributed clients and a coordination / aggregation
  function
- Operational setting: Repeated distributed training under adversarial risk
- Relevant technical constraint: Secure aggregation
- Observability condition: Limited direct observability of individual client
  behaviour
- Relevant technical capability: Client-level early-warning detection prior
  to aggregation

These characteristics describe the technical setting from which the
paper-supported operational priority is reconstructed.

---

## 3. Distributed operational context

The original case concerns a distributed Federated Learning environment in
which participating clients contribute local updates while a coordination
function manages aggregation.

Relevant documented characteristics include:

- Distributed clients
- Decentralised production of model updates
- Central coordination and aggregation
- Secure aggregation
- Partial observability
- Adversarial behaviour
- Strong and stealthy attack scenarios

These conditions constrain the type of detection mechanism that can operate in
the documented setting.

They are supporting contextual evidence for the CR.3 reconstruction rather
than an independent reconstruction of CR.1.

---

## 4. Adversarial context

The original study examines early detection of adversarial behaviour,
including backdoor and poisoning attacks.

The paper-supported retrospective reconstruction identifies operational
requirements concerning:

- Robustness against strong attacks
- Robustness against stealthy attacks
- Early detection
- Compatibility with secure aggregation

These requirements provide the documentary basis for the context-dependent
priority represented in `principle-prioritisation.md`.

---

## 5. Observability and aggregation constraints

Secure aggregation and distributed operation constrain the information
available to the detection mechanism.

The documented technical setting therefore combines:

- Limited observability of individual client behaviour
- A requirement to identify relevant deviations
- Compatibility with the aggregation architecture
- A requirement for lightweight operation

These constraints are important because they explain why the Engineering
Representations reconstructed through FR.1 concern:

- Lightweight early detection
- Benign-reference calibration
- Threshold-based monitoring

They do not independently establish CR.1 or CR.6 reconstruction.

---

## 6. Documented detection setting

The original study provides technical evidence concerning:

- Client-level early-warning detection
- Detection prior to aggregation
- A benign reference distribution
- Bootstrap-based calibration
- Statistical distance measures
- Per-feature detection thresholds
- Experimental threshold exceedances

These mechanisms and experimental elements belong to the documented technical
instantiation and evidence base.

They are not themselves Contextual Refinement outputs.

---

## 7. Relationship to CR.3 — Principle Prioritisation

The contextual information in this file supports the paper-reported
reconstruction of **CR.3 — Principle Prioritisation**.

The relevant documented conditions include:

- Adversarial behaviour
- Strong and stealthy attack scenarios
- Partial observability
- Secure aggregation
- Need for early detection
- Need for lightweight operation

The reconstructed contextual priority is:

> The engineering response should provide lightweight early detection of
> adversarial behaviour while remaining compatible with the
> secure-aggregation constraints of the Federated Learning setting.

This decision is represented formally in `principle-prioritisation.md`.

This context file provides supporting evidence for that decision but does not
constitute an independent CR.1 reconstruction.

---

## 8. Relationship to FR.1 — Engineering Representation Derivation

The paper-supported CR.3 output provides input to
**FR.1 — Engineering Representation Derivation**.

The reconstructed Engineering Representations are:

- `FL-ER01` — Lightweight early-detection representation
- `FL-ER02` — Benign-reference calibration representation
- `FL-ER03` — Threshold-based monitoring representation

Their concrete technical enactment is documented through:

- Pre-aggregation client-level early-warning detection
- Benign reference distribution
- Bootstrap calibration
- Statistical distance measures
- Per-feature detection thresholds

The corresponding reconstruction is represented in
`engineering-representation.md`.

---

## 9. Additional illustrative assumptions

The reusable context template supports explicit assumption documentation.

For purposes of demonstrating that capability, the following conditions can be
represented as illustrative assumptions:

| Assumption ID | Illustrative assumption | Validity condition | Related element |
|---|---|---|---|
| FL-A01 | The operating conditions remain sufficiently compatible with those under which the documented detection evidence is meaningful | Relevant training and adversarial conditions do not change materially beyond the conditions supporting the detection approach | FL-ER01 |
| FL-A02 | The benign reference remains sufficiently meaningful for calibration | The relationship between the benign reference and the operating conditions remains materially applicable | FL-ER02 |
| FL-A03 | The threshold-based detection conditions remain sufficiently applicable | The calibration and detection conditions remain compatible with the current technical setting | FL-ER03 |

These assumptions are additional worked-template content.

They do **not** establish paper-supported reconstruction of
**CR.4 — Assumption Documentation**.

Detailed illustrative assumption management is provided in
`assumption-log.md`.

---

## 10. Pre-aggregation placement

Detection prior to aggregation is explicitly documented in the original
technical study.

Within the analytical evaluation reported in the associated article, this
placement is treated as part of the **documented technical instantiation** of
the lightweight early-detection representation.

The relationship is:

**FL-ER01 — Lightweight early-detection representation  
→ documented client-level detection prior to aggregation**

This technical placement does **not** establish independent reconstruction of:

- CR.6 — Lifecycle Anchoring
- FR.5 — Shift-Left Integration
- P1 — Lifecycle Anchoring

This distinction is deliberate.

---

## 11. Repeated training rounds

The original system operates through repeated Federated Learning rounds and
produces repeated operational evidence.

These characteristics can be represented through additional monitoring or
feedback templates.

They do not establish paper-supported reconstruction of:

- CR.5 — Context Revision Trigger
- FR.4 — Iterative Feedback Integration
- FR.6 — Continuity Enforcement
- P3 — Continuity and Iterative Feedback

---

## 12. Additional illustrative review conditions

In a prospective application, contextual or technical changes could require
review of the worked records.

Examples include:

| Review condition | Potentially affected element | Evidence source |
|---|---|---|
| Material change in adversarial conditions | CR.3 priority; FL-ER01 | Threat / experimental evidence |
| Material change in the benign reference conditions | FL-ER02 | Calibration / operational evidence |
| Material change in threshold behaviour | FL-ER03 | Detection / experimental evidence |
| Material change in secure-aggregation constraints | CR.3 priority; FL-ER01 | Technical / architectural evidence |

These are prospective illustrative review conditions.

They do not constitute reconstructed CR.5 execution.

---

## 13. Relationship to repository artefacts

### Paper-supported worked artefacts

- `principle-prioritisation.md`
- `engineering-representation.md`

### Repository traceability representation

- `traceability-matrix.csv`

### Additional illustrative template artefacts

- `context-description.md`
- `responsibility-map.csv`
- `assumption-log.md`
- `monitoring-plan.md`
- `feedback-log.md`

The presence of these additional templates does not extend the rule coverage
reported in the associated article.

---

## 14. Verification and evidence

The contextual information represented here is grounded in documented:

- Distributed Federated Learning
- Partial observability
- Secure aggregation
- Adversarial backdoor / poisoning setting
- Strong and stealthy attack scenarios
- Client-level early-warning detection
- Pre-aggregation detection
- Benign reference distribution
- Bootstrap calibration
- Statistical distance measures
- Per-feature detection thresholds
- Experimental threshold exceedances

These elements support interpretation of the paper-supported
**CR.3 → FR.1 → P2** reconstruction.

---

## 15. Analytical boundary

For the Federated Learning case, the associated article supports:

### Contextual Refinement
- **CR.3 — Principle Prioritisation**

### Functional Refinement
- **FR.1 — Engineering Representation Derivation**

### Assessment criterion
- **P2 — Coordinated Contextual and Functional Refinement**

This context description does not add:

- CR.1
- CR.4
- CR.5
- CR.6
- P1
- P3

to that analytical reconstruction.

P4 — Cross-Domain Adaptability is assessed through cross-case comparison.

---

## 16. Versioning and ownership

- Artefact type: Additional illustrative completion of a CRISP-TAI v0.2.0
  template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked-template representation
- Original project record: No
- Paper-supported CR.1 reconstruction: No
- Paper-supported CR.4 reconstruction: No
- Paper-supported CR.6 reconstruction: No

---

## Notes

This document provides structured contextual information for understanding the
Federated Learning worked example.

Its role is:

**documented technical context  
→ supporting evidence for CR.3  
→ FR.1 Engineering Representations  
→ documented technical instantiation  
→ experimental evidence  
→ P2**

It should not be interpreted as an independent reconstruction of CR.1,
assumption management, lifecycle anchoring, contextual revision, or lifecycle
continuity.
