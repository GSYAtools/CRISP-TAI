# Worked Example — Federated Learning with Early Trustworthiness Monitoring

This directory provides an **illustrative worked example** showing how the
reusable CRISP-TAI repository templates can be populated retrospectively using
documentary evidence from the Federated Learning case examined in the
associated research article.

The example is based on material documented in:

*Early detection of backdoor attacks in federated learning via ecosystemic
symmetry breaking*.

It represents that material using the **v0.2.0 CRISP-TAI artefact structure**.

This example does **not** imply that the Lifecycle Refinement Framework or
CRISP-TAI was prospectively applied during the original Federated Learning
study. The completed artefacts are retrospective representations intended to
illustrate how the current templates can be used.

---

## Example scope

The case concerns a Federated Learning setting characterised by partial
observability, distributed control, secure aggregation, and adversarial
behaviour.

The original study documents:

- Distributed Federated Learning
- Secure aggregation
- Strong and stealthy adversarial scenarios
- A lightweight client-level early-warning detection mechanism
- Detection prior to aggregation
- A benign reference distribution
- Bootstrap-based calibration
- Statistical distance measures
- Per-feature detection thresholds
- Experimental threshold exceedances

Within the analytical evaluation reported in the associated article, this
evidence supports reconstruction of:

- **CR.3 — Principle Prioritisation**
- **FR.1 — Engineering Representation Derivation**

The case provides analytical evidence for:

- **P2 — Coordinated Contextual and Functional Refinement**

The associated article does not use the Federated Learning case as independent
evidence of P1 — Lifecycle Anchoring or P3 — Continuity and Iterative
Feedback.

P4 — Cross-Domain Adaptability is assessed through comparison of the three
retrospective applications rather than through this case alone.

---

## Paper-supported reconstruction

The principal analytical chain for this case is:

**Documented operational priorities and constraints  
→ CR.3 Principle Prioritisation  
→ FR.1 process-independent Engineering Representations  
→ documented technical instantiation  
→ experimental operational evidence  
→ P2**

CR.3 reconstructs the operational priority of providing lightweight early
detection of adversarial behaviour while remaining compatible with the
secure-aggregation constraints of the Federated Learning setting.

FR.1 reconstructs process-independent Engineering Representations concerning:

- Lightweight early detection
- Benign-reference calibration
- Threshold-based monitoring

The original technical study then provides documented mechanisms through which
these representations can be retrospectively instantiated.

---

## How to interpret the files in this directory

The files in this directory are **completed examples of the reusable
templates** provided under `/templates`.

They should be read as retrospective or illustrative representations of
documented case evidence, not as original project records.

Two categories of worked artefact are intentionally distinguished.

### Paper-supported reconstruction

The following artefacts represent the rule reconstruction reported in the
associated article:

- `principle-prioritisation.md` — CR.3
- `engineering-representation.md` — FR.1

The corresponding technical instantiation and experimental evidence are
linked through `traceability-matrix.csv`.

### Additional illustrative template usage

The remaining templates demonstrate how other contextual, responsibility,
assumption, traceability, monitoring, or feedback information associated with
the same technical setting could be represented in a prospective or broader
use of CRISP-TAI.

Their inclusion does **not** imply that additional CR or FR rules were
reconstructed as part of the analytical evaluation reported in the associated
article.

Template availability therefore must not be interpreted as rule coverage.

---

## Contextual Refinement worked artefacts

### `context-description.md`

Provides an illustrative structured description of the distributed,
partially observable Federated Learning setting, including secure aggregation
and adversarial conditions.

This contextual description supports readability and reuse of the worked
example.

It does **not** imply that CR.1 — Context Interpretation is part of the
paper-supported Federated Learning reconstruction.

### `responsibility-map.csv`

Illustrates how responsibilities associated with clients, coordination,
monitoring, and technical operation can be represented using the reusable
responsibility template.

Its inclusion does **not** imply paper-supported reconstruction of
CR.2 — Responsibility Allocation.

### `principle-prioritisation.md`

Represents the paper-supported reconstruction of
**CR.3 — Principle Prioritisation**.

The documented operational context supports a priority requiring:

> lightweight early detection of adversarial behaviour while remaining
> compatible with secure aggregation.

The reconstruction is grounded in the original study's adversarial setting,
including strong and stealthy attacks, partial observability, and
secure-aggregation constraints.

### `assumption-log.md`

Illustrates how assumptions and validity conditions associated with the
technical setting could be represented using the reusable assumption template.

Its inclusion does **not** imply paper-supported reconstruction of
CR.4 — Assumption Documentation or CR.5 — Context Revision Trigger.

---

## Functional Refinement worked artefacts

### `engineering-representation.md`

Represents the paper-supported reconstruction of
**FR.1 — Engineering Representation Derivation**.

The reconstructed process-independent Engineering Representations are:

- `FL-ER01` — Lightweight early-detection representation
- `FL-ER02` — Benign-reference calibration representation
- `FL-ER03` — Threshold-based monitoring representation

These describe required engineering capabilities without prescribing the
specific statistical implementation used in the original study.

### `traceability-matrix.csv`

Provides an inspectable mapping among:

**CR.3 operational priority  
→ FR.1 Engineering Representation  
→ documented technical instantiation  
→ experimental evidence  
→ P2**

The matrix is used as a repository traceability artefact.

Its use does **not** imply that FR.2 — Decision Traceability is independently
reconstructed for the Federated Learning case in the associated article.

Likewise, reusable fields concerning anchoring, scope, or placement do not
constitute evidence of CR.6, CR.7, or FR.5 reconstruction.

### `monitoring-plan.md`

Illustrates how the documented detection and monitoring mechanisms could be
represented using the reusable monitoring template.

The original study genuinely contains per-round detection and operational
monitoring behaviour. However, representing those characteristics through
this template does **not** imply that FR.4 or FR.6 is part of the
paper-supported retrospective reconstruction.

### `feedback-log.md`

Illustrates how detection evidence, threshold exceedances, or other
operational observations could be connected to conditional review paths in a
prospective application.

It does not claim historical CR.5, FR.3, FR.4, or FR.6 execution.

---

## Documented technical instantiation

The original Federated Learning study provides concrete technical mechanisms
through which the reconstructed Engineering Representations can be
retrospectively mapped.

### FL-ER01 — Lightweight early detection

Documented enactment:

- Client-level early-warning detection
- Detection prior to aggregation

### FL-ER02 — Benign-reference calibration

Documented enactment:

- Benign reference distribution
- Bootstrap calibration procedure

### FL-ER03 — Threshold-based monitoring

Documented enactment:

- Statistical distance measures
- Per-feature detection thresholds

These mechanisms are **documented technical instantiations**, not outputs
prospectively generated through FR.1.

---

## Relationship to experimental evidence

The Federated Learning case is particularly useful because the original study
provides experimental operational evidence in addition to the documented
technical mechanisms.

The evaluation includes:

- Benign updates used to establish the calibrated reference
- Strong attack scenarios
- Stealthy attack scenarios
- Independent experimental runs
- Observed threshold exceedances

This evidence supports the analytical relationship:

**operational constraints  
→ reconstructed Engineering Representations  
→ technical instantiation  
→ observed operational behaviour**

and provides the basis for the P2 assessment reported in the associated
article.

The experimental results validate the original detection method within its
study conditions; they do **not** constitute independent empirical validation
of CRISP-TAI or the Lifecycle Refinement Framework.

---

## Relationship to pre-aggregation placement

Detection prior to aggregation is an important documented characteristic of
the original technical mechanism.

Within the analytical evaluation reported in the associated article, however,
this placement is treated as part of the **documented technical
instantiation** of `FL-ER01`.

It is not used to claim:

- CR.6 — Lifecycle Anchoring
- FR.5 — Shift-Left Integration
- P1 — Lifecycle Anchoring

This distinction prevents a documented implementation location from being
automatically interpreted as reconstruction of a lifecycle-refinement rule.

---

## Relationship to repeated training rounds

The original technical mechanism operates across Federated Learning training
rounds and produces repeated detection evidence.

These characteristics may be represented using the monitoring and feedback
templates for illustrative purposes.

They do not establish paper-supported reconstruction of:

- CR.5 — Context Revision Trigger
- FR.3 — Operational Adjustment
- FR.4 — Iterative Feedback Integration
- FR.6 — Continuity Enforcement
- P3 — Continuity and Iterative Feedback

---

## Canonical retrospective application record

The methodological reconstruction of this case is documented separately in:

`/logs/federated-learning-retrospective-application.md`

That record defines the canonical analytical boundary for this case:

- CR reconstruction: **CR.3**
- FR reconstruction: **FR.1**
- Assessment criterion: **P2**

Where an example-level template contains additional fields, relationships, or
illustrative refinement paths, the canonical retrospective application record
and the associated research article determine which rules and assessment
criteria are actually supported by the analytical evaluation.

---

## Relationship to the original Federated Learning material

The original Federated Learning study remains the evidential source for the
retrospective reconstruction.

The completed templates in this directory:

- Do not replace the original technical or experimental description
- Do not constitute original project documentation
- Do not reimplement the detection method
- Do not demonstrate prospective execution of CRISP-TAI
- Do not constitute independent empirical validation of the Lifecycle
  Refinement Framework
- Do not imply reconstruction of every CR or FR rule represented by the
  reusable template structure
- Do provide an illustrative and inspectable representation of the
  relationship between documented operational constraints, reconstructed
  Engineering Representations, technical instantiation, and experimental
  evidence

---

## Purpose of the worked example

This example is intended primarily to illustrate:

1. Reconstruction of a context-dependent operational priority through CR.3
2. Derivation of process-independent Engineering Representations through FR.1
3. Separation of those representations from their concrete statistical and
   technical implementation
4. Mapping to documented benign-reference calibration, statistical distance
   measures, detection thresholds, and pre-aggregation detection
5. Connection to experimental threshold-exceedance evidence
6. Use of additional repository templates without converting template
   availability into unsupported rule-coverage claims

It should therefore be used as an **illustrative worked example**, not as a
reference implementation, certification procedure, or claim that CRISP-TAI
was used during the original Federated Learning study.
