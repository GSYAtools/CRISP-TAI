# Monitoring Plan — Federated Learning Worked Example

This document is an **additional illustrative completion** of the
`monitoring-plan.md` template using technical monitoring evidence documented
in the Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

The analytical evaluation reported in the associated article reconstructs:

- **CR.3 — Principle Prioritisation**
- **FR.1 — Engineering Representation Derivation**

and provides analytical evidence for:

- **P2 — Coordinated Contextual and Functional Refinement**

The original Federated Learning study contains genuine detection and monitoring
mechanisms. Representing those mechanisms through this reusable template does
**not** imply paper-supported reconstruction of FR.4 or FR.6, nor does it
provide independent evidence of P3.

---

## 1. Monitoring record

- Monitoring plan ID: `FL-MON-01`
- System or component: Federated Learning setting
- Operational environment: Distributed and partially observable Federated
  Learning under adversarial conditions
- Related contextual decision:
  - `FL-CD01`
- Related Engineering Representations:
  - `FL-ER01` — Lightweight early-detection representation
  - `FL-ER02` — Benign-reference calibration representation
  - `FL-ER03` — Threshold-based monitoring representation
- Related technical instantiations:
  - `FL-PI01` — Client-level early-warning detection
  - `FL-PI02` — Benign reference distribution and bootstrap calibration
  - `FL-PI03` — Statistical distance measures and per-feature thresholds
- Paper-supported CR reconstruction:
  - `CR.3`
- Paper-supported FR reconstruction:
  - `FR.1`
- Paper-supported assessment criterion:
  - `P2`
- Artefact status: Additional illustrative worked-template representation
- Repository version: `0.2.0`

---

## 2. Documented technical monitoring scope

The original Federated Learning study documents technical mechanisms that
produce operational detection evidence.

For purposes of illustrating the reusable monitoring template, those
mechanisms can be represented as follows:

| Monitoring item ID | Technical concern | Element observed | Related Engineering Representation | Documented technical mechanism | Evidence purpose |
|---|---|---|---|---|---|
| FL-M01 | Lightweight early detection | Behaviour relevant to strong or stealthy adversarial conditions | FL-ER01 | Client-level early-warning detection | Observe whether behaviour relevant to the documented adversarial scenarios is detected |
| FL-M02 | Benign-reference calibration | Behaviour of the benign reference used for calibration | FL-ER02 | Benign reference distribution and bootstrap calibration | Establish the calibrated reference against which deviations are evaluated |
| FL-M03 | Threshold-based monitoring | Statistical deviation from the calibrated benign reference | FL-ER03 | Statistical distance measures and per-feature detection thresholds | Make relevant deviations observable through calibrated detection criteria |

These are technical monitoring relations documented in the original study.

They are not retrospective FR.4 or FR.6 outputs.

---

## 3. Monitoring evidence

| Monitoring item ID | Evidence / signal | Source | Documented condition | Related experimental evidence |
|---|---|---|---|---|
| FL-M01 | Early-warning detection behaviour | Documented detection mechanism | Detection operates under the relevant Federated Learning and adversarial conditions | Detection behaviour under strong and stealthy attack scenarios |
| FL-M02 | Benign-reference behaviour and calibration output | Benign reference / bootstrap calibration | Benign updates are used to establish the calibrated reference | Calibrated benign reference across the documented experimental procedure |
| FL-M03 | Statistical-distance values relative to calibrated thresholds | Detection mechanism | Relevant deviations are evaluated using per-feature thresholds | Observed threshold exceedances across documented attack scenarios and experimental runs |

The original technical study determines the concrete statistical signals,
features, calibration procedures, and thresholds.

CRISP-TAI does not redefine those mechanisms.

---

## 4. Relationship to the paper-supported reconstruction

The monitoring evidence represented here is related to the paper-supported
reconstruction through:

**documented operational priorities and constraints  
→ CR.3 Principle Prioritisation  
→ FL-CD01  
→ FR.1 Engineering Representation Derivation  
→ FL-ER01 / FL-ER02 / FL-ER03  
→ documented technical instantiation  
→ monitoring and experimental evidence**

The monitoring evidence therefore helps make the relationship between the
reconstructed Engineering Representations and the original technical study
inspectable.

It does not introduce additional refinement rules.

---

## 5. Relationship to FL-ER01 — Lightweight early detection

`FL-ER01` represents the process-independent requirement:

> The engineering solution shall provide a lightweight capability for
> detecting behaviour relevant to the documented strong and stealthy
> adversarial conditions while remaining compatible with the Federated
> Learning operating constraints.

The documented technical instantiation is:

- Client-level early-warning detection
- Detection prior to aggregation

The associated evidence includes detection behaviour observed under the
documented adversarial scenarios.

The pre-aggregation location belongs to the technical instantiation.

It does not establish:

- CR.6 — Lifecycle Anchoring
- FR.5 — Shift-Left Integration
- P1 — Lifecycle Anchoring

---

## 6. Relationship to FL-ER02 — Benign-reference calibration

`FL-ER02` represents the process-independent requirement:

> The engineering solution shall establish a calibrated reference derived from
> benign behaviour against which relevant deviations can be evaluated.

The documented technical instantiation is:

- Benign reference distribution
- Bootstrap calibration procedure

The associated monitoring evidence concerns the establishment and behaviour of
the calibrated benign reference.

The calibration procedure remains part of the original technical method rather
than an FR.1 output.

---

## 7. Relationship to FL-ER03 — Threshold-based monitoring

`FL-ER03` represents the process-independent requirement:

> The engineering solution shall provide calibrated detection criteria through
> which relevant deviations from the benign reference can be made observable.

The documented technical instantiation is:

- Statistical distance measures
- Per-feature detection thresholds

The associated evidence includes:

- Statistical-distance behaviour
- Threshold exceedances
- Results under strong attack scenarios
- Results under stealthy attack scenarios

Repeated evaluation of these signals is technical monitoring behaviour.

It does not by itself establish FR.4, FR.6, or P3.

---

## 8. Experimental evidence

The original study provides experimental evidence associated with the
monitoring mechanisms.

Relevant evidence includes:

- Benign updates used to establish the reference distribution
- Bootstrap-based calibration
- Strong attack scenarios
- Stealthy attack scenarios
- Independent experimental runs
- Observed threshold exceedances

This evidence supports inspection of the relationship:

**Engineering Representation  
→ technical instantiation  
→ observed technical behaviour**

The experimental evidence validates the original detection method within its
study conditions.

It does **not** constitute independent empirical validation of CRISP-TAI or the
Lifecycle Refinement Framework.

---

## 9. Additional illustrative validity review

The reusable monitoring template can also demonstrate how a prospective
application could review whether the conditions supporting the Engineering
Representations remain applicable.

| Evidence item | Illustrative condition requiring review | Related assumption | Related Engineering Representation |
|---|---|---|---|
| Early-detection behaviour | Material change in adversarial or operating conditions | FL-A01 | FL-ER01 |
| Benign-reference behaviour | Material change in benign behaviour or calibration characteristics | FL-A02 | FL-ER02 |
| Threshold behaviour | Material change in statistical-distance distributions or threshold behaviour | FL-A03 | FL-ER03 |

These are **prospective illustrative review conditions**.

They are not historical feedback events reconstructed from the original study.

---

## 10. Illustrative evidence review

In a prospective application, a monitoring observation could be represented
using:

- Evidence record ID:
- Monitoring item ID:
- Evidence observed:
- Engineering Representation potentially affected:
- Illustrative assumption potentially affected:
- Assessment:
  - Existing relation remains supported
  - Additional evidence is required
  - Validity condition may require review
  - Engineering Representation may require review
- Rationale:
- Follow-up required:

A detection signal or threshold exceedance would remain technical evidence.

It would not automatically constitute a contextual revision, engineering
adjustment, or governance decision.

---

## 11. Relationship to feedback and revision

The repository also contains `feedback-log.md` to demonstrate how later
evidence could be connected to conditional review paths in a prospective
application.

For example:

**monitoring evidence  
→ review of a validity condition  
→ potential engineering or contextual review where justified**

This illustrates the capabilities of the reusable templates.

It does **not** establish paper-supported reconstruction of:

- CR.5 — Context Revision Trigger
- FR.3 — Operational Adjustment
- FR.4 — Iterative Feedback Integration
- FR.6 — Continuity Enforcement

---

## 12. Repeated training rounds

Federated Learning operates through repeated training rounds, and the
documented detection mechanism can produce evidence during continued
operation.

This is a genuine characteristic of the original technical setting.

However:

**repeated technical monitoring ≠ FR.6 Continuity Enforcement**

and:

**repeated detection evidence ≠ FR.4 Iterative Feedback Integration**

FR.4 and FR.6 are refinement functions with their own inputs, procedures,
outputs, and verification conditions. Their reconstruction cannot be inferred
solely from repeated technical operation.

The associated article therefore does not use this case as evidence of P3.

---

## 13. Relationship to P2

This monitoring artefact helps expose the technical side of the
paper-supported P2 relation:

**CR.3 operational priority  
→ FR.1 Engineering Representation  
→ technical instantiation  
→ monitoring / experimental evidence**

The paper-supported assessment criterion remains:

- **P2 — Coordinated Contextual and Functional Refinement**

This file does not provide additional criterion coverage.

---

## 14. Analytical boundary

For the Federated Learning case, the associated article supports:

### Contextual Refinement
- **CR.3 — Principle Prioritisation**

### Functional Refinement
- **FR.1 — Engineering Representation Derivation**

### Assessment criterion
- **P2 — Coordinated Contextual and Functional Refinement**

This monitoring plan does not establish retrospective reconstruction of:

- CR.5
- CR.6
- FR.3
- FR.4
- FR.5
- FR.6
- P1
- P3

P4 — Cross-Domain Adaptability is assessed through cross-case comparison.

---

## 15. Versioning and ownership

- Artefact type: Additional illustrative completion of a CRISP-TAI v0.2.0
  template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked-template representation
- Original project record: No
- Paper-supported FR.4 reconstruction: No
- Paper-supported FR.6 reconstruction: No
- Paper-supported P3 evidence: No

---

## Notes

This monitoring plan represents **genuine technical monitoring evidence from
the original Federated Learning study** without converting that evidence into
unsupported Lifecycle Refinement rule coverage.

Its relationship to the paper-supported reconstruction is:

**CR.3  
→ FL-CD01  
→ FR.1  
→ FL-ER01 / FL-ER02 / FL-ER03  
→ technical instantiation  
→ monitoring and experimental evidence  
→ P2**

Additional review paths demonstrate reusable template capabilities only.
