# Assumption Log — Federated Learning Worked Example

This document is an **illustrative retrospective completion** of the
`assumption-log.md` template using documentary evidence from the Federated
Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact primarily illustrates:

- **CR.4 — Assumption Documentation**
- **CR.5 — Context Revision Trigger**, where operational or technical evidence
  challenges an existing contextual assumption or interpretation

---

## 1. Log information

- System or component: Federated Learning setting
- Log ID: `FL-ASSUMPTIONS-01`
- Related context record: `FL-CTX-01`
- Related prioritisation record: `FL-PRIO-01`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Assumption register

The assumptions below are retrospective representations of operating
conditions supported by the documented Federated Learning case.

| Assumption ID | Assumption | Type | Validity condition | Rationale / evidence | Affected contextual decision or interpretation | Responsible role | Revision trigger | Status |
|---|---|---|---|---|---|---|---|---|
| FL-A01 | The operating and participation conditions remain sufficiently compatible with those under which the documented detection evidence is meaningful | Operational / Security | Client participation, training behaviour, adversarial conditions, and other relevant operating characteristics do not change materially beyond the conditions underlying the detection approach | Documented adversarial FL setting and operating conditions | Detection and monitoring evidence remains interpretable within the reconstructed operational context | Operations and Security Team | Material change in client population, participation behaviour, adversarial conditions, or repeated evidence inconsistent with the existing assumption | Active |
| FL-A02 | Detection signals remain sufficiently informative to support operational review | Operational / Detection | The relationship between the observed detection signals and the relevant system behaviour remains materially valid under current operating conditions | Documented early-detection and monitoring mechanism | Detection evidence can continue to support review before aggregation without being treated as an automatic verdict | Operations and Security Team | Material drift, degradation, instability, or repeated contradictory detection evidence | Active |
| FL-A03 | The Federated Learning and aggregation configuration remains compatible with the reconstructed early-monitoring approach | Technical / Operational | No material protocol, aggregation, orchestration, or architectural change invalidates the conditions under which detection and monitoring occur | Documented FL architecture, secure aggregation, and pre-aggregation detection setting | Detection and monitoring requirements can remain anchored before aggregation and maintained across training rounds | Server / Coordinator | Material change in aggregation protocol, training configuration, system architecture, or monitoring placement | Active |

The earlier repository version expressed these assumptions more directly as
"majority of clients are benign", "detection signals remain calibrated", and
"aggregation protocol remains secure". The v0.2.0 reconstruction instead
records the **conditions whose continued validity is required by the
trustworthiness-related decisions represented in this example**, avoiding
stronger claims than the available documentary evidence supports.

---

## 3. Assumption types

The worked example uses the following contextual categories:

- **Operational / Security** — participation conditions, adversarial behaviour,
  and relevant operating characteristics
- **Operational / Detection** — conditions under which detection evidence
  remains meaningful for review
- **Technical / Operational** — aggregation, orchestration, architecture, and
  monitoring-placement conditions

These categories describe the assumptions reconstructed from this case and do
not constitute a mandatory taxonomy.

---

## 4. Assumption review

When operational or technical evidence challenges an assumption, it should be
reviewed against its documented validity condition.

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
- Affected contextual decision or interpretation:
- Related Engineering Representation(s):
- Supporting rationale:

Relevant evidence may include:

- Changes in client participation or population
- Material changes in observed system behaviour
- Detection-signal drift or degradation
- Repeated or contradictory anomaly evidence
- Changes in aggregation or training configuration
- Changes in the technical conditions under which monitoring is performed

A review does not automatically imply contextual revision.

---

## 5. Context revision decision

Where evidence challenges an assumption or another contextual element,
**CR.5 — Context Revision Trigger** determines whether the existing contextual
interpretation should be:

- Retained
- Updated
- Reconsidered through a new refinement cycle

### Retrospective decision record

- Revision record ID:
- Assumption ID:
- Triggering evidence:
- Affected contextual interpretation:
- Responsible role(s):
- Revision decision:
- Decision rationale:
- Updated assumption or validity condition, where applicable:
- Updated contextual interpretation, where applicable:
- Downstream Engineering Representation(s) potentially affected:
- Related feedback record:

This worked example does not claim that a specific CR.5 record was produced
during the original Federated Learning study. It illustrates how documented
operational evidence can be represented using the current CRISP-TAI
refinement structure.

---

## 6. Monitoring and evidence sources

| Assumption ID | Evidence / signal | Source | Review condition | Responsible role | Related Engineering Representation |
|---|---|---|---|---|---|
| FL-A01 | Material change in client participation, behaviour, or adversarial conditions | Training and operational evidence | Change potentially affects the conditions under which detection evidence is interpreted | Operations and Security Team | FL-ER01; FL-ER02 |
| FL-A02 | Drift, instability, degradation, or contradictory detection evidence | Detection and monitoring mechanism | Evidence suggests that current signals may no longer support the existing interpretation | Operations and Security Team | FL-ER01; FL-ER02 |
| FL-A03 | Change in aggregation, orchestration, training configuration, or monitoring placement | Technical configuration / system evidence | Change potentially invalidates pre-aggregation anchoring or continued monitoring | Server / Coordinator | FL-ER01; FL-ER03 |

The related Engineering Representations are completed in
`engineering-representation.md`.

---

## 7. Relationship to lifecycle anchoring

`FL-A03` is particularly relevant to **CR.6 — Lifecycle Anchoring**.

The reconstructed early-monitoring requirement depends on detection evidence
being available before aggregation and on monitoring remaining available
across successive training rounds.

A material change in the aggregation or training configuration may therefore
invalidate not only a technical assumption but also the anchoring conditions
associated with subsequent Process Instantiation.

The relationship is:

**Technical or operational condition  
→ validity of contextual assumption  
→ lifecycle anchoring condition  
→ affected Engineering Representation  
→ review of Process Instantiation where required**

---

## 8. Revision history

| Version | Date | Assumption / record affected | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|---|
| 0.2.0 | Retrospective reconstruction | Initial worked example | Alignment with revised Lifecycle Refinement Framework | Assumptions represented using explicit validity conditions and CR.5 revision structure | Repository authors |

---

## Notes

This log is a **retrospectively completed contextual-refinement artefact**.

The assumptions above are not presented as verbatim assumptions originally
recorded during the Federated Learning study. They are structured
reconstructions of conditions supported by the documentary evidence used in
the retrospective analysis.

Their purpose is to demonstrate the CR.4 relationship:

**Assumption  
→ validity condition  
→ affected contextual decision  
→ revision trigger**

and, where relevant, the CR.5 relationship:

**Triggering evidence  
→ contextual review  
→ retain / update / reconsider  
→ subsequent Functional Refinement where required**

The example also illustrates that an invalidated technical or operational
assumption may require reconsideration of a previously established lifecycle
anchoring condition.
