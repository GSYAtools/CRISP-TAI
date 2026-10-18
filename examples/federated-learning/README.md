# Worked Example — Federated Learning with Early Trustworthiness Monitoring

This directory provides an **illustrative worked example** showing how the
reusable CRISP-TAI repository templates can be populated retrospectively using
documentary evidence from the Federated Learning case examined in the
associated research article.

The example is based on material documented in:

*Early detection of backdoor attacks in federated learning via ecosystemic
symmetry breaking*.

It represents that material using the **v0.2.0 CRISP-TAI artefact structure**.

This example does **not** imply that the Lifecycle Refinement Framework or
CRISP-TAI was prospectively applied during the original Federated Learning
study. The completed artefacts are retrospective representations intended to
illustrate how the current templates can be used.

---

## Example scope

The case concerns a Federated Learning setting in which distributed clients
participate in repeated training rounds and secure aggregation limits direct
observability of individual client updates.

Relevant characteristics documented in the case include:

- Distributed clients participating in repeated training rounds
- A central coordination and aggregation function
- Secure aggregation
- Limited observability of individual client behaviour
- Adversarial risk associated with backdoor or poisoning attacks
- Detection and monitoring before aggregation
- Operational evidence requiring interpretation rather than automatic
  trustworthiness judgement
- Continued monitoring across successive training rounds

These characteristics make the case useful for illustrating operational
context interpretation, assumption management, lifecycle anchoring, early
detection and monitoring requirements, operational adjustment, feedback, and
continuity.

---

## How to interpret the files in this directory

The files in this directory are **completed examples of the reusable
templates** provided under `/templates`.

They should be read as retrospective representations of documented case
evidence, not as original project records.

The example follows the refinement and instantiation chain:

**Documented case evidence  
→ reconstructed contextual decision  
→ reconstructed process-independent Engineering Representation  
→ documented process-specific instantiation  
→ operational evidence and revision, where available**

The example deliberately distinguishes detection or monitoring evidence from
the governance and engineering decisions that may follow from it.

---

## Contextual Refinement worked artefacts

### `context-description.md`

Represents the distributed, partially observable operational context
reconstructed from the Federated Learning case, including secure aggregation,
repeated training rounds, adversarial risk, and relevant contextual
constraints.

### `responsibility-map.csv`

Illustrates how responsibilities associated with coordination, monitoring,
evidence interpretation, and subsequent decision-making can be represented
without assuming that detection signals automatically determine governance or
operational actions.

### `principle-prioritisation.md`

Illustrates how relevant trustworthiness concerns and contextual dependencies
can be represented where the documentary evidence supports an explicit
priority, constraint, or trade-off.

### `assumption-log.md`

Represents assumptions and validity conditions associated with the operating
environment, detection conditions, and continued monitoring across training
rounds.

---

## Functional Refinement worked artefacts

### `engineering-representation.md`

Shows how reconstructed contextual constraints can be expressed as
**process-independent Engineering Representations** concerning detection,
monitoring, response, and continuity before their process-specific technical
placement.

### `traceability-matrix.csv`

Provides the principal end-to-end mapping artefact for the worked example. It
links:

**contextual decision  
→ Engineering Representation  
→ lifecycle anchoring / scope / placement constraints  
→ Process Instantiation  
→ documented technical enactment**

The Federated Learning case is particularly useful for illustrating lifecycle
anchoring because relevant detection and monitoring requirements must be
addressed before aggregation and maintained across repeated training rounds.

### `monitoring-plan.md`

Illustrates how detection and monitoring requirements can be related to
operational evidence collected during repeated training rounds.

### `feedback-log.md`

Illustrates how alerts, anomaly signals, reviews, or other operational evidence
can be assessed against existing contextual assumptions and Engineering
Representations before any contextual revision, engineering adjustment, or
process-specific response is represented.

---

## Relationship to the detection method

This worked example does **not** reimplement, reproduce, or evaluate the
underlying detection method.

The detection mechanism remains part of the original technical study. Within
this repository, its documented behaviour is used only as evidence for
illustrating how a technical detection capability can relate to:

- Contextual operational constraints
- Process-independent detection and monitoring requirements
- Lifecycle anchoring before aggregation
- Evidence interpretation
- Potential engineering adjustment
- Continued monitoring across training rounds

A detection signal is therefore represented as **evidence requiring
interpretation**, not as an automatic trustworthiness verdict or governance
decision.

---

## Canonical retrospective application record

The methodological reconstruction of this case is documented separately in:

`/logs/federated-learning-retrospective-application.md`

That record explains:

- The documentary evidence used
- Which CR and FR functions can be reconstructed from that evidence
- The reconstructed Engineering Representations
- The documented technical enactment
- The process-level properties for which the case provides analytical evidence

The files in this directory complement that record by showing **how the
reconstruction can be represented using the reusable v0.2.0 templates**.

---

## Relationship to the original Federated Learning material

The original Federated Learning study remains the evidential source for the
retrospective reconstruction.

The completed templates in this directory:

- Do not replace the original technical or experimental description
- Do not constitute original project documentation
- Do not reimplement or validate the detection method
- Do not demonstrate prospective execution of CRISP-TAI
- Do not constitute independent empirical validation of the Lifecycle
  Refinement Framework
- Do provide an illustrative, inspectable representation of how documented
  case evidence can be structured using the current CRISP-TAI artefacts

---

## Purpose of the worked example

This example is intended to help practitioners understand how to move from a
documented technical and operational setting to:

1. Contextual interpretations and assumptions
2. Process-independent detection, monitoring, response, and continuity
   Engineering Representations
3. Process-specific technical instantiation
4. Traceability across those elements
5. Operational evidence and feedback
6. Contextual or engineering revision where supported by evidence

It should therefore be used as an **illustrative worked example**, not as a
reference implementation, certification procedure, or claim that CRISP-TAI
was used during the original Federated Learning study.
