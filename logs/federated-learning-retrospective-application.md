# Retrospective Application Log — Federated Learning

This record documents the **retrospective application** of the Lifecycle
Refinement Framework through its CRISP-TAI instantiation to the Federated
Learning (FL) case examined in the associated research article.

The case concerns early detection of backdoor and poisoning attacks in a
distributed Federated Learning setting. The retrospective reconstruction is
aligned with the original study:

*Early detection of backdoor attacks in federated learning via ecosystemic
symmetry breaking*.

This record reconstructs only those Contextual Refinement and Functional
Refinement relations supported by the analytical evaluation reported in the
associated article.

It does **not** imply that CRISP-TAI was prospectively executed during the
original study and should not be interpreted as independent empirical
validation of the framework.

---

## 1. Application scope

- Setting: Federated Learning with distributed clients and secure aggregation
- Application type: Retrospective analytical reconstruction
- Framework instantiation: CRISP-TAI
- Primary challenge: Partial observability, distributed control, and
  adversarial behaviour
- CR reconstruction reported in the associated article:
  **CR.3 — Principle Prioritisation**
- FR reconstruction reported in the associated article:
  **FR.1 — Engineering Representation Derivation**
- Assessment criterion supported:
  **P2 — Coordinated Contextual and Functional Refinement**
- Evidence basis:
  - Operational constraints documented in the original study
  - Robustness requirements concerning strong and stealthy attacks
  - Compatibility with secure aggregation
  - Benign reference distribution
  - Bootstrap calibration procedure
  - Statistical distance measures
  - Per-feature detection thresholds
  - Experimental threshold exceedances

---

## 2. Reconstructed Contextual Refinement

### CR.3 — Principle Prioritisation

The original Federated Learning study documents operational priorities and
constraints relevant to the adversarial setting.

The analytical reconstruction reported in the associated article identifies
two particularly relevant conditions:

- Robustness against strong and stealthy attacks
- Compatibility with secure aggregation

These documented conditions provide the basis for reconstructing a
context-dependent operational priority through
**CR.3 — Principle Prioritisation**.

**Reconstructed contextual output:**

> The engineering response should provide lightweight early detection of
> adversarial behaviour while remaining compatible with the secure-aggregation
> constraints of the Federated Learning setting.

This reconstruction captures the operational balance documented in the
original study.

It does not establish a universal prioritisation of robustness or security
over other trustworthiness concerns.

**Documentary basis:**

- Adversarial threat setting
- Partial observability
- Secure aggregation
- Strong and stealthy attack scenarios
- Operational requirement for early detection

---

## 3. Reconstructed Functional Refinement

### FR.1 — Engineering Representation Derivation

The operational priority reconstructed through CR.3 can be expressed as
process-independent Engineering Representations.

The associated article identifies representations requiring:

- Lightweight early detection
- Benign-reference calibration
- Threshold-based monitoring

These representations express **what engineering capabilities are required**
without making the specific statistical implementation part of FR.1.

### Reconstructed Engineering Representations

#### FL-ER01 — Lightweight early-detection representation

Potentially adversarial behaviour should be detectable early enough to support
the intended Federated Learning operation without requiring unrestricted
inspection of individual client behaviour.

#### FL-ER02 — Benign-reference calibration representation

The detection mechanism should establish an operational reference from benign
behaviour against which relevant deviations can be evaluated.

#### FL-ER03 — Threshold-based monitoring representation

Detection evidence should be evaluated against calibrated decision thresholds
that make relevant deviations observable during operation.

These are **process-independent Engineering Representations**.

The benign reference distribution, bootstrap procedure, statistical distance
measures, and concrete per-feature thresholds documented in the original study
belong to their subsequent technical instantiation.

---

## 4. Documented process-specific instantiation

The original case material provides concrete technical evidence through which
the reconstructed Engineering Representations were enacted.

| Engineering Representation | Documented technical instantiation |
|---|---|
| FL-ER01 — Lightweight early detection | Client-level early-warning detection mechanism operating prior to aggregation |
| FL-ER02 — Benign-reference calibration | Benign reference distribution and bootstrap calibration procedure |
| FL-ER03 — Threshold-based monitoring | Statistical distance measures and per-feature detection thresholds |

The original experimental evaluation additionally provides operational
evidence through:

- Benign updates used to establish the calibrated reference
- Strong attack scenarios
- Stealthy attack scenarios
- Independent experimental runs
- Observed threshold exceedances

These elements provide documented evidence that the reconstructed operational
priority and Engineering Representations can be related to concrete technical
mechanisms.

Their existence does not imply that CR.3 or FR.1 were prospectively executed
during development of the original study.

---

## 5. Traceability summary

| Trustworthiness concern | Contextual reconstruction | CR rule | Engineering Representation | FR rule | Documented instantiation evidence |
|---|---|---|---|---|---|
| Early adversarial detection | Robustness against strong and stealthy attacks under partial observability and secure aggregation | CR.3 | Lightweight early-detection representation | FR.1 | Client-level pre-aggregation early-warning mechanism |
| Detection calibration | Early detection must operate using an appropriate reference under the documented FL conditions | CR.3 | Benign-reference calibration representation | FR.1 | Benign reference distribution and bootstrap calibration |
| Operational detection criterion | Relevant deviations must become observable through the detection mechanism | CR.3 | Threshold-based monitoring representation | FR.1 | Statistical distance measures, per-feature thresholds, and observed experimental threshold exceedances |

---

## 6. P2 — Coordinated Contextual and Functional Refinement

The Federated Learning case provides analytical evidence for:

**P2 — Coordinated Contextual and Functional Refinement**

through the reconstructable relationship:

**documented operational priorities and constraints  
→ CR.3 Principle Prioritisation  
→ FR.1 process-independent Engineering Representations  
→ documented technical instantiation  
→ experimental operational evidence**

The experimental evaluation provides a particularly useful connection between
the reconstructed refinement chain and the documented technical mechanism.

Benign updates establish the calibrated reference, while strong and stealthy
attack scenarios are evaluated against the resulting thresholds. The observed
threshold exceedances therefore provide documentary evidence connecting:

- The operational constraints reconstructed through CR.3
- The Engineering Representations reconstructed through FR.1
- Their concrete technical instantiation

This is the basis for the P2 assessment reported in the associated article.

---

## 7. Assessment boundary

The Federated Learning retrospective application reported in the associated
article is limited to:

### Contextual Refinement
- **CR.3 — Principle Prioritisation**

### Functional Refinement
- **FR.1 — Engineering Representation Derivation**

### Assessment criterion
- **P2 — Coordinated Contextual and Functional Refinement**

The paper-supported retrospective application does **not** use this case as
evidence of:

- CR.1 — Context Interpretation
- CR.4 — Assumption Documentation
- CR.5 — Context Revision Trigger
- CR.6 — Lifecycle Anchoring
- CR.7 — Scope Control
- FR.2 — Decision Traceability
- FR.3 — Operational Adjustment
- FR.4 — Iterative Feedback Integration
- FR.5 — Shift-Left Integration
- FR.6 — Continuity Enforcement
- P1 — Lifecycle Anchoring
- P3 — Continuity and Iterative Feedback

P4 — Cross-Domain Adaptability is assessed through the cross-case comparison
of all three retrospective applications rather than through the Federated
Learning case alone.

---

## 8. Relationship to repository artefacts

The paper-supported reconstruction can be represented principally through:

- `templates/contextual-refinement/principle-prioritisation.md`
- `templates/functional-refinement/engineering-representation.md`

The worked example also uses other reusable templates to demonstrate how
additional contextual, responsibility, assumption, traceability, monitoring,
or feedback information could be structured.

Those additional worked-template artefacts do **not** extend the set of CR or
FR rules reconstructed for Federated Learning in the associated article.

The distinction is:

**paper-supported reconstruction**
- CR.3
- FR.1
- P2

versus:

**additional illustrative template usage**
- Other contextual or functional artefacts used to demonstrate repository
  reuse and integration

---

## 9. Relationship to pre-aggregation placement

The original study documents detection **prior to aggregation**.

This is relevant technical evidence concerning the implementation of the
early-detection mechanism.

Within the paper-supported retrospective evaluation, however, this technical
placement is treated as part of the documented instantiation of the
reconstructed Engineering Representation.

It is **not** used to claim independent reconstruction of
**CR.6 — Lifecycle Anchoring** or evidence of
**P1 — Lifecycle Anchoring** for the Federated Learning case.

This distinction preserves the analytical boundary reported in the associated
article.

---

## 10. Relationship to repeated training rounds

The original Federated Learning mechanism operates across training rounds and
produces operational detection evidence.

These characteristics can be used in the worked example to illustrate
monitoring, assumption review, feedback, or continuity templates.

They are not used in the associated article to claim retrospective
reconstruction of:

- FR.4 — Iterative Feedback Integration
- FR.6 — Continuity Enforcement
- P3 — Continuity and Iterative Feedback

The repository therefore distinguishes the **technical characteristics of the
original system** from the **refinement rules reconstructed in the analytical
evaluation**.

---

## 11. Verification and evidence

The paper-supported reconstruction is grounded in documented:

- Partial observability
- Distributed Federated Learning
- Secure aggregation
- Strong and stealthy adversarial scenarios
- Lightweight early-warning detection
- Benign reference distribution
- Bootstrap calibration
- Statistical distance measures
- Per-feature detection thresholds
- Experimental threshold exceedances

These elements allow the relationship between CR.3, FR.1, and the documented
technical mechanism to be inspected without claiming prospective framework
execution.

---

## 12. Analytical status

- Application type: Retrospective analytical reconstruction
- Original CRISP-TAI project record: No
- Prospective framework execution: No
- Independent empirical validation of CRISP-TAI: No
- Paper-supported CR reconstruction: CR.3
- Paper-supported FR reconstruction: FR.1
- Paper-supported assessment criterion: P2

---

## Notes

This record is a **retrospective application log**, not an execution log.

Its authoritative analytical chain is:

**documented FL operational constraints  
→ CR.3 Principle Prioritisation  
→ FR.1 Engineering Representation Derivation  
→ documented technical instantiation  
→ experimental operational evidence  
→ P2**

The original Federated Learning study contains additional contextual,
monitoring, placement, and repeated-operation characteristics. These may be
represented using additional repository templates for illustrative purposes,
but they do not extend the retrospective rule reconstruction reported in the
associated article.
