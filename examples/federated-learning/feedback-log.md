# Feedback Log — Federated Learning Worked Example

This document is an **additional illustrative completion** of the
`feedback-log.md` template using technical and experimental evidence that can
be related to the Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

The analytical evaluation reported in the associated article reconstructs:

- **CR.3 — Principle Prioritisation**
- **FR.1 — Engineering Representation Derivation**

and provides analytical evidence for:

- **P2 — Coordinated Contextual and Functional Refinement**

It does **not** reconstruct CR.5, FR.3, FR.4, or FR.6 for this case.

Accordingly, this file demonstrates how the reusable feedback template could
represent later evidence and conditional review paths without extending the
analytical claims made in the associated article.

---

## 1. Log information

- Feedback log ID: `FL-FEEDBACK-01`
- System or component: Federated Learning setting
- Related contextual decision:
  - `FL-CD01`
- Related monitoring illustration:
  - `FL-MON-01`
- Related Engineering Representations:
  - `FL-ER01` — Lightweight early-detection representation
  - `FL-ER02` — Benign-reference calibration representation
  - `FL-ER03` — Threshold-based monitoring representation
- Related technical instantiations:
  - `FL-PI01`
  - `FL-PI02`
  - `FL-PI03`
- Paper-supported CR reconstruction:
  - `CR.3`
- Paper-supported FR reconstruction:
  - `FR.1`
- Paper-supported assessment criterion:
  - `P2`
- Artefact status: Additional illustrative worked-template representation
- Repository version: `0.2.0`

---

## 2. Evidence sources

The original Federated Learning study provides technical and experimental
evidence that can be used to demonstrate the feedback template.

Relevant evidence includes:

- Early-warning detection behaviour
- Benign reference observations
- Bootstrap calibration results
- Statistical-distance values
- Per-feature threshold behaviour
- Threshold exceedances
- Strong attack scenarios
- Stealthy attack scenarios
- Independent experimental runs
- Material changes in the technical conditions supporting the detection
  mechanism

These sources are treated here as **evidence that could support review in a
prospective application**.

They are not reconstructed historical CRISP-TAI feedback events.

---

## 3. Illustrative feedback entries

| Feedback ID | Evidence source | Evidence / observation | Related concern | Related Engineering Representation | Related technical instantiation | Status |
|---|---|---|---|---|---|---|
| FL-F01 | Early-warning / adversarial evidence | Detection behaviour under strong or stealthy adversarial conditions differs materially from the conditions supporting the current early-detection capability | Lightweight early detection | FL-ER01 | FL-PI01 | Illustrative conditional review |
| FL-F02 | Benign-reference / calibration evidence | The benign reference or its calibrated characteristics differ materially from the conditions supporting the current calibration | Benign-reference calibration | FL-ER02 | FL-PI02 | Illustrative conditional review |
| FL-F03 | Statistical-distance / threshold evidence | Statistical-distance behaviour or threshold exceedances differ materially from the conditions supporting the current detection criteria | Threshold-based monitoring | FL-ER03 | FL-PI03 | Illustrative conditional review |
| FL-F04 | Technical / architectural evidence | Secure-aggregation or other relevant operating constraints change materially | Context-dependent operational priority | FL-ER01; FL-ER02; FL-ER03 | FL-PI01; FL-PI02; FL-PI03 | Illustrative conditional review |

These entries are **illustrative review conditions**, not historical incidents
reconstructed from the original study.

---

## 4. Illustrative assessment

### FL-F01 — Early-detection evidence

Potentially related records:

- `FL-CD01`
- `FL-A01`
- `FL-ER01`
- `FL-PI01`

Possible prospective assessment:

- Existing early-detection relation remains supported
- Additional evidence is required
- The validity condition represented by FL-A01 requires review
- FL-ER01 requires engineering review
- FL-PI01 requires technical review

---

### FL-F02 — Benign-reference evidence

Potentially related records:

- `FL-A02`
- `FL-ER02`
- `FL-PI02`

Possible prospective assessment:

- Existing benign reference remains suitable
- Additional calibration evidence is required
- FL-A02 requires review
- FL-ER02 requires engineering review
- FL-PI02 requires technical review

---

### FL-F03 — Threshold evidence

Potentially related records:

- `FL-A03`
- `FL-ER03`
- `FL-PI03`

Possible prospective assessment:

- Existing calibrated thresholds remain suitable
- Additional experimental evidence is required
- FL-A03 requires review
- FL-ER03 requires engineering review
- FL-PI03 requires technical review

---

### FL-F04 — Operating-constraint evidence

Potentially related records:

- `FL-CTX-01`
- `FL-PRIO-01`
- `FL-CD01`
- `FL-ER01`
- `FL-ER02`
- `FL-ER03`

Possible prospective assessment:

- Existing contextual priority remains applicable
- The operating constraints have materially changed
- FL-CD01 requires contextual reconsideration
- One or more Engineering Representations require subsequent review

These assessments illustrate how evidence could be connected to existing
records.

They do not constitute retrospective reconstruction of
**FR.4 — Iterative Feedback Integration**.

---

## 5. Relationship to the paper-supported reconstruction

The authoritative Federated Learning reconstruction is:

**documented operational priorities and constraints  
→ CR.3 Principle Prioritisation  
→ FL-CD01  
→ FR.1 Engineering Representation Derivation  
→ FL-ER01 / FL-ER02 / FL-ER03  
→ documented technical instantiation  
→ experimental evidence  
→ P2**

This feedback log sits **outside that reconstructed rule path**.

Its purpose is to demonstrate how later evidence could be connected to those
records in a prospective application.

---

## 6. Illustrative CR.5 path

In a prospective application, evidence challenging the contextual conditions
supporting `FL-CD01` could provide input to
**CR.5 — Context Revision Trigger**.

For example:

**material change in adversarial conditions  
or secure-aggregation constraints  
→ review of FL-CD01  
→ retain / update / reconsider the contextual priority**

Evidence concerning only a calibration or threshold mechanism would not
necessarily require contextual revision.

It could instead require review of the corresponding Engineering
Representation or technical instantiation.

No CR.5 execution is claimed for the retrospective Federated Learning
application reported in the associated article.

---

## 7. Illustrative engineering review

Where evidence indicates that an Engineering Representation may no longer be
adequate, a prospective application could perform subsequent Functional
Refinement.

| Feedback ID | Existing Engineering Representation | Illustrative engineering review |
|---|---|---|
| FL-F01 | FL-ER01 | Review whether the lightweight early-detection capability remains adequate |
| FL-F02 | FL-ER02 | Review whether the benign-reference calibration capability remains adequate |
| FL-F03 | FL-ER03 | Review whether the threshold-based monitoring capability remains adequate |
| FL-F04 | FL-ER01; FL-ER02; FL-ER03 | Review affected Engineering Representations after any revised contextual prioritisation |

This section does not claim retrospective reconstruction of
**FR.3 — Operational Adjustment**.

If an adjustment were required prospectively, it would need to be represented
through the appropriate refinement function before technical enactment.

---

## 8. Illustrative technical-instantiation review

Where an Engineering Representation changes, the corresponding technical
instantiation could require review.

| Feedback ID | Engineering Representation | Existing technical instantiation | Potential prospective review | Traceability record |
|---|---|---|---|---|
| FL-F01 | FL-ER01 | FL-PI01 | Review the client-level early-warning detection mechanism | FL-T01 |
| FL-F02 | FL-ER02 | FL-PI02 | Review the benign reference distribution or bootstrap calibration procedure | FL-T02 |
| FL-F03 | FL-ER03 | FL-PI03 | Review statistical distance measures or calibrated per-feature thresholds | FL-T03 |
| FL-F04 | FL-ER01; FL-ER02; FL-ER03 | FL-PI01; FL-PI02; FL-PI03 | Review affected technical mechanisms after any revised contextual or engineering decision | FL-T01; FL-T02; FL-T03 |

This is an illustrative prospective propagation path.

It is not a reconstructed historical re-instantiation.

---

## 9. Illustrative evidence-to-review trace

| Feedback ID | Evidence | Contextual decision potentially affected | Engineering Representation potentially affected | Contextual review | Engineering review | Technical-instantiation review |
|---|---|---|---|---|---|---|
| FL-F01 | Material change in early-detection behaviour under relevant adversarial conditions | FL-CD01 where the operational priority itself is challenged | FL-ER01 | Conditional | Conditional | FL-PI01 if required |
| FL-F02 | Material change in benign-reference or calibration behaviour | — | FL-ER02 | Not necessarily required | Conditional | FL-PI02 if required |
| FL-F03 | Material change in statistical-distance or threshold behaviour | — | FL-ER03 | Not necessarily required | Conditional | FL-PI03 if required |
| FL-F04 | Material change in secure-aggregation or relevant operating constraints | FL-CD01 | FL-ER01; FL-ER02; FL-ER03 | Conditional | Conditional | Affected FL-PI records if required |

This distinction is deliberate.

Not every technical observation requires contextual revision.

---

## 10. Relationship to experimental evidence

The original study already provides experimental observations such as
threshold exceedances under documented attack conditions.

Within the paper-supported retrospective reconstruction, those observations
serve as **experimental evidence associated with the documented technical
instantiation**.

They are not interpreted as historical CRISP-TAI feedback events.

This distinction is:

**experimental result in the original technical study**

versus:

**feedback event processed through a lifecycle-refinement mechanism**.

The former is documented.

The latter is illustrated here only as a possible prospective use of the
template.

---

## 11. Relationship to repeated operation

Federated Learning operates across repeated training rounds and can produce
repeated detection evidence.

That fact alone does not establish:

- FR.4 — Iterative Feedback Integration
- FR.6 — Continuity Enforcement
- P3 — Continuity and Iterative Feedback

Repeated technical operation and lifecycle-refinement feedback are different
concepts.

The associated article therefore does not use the Federated Learning case as
evidence of P3.

---

## 12. Relationship to assessment criteria

This feedback artefact does not provide additional assessment-criterion
coverage.

The paper-supported Federated Learning criterion remains:

- **P2 — Coordinated Contextual and Functional Refinement**

The case is not used as independent evidence of:

- P1 — Lifecycle Anchoring
- P3 — Continuity and Iterative Feedback

P4 — Cross-Domain Adaptability is assessed through the cross-case comparison.

---

## 13. Scope limitation

This worked artefact does **not** claim:

- Historical CR.5 execution
- Historical FR.3 execution
- Historical FR.4 execution
- Historical FR.6 execution
- A historical CRISP-TAI feedback cycle
- A historical governance escalation
- Automatic mitigation from threshold exceedance
- P1 evidence
- P3 evidence

The original study's experimental observations and technical mechanisms remain
valid evidence about that study.

They are not reclassified as lifecycle-refinement events.

---

## 14. Closure and follow-up

In a prospective application, a feedback item could be closed only after the
relevant review and resulting decisions had been documented.

Relevant information could include:

- Evidence reviewed
- Validity condition affected
- Whether contextual reconsideration was required
- Whether an Engineering Representation was retained or revised
- Whether technical instantiation required review
- Responsible role
- Supporting rationale
- Follow-up required

No historical closure decisions are reconstructed here.

---

## 15. Versioning and ownership

- Artefact type: Additional illustrative completion of a CRISP-TAI v0.2.0
  template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked-template representation
- Original project record: No
- Paper-supported CR.5 reconstruction: No
- Paper-supported FR.3 reconstruction: No
- Paper-supported FR.4 reconstruction: No
- Paper-supported FR.6 reconstruction: No
- Paper-supported P3 evidence: No

---

## Notes

This feedback log demonstrates how technical or experimental evidence could be
connected to a prospective review process without extending the retrospective
claims of the associated article.

Its illustrative relation is:

**paper-supported CR.3 / FR.1 records  
→ later technical or experimental evidence  
→ potential contextual or engineering review  
→ potential technical re-instantiation**

The authoritative analytical chain remains:

**CR.3  
→ FL-CD01  
→ FR.1  
→ FL-ER01 / FL-ER02 / FL-ER03  
→ documented technical instantiation  
→ experimental evidence  
→ P2**
