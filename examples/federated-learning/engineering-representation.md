# Engineering Representation — Federated Learning Worked Example

This document is an **illustrative retrospective completion** of the
`engineering-representation.md` template using documentary evidence from the
Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

For the analytical evaluation reported in the associated article, this worked
artefact represents **FR.1 — Engineering Representation Derivation**.

The paper-supported reconstruction expresses the operational priority
reconstructed through **CR.3 — Principle Prioritisation** as
process-independent Engineering Representations concerning:

- Lightweight early detection
- Benign-reference calibration
- Threshold-based monitoring

These representations remain distinct from the statistical and technical
mechanisms through which they are subsequently instantiated.

---

## 1. Representation record

- Record group ID: `FL-ER`
- System or component: Federated Learning setting
- Primary reconstructed rule:
  - `FR.1 — Engineering Representation Derivation`
- Originating Contextual Refinement:
  - `CR.3 — Principle Prioritisation`
- Originating contextual decision:
  - `FL-CD01`
- Primary challenge:
  - Partial observability
  - Distributed control
  - Adversarial behaviour
- Relevant operational priority:
  - Lightweight early detection of strong and stealthy adversarial behaviour
    while remaining compatible with secure aggregation
- Related context record:
  - `FL-CTX-01`
- Related prioritisation record:
  - `FL-PRIO-01`
- Artefact status: Paper-supported retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Originating contextual decision

The paper-supported FR.1 reconstruction originates from the contextual priority
represented by `FL-CD01`.

### FL-CD01 — Operational priority

> The engineering response should provide lightweight early detection of
> adversarial behaviour, including strong and stealthy attacks, while
> remaining compatible with the secure-aggregation constraints of the
> Federated Learning setting.

This decision is reconstructed through
**CR.3 — Principle Prioritisation**.

Its documentary basis includes:

- Strong attack scenarios
- Stealthy attack scenarios
- Partial observability
- Secure aggregation
- Need for early detection
- Need for lightweight operation

FR.1 expresses this contextual priority in process-independent engineering
form.

---

## 3. FR.1 — Engineering Representation derivation

| Representation ID | Contextual decision ID | Representation type | Engineering Representation | Rationale |
|---|---|---|---|---|
| FL-ER01 | FL-CD01 | Lightweight early-detection representation | The engineering solution shall provide a lightweight capability for detecting behaviour relevant to the documented strong and stealthy adversarial conditions while remaining compatible with the Federated Learning operating constraints | Expresses the required early-detection capability independently of the specific detection algorithm or its final technical placement |
| FL-ER02 | FL-CD01 | Benign-reference calibration representation | The engineering solution shall establish a calibrated reference derived from benign behaviour against which relevant deviations can be evaluated | Expresses the required calibration capability independently of the specific bootstrap procedure or reference-distribution implementation |
| FL-ER03 | FL-CD01 | Threshold-based monitoring representation | The engineering solution shall provide calibrated detection criteria through which relevant deviations from the benign reference can be made observable | Expresses the required threshold-based detection capability independently of the specific statistical distance measures, features, or numerical thresholds |

These are **process-independent Engineering Representations**.

They do not prescribe:

- A specific CRISP-DM phase
- A particular detection algorithm
- A statistical distance measure
- A bootstrap implementation
- A feature set
- A numerical threshold
- A concrete technical component
- A lifecycle artefact

Those choices belong to subsequent technical and process-specific
instantiation.

---

## 4. Representation specification

### FL-ER01 — Lightweight early detection

- Representation type: Lightweight early-detection representation
- Originating contextual decision: `FL-CD01`
- Relevant constraints:
  - Strong adversarial behaviour
  - Stealthy adversarial behaviour
  - Partial observability
  - Secure aggregation
  - Lightweight operation
- Verification condition: A documented technical mechanism can be identified
  that provides the required early-warning capability under the relevant
  Federated Learning constraints
- Documented technical evidence:
  - Client-level early-warning detection
  - Detection prior to aggregation

The fact that the documented mechanism operates before aggregation belongs to
its technical instantiation. It does not make lifecycle placement part of
FR.1.

---

### FL-ER02 — Benign-reference calibration

- Representation type: Benign-reference calibration representation
- Originating contextual decision: `FL-CD01`
- Relevant constraints:
  - Detection requires an operational reference against which deviations can
    be assessed
  - The reference must be established under the documented Federated Learning
    conditions
- Verification condition: A documented calibration mechanism can be related to
  a benign reference used by the detection approach
- Documented technical evidence:
  - Benign reference distribution
  - Bootstrap calibration procedure

The benign reference distribution and bootstrap procedure are concrete
technical mechanisms.

They are not FR.1 outputs themselves.

---

### FL-ER03 — Threshold-based monitoring

- Representation type: Threshold-based monitoring representation
- Originating contextual decision: `FL-CD01`
- Relevant constraints:
  - Relevant deviations must become observable
  - Detection criteria must be calibrated against the reference behaviour
- Verification condition: A documented technical mechanism provides calibrated
  criteria against which relevant deviations can be evaluated
- Documented technical evidence:
  - Statistical distance measures
  - Per-feature detection thresholds
  - Experimental threshold exceedances

The statistical measures and numerical thresholds belong to technical
instantiation rather than to the process-independent Engineering
Representation.

---

## 5. Derivation rationale

The paper-supported reconstruction follows:

**documented operational priorities and constraints  
→ CR.3 Principle Prioritisation  
→ FL-CD01  
→ FR.1 Engineering Representation Derivation**

The three Engineering Representations express complementary engineering
capabilities required by the same contextual priority.

### Early detection

**Strong and stealthy adversarial conditions  
+ need for lightweight operation  
+ secure-aggregation constraints  
→ lightweight early-detection capability  
→ FL-ER01**

### Calibration

**Need to distinguish relevant deviations from expected benign behaviour  
→ benign-reference calibration capability  
→ FL-ER02**

### Detection criterion

**Calibrated reference  
+ need to make relevant deviations observable  
→ threshold-based monitoring capability  
→ FL-ER03**

This decomposition remains independent of the concrete statistical mechanisms
used by the original study.

---

## 6. Documented technical instantiation

The original Federated Learning study documents concrete technical mechanisms
through which the reconstructed Engineering Representations can be
retrospectively mapped.

| Representation ID | Instantiation ID | Documented technical enactment | Instantiation rationale |
|---|---|---|---|
| FL-ER01 | FL-PI01 | Client-level early-warning detection operating prior to aggregation | Provides the lightweight early-detection capability represented by FL-ER01 |
| FL-ER02 | FL-PI02 | Benign reference distribution and bootstrap calibration procedure | Provides the calibrated benign-reference capability represented by FL-ER02 |
| FL-ER03 | FL-PI03 | Statistical distance measures and per-feature detection thresholds | Provides the threshold-based detection capability represented by FL-ER03 |

These mappings are **retrospective technical instantiations**.

They do not imply that `FL-ER01` to `FL-ER03` were explicitly formulated
before the original technical mechanisms were developed.

---

## 7. Experimental operational evidence

The original study also provides experimental evidence associated with the
technical instantiation.

Relevant evidence includes:

- Benign updates used to establish the calibrated reference
- Strong attack scenarios
- Stealthy attack scenarios
- Independent experimental runs
- Observed threshold exceedances

The relationship can therefore be inspected as:

**FL-ER01 / FL-ER02 / FL-ER03  
→ documented technical mechanisms  
→ experimental operational evidence**

This experimental evidence belongs to the original technical study.

It does not constitute independent empirical validation of FR.1 or of the
Lifecycle Refinement Framework.

---

## 8. Relationship to P2

The Federated Learning case provides analytical evidence for:

**P2 — Coordinated Contextual and Functional Refinement**

through the chain:

**documented operational constraints  
→ CR.3  
→ FL-CD01  
→ FR.1  
→ FL-ER01 / FL-ER02 / FL-ER03  
→ documented technical instantiation  
→ experimental evidence**

This demonstrates that the contextual priority reconstructed from the original
case can be translated into identifiable process-independent engineering
capabilities and related retrospectively to concrete technical mechanisms.

---

## 9. Process-instantiation boundary

The distinction between Engineering Representation and technical enactment is
particularly important in this case.

For example:

### Process-independent representation

`FL-ER02`:

> The engineering solution shall establish a calibrated reference derived from
> benign behaviour against which relevant deviations can be evaluated.

### Documented technical enactment

- Benign reference distribution
- Bootstrap calibration procedure

Likewise:

### Process-independent representation

`FL-ER03`:

> The engineering solution shall provide calibrated detection criteria through
> which relevant deviations from the benign reference can be made observable.

### Documented technical enactment

- Statistical distance measures
- Per-feature detection thresholds

The relationship is therefore:

**CR.3 contextual decision  
→ FR.1 Engineering Representation  
→ technical / Process Instantiation  
→ experimental evidence**

and not:

**CR.3  
→ FR.1  
→ statistical algorithm**

---

## 10. Relationship to pre-aggregation placement

The original study documents detection prior to aggregation.

This is retained as technical evidence concerning `FL-PI01`.

Within the analytical evaluation reported in the associated article, it does
not establish independent reconstruction of:

- CR.6 — Lifecycle Anchoring
- FR.5 — Shift-Left Integration
- P1 — Lifecycle Anchoring

The process-independent `FL-ER01` requires lightweight early detection but does
not prescribe the final lifecycle or architectural location.

---

## 11. Additional illustrative assumptions

The additional `assumption-log.md` demonstrates how validity conditions could
be associated with the three Engineering Representations in a prospective
application:

- `FL-A01` ↔ `FL-ER01`
- `FL-A02` ↔ `FL-ER02`
- `FL-A03` ↔ `FL-ER03`

These relations support reusable template integration.

They are not inputs used to claim CR.4 reconstruction in the associated
article.

---

## 12. Additional illustrative monitoring and feedback

The original technical system produces repeated detection evidence across
Federated Learning operation.

The repository may represent such evidence using:

- `monitoring-plan.md`
- `feedback-log.md`

Those worked artefacts demonstrate how the reusable templates could be
connected to the technical setting.

They do not establish paper-supported reconstruction of:

- FR.3 — Operational Adjustment
- FR.4 — Iterative Feedback Integration
- FR.6 — Continuity Enforcement
- P3 — Continuity and Iterative Feedback

---

## 13. Verification and evidence

The paper-supported FR.1 reconstruction is grounded in documented:

- Partial observability
- Distributed Federated Learning
- Secure aggregation
- Strong adversarial scenarios
- Stealthy adversarial scenarios
- Lightweight early-warning detection
- Benign reference distribution
- Bootstrap calibration
- Statistical distance measures
- Per-feature detection thresholds
- Experimental threshold exceedances

Verification in this worked example means that each reconstructed Engineering
Representation can be related to:

1. `FL-CD01`
2. A documented technical mechanism
3. Relevant experimental evidence

It does not mean that FR.1 was prospectively executed during the original
study.

---

## 14. Analytical boundary

For the Federated Learning case, the associated article supports:

### Contextual Refinement
- **CR.3 — Principle Prioritisation**

### Functional Refinement
- **FR.1 — Engineering Representation Derivation**

### Assessment criterion
- **P2 — Coordinated Contextual and Functional Refinement**

This artefact does not establish reconstruction of:

- FR.2 — Decision Traceability
- FR.3 — Operational Adjustment
- FR.4 — Iterative Feedback Integration
- FR.5 — Shift-Left Integration
- FR.6 — Continuity Enforcement
- P1 — Lifecycle Anchoring
- P3 — Continuity and Iterative Feedback

P4 — Cross-Domain Adaptability is assessed through cross-case comparison.

---

## 15. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Paper-supported illustrative worked example
- Original project record: No
- Paper-supported FR reconstruction: FR.1

---

## Notes

This worked artefact represents the principal paper-supported Functional
Refinement result for the Federated Learning case.

Its authoritative analytical chain is:

**documented operational constraints  
→ CR.3  
→ FL-CD01  
→ FR.1  
→ lightweight early detection / benign-reference calibration /
threshold-based monitoring  
→ documented technical instantiation  
→ experimental evidence  
→ P2**

The example deliberately separates the process-independent engineering
capabilities reconstructed through FR.1 from the statistical and technical
mechanisms used in the original Federated Learning study.
