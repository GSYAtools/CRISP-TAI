# Instantiation Log — Federated Learning (Early Trustworthiness Monitoring)

This log documents the **execution-based instantiation of CRISP-TAI** in a
**Federated Learning (FL)** scenario focused on early detection of backdoor
and poisoning attacks during system operation.

The instantiation is aligned with the study:
*Early detection of backdoor attacks in federated learning via ecosystemic symmetry breaking*,
and records **process-level decisions and refinements**, not algorithmic details
or experimental results.

---

## 1. Instantiation scope

- System: Federated Learning with secure aggregation
- Scope: Operational monitoring and governance during training rounds
- Instantiation phase: Deployment and continuous operation
- Responsible body: Operations and Security Team

---

## 2. Applied Contextual Refinement (CR) rules

- **CR.1 — Context Interpretation**  
  Interpreted the FL setting as a partially observable system with distributed
  clients, secure aggregation, and adversarial risk.

- **CR.2 — Responsibility Allocation**  
  Allocated responsibilities for monitoring, alert interpretation, and escalation
  to the Operations and Security Team, with governance oversight.

- **CR.3 — Principle Prioritisation**  
  Prioritised robustness and security over performance optimisation, reflecting
  the adversarial threat model.

- **CR.4 — Assumption Documentation**  
  Documented assumptions regarding benign majority of clients, stability of
  detection signals, and effectiveness of aggregation protocols.

- **CR.5 — Context Revision Triggers**  
  Defined triggers such as repeated alerts, calibration drift, or changes in
  client population to revisit assumptions and priorities.

---

## 3. Applied Functional Refinement (FR) rules

- **FR.1 — Artefact Derivation**  
  Derived monitoring and escalation artefacts from contextual interpretations,
  including monitoring plans and response procedures.

- **FR.2 — Decision Traceability**  
  Linked trustworthiness decisions to monitoring artefacts and responsible roles
  across training rounds.

- **FR.3 — Operational Adjustment**  
  Enabled pre-aggregation mitigation actions (e.g., client exclusion) based on
  detected anomalies.

- **FR.4 — Iterative Feedback Integration**  
  Integrated feedback from alerts and reviews to adjust thresholds and assumptions.

- **FR.6 — Continuity Enforcement**  
  Ensured that monitoring and review remained active across successive training
  rounds and system updates.

---

## 4. Key instantiation outcomes

- Trustworthiness monitoring was embedded **before aggregation**, rather than
  applied post-hoc.
- Alerts were treated as **signals requiring interpretation**, not automatic verdicts.
- Governance decisions could be taken early, reducing systemic risk.

---

## 5. Lessons learned

- Early operational monitoring is critical in partially observable FL settings.
- Explicit separation between detection signals and governance decisions improves
  interpretability and trust.
- CRISP-TAI artefacts supported coordination between technical and governance roles
  without modifying the underlying FL protocol.

---

## Notes

This instantiation log focuses on **process execution and refinement**.
It complements the technical contribution of the referenced paper by
making trustworthiness-related reasoning explicit and traceable.
