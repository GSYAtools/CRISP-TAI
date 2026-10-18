# Retrospective Application Log — Federated Learning

This record documents the **retrospective application** of the Lifecycle
Refinement Framework through its CRISP-TAI instantiation to the Federated
Learning (FL) case examined in the associated research article.

The case concerns early detection of backdoor and poisoning attacks in a
distributed Federated Learning setting. The retrospective reconstruction is
aligned with the original study:

*Early detection of backdoor attacks in federated learning via ecosystemic
symmetry breaking*.

This record reconstructs trustworthiness-related contextual decisions,
engineering representations, and their documented technical enactment from the
available case material. It does **not** imply that CRISP-TAI was prospectively
executed during the original study and should not be interpreted as independent
empirical validation of the framework.

---

## 1. Application scope

- Setting: Federated Learning with distributed clients and secure aggregation
- Application type: Retrospective analytical reconstruction
- Framework instantiation: CRISP-TAI
- Primary concern examined: Early operational detection and response to
  adversarial behaviour
- Operational context: Repeated training rounds in a partially observable
  distributed environment
- Evidence basis: Documented operational constraints, detection mechanisms,
  monitoring logic, and technical mitigation or response mechanisms described
  in the original case material

---

## 2. Reconstructed Contextual Refinement

### CR.1 — Context Interpretation

The documented FL setting provides evidence for reconstructing the relevant
operational context, including distributed clients, secure aggregation,
partial observability, repeated training rounds, and adversarial risk.

**Reconstructed contextual output:**
- An interpretation of the system as a distributed and partially observable
  operational environment in which trustworthiness-related evidence must be
  interpreted before aggregation and across successive training rounds.

**Documentary basis:**
- System architecture, secure-aggregation setting, adversarial threat model,
  and operational conditions documented in the original study.

### CR.4 — Assumption Documentation

The case material contains operational assumptions and conditions on which
detection and response depend.

**Reconstructed contextual output:**
- Assumptions and operational constraints concerning the expected system
  behaviour, detection conditions, and distributed training environment.

**Documentary basis:**
- Conditions and assumptions underlying the detection and monitoring approach
  described in the original study.

### CR.6 — Lifecycle Anchoring

The case provides evidence that relevant trustworthiness-related requirements
must be considered before aggregation and maintained during repeated training
rounds.

**Reconstructed anchoring output:**
- Lifecycle and operational conditions requiring early placement of detection
  and monitoring mechanisms before aggregation and their continued availability
  during operation.

CR.6 records these anchoring conditions without making the final technical
placement itself part of Contextual Refinement.

---

## 3. Reconstructed Functional Refinement

### FR.1 — Engineering Representation Derivation

The reconstructed contextual constraints can be expressed through
process-independent engineering representations concerning detection,
monitoring, and response.

**Reconstructed engineering representations include:**
- Detection requirements
- Monitoring requirements
- Response or mitigation requirements
- Operational review requirements

These representations describe the engineering response required by the
context without prescribing their final technical implementation or lifecycle
location.

### FR.2 — Decision Traceability

The documented relationship among operational constraints, detection signals,
monitoring mechanisms, and technical response provides evidence for
reconstructing traceability between contextual decisions and engineering
representations.

**Reconstructed traceability relation:**

**Operational constraint / contextual decision  
→ detection or monitoring Engineering Representation  
→ documented technical enactment**

### FR.3 — Operational Adjustment

Where detected evidence indicates that an operational response may be
required, the case supports reconstruction of an engineering representation
specifying the required adjustment or mitigation condition.

FR.3 is interpreted here as deriving or revising the **Engineering
Representation specifying the adjustment**. It does not itself execute a
client exclusion, configuration change, or other mitigation action.

### FR.4 — Iterative Feedback Integration

Detection and monitoring evidence can be related back to existing operational
assumptions and engineering representations.

The reconstructed feedback relation is:

**Operational evidence  
→ assessment against existing assumptions and Engineering Representations  
→ potential contextual reconsideration or engineering revision**

This reconstruction does not imply that the original study executed the
Lifecycle Refinement Framework prospectively.

### FR.6 — Continuity Enforcement

The repeated-round nature of Federated Learning provides evidence for
reconstructing continuity requirements concerning monitoring and review across
successive training rounds.

**Reconstructed engineering representation:**
- Monitoring and review obligations must remain active across repeated rounds
  and relevant system changes.

---

## 4. Documented process-specific instantiation

The original case material documents technical mechanisms through which the
reconstructed engineering representations were enacted.

Representative instantiation evidence includes:

- Detection mechanisms operating before aggregation
- Monitoring across training rounds
- Alert or anomaly signals requiring interpretation
- Technical response or mitigation mechanisms
- Continued observation across successive rounds

These elements are treated retrospectively as **documented process-specific
instantiations** of the reconstructed engineering representations.

Their existence in the original system does not imply that CRISP-TAI was used
prospectively to derive them.

---

## 5. Traceability summary

| Trustworthiness concern | Contextual reconstruction | CR rule | Engineering Representation | FR rule | Documented instantiation evidence |
|---|---|---|---|---|---|
| Distributed adversarial risk | Partially observable FL environment with distributed clients and secure aggregation | CR.1 | Detection and monitoring requirements | FR.1; FR.2 | Detection and monitoring mechanisms documented in the original case |
| Operational assumptions | Detection and response depend on documented operating conditions and assumptions | CR.4 | Review and monitoring requirements | FR.1; FR.2; FR.4 | Monitoring evidence and review logic |
| Early detection | Relevant trustworthiness controls must operate before aggregation | CR.6 | Early detection / placement requirement | FR.1 | Pre-aggregation detection mechanism |
| Operational response | Detection evidence may require a defined engineering response | CR.1; CR.4 | Operational adjustment or mitigation requirement | FR.3 | Documented technical response or mitigation mechanism |
| Continuity | Monitoring must persist across repeated training rounds | CR.6 | Continuity requirement | FR.6 | Continued monitoring across successive rounds |

---

## 6. Process-level evidence

This retrospective application provides evidence primarily for:

- **Lifecycle anchoring**, through the documented placement of detection and
  monitoring mechanisms before aggregation and during repeated operation
- **Coordinated contextual and functional refinement**, through the
  reconstructable relationship between operational constraints and
  detection, monitoring, and response representations
- **Iterative feedback integration**, through the relationship between
  operational evidence, review, and potential revision
- **Continuity**, through monitoring and review across successive training
  rounds

The evidence is analytical and retrospective. It supports reconstruction of
these process-level properties within the CRISP-TAI instantiation but does not
establish prospective effectiveness or independent empirical validation.

---

## 7. Relationship to repository artefacts

The reconstruction can be represented using:

- `templates/contextual-refinement/context-description.md`
- `templates/contextual-refinement/assumption-log.md`
- `templates/functional-refinement/engineering-representation.md`
- `templates/functional-refinement/traceability-matrix.csv`
- `templates/functional-refinement/monitoring-plan.md`
- `templates/functional-refinement/feedback-log.md`

These reusable templates make the reconstructed chain explicit while
preserving the distinction between original documentary evidence and the
retrospective application of the framework.

---

## Notes

This record is a **retrospective application log**, not an execution log.

Its purpose is to document how evidence already present in the Federated
Learning case can be reconstructed through Contextual Refinement, Functional
Refinement, and subsequent process-specific instantiation.

The record does not claim that the original technical study was designed or
executed using CRISP-TAI.
