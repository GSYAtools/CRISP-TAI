# Worked Example — TrustAIoT

This directory provides an **illustrative worked example** showing how the
reusable CRISP-TAI repository templates can be populated retrospectively using
documentary evidence from the TrustAIoT case examined in the associated
research article.

The example is based on material documented in:

*TrustAIoT: A framework for building trustworthy AIoT platforms*.

It represents that material using the **v0.2.0 CRISP-TAI artefact structure**.

This example does **not** imply that the Lifecycle Refinement Framework or
CRISP-TAI was prospectively applied during the original development of
TrustAIoT. The completed artefacts are retrospective representations intended
to illustrate how the current templates can be used.

---

## Example scope

TrustAIoT concerns a long-lived AI-enabled Internet of Things platform
supporting multiple projects and stakeholders.

Relevant characteristics documented in the case include:

- Edge–fog–cloud architectural organisation
- Heterogeneous devices and AI-enabled components
- Multiple organisational and governance actors
- Regulatory and strategic constraints
- Continuous monitoring and user feedback
- Change-management and maintenance processes
- Policy adaptation during platform evolution

These characteristics make the case useful for illustrating contextual
assumptions, lifecycle anchoring, feedback integration, continuity, and
contextual revision.

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

---

## Contextual Refinement worked artefacts

### `context-description.md`

Represents contextual information and assumptions reconstructed from
stakeholder requirements, regulations, strategic objectives, operational
conditions, and governance information documented in TrustAIoT.

### `responsibility-map.csv`

Illustrates how relevant governance and operational responsibilities can be
represented using the CR.2-oriented responsibility template.

### `principle-prioritisation.md`

Illustrates how contextual trustworthiness priorities or trade-offs can be
represented where supported by the documented case material.

### `assumption-log.md`

Represents assumptions, validity conditions, and revision triggers associated
with the platform context.

---

## Functional Refinement worked artefacts

### `engineering-representation.md`

Shows how reconstructed contextual decisions can be expressed as
**process-independent Engineering Representations** before their
process-specific lifecycle mapping.

### `traceability-matrix.csv`

Provides the principal end-to-end mapping artefact for the worked example. It
links:

**contextual decision  
→ Engineering Representation  
→ lifecycle anchoring / scope / placement constraints  
→ Process Instantiation  
→ instantiated lifecycle artefact or operational mechanism**

### `monitoring-plan.md`

Illustrates monitoring and continuity requirements reconstructed from the
documented TrustAIoT monitoring, maintenance, and operational mechanisms.

### `feedback-log.md`

Illustrates how monitoring, validation, or user evidence can be related to
existing contextual interpretations and Engineering Representations and,
where required, propagated through contextual revision and subsequent
re-refinement.

---

## Canonical retrospective application record

The methodological reconstruction of this case is documented separately in:

`/logs/trustaiot-retrospective-application.md`

That record explains:

- The documentary evidence used
- Which CR and FR functions can be reconstructed from that evidence
- The reconstructed Engineering Representations
- The documented process-specific instantiation
- The process-level properties for which the case provides analytical evidence

The files in this directory complement that record by showing **how the
reconstruction can be represented using the reusable v0.2.0 templates**.

---

## Relationship to the original TrustAIoT material

The original TrustAIoT material remains the evidential source for the
retrospective reconstruction.

The completed templates in this directory:

- Do not replace the original architectural or process descriptions
- Do not constitute original TrustAIoT project documentation
- Do not demonstrate prospective execution of CRISP-TAI
- Do not constitute independent empirical validation
- Do provide an illustrative, inspectable representation of how documented
  case evidence can be structured using the current CRISP-TAI artefacts

---

## Purpose of the worked example

This example is intended to help practitioners understand how to move from
documented contextual and operational evidence to:

1. Contextual interpretations and decisions
2. Process-independent Engineering Representations
3. Process-specific lifecycle instantiation
4. Traceability across those elements
5. Monitoring, feedback, and revision where supported by evidence

It should therefore be used as an **illustrative worked example**, not as a
prescriptive reference implementation.
