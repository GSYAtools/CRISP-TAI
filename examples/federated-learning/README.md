# Example — Federated Learning with Early Trustworthiness Monitoring

This example illustrates how **CRISP-TAI** can be instantiated in a
**Federated Learning (FL)** setting where trustworthiness concerns arise
primarily during **system operation**, rather than at design time.

The example is derived from the study  
*Early detection of backdoor attacks in federated learning via ecosystemic symmetry breaking* (https://github.com/GSYAtools/Backdoor_attacks_FL),
and reinterprets that work from a **process and lifecycle perspective**,
focusing on how early warning, monitoring, and revision mechanisms can
be embedded within an AI development lifecycle.

---

## Context overview

The system consists of a standard Federated Learning setup with:

- A central coordinator orchestrating training rounds
- Multiple distributed clients training locally on private, non-i.i.d. data
- Secure aggregation preventing inspection of individual updates

This setting is representative of large-scale, privacy-preserving
deployments such as mobile services or cross-organisational learning.

---

## Stakeholders and roles

The scenario involves the following roles:

- **Clients**  
  Local training nodes producing model updates from private data.

- **Server / Coordinator**  
  Entity responsible for aggregation and orchestration, with limited
  visibility due to secure aggregation.

- **Operations and Security Team**  
  Actors responsible for monitoring, interpreting alerts, and triggering
  mitigation actions.

- **Governance Board**  
  Body responsible for defining acceptable risk levels and escalation policies.

Trustworthiness-related responsibilities are **distributed** and
must be coordinated without direct access to raw updates.

---

## Trustworthiness concerns

Based on the analysis presented in the paper :contentReference[oaicite:3]{index=3},
the primary trustworthiness concerns in this scenario include:

- **Robustness and security**  
  Protection against poisoning and backdoor attacks.

- **Early detection**  
  Identification of malicious behaviour before aggregation.

- **Interpretability of alerts**  
  Ability to understand and act upon detection signals.

- **Operational continuity**  
  Sustained monitoring across training rounds and system evolution.

These concerns motivate a strong emphasis on **Functional Refinement**.

---

## Application of Contextual Refinement (CR)

Contextual Refinement artefacts are used to define the operational
and governance setting of FL security monitoring:

- `context-description.md`  
  Captures assumptions about secure aggregation, client behaviour,
  and acceptable operational risk.

- `responsibility-map.csv`  
  Allocates responsibility for monitoring, alert interpretation,
  and mitigation decisions.

- `principle-prioritisation.md`  
  Prioritises early detection and robustness over performance
  optimisation in adversarial settings.

- `assumption-log.md`  
  Records assumptions about benign client behaviour and
  calibration validity, together with revision triggers.

These artefacts support **CR.1–CR.5**.

---

## Application of Functional Refinement (FR)

Functional Refinement connects the monitoring technique described
in the paper :contentReference[oaicite:4]{index=4} to lifecycle artefacts:

- `artefact-derivation.md`  
  Links early-warning interpretations to monitoring and response artefacts.

- `traceability-matrix.csv`  
  Provides traceability between trustworthiness concerns,
  lifecycle decisions, and operational artefacts.

- `monitoring-plan.md`  
  Defines how per-client statistical signals are monitored
  before aggregation.

- `feedback-log.md`  
  Records alerts, interpretations, and resulting mitigation actions.

These artefacts support **FR.1–FR.6**.

---

## Relation to the detection method

This example does **not** reimplement or evaluate the detection method
itself. Instead, it demonstrates how such a method can be:

- Embedded into an AI lifecycle
- Interpreted as a trustworthiness signal rather than a binary verdict
- Integrated with governance and escalation mechanisms

CRISP-TAI thus complements the technical contribution by providing
a **process-level structure** for its operational use.

---

## Purpose of the example

This example is **illustrative and partial**.

Its goal is to show how CRISP-TAI:
- Structures early-warning mechanisms
- Supports interpretability and decision-making
- Enables continuous trustworthiness management in FL systems

It is not intended as a reference implementation or a certification procedure.
