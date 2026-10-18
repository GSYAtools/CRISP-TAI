This document is an **illustrative retrospective completion** of the
`engineering-representation.md` template using documentary evidence from the
Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact illustrates **FR.1 — Engineering Representation
Derivation** by showing how reconstructed contextual decisions can be expressed
as **process-independent Engineering Representations** before their subsequent
technical and lifecycle instantiation.

---

## 1. Representation record

- Record group ID: `FL-ER`
- System or component: Federated Learning setting
- Trustworthiness concerns: Early detection, monitoring, operational response,
  evidence interpretation, and continuity
- Trigger for engineering representation: Reconstructed contextual decisions
  require explicit engineering expression before their documented technical
  enactment can be represented
- Responsible engineering role(s): Reconstructed coordination, monitoring,
  security, and operational actors
- Supporting governance role(s): Reconstructed governance actors where
  escalation or contextual reconsideration is required
- Related context record: `FL-CTX-01`
- Related prioritisation record: `FL-PRIO-01`
- Related assumption records: `FL-A01` to `FL-A03`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Originating contextual decisions

| Contextual decision ID | Contextual decision / interpretation | Applicable constraint, priority, responsibility, or assumption | Source |
|---|---|---|---|
| FL-CD01 | The partially observable and adversarial FL environment requires relevant detection and monitoring evidence to be available early enough to support review before aggregation | Secure aggregation, limited observability, adversarial risk, and assumptions `FL-A01` to `FL-A03` | `context-description.md`; `principle-prioritisation.md`; `assumption-log.md` |
| FL-CD02 | Detection evidence requires explicit interpretation before it can justify an engineering or operational response | A detection or anomaly signal is evidence for review rather than an automatic trustworthiness verdict | `context-description.md`; `principle-prioritisation.md`; `responsibility-map.csv` |
| FL-CD03 | Detection, monitoring, and review capabilities must remain available across successive training rounds while their supporting conditions remain valid | Repeated operation, lifecycle anchoring, and assumptions `FL-A02` and `FL-A03` | `context-description.md`; `assumption-log.md` |

These contextual decisions are retrospective reconstructions from the
documented Federated Learning evidence.

---

## 3. Engineering Representation derivation

| Representation ID | Contextual decision ID | Representation type | Engineering Representation | Rationale | Responsible role |
|---|---|---|---|---|---|
| FL-ER01 | FL-CD01 | Detection and monitoring requirement | Security-relevant detection and monitoring evidence shall be available before aggregation where supported by the documented detection mechanism and shall remain available for operational review | Operationalises the contextual requirement for early evidence under limited observability without prescribing the specific detection implementation | Operations and Security Team / Server Coordinator |
| FL-ER02 | FL-CD02 | Operational review and adjustment requirement | Detection or anomaly evidence shall be interpreted against the applicable operating conditions before any resulting engineering adjustment or operational response is represented | Preserves the separation between technical evidence and subsequent engineering or governance decisions | Operations and Security Team |
| FL-ER03 | FL-CD03 | Continuity requirement | Relevant detection, monitoring, and review obligations shall remain active across successive training rounds and shall be reconsidered when their supporting technical or contextual conditions materially change | Operationalises continued monitoring and review without making them one-time controls | Server / Coordinator and Operations and Security Team |

These are **process-independent Engineering Representations**. They do not
prescribe a specific CRISP-DM phase, implementation component, detection
algorithm, mitigation action, or lifecycle artefact.

---

## 4. Representation specification

### FL-ER01 — Early detection and monitoring

- Representation type: Detection and monitoring requirement
- Originating contextual decision: `FL-CD01`
- Applicable constraints:
  - Secure aggregation
  - Limited observability
  - Distributed participation
  - Detection before aggregation
- Relevant assumptions: `FL-A01`, `FL-A02`, `FL-A03`
- Responsible role(s): Operations and Security Team; Server / Coordinator
- Verification condition: Relevant detection evidence is available for review
  before aggregation under the documented operating conditions
- Dependencies: Detection mechanism, training-round orchestration, and
  aggregation configuration
- Revision conditions: Material change in detection behaviour, client
  conditions, aggregation configuration, or monitoring placement

### FL-ER02 — Operational review and adjustment

- Representation type: Operational review and adjustment requirement
- Originating contextual decision: `FL-CD02`
- Applicable constraints:
  - Detection evidence may be uncertain or incomplete
  - Evidence interpretation and operational decision-making remain distinct
- Relevant assumptions: `FL-A01`, `FL-A02`
- Responsible role(s): Operations and Security Team; governance actor where
  escalation is required
- Verification condition: A resulting response can be traced to reviewed
  evidence and an explicit engineering or operational decision
- Dependencies: Monitoring evidence, responsibility allocation, and escalation
  conditions
- Revision conditions: Repeated contradictory evidence, inappropriate response
  conditions, or changed operating assumptions

### FL-ER03 — Monitoring and review continuity

- Representation type: Continuity requirement
- Originating contextual decision: `FL-CD03`
- Applicable constraints:
  - Repeated training rounds
  - Continued validity of monitoring and aggregation conditions
- Relevant assumptions: `FL-A02`, `FL-A03`
- Responsible role(s): Server / Coordinator; Operations and Security Team
- Verification condition: Relevant monitoring and review remain active across
  successive rounds
- Dependencies: Training orchestration, detection mechanism, and monitoring
  capability
- Revision conditions: Material system, protocol, aggregation, or monitoring
  change

---

## 5. Derivation rationale

The reconstructed Engineering Representations are derived from documented
operational constraints rather than from a direct mapping between a
trustworthiness concern and a lifecycle artefact.

The derivation logic is:

**Documented operational evidence and constraints  
→ reconstructed contextual interpretation or decision  
→ required engineering function  
→ process-independent Engineering Representation**

For example:

**Secure aggregation + limited observability + documented pre-aggregation
detection  
→ relevant security evidence must be available early enough for review  
→ an explicit early-detection requirement is required  
→ `FL-ER01`**

Similarly:

**Detection signal + need for interpretation before intervention  
→ evidence must be reviewed before a response is determined  
→ an explicit operational review / adjustment requirement is required  
→ `FL-ER02`**

This remains separate from the technical mechanism through which the
requirement was originally enacted.

---

## 6. Traceability

| Representation ID | Trustworthiness concern | Contextual decision | Responsibility record | Assumption record(s) | Supporting documentary evidence |
|---|---|---|---|---|---|
| FL-ER01 | Early detection and security monitoring | FL-CD01 | FL-R02; FL-R03 | FL-A01; FL-A02; FL-A03 | Distributed FL architecture, secure aggregation, pre-aggregation detection and monitoring |
| FL-ER02 | Evidence interpretation and operational response | FL-CD02 | FL-R03; FL-R04 | FL-A01; FL-A02 | Detection / anomaly evidence, review and response functions |
| FL-ER03 | Operational continuity | FL-CD03 | FL-R02; FL-R03 | FL-A02; FL-A03 | Repeated training rounds and continued monitoring |

The complete refinement-to-instantiation chain is represented in
`traceability-matrix.csv`.

---

## 7. Revision conditions

| Revision condition | Representation affected | Evidence source | Responsible role |
|---|---|---|---|
| Material degradation or change in detection evidence | FL-ER01; FL-ER02 | Detection / monitoring evidence | Operations and Security Team |
| Material change in client participation or adversarial conditions | FL-ER01; FL-ER02 | Training / operational evidence | Operations and Security Team |
| Material change in aggregation or training configuration | FL-ER01; FL-ER03 | Technical / configuration evidence | Server / Coordinator |
| Evidence indicates that the current response conditions are inappropriate | FL-ER02 | Operational review evidence | Operations and Security Team; governance actor where required |
| Monitoring or review cannot be maintained across rounds | FL-ER03 | Operational / continuity evidence | Server / Coordinator; Operations and Security Team |

---

## 8. Subsequent Process Instantiation

The original Federated Learning case documents technical mechanisms through
which the reconstructed Engineering Representations can be retrospectively
mapped.

| Representation ID | Instantiation ID | Documented lifecycle location or mechanism | Documented process-specific enactment | Instantiation rationale |
|---|---|---|---|---|
| FL-ER01 | FL-PI01 | Before aggregation during each relevant training round | Documented pre-aggregation detection and monitoring mechanism | The mechanism provides the early evidence required by FL-ER01 |
| FL-ER02 | FL-PI02 | Operational review following relevant detection evidence | Alert / anomaly interpretation and documented technical response or mitigation mechanisms | These mechanisms provide a process-specific location for evidence review and any resulting response |
| FL-ER03 | FL-PI03 | Successive training rounds and continued operation | Continued detection, monitoring, and review across rounds | The repeated monitoring mechanism enacts the continuity requirement represented by FL-ER03 |

These mappings are **retrospective Process Instantiations**. They do not imply
that `FL-ER01` to `FL-ER03` were explicitly formulated before the original
technical mechanisms were developed.

---

## 9. Operational adjustment boundary

`FL-ER02` is particularly relevant to **FR.3 — Operational Adjustment**.

Where reviewed evidence indicates that an operational change is required, FR.3
does not itself execute a client exclusion, threshold change, configuration
change, or other intervention.

Instead, the refinement relation is:

**Reviewed operational evidence  
→ required adjustment identified  
→ new or revised Engineering Representation specifying the adjustment  
→ subsequent Process Instantiation  
→ technical enactment**

This distinction prevents the detection mechanism from being treated as an
automatic decision mechanism.

---

## 10. Verification and evidence

The retrospective FR.1 reconstruction is supported by documented:

- Distributed Federated Learning architecture
- Secure aggregation
- Adversarial poisoning / backdoor setting
- Pre-aggregation detection
- Monitoring evidence
- Repeated training rounds
- Technical response or mitigation mechanisms
- Continued monitoring across rounds

Verification in this worked example means that each reconstructed Engineering
Representation can be related to:

1. A documented contextual or operational condition
2. A reconstructed contextual decision
3. Supporting documentary evidence
4. A documented technical enactment

It does not mean that FR.1 was prospectively executed in the original study.

---

## 11. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This worked artefact demonstrates the revised methodological boundary:

**Contextual decision  
→ process-independent Engineering Representation  
→ Process Instantiation  
→ documented technical enactment**

The previous repository version represented the relation more directly as
`Interpretation → Derived Artefact`. The v0.2.0 example separates these steps
explicitly.

The example also preserves a second boundary that is particularly important in
this case:

**Detection evidence ≠ operational or governance decision.**

Evidence must first be interpreted before any required engineering adjustment
or subsequent process-specific action is represented.
