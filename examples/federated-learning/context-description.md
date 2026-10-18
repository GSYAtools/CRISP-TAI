# Context Description — Federated Learning Worked Example

This document is an **illustrative retrospective completion** of the
`context-description.md` template using documentary evidence from the
Federated Learning case.

It is not an original project record and does not imply prospective
application of CRISP-TAI.

This worked artefact primarily illustrates **CR.1 — Context Interpretation**
and **CR.4 — Assumption Documentation**, together with contextual information
supporting **CR.6 — Lifecycle Anchoring** in the retrospective reconstruction
described in `/logs/federated-learning-retrospective-application.md`.

---

## 1. Refinement record

- Record ID: `FL-CTX-01`
- Trustworthiness concern or principle: Early detection and continued
  monitoring of adversarial behaviour in a distributed Federated Learning
  environment
- Trigger for contextual interpretation: Retrospective reconstruction of the
  documented operational conditions under which detection and monitoring are
  required
- Responsible role(s): Reconstructed operational, coordination, and security
  actors
- Supporting stakeholders: Distributed clients, coordination function,
  operational and governance actors represented in the case
- Related record(s): `FL-A01`, `FL-A02`, `FL-A03`, `FL-ER01`, `FL-ER02`,
  `FL-ER03`

---

## 2. System overview

- System name: Federated Learning setting with secure aggregation
- High-level purpose: Train a shared model through distributed client
  participation without centralising local training data
- Relevant actors: Distributed clients, coordination / aggregation function,
  and operational or security actors
- Decision or action supported by the relevant mechanism: Detection and
  interpretation of evidence potentially indicating adversarial behaviour
- Intended use considered in this reconstruction: Repeated distributed
  training under adversarial risk
- Deployment environment: Distributed and partially observable operational
  environment
- Relevant contextual variation: Changes in participating clients, training
  rounds, observed system behaviour, or detection conditions

---

## 3. Organisational and responsibility context

The documented setting includes responsibilities distributed across technical
and operational functions.

Relevant actors include:

- Distributed clients producing local updates
- A central coordination / aggregation function
- Operational or security actors responsible for monitoring and interpreting
  relevant evidence
- Governance or decision-making functions where escalation or intervention is
  required

The retrospective reconstruction does not assume that a detection signal
automatically determines an operational or governance decision.

Detailed reconstructed responsibility relations are represented in
`responsibility-map.csv`.

---

## 4. Regulatory and governance context

The retrospective analysis focuses on the operational and governance
conditions documented in the technical case rather than reconstructing a
complete legal or compliance assessment.

Relevant governance considerations include:

- Distributed responsibility
- Limited observability
- Interpretation of detection evidence
- Escalation or response where relevant
- Continued monitoring across repeated training rounds

This worked example does not constitute a legal or compliance determination.

---

## 5. Social and stakeholder context

The case is primarily technical and operational. The available documentary
evidence does not support reconstructing a detailed social or stakeholder
analysis beyond the actors participating in or governing the Federated
Learning process.

Accordingly, this worked example does not infer additional stakeholder
expectations or social impacts not documented in the source material.

---

## 6. Operational context

The relevant operational conditions include:

- Multiple distributed clients
- Repeated training rounds
- Secure aggregation
- Limited direct observability of individual client behaviour
- Adversarial risk associated with poisoning or backdoor attacks
- Detection and monitoring before aggregation
- Operational evidence requiring interpretation
- Continued monitoring across successive rounds

These conditions are central to the retrospective reconstruction because they
determine both the required engineering response and its anchoring relative to
aggregation.

---

## 7. Contextual interpretation

- Trustworthiness concern: Detection and management of adversarial behaviour
  under limited observability
- Applicable contextual constraints:
  - Distributed training
  - Secure aggregation
  - Limited visibility of individual client behaviour
  - Repeated training rounds
  - Adversarial threat conditions
- Relevant expectation: Evidence relevant to adversarial behaviour must be
  observable and interpretable early enough to support review before
  aggregation where the documented detection mechanism permits it
- Contextual interpretation: The partially observable and repeated-round FL
  environment requires explicit detection and monitoring requirements whose
  relevant evidence can be interpreted before aggregation and maintained
  during continued operation
- Supporting rationale: Documented FL architecture, aggregation conditions,
  adversarial threat model, and early-detection mechanism
- Supporting evidence: Original Federated Learning case material

This section represents the principal retrospective output associated with
**CR.1 — Context Interpretation**.

---

## 8. Trustworthiness priorities and trade-offs

The original case identifies robustness, security, early detection,
interpretability of alerts, and operational continuity as relevant concerns.

Their presence does not by itself establish a complete formal priority
ordering.

Where a context-specific priority, constraint, or trade-off can be supported
by the documentary evidence, it is represented separately in
`principle-prioritisation.md`.

---

## 9. Contextual assumptions

| Assumption ID | Assumption | Validity condition | Affected contextual decision / interpretation | Evidence or rationale |
|---|---|---|---|---|
| FL-A01 | The operating conditions remain sufficiently compatible with those under which the detection evidence is meaningful | Client population, training behaviour, and relevant system conditions do not change materially beyond the assumptions underlying the detection approach | Detection and monitoring evidence remains interpretable within the reconstructed operational context | Conditions underlying the documented detection approach |
| FL-A02 | Detection signals remain sufficiently informative for operational review | The relationship between the observed signals and relevant system behaviour remains materially valid | Detection evidence can continue to support review before aggregation | Documented detection and monitoring mechanism |
| FL-A03 | The aggregation and training configuration remains compatible with the reconstructed early-monitoring approach | No material protocol or architectural change invalidates the conditions under which monitoring occurs | Detection and monitoring requirements can remain anchored before aggregation and across training rounds | Documented FL and aggregation configuration |

Detailed assumption management is represented in `assumption-log.md`.

---

## 10. Lifecycle anchoring conditions

The Federated Learning case provides explicit evidence for reconstructing
**CR.6 — Lifecycle Anchoring**.

The relevant anchoring conditions are:

- Detection evidence must be available **before aggregation** where it is
  intended to support early review.
- Monitoring must remain available across **successive training rounds**.
- Relevant evidence must remain connected to an identifiable review or
  response mechanism.
- Changes in the FL configuration that affect these conditions require
  reconsideration of the corresponding Engineering Representations.

These conditions constrain subsequent Process Instantiation without making
the final technical placement part of Contextual Refinement.

---

## 11. Revision conditions

| Revision condition | Affected contextual element | Evidence source | Responsible role |
|---|---|---|---|
| Material change in client population or participation conditions | FL-A01 and operational context | Training / operational evidence | Relevant operational actor |
| Material drift or degradation in detection evidence | FL-A02 | Detection / monitoring evidence | Monitoring / security actor |
| Material change in aggregation or FL configuration | FL-A03 and lifecycle anchoring | System or protocol change evidence | Coordination / technical actor |
| Repeated or materially changed anomaly evidence | Existing contextual interpretation or assumption | Detection / review evidence | Operational / governance actor |

Where such evidence challenges an existing assumption or contextual
interpretation, **CR.5 — Context Revision Trigger** determines whether the
affected element should be retained, updated, or reconsidered.

---

## 12. Context revision record

This worked example does not claim a specific historical CR.5 execution unless
supported by the original documentary evidence.

The reconstructed revision relation is:

**Detection / operational evidence  
→ review of existing assumptions and contextual interpretation  
→ retain, update, or reconsider where required  
→ subsequent Functional Refinement**

Specific feedback relations are represented in `feedback-log.md`.

---

## 13. Verification and evidence

Evidence supporting this retrospective contextual reconstruction includes:

- Documented distributed FL architecture
- Secure-aggregation conditions
- Repeated training rounds
- Adversarial threat setting
- Detection and monitoring mechanism
- Early pre-aggregation observation
- Operational evidence and review conditions
- Continued monitoring across rounds

Related worked artefacts:

- `responsibility-map.csv`
- `principle-prioritisation.md`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`
- `monitoring-plan.md`
- `feedback-log.md`

---

## 14. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: Federated Learning
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This document represents **documented Federated Learning evidence using the
current CRISP-TAI contextual-refinement structure**.

It should not be interpreted as evidence that CRISP-TAI was used prospectively
during the original study.

Its purpose is to demonstrate how a documented operational setting can be
represented as:

**Operational context  
→ contextual interpretation and assumptions  
→ lifecycle anchoring conditions  
→ subsequent process-independent Engineering Representations  
→ Process Instantiation**

without treating the detection mechanism itself as an automatic
trustworthiness judgement.
