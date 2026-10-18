# Assumption Log — Federated Learning Worked Example

This document is an **additional illustrative completion** of the
`assumption-log.md` template using contextual and technical conditions that
can be related to the Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

The analytical evaluation reported in the associated article reconstructs:

- **CR.3 — Principle Prioritisation**
- **FR.1 — Engineering Representation Derivation**

and provides analytical evidence for:

- **P2 — Coordinated Contextual and Functional Refinement**

It does **not** reconstruct **CR.4 — Assumption Documentation** or
**CR.5 — Context Revision Trigger** for the Federated Learning case.

Accordingly, this file demonstrates how the reusable assumption template could
be populated consistently with the documented technical setting without
extending the analytical claims made in the associated article.

---

## 1. Log information

- System or component: Federated Learning setting
- Log ID: `FL-ASSUMPTIONS-01`
- Related context record: `FL-CTX-01`
- Related prioritisation record: `FL-PRIO-01`
- Related contextual decision: `FL-CD01`
- Paper-supported CR reconstruction: `CR.3`
- Paper-supported FR reconstruction: `FR.1`
- Template function illustrated here: `CR.4 — Assumption Documentation`
- Artefact status: Additional illustrative worked-template representation
- Repository version: `0.2.0`

---

## 2. Assumption register

The assumptions below are **illustrative structured assumptions** derived from
technical and operational conditions documented in the Federated Learning
case.

They are not presented as assumptions explicitly reconstructed through CR.4
in the analytical evaluation reported in the associated article.

| Assumption ID | Assumption | Type | Validity condition | Rationale / evidence | Related Engineering Representation | Responsible role | Illustrative review trigger | Status |
|---|---|---|---|---|---|---|---|---|
| FL-A01 | The documented adversarial and operating conditions remain sufficiently compatible with those under which lightweight early detection is meaningful | Operational / Adversarial | Relevant attack characteristics, client behaviour, and operating conditions do not change materially beyond the conditions supporting the documented early-warning approach | Strong and stealthy attack scenarios and documented early-warning mechanism | FL-ER01 | Detection / Monitoring Function | Material change in adversarial behaviour, operating conditions, or observed detection behaviour | Illustrative |
| FL-A02 | The benign reference remains sufficiently representative of the non-adversarial operating conditions required for calibration | Calibration / Statistical | The relationship between the benign reference distribution and current non-adversarial behaviour remains materially applicable | Documented benign reference distribution and bootstrap calibration procedure | FL-ER02 | Detection / Monitoring Function | Material change in benign behaviour, reference distribution, or calibration characteristics | Illustrative |
| FL-A03 | The calibrated threshold conditions remain sufficiently applicable to distinguish relevant deviations under the documented detection setting | Detection / Statistical | Statistical-distance behaviour and the conditions supporting the calibrated per-feature thresholds remain materially compatible with current operation | Documented statistical distance measures, per-feature thresholds, and experimental threshold exceedances | FL-ER03 | Detection / Monitoring Function | Material change in distance distributions, threshold behaviour, attack characteristics, or calibration conditions | Illustrative |

These assumptions expose validity conditions associated with the three
paper-supported Engineering Representations.

Their inclusion does **not** add CR.4 to the set of rules reconstructed for
Federated Learning in the associated article.

---

## 3. Relationship to the paper-supported CR.3 decision

The paper-supported contextual decision is:

`FL-CD01`

> The engineering response should provide lightweight early detection of
> adversarial behaviour, including strong and stealthy attacks, while
> remaining compatible with the secure-aggregation constraints of the
> Federated Learning setting.

The assumptions in this file are not used to establish CR.3 as an additional
retrospective result.

Instead, they illustrate validity conditions that could be made explicit in a
prospective application once the contextual priority and its Engineering
Representations had been defined.

The distinction is:

**paper-supported evidence  
→ CR.3  
→ FL-CD01**

versus:

**documented technical conditions  
→ additional illustrative assumptions  
→ validity conditions associated with FL-ER01–FL-ER03**

---

## 4. Assumption types

The worked example uses the following illustrative categories:

- **Operational / Adversarial** — conditions under which lightweight early
  detection remains meaningful
- **Calibration / Statistical** — conditions supporting the benign reference
  used for calibration
- **Detection / Statistical** — conditions supporting calibrated
  threshold-based monitoring

These categories are used only for this worked example.

They do not constitute a mandatory taxonomy or an additional analytical
result.

---

## 5. Illustrative assumption review

In a prospective application, evidence challenging one of these assumptions
could be assessed against its documented validity condition.

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
- Related Engineering Representation:
- Supporting rationale:
- Follow-up required:

Potential evidence could include:

- Material change in adversarial behaviour
- Change in strong or stealthy attack characteristics
- Change in benign client behaviour
- Change in the benign reference distribution
- Calibration instability
- Change in statistical-distance behaviour
- Unexpected threshold behaviour
- Material change in secure-aggregation or operating conditions

This section demonstrates prospective use of the reusable assumption template.

It does not reconstruct a historical assumption-review process performed in
the original Federated Learning study.

---

## 6. Illustrative CR.5 path

In a prospective application, evidence invalidating an assumption could
provide input to **CR.5 — Context Revision Trigger** where the evidence also
challenges an existing contextual decision.

For example:

**material change in adversarial or secure-aggregation conditions  
→ review of the conditions supporting FL-CD01  
→ retain / update / reconsider the contextual priority**

Evidence affecting only the technical validity of an Engineering
Representation could instead require engineering review without necessarily
requiring contextual revision.

### Illustrative revision record

- Revision record ID:
- Assumption ID:
- Triggering evidence:
- Contextual decision potentially affected:
- Engineering Representation potentially affected:
- Responsible role(s):
- Review outcome:
- Rationale:
- Follow-up required:

No CR.5 execution is claimed for the Federated Learning retrospective
application reported in the associated article.

---

## 7. Illustrative evidence sources

| Assumption ID | Evidence / signal | Source | Review condition | Related Engineering Representation |
|---|---|---|---|---|
| FL-A01 | Material change in adversarial behaviour or early-warning detection behaviour | Threat / detection / experimental evidence | Evidence may affect whether lightweight early detection remains appropriate under the documented operational priority | FL-ER01 |
| FL-A02 | Material change in benign behaviour or calibrated reference characteristics | Benign-reference / calibration evidence | Evidence may affect whether the benign reference remains suitable for calibration | FL-ER02 |
| FL-A03 | Material change in statistical-distance distributions or threshold behaviour | Detection / experimental evidence | Evidence may affect whether the calibrated thresholds remain meaningful | FL-ER03 |

These rows demonstrate how evidence could be connected to assumption review in
a prospective application.

They are not historical monitoring or feedback records.

---

## 8. Relationship to FR.1 Engineering Representations

The paper-supported FR.1 reconstruction defines:

### FL-ER01 — Lightweight early-detection representation

Related illustrative assumption:

- `FL-A01`

### FL-ER02 — Benign-reference calibration representation

Related illustrative assumption:

- `FL-A02`

### FL-ER03 — Threshold-based monitoring representation

Related illustrative assumption:

- `FL-A03`

This one-to-one relationship is deliberate.

It demonstrates how a prospective implementation could associate explicit
validity conditions with each Engineering Representation without implying that
CR.4 was reconstructed in the retrospective evaluation.

---

## 9. Relationship to technical instantiation

The original study documents concrete mechanisms corresponding to the three
Engineering Representations:

| Engineering Representation | Documented technical instantiation | Illustrative assumption |
|---|---|---|
| FL-ER01 | Client-level early-warning detection prior to aggregation | FL-A01 |
| FL-ER02 | Benign reference distribution and bootstrap calibration | FL-A02 |
| FL-ER03 | Statistical distance measures and per-feature detection thresholds | FL-A03 |

Experimental threshold exceedances provide additional evidence concerning the
behaviour of the instantiated detection mechanism.

This relationship does not transform the illustrative assumptions into
paper-supported CR.4 outputs.

---

## 10. Pre-aggregation placement and lifecycle anchoring

The original study documents detection prior to aggregation.

That placement is retained as evidence about the **technical instantiation of
FL-ER01**.

It is not represented here as an assumption requiring CR.6, nor does it
establish:

- CR.6 — Lifecycle Anchoring
- FR.5 — Shift-Left Integration
- P1 — Lifecycle Anchoring

A prospective application could explicitly represent lifecycle anchoring if
required, but that would extend beyond the analytical reconstruction reported
for this case.

---

## 11. Repeated operation and continuity

The original technical mechanism operates across Federated Learning rounds.

This characteristic may motivate assumption review in a prospective
application, particularly if the operating or calibration conditions change.

It does not establish retrospective reconstruction of:

- FR.4 — Iterative Feedback Integration
- FR.6 — Continuity Enforcement
- P3 — Continuity and Iterative Feedback

---

## 12. Analytical boundary

For the Federated Learning case, the associated article supports:

### Contextual Refinement
- **CR.3 — Principle Prioritisation**

### Functional Refinement
- **FR.1 — Engineering Representation Derivation**

### Assessment criterion
- **P2 — Coordinated Contextual and Functional Refinement**

This file additionally illustrates:

- **CR.4 — Assumption Documentation**
- A possible prospective relationship with **CR.5 — Context Revision Trigger**

Those additional template functions are **not** claimed as reconstructed rules
in the retrospective analytical evaluation.

---

## 13. Versioning and ownership

- Artefact type: Additional illustrative completion of a CRISP-TAI v0.2.0
  template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked-template representation
- Original project record: No
- Paper-supported CR.4 reconstruction: No
- Paper-supported CR.5 reconstruction: No
- Paper-supported CR.6 reconstruction: No

---

## Notes

This log demonstrates how assumptions can be associated with the
paper-supported Federated Learning Engineering Representations without
extending the claims of the associated article.

Its illustrative relation is:

**FL-ER01 → FL-A01 → early-detection validity condition**

**FL-ER02 → FL-A02 → benign-reference validity condition**

**FL-ER03 → FL-A03 → threshold-validity condition**

The authoritative analytical chain remains:

**documented operational constraints  
→ CR.3  
→ FL-CD01  
→ FR.1  
→ FL-ER01 / FL-ER02 / FL-ER03  
→ documented technical instantiation  
→ experimental evidence  
→ P2**
