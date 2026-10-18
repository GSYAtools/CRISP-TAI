# Feedback Log — Federated Learning Worked Example

This document is an **illustrative retrospective completion** of the
`feedback-log.md` template using documentary evidence from the Federated
Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact primarily illustrates:

- **FR.4 — Iterative Feedback Integration**
- **CR.5 — Context Revision Trigger**, where operational evidence challenges
  an existing contextual interpretation or assumption
- **FR.3 — Operational Adjustment**, where reviewed evidence requires a new or
  revised Engineering Representation specifying an operational response

---

## 1. Log information

- Feedback log ID: `FL-FEEDBACK-01`
- System or component: Federated Learning setting
- Related context record: `FL-CTX-01`
- Related monitoring plan: `FL-MON-01`
- Related Engineering Representations:
  - `FL-ER01`
  - `FL-ER02`
  - `FL-ER03`
- Responsible roles: Operations and Security Team; Server / Coordinator;
  governance actor where escalation is required
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Evidence sources

Relevant feedback may originate from:

- Pre-aggregation detection evidence
- Anomaly or alert signals
- Repeated or contradictory detection evidence
- Changes in observed training behaviour
- Changes in client participation or operating conditions
- Changes in aggregation or training configuration
- Operational review outcomes
- Evidence concerning continued monitoring across training rounds

These sources provide **evidence for review**. They do not automatically
determine an operational response or governance decision.

---

## 3. Feedback entries

The entries below illustrate how evidence documented in the Federated Learning
case can be represented using the current feedback structure.

| Feedback ID | Evidence source | Evidence / observation | Trustworthiness concern | Trigger / collection condition | Related monitoring item | Responsible role | Status |
|---|---|---|---|---|---|---|---|
| FL-F01 | Pre-aggregation detection / monitoring | Detection evidence indicates potentially anomalous or adversarial behaviour requiring review | Early detection and security monitoring | Relevant detection evidence observed before aggregation | FL-M01 | Operations and Security Team | Under review |
| FL-F02 | Detection / monitoring review | Repeated, changed, or contradictory detection evidence may challenge the current interpretation of the signal | Evidence interpretation | Material change or repeated evidence affecting the current interpretation | FL-M02 | Operations and Security Team | Under review |
| FL-F03 | Technical / configuration evidence | A material change in aggregation, orchestration, or training configuration may affect the existing monitoring placement or continuity conditions | Lifecycle anchoring and continuity | Relevant system or configuration change | FL-M04 | Server / Coordinator | Under review |
| FL-F04 | Continued operation | Monitoring or review is unavailable or no longer consistent across successive training rounds | Operational continuity | Evidence of discontinuity during repeated operation | FL-M03 | Server / Coordinator; Operations and Security Team | Under review |

These entries are retrospective representations of evidence types supported by
the documented case. They are not claimed to be verbatim historical feedback
records.

---

## 4. Assessment against existing refinement records

### FL-F01 — Potentially adversarial behaviour

- Existing contextual decision potentially affected: `FL-CD01`; `FL-CD02`
- Related assumptions: `FL-A01`; `FL-A02`
- Existing Engineering Representations:
  - `FL-ER01`
  - `FL-ER02`
- Existing Process Instantiations:
  - `FL-PI01`
  - `FL-PI02`
- Responsible reviewer: Operations and Security Team
- Possible assessment:
  - Evidence does not justify further response
  - Additional review is required
  - An engineering adjustment may be required
  - Evidence requires governance escalation

The detection evidence does not itself determine which assessment is selected.

### FL-F02 — Changed or repeated detection evidence

- Existing contextual decision potentially affected: `FL-CD02`
- Related assumption: `FL-A02`
- Existing Engineering Representation: `FL-ER02`
- Responsible reviewer: Operations and Security Team
- Possible assessment:
  - Existing interpretation remains adequate
  - Detection evidence requires further review
  - `FL-A02` may no longer remain valid
  - Existing response conditions require engineering reconsideration

### FL-F03 — Technical or configuration change

- Existing contextual decisions potentially affected:
  - `FL-CD01`
  - `FL-CD03`
- Related assumption: `FL-A03`
- Existing Engineering Representations:
  - `FL-ER01`
  - `FL-ER03`
- Existing Process Instantiations:
  - `FL-PI01`
  - `FL-PI03`
- Responsible reviewer: Server / Coordinator with relevant operational actors
- Possible assessment:
  - Existing anchoring remains valid
  - Pre-aggregation placement requires review
  - Monitoring continuity requires review
  - Contextual or engineering re-refinement is required

### FL-F04 — Monitoring discontinuity

- Existing contextual decision potentially affected: `FL-CD03`
- Related assumptions:
  - `FL-A02`
  - `FL-A03`
- Existing Engineering Representation: `FL-ER03`
- Existing Process Instantiation: `FL-PI03`
- Responsible reviewers: Server / Coordinator; Operations and Security Team
- Possible assessment:
  - Continuity remains adequate
  - Monitoring requirement is temporarily unmet
  - Engineering or process-specific revision is required

These assessments illustrate **FR.4 — Iterative Feedback Integration** by
relating operational evidence to existing contextual and engineering records
before a revision or response is determined.

---

## 5. Context revision decision

Where evidence challenges an assumption or contextual interpretation,
**CR.5 — Context Revision Trigger** determines whether the affected contextual
element should be retained, updated, or reconsidered.

| Feedback ID | Contextual element potentially affected | CR.5 invoked when | Possible revision decision | Related assumption |
|---|---|---|---|---|
| FL-F01 | FL-CD01 / FL-CD02 | Evidence challenges the operating assumptions under which detection or interpretation remains meaningful | Retain / Update / Reconsider | FL-A01; FL-A02 |
| FL-F02 | FL-CD02 | Detection behaviour materially challenges the current interpretation of evidence | Retain / Update / Reconsider | FL-A02 |
| FL-F03 | FL-CD01 / FL-CD03 | Technical change invalidates an existing operational or anchoring condition | Retain / Update / Reconsider | FL-A03 |
| FL-F04 | FL-CD03 | Monitoring discontinuity challenges the contextual expectation of continued observation | Retain / Update / Reconsider | FL-A02; FL-A03 |

CR.5 is **conditional**. The existence of an alert or technical change does not
by itself demonstrate that contextual revision occurred.

---

## 6. Engineering update decision

Where reviewed evidence requires an engineering change, the response should be
represented through subsequent Functional Refinement.

| Feedback ID | Existing Engineering Representation | Potential engineering response | Applicable FR function | Responsible role |
|---|---|---|---|---|
| FL-F01 | FL-ER01 / FL-ER02 | Retain the existing requirements or derive a revised response requirement where reviewed evidence justifies adjustment | FR.3; FR.4 | Operations and Security Team |
| FL-F02 | FL-ER02 | Revise evidence-interpretation or operational-response requirements where current conditions are no longer adequate | FR.3; FR.4 | Operations and Security Team |
| FL-F03 | FL-ER01 / FL-ER03 | Revise detection placement or continuity requirements where the technical configuration has materially changed | FR.4; FR.6; subsequent FR as required | Server / Coordinator; Operations and Security Team |
| FL-F04 | FL-ER03 | Revise continuity requirements or their process-specific enactment | FR.4; FR.6 | Server / Coordinator; Operations and Security Team |

Where **FR.3 — Operational Adjustment** applies, it produces or revises the
Engineering Representation specifying the required adjustment.

It does **not** itself perform a client exclusion, threshold update,
configuration change, or other intervention.

---

## 7. Process-specific propagation

Where an Engineering Representation changes, its existing Process
Instantiation may require corresponding review.

| Feedback ID | Engineering Representation | Existing instantiation | Potential propagation | Traceability record |
|---|---|---|---|---|
| FL-F01 | FL-ER01 / FL-ER02 | FL-PI01 / FL-PI02 | Review the pre-aggregation monitoring or operational-response enactment where required | FL-T01 / FL-T02 |
| FL-F02 | FL-ER02 | FL-PI02 | Review the evidence-review or response mechanism where required | FL-T02 |
| FL-F03 | FL-ER01 / FL-ER03 | FL-PI01 / FL-PI03 | Reconsider monitoring placement or continued monitoring across rounds | FL-T01 / FL-T03 |
| FL-F04 | FL-ER03 | FL-PI03 | Restore, revise, or re-instantiate the affected continuity mechanism where required | FL-T03 |

This propagation belongs to subsequent **Process Instantiation**, not to FR.4
itself.

---

## 8. Evidence-to-decision trace

| Feedback ID | Evidence | Affected contextual element | Affected Engineering Representation | CR.5 decision | Engineering update | Instantiation update |
|---|---|---|---|---|---|---|
| FL-F01 | Potentially adversarial detection evidence | FL-CD01 / FL-CD02 | FL-ER01 / FL-ER02 | Conditional on assessment | Conditional on reviewed evidence | FL-PI01 / FL-PI02 if required |
| FL-F02 | Repeated or changed detection evidence | FL-CD02 | FL-ER02 | Conditional on impact on FL-A02 | Conditional on assessment | FL-PI02 if required |
| FL-F03 | Aggregation / training configuration change | FL-CD01 / FL-CD03 | FL-ER01 / FL-ER03 | Conditional on invalidated anchoring or operating condition | Conditional on assessment | FL-PI01 / FL-PI03 if required |
| FL-F04 | Monitoring discontinuity | FL-CD03 | FL-ER03 | Conditional on contextual impact | Conditional on assessment | FL-PI03 if required |

The repeated use of `Conditional` is deliberate. The documentary evidence
supports the existence of detection, monitoring, review, and technical
response mechanisms, but it does not justify reconstructing a specific
historical decision for every possible evidence condition.

---

## 9. Relationship to documented mitigation mechanisms

The original Federated Learning material includes technical response or
mitigation mechanisms.

Within this worked example, those mechanisms are treated as **documented
process-specific enactments**, not as direct outputs of detection evidence.

The retrospective relation is therefore:

**Detection evidence  
→ operational review  
→ required adjustment identified, where justified  
→ Engineering Representation through FR.3  
→ Process Instantiation  
→ documented technical response or mitigation**

This replaces the direct relationship used in the earlier repository version:

**Anomalous behaviour → client excluded**

and similarly avoids treating repeated alerts as automatically implying a
threshold change.

---

## 10. Closure and follow-up

For a prospective application, a feedback item should be closed only when the
required assessment and resulting decisions have been documented.

Relevant closure information would include:

- Whether contextual revision was required
- Whether an Engineering Representation was retained or revised
- Whether Process Instantiation required update
- Whether continued monitoring remains necessary
- Responsible role
- Supporting evidence

This retrospective worked example does not invent closure decisions where the
original documentary evidence does not provide them.

---

## 11. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This worked feedback log illustrates:

**Operational evidence  
→ FR.4 assessment  
→ CR.5 where contextual reconsideration is required  
→ subsequent Functional Refinement  
→ revised Engineering Representation  
→ updated Process Instantiation where required**

Where an operational adjustment is required:

**Reviewed evidence  
→ FR.3  
→ new or revised Engineering Representation  
→ Process Instantiation  
→ technical enactment**

The example deliberately preserves the boundary between **detection evidence**
and **decision or action**.
