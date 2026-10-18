# Principle Prioritisation — Federated Learning Worked Example

This document is an **illustrative retrospective completion** of the
`principle-prioritisation.md` template using documentary evidence from the
Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact illustrates **CR.3 — Principle Prioritisation** where the
documented adversarial and operational context supports an explicit
context-dependent priority, constraint, or trade-off.

---

## 1. Prioritisation record

- Record ID: `FL-PRIO-01`
- System or component: Federated Learning setting
- Trigger for prioritisation: Adversarial risk must be addressed under secure
  aggregation, limited observability, and repeated training rounds
- Decision context: Early detection and operational monitoring of potentially
  adversarial behaviour
- Applicable trustworthiness concerns:
  - Robustness and security
  - Early detection
  - Interpretability of detection evidence
  - Operational continuity
- Responsible role(s): Reconstructed operational, security, coordination, and
  governance actors
- Accountable role: Relevant governance authority where escalation requires a
  governance decision
- Related context record: `FL-CTX-01`
- Related responsibility records: `FL-R01` to `FL-R04`
- Artefact status: Retrospective worked-example representation

---

## 2. Applicable trustworthiness principles or concerns

| Principle / concern | Why applicable | Contextual constraint or expectation | Relevant actor(s) |
|---|---|---|---|
| Robustness and security | The documented scenario considers poisoning and backdoor attacks during Federated Learning | Relevant adversarial behaviour should be detectable early enough to support review before aggregation where the documented mechanism permits it | Operations and Security Team; Server / Coordinator |
| Early detection | The technical contribution specifically addresses detection before aggregation | Detection evidence must become available at a point where it can still inform subsequent review or response | Operations and Security Team; Server / Coordinator |
| Interpretability of detection evidence | Detection signals require interpretation before they can support an engineering or governance decision | An anomaly or alert must not be treated as an automatic trustworthiness verdict | Operations and Security Team; Governance Board where escalation is required |
| Operational continuity | Federated Learning proceeds through repeated training rounds | Monitoring and review capabilities must remain available across successive rounds | Server / Coordinator; Operations and Security Team |

The presence of these concerns does not imply a universal ordering among
trustworthiness principles.

---

## 3. Tensions and dependencies

The documented case supports several operational dependencies relevant to
context-specific prioritisation.

| Tension / dependency | Concerns involved | Contextual consideration | Retrospective interpretation |
|---|---|---|---|
| Early detection vs. erroneous intervention | Early detection; robustness and security; evidence interpretation | Acting on insufficiently interpreted detection evidence may result in unnecessary intervention | Early detection should provide evidence for review rather than automatically determine an operational action |
| Security response vs. continued training | Robustness and security; operational continuity | A response to suspected adversarial behaviour may affect participation or training progression | Any operational adjustment should be justified against the available evidence and represented explicitly before enactment |
| Limited observability vs. evidence interpretation | Security; interpretability of detection evidence | Secure aggregation constrains direct inspection of individual client behaviour | Monitoring and decision-making must operate using the evidence available under the documented observability constraints |
| Early placement vs. continued monitoring | Early detection; operational continuity | Detection is relevant before aggregation but the system evolves across repeated rounds | Early detection must be combined with continued monitoring rather than treated as a one-time control |

---

## 4. Prioritisation or trade-off decision

The documentary evidence supports a contextual priority concerning early
adversarial detection, but it does not justify reconstructing a complete
`High / Medium / Low` ranking across all trustworthiness concerns.

The retrospective contextual decision is therefore represented as:

> Under the documented adversarial and limited-observability conditions,
> detection and monitoring of potentially malicious behaviour should occur
> early enough to provide evidence for review before aggregation, while
> preserving explicit interpretation of that evidence and continued
> monitoring across subsequent training rounds.

This decision prioritises the **timely availability of security-relevant
evidence** without treating detection signals as automatic decisions or
assuming that security concerns eliminate other operational constraints.

---

## 5. Decision rationale

The reconstructed decision is supported by:

- The documented poisoning and backdoor threat setting
- Secure aggregation and limited observability
- Detection before aggregation
- Repeated training rounds
- The need to interpret anomaly or detection evidence
- Continued monitoring during operation

### Alternatives not reconstructed

The available evidence does not justify:

- Assigning fixed `High / Medium / Low` levels to all trustworthiness concerns
- Inferring a universal priority of security over every other system objective
- Treating every detection signal as sufficient evidence for mitigation
- Inferring a fixed acceptable false-positive rate or intervention threshold

These decisions would require additional contextual or empirical evidence.

---

## 6. Resulting contextual decision

- Affected concerns: Robustness and security, early detection,
  interpretability of evidence, and operational continuity
- Adopted contextual decision: Security-relevant evidence should be available
  before aggregation where supported by the documented mechanism and should
  remain subject to explicit interpretation before subsequent action
- Continuity condition: Relevant monitoring should persist across successive
  training rounds
- Applicable constraints: Secure aggregation, limited observability,
  distributed participation, and repeated operation
- Responsible actors: Reconstructed coordination, monitoring, security, and
  governance actors
- Related assumptions: `FL-A01`, `FL-A02`, `FL-A03`
- Related context record: `FL-CTX-01`

The engineering response required by this contextual decision is represented
separately through `engineering-representation.md`.

---

## 7. Review and revision conditions

| Revision condition | Affected decision | Evidence source | Responsible role |
|---|---|---|---|
| Material change in the adversarial or operating conditions | Early-detection and monitoring priority | Operational / threat evidence | Operations and Security Team |
| Material change in detection behaviour or evidence quality | Interpretation and use of detection evidence | Detection / monitoring evidence | Operations and Security Team |
| Material change in aggregation or training configuration | Early placement and monitoring conditions | Technical / configuration evidence | Server / Coordinator |
| Repeated evidence suggesting that the current response conditions are inappropriate | Relationship between detection evidence and operational response | Review / operational evidence | Operations and Security Team; governance actor where required |

Where such evidence challenges the contextual decision or its assumptions,
**CR.5 — Context Revision Trigger** determines whether the decision should be
retained, updated, or reconsidered.

---

## 8. Verification and evidence

Supporting documentary evidence includes:

- Distributed Federated Learning architecture
- Secure-aggregation conditions
- Adversarial backdoor / poisoning setting
- Detection before aggregation
- Monitoring across repeated training rounds
- Detection or anomaly evidence requiring interpretation

Related worked artefacts:

- `context-description.md`
- `responsibility-map.csv`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`
- `monitoring-plan.md`
- `feedback-log.md`

---

## 9. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This worked artefact distinguishes **documented contextual priority** from an
invented ordinal ranking.

The earlier repository version represented Robustness and Security as `High`
and Transparency and Fairness as `Medium`. The v0.2.0 example does not retain
those levels unless the underlying documentary evidence establishes that such
a formal ranking was actually made.

The resulting contextual decision remains process-independent. Its engineering
operationalisation is represented through Functional Refinement before
subsequent Process Instantiation.
