# Principle Prioritisation — TrustAIoT Worked Example

This document is an **additional illustrative completion** of the
`principle-prioritisation.md` template using documentary evidence from the
TrustAIoT case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

The analytical evaluation reported in the associated article reconstructs:

- **CR.4 — Assumption Documentation**
- **CR.6 — Lifecycle Anchoring**
- **FR.4 — Iterative Feedback Integration**
- **FR.6 — Continuity Enforcement**

It does **not** independently reconstruct
**CR.3 — Principle Prioritisation** for the TrustAIoT case.

Accordingly, this file demonstrates how trustworthiness concerns and
dependencies documented in TrustAIoT can be represented using the reusable
prioritisation template without extending the analytical claims made in the
associated article.

---

## 1. Prioritisation record

- Record ID: `TAIOT-PRIO-01`
- System or component: TrustAIoT platform
- Purpose of this record: Illustrate representation of documented
  trustworthiness concerns and contextual dependencies
- Decision context: Platform-level governance and continued operation
- Related context record: `TAIOT-CTX-01`
- Related assumption records:
  - `TAIOT-A01`
  - `TAIOT-A02`
  - `TAIOT-A03`
- Paper-supported CR reconstruction:
  - `CR.4`
  - `CR.6`
- Template function illustrated here:
  - `CR.3 — Principle Prioritisation`
- Artefact status: Additional illustrative worked-template representation
- Repository version: `0.2.0`

---

## 2. Documented trustworthiness concerns

The TrustAIoT material identifies multiple trustworthiness concerns relevant
to platform governance and evolution.

| Principle / concern | Why applicable | Contextual dependency or expectation | Relevant actor(s) |
|---|---|---|---|
| Lawfulness | Platform operation is subject to regulatory and governance requirements | Trustworthiness-related activities must remain compatible with applicable requirements as the platform evolves | Platform Owner; Compliance Team |
| Robustness | AIoT operation involves heterogeneous devices, AI-enabled components, and technical dependencies | Relevant technical and operational mechanisms must remain suitable under changing platform conditions | Platform Architecture Team; Project Teams |
| Explainability / transparency | Human-centred governance and oversight require understandable system behaviour and decisions | Explanation-related concerns remain relevant to platform governance and project-level enactment | Platform Owner; Platform Architecture Team; Project Teams |
| Sustainability | Long-lived AIoT operation introduces lifecycle and resource considerations | Platform evolution and device lifecycle management may affect long-term trustworthiness concerns | Platform Owner; Platform Architecture Team |
| Accountability | Multiple platform and project actors participate in governance and operation | Responsibility boundaries must remain identifiable across organisational and technical layers | Platform Owner; Compliance Team; Project Teams |

The presence of these concerns does **not** establish a paper-supported CR.3
priority ordering.

---

## 3. Documented dependencies

The case material supports representation of dependencies among the concerns
above.

| Dependency | Concerns involved | Contextual consideration | Worked-example interpretation |
|---|---|---|---|
| Regulatory alignment during platform evolution | Lawfulness; accountability | Governance and policy conditions may evolve during long-term operation | Existing assumptions and governance conditions may require later review |
| Human-centred operation under technical complexity | Explainability / transparency; robustness | Heterogeneous AIoT components may complicate explanation and oversight | Explanation-related concerns coexist with operational and architectural constraints |
| Long-term platform evolution | Sustainability; robustness; accountability | Maintenance, device evolution, organisational change, and policy change affect continued operation | Monitoring, maintenance, feedback, and adaptation mechanisms remain relevant during evolution |

These dependencies are useful contextual information.

They are not presented as quantified trade-offs or as evidence that CR.3 was
independently reconstructed in the associated article.

---

## 4. Illustrative prioritisation constraint

The documentary evidence does not provide a sufficient basis for reconstructing
a complete `High / Medium / Low` ordering across the identified concerns.

For purposes of demonstrating the reusable template, the documented concerns
can instead be summarised through the following **illustrative contextual
constraint**:

> Platform governance should continue to account for applicable regulatory,
> accountability, robustness, transparency, and lifecycle concerns as
> TrustAIoT evolves, with their treatment justified against the relevant
> contextual conditions.

This statement organises documented concerns without claiming a paper-supported
CR.3 output.

It should not be interpreted as:

- A universal ranking of trustworthiness principles
- A reconstructed historical prioritisation decision
- An additional contextual decision used by the paper's analytical evaluation

---

## 5. Relationship to CR.4 — Assumption Documentation

The documented concerns represented here are relevant to the assumptions
reconstructed through CR.4.

For example:

- Regulatory and governance concerns contribute to the conditions represented
  by `TAIOT-A01`.
- Monitoring and stakeholder-related concerns contribute to the conditions
  represented by `TAIOT-A02`.
- Lifecycle, maintenance, and adaptation concerns contribute to the conditions
  represented by `TAIOT-A03`.

The paper-supported relationship is therefore not:

**CR.3 prioritisation  
→ CR.4 assumptions**

but rather:

**documented TrustAIoT contextual evidence  
→ CR.4 assumptions and validity conditions**

This file provides supporting organisation of that contextual evidence.

---

## 6. Relationship to CR.6 — Lifecycle Anchoring

Several concerns represented in this file have identifiable lifecycle
dependencies.

For example:

- Regulatory and governance requirements may affect governance and review
  activities.
- Robustness concerns may affect testing, validation, monitoring, and
  maintenance.
- Transparency concerns may affect governance, oversight, and project-level
  activities.
- Sustainability concerns may affect maintenance and platform evolution.
- Accountability concerns may span multiple lifecycle and organisational
  locations.

These dependencies support interpretation of the paper-supported
**CR.6 — Lifecycle Anchoring** reconstruction.

Final mapping to a specific TrustAIoT lifecycle activity or mechanism belongs
to Process Instantiation.

---

## 7. Relationship to FR.4 and FR.6

The concerns and dependencies represented here may also help interpret later
operational evidence.

### FR.4 — Iterative Feedback Integration

Monitoring, validation, or user evidence may reveal that an existing
contextual assumption or engineering record requires review.

### FR.6 — Continuity Enforcement

Trustworthiness-related obligations associated with the documented concerns
may need to remain active or be reconsidered during platform evolution.

These are paper-supported TrustAIoT functions.

Their reconstruction does not depend on treating this file as evidence of
CR.3.

---

## 8. Additional illustrative review conditions

For purposes of demonstrating the reusable prioritisation template, the
represented concerns could be reviewed in a prospective application when the
underlying context changes.

| Illustrative review condition | Concern potentially affected | Evidence source |
|---|---|---|
| Material regulatory or policy change | Lawfulness; accountability | Regulatory / policy evidence |
| Material architectural or platform change | Robustness; explainability / transparency | Platform / architectural evidence |
| Material change in stakeholder expectations | Explainability / transparency; accountability | User / stakeholder feedback |
| Material lifecycle or device-management change | Sustainability; robustness | Maintenance / lifecycle evidence |
| Material organisational change | Accountability | Governance / organisational evidence |

These are prospective illustrative review conditions.

They do not establish historical CR.3 or CR.5 execution.

---

## 9. Conditional relationship to CR.5

Where new evidence invalidates an assumption reconstructed through CR.4, a
prospective application could invoke:

**CR.5 — Context Revision Trigger**

The relevant framework relation would be:

**new evidence  
→ review of an existing contextual assumption  
→ CR.5 where contextual reconsideration is justified  
→ subsequent Functional Refinement**

This is a conditional framework path.

It does not add CR.5 to the canonical TrustAIoT rule reconstruction.

---

## 10. Decisions not reconstructed

The available evidence does not justify using this worked artefact to claim:

- A formal `High / Medium / Low` ranking
- A universal ordering among Lawfulness, Robustness, Explainability,
  Sustainability, and Accountability
- A quantified trade-off among those concerns
- A historical CR.3 execution
- A new contextual decision ID feeding the paper-supported Functional
  Refinement reconstruction
- Historical CR.5 execution

These limitations are deliberate.

Absence of documentary evidence should not be replaced by inferred
prioritisation.

---

## 11. Verification and evidence

Supporting documentary evidence includes:

- Stakeholder requirements
- Regulatory and governance inputs
- Strategic objectives
- Platform governance structures
- Architectural organisation
- Testing and validation mechanisms
- Continuous monitoring
- User-feedback mechanisms
- Maintenance and change-management procedures
- Policy-adaptation mechanisms

Related paper-supported worked artefacts:

- `context-description.md`
- `assumption-log.md`
- `monitoring-plan.md`
- `feedback-log.md`

Supporting repository artefacts:

- `responsibility-map.csv`
- `engineering-representation.md`
- `traceability-matrix.csv`

---

## 12. Analytical boundary

For TrustAIoT, the associated article supports:

### Contextual Refinement
- **CR.4 — Assumption Documentation**
- **CR.6 — Lifecycle Anchoring**

### Functional Refinement
- **FR.4 — Iterative Feedback Integration**
- **FR.6 — Continuity Enforcement**

### Assessment criteria
- **P1 — Lifecycle Anchoring**
- **P2 — Coordinated Contextual and Functional Refinement**
- **P3 — Continuity and Iterative Feedback**

This file illustrates the structure of a CR.3-oriented reusable template but
does **not** add CR.3 to that analytical reconstruction.

P4 — Cross-Domain Adaptability is assessed through cross-case comparison.

---

## 13. Versioning and ownership

- Artefact type: Additional illustrative completion of a CRISP-TAI v0.2.0
  template
- Source case: TrustAIoT
- Repository version: `0.2.0`
- Status: Illustrative worked-template representation
- Original project record: No
- Paper-supported CR.3 reconstruction: No
- Paper-supported CR.5 reconstruction: No

---

## Notes

This artefact demonstrates that a reusable prioritisation template can remain
useful even when the retrospective analytical evaluation does not reconstruct
CR.3 for the case.

Its role is:

**documented trustworthiness concerns and dependencies  
→ supporting contextual representation  
→ interpretation of CR.4 assumptions and CR.6 lifecycle dependencies**

rather than:

**documented concerns  
→ claimed CR.3 reconstruction**

The authoritative TrustAIoT analytical boundary remains:

**CR.4 / CR.6  
→ FR.4 / FR.6  
→ documented Process Instantiation  
→ P1 / P2 / P3**
