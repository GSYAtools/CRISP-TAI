# Monitoring Plan — Federated Learning Worked Example

This document is an **illustrative retrospective completion** of the
`monitoring-plan.md` template using documentary evidence from the Federated
Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact primarily illustrates:

- **FR.6 — Continuity Enforcement**
- **FR.4 — Iterative Feedback Integration**

It also shows how operational evidence may provide input to **FR.3 —
Operational Adjustment** or **CR.5 — Context Revision Trigger** where the
documented conditions for those rules are met.

---

## 1. Monitoring record

- Monitoring plan ID: `FL-MON-01`
- System or component: Federated Learning setting
- Operational environment: Distributed and partially observable training
  environment with repeated training rounds and adversarial risk
- Responsible monitoring role(s): Operations and Security Team; Server /
  Coordinator
- Accountable role: Relevant governance authority where escalation is required
- Related context record: `FL-CTX-01`
- Related Engineering Representations:
  - `FL-ER01`
  - `FL-ER03`
- Related Process Instantiations:
  - `FL-PI01`
  - `FL-PI03`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Monitoring scope

The Federated Learning case documents detection and monitoring before
aggregation and continued observation across successive training rounds.

These mechanisms provide evidence for retrospectively representing the
following monitoring scope:

| Monitoring item ID | Trustworthiness concern | Element monitored | Element type | Related representation / contextual record | Reason for monitoring |
|---|---|---|---|---|---|
| FL-M01 | Early detection and security monitoring | Detection evidence relevant to potentially adversarial behaviour before aggregation | Engineering Representation / operational evidence | FL-ER01; FL-CD01 | Preserve availability of security-relevant evidence early enough to support review |
| FL-M02 | Evidence interpretation | Continued usefulness of detection evidence for operational review | Contextual / engineering condition | FL-ER02; FL-A02 | Identify whether detection evidence remains sufficiently informative under current operating conditions |
| FL-M03 | Operational continuity | Continued availability of detection, monitoring, and review across training rounds | Continuity requirement | FL-ER03; FL-CD03 | Ensure that monitoring is not treated as a one-time control |
| FL-M04 | Lifecycle anchoring | Continued compatibility of monitoring placement with the aggregation and training configuration | Contextual / technical condition | FL-ER01; FL-ER03; FL-A03 | Detect changes that may invalidate the reconstructed pre-aggregation anchoring condition |

---

## 3. Monitoring evidence and signals

The original case documents technical detection and monitoring signals. This
worked example represents them as **evidence for review**, rather than as
automatic trustworthiness verdicts.

| Monitoring item ID | Evidence / signal | Source | Collection or review condition | Responsible role | Evidence record |
|---|---|---|---|---|---|
| FL-M01 | Detection or anomaly evidence associated with potentially adversarial client behaviour | Documented detection mechanism | Before aggregation during relevant training rounds | Operations and Security Team | FL-EV01 |
| FL-M02 | Material change, drift, instability, or contradictory behaviour in detection evidence | Detection / monitoring mechanism | When evidence suggests that the current interpretation may no longer remain valid | Operations and Security Team | FL-EV02 |
| FL-M03 | Evidence that monitoring or review is unavailable or inconsistent across successive rounds | Training and monitoring process | During continued operation across training rounds | Server / Coordinator; Operations and Security Team | FL-EV03 |
| FL-M04 | Material change in aggregation, orchestration, or training configuration | Technical configuration / system evidence | When a change may affect pre-aggregation monitoring or repeated-round continuity | Server / Coordinator | FL-EV04 |

Where the original technical study uses specific statistical signals, those
signals remain part of the underlying detection method. CRISP-TAI treats their
outputs as evidence to be interpreted within the refinement process.

---

## 4. Continuity requirements

This section retrospectively represents the continuity obligations associated
with `FL-ER03`.

| Element ID | Element requiring continuity | Owner | Monitoring obligation | Review obligation | Update condition | Continuity evidence |
|---|---|---|---|---|---|---|
| FL-CONT01 | Pre-aggregation detection capability | Operations and Security Team / Server Coordinator | Preserve availability of relevant detection evidence before aggregation | Review when detection conditions or technical placement materially change | Detection, aggregation, or architecture change | Detection / monitoring records |
| FL-CONT02 | Operational evidence review | Operations and Security Team | Preserve a review step between detection evidence and any resulting response | Review when evidence quality or response conditions materially change | Detection drift, contradictory evidence, or changed response conditions | Review records |
| FL-CONT03 | Repeated-round monitoring | Server / Coordinator; Operations and Security Team | Maintain relevant monitoring across successive training rounds | Review continuity after material system or protocol changes | Training, aggregation, or monitoring change | Repeated-round monitoring records |
| FL-CONT04 | Escalation capability | Operations and Security Team / governance actor | Preserve an escalation path for evidence requiring governance or contextual reconsideration | Review when responsibilities or governance conditions change | Organisational or governance change | Escalation / decision records |

These requirements illustrate **FR.6 — Continuity Enforcement**.

---

## 5. Evidence review

Relevant monitoring evidence should be assessed against the existing
contextual interpretations, assumptions, and Engineering Representations.

### Illustrative review structure

- Evidence record ID:
- Monitoring item ID:
- Evidence observed:
- Existing contextual decision affected:
- Existing assumption affected:
- Existing Engineering Representation affected:
- Responsible reviewer(s):
- Assessment:
  - No relevant deviation
  - Engineering review required
  - Potential contextual change
  - Assumption potentially invalidated
  - Detection or monitoring requirement potentially unmet
  - Operational response may be required
- Rationale:
- Follow-up required:

A detection or anomaly signal does **not** by itself determine the assessment
outcome.

---

## 6. Feedback integration

Where operational evidence is relevant to an existing contextual interpretation
or Engineering Representation, **FR.4 — Iterative Feedback Integration** can be
represented as:

**Detection / operational evidence  
→ assessment against existing assumptions and Engineering Representations  
→ contextual reconsideration where required  
→ engineering re-refinement where required**

For this worked example:

- Related feedback record: `feedback-log.md`
- Potentially affected contextual decisions:
  - `FL-CD01`
  - `FL-CD02`
  - `FL-CD03`
- Potentially affected assumptions:
  - `FL-A01`
  - `FL-A02`
  - `FL-A03`
- Potentially affected Engineering Representations:
  - `FL-ER01`
  - `FL-ER02`
  - `FL-ER03`

Where evidence challenges an assumption or contextual interpretation,
**CR.5 — Context Revision Trigger** determines whether the affected element
should be retained, updated, or reconsidered.

---

## 7. Operational adjustment

Where reviewed evidence indicates that an operational adjustment is required,
the required response should first be represented as a new or revised
Engineering Representation.

### Illustrative FR.3 record

- Triggering evidence:
- Existing Engineering Representation affected:
- Required operational adjustment:
- New or revised Engineering Representation:
- Responsible role:
- Supporting rationale:
- Related traceability record:

This illustrates **FR.3 — Operational Adjustment**.

The relationship is:

**Detection evidence  
→ review  
→ required adjustment identified  
→ Engineering Representation  
→ Process Instantiation  
→ technical enactment**

FR.3 therefore does not itself exclude a client, modify a threshold, change a
configuration, or perform another mitigation action.

---

## 8. Escalation and decision process

The reconstructed responsibility structure distinguishes technical evidence,
operational review, and governance decision-making.

- Initial evidence source: Detection / monitoring mechanism
- Operational reviewer: Operations and Security Team
- Technical coordination role: Server / Coordinator
- Governance escalation: Governance Board where the evidence affects a
  governance decision, contextual constraint, or accepted operating condition
- Required documentation:
  - Evidence observed
  - Applicable assumptions
  - Engineering Representation affected
  - Review outcome
  - Required adjustment, where applicable
  - Subsequent instantiation or contextual revision, where required

Related worked artefacts:

- `responsibility-map.csv`
- `feedback-log.md`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`

---

## 9. Process-specific monitoring instantiation

The reconstructed monitoring requirements can be retrospectively mapped to the
documented Federated Learning mechanisms.

### Early detection

- Engineering Representation ID: `FL-ER01`
- Instantiation ID: `FL-PI01`
- Framework instantiation: CRISP-TAI
- Target process: CRISP-DM
- Target lifecycle location: Continuous Deployment & Monitoring
- Process-specific location: Before aggregation during relevant training rounds
- Documented enactment: Pre-aggregation detection and monitoring mechanism
- Traceability record: `FL-T01`

### Continued monitoring

- Engineering Representation ID: `FL-ER03`
- Instantiation ID: `FL-PI03`
- Framework instantiation: CRISP-TAI
- Target process: CRISP-DM
- Target lifecycle location: Continuous Deployment & Monitoring
- Process-specific location: Successive training rounds and continued operation
- Documented enactment: Continued detection, monitoring, and review across
  rounds
- Traceability record: `FL-T03`

These are **retrospective Process Instantiations**. They do not imply that
`FL-ER01` or `FL-ER03` were explicitly formulated before the original
technical mechanisms were developed.

---

## 10. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This monitoring plan represents documented Federated Learning evidence using
the current CRISP-TAI monitoring and continuity structure.

Its purpose is to illustrate:

**Engineering Representation  
→ Process Instantiation  
→ detection / operational evidence  
→ FR.4 assessment  
→ CR.5 where contextual reconsideration is required  
→ subsequent Functional Refinement and re-instantiation where necessary**

The worked example does not define or evaluate the underlying detection
algorithm and does not prescribe universal thresholds, metrics, or response
rules.

Most importantly, it preserves the distinction:

**Detection signal = evidence for review, not an automatic decision.**
