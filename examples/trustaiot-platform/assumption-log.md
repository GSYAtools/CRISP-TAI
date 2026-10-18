# Assumption Log — TrustAIoT Worked Example

This document is an **illustrative retrospective completion** of the
`assumption-log.md` template using documentary evidence from the TrustAIoT
case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

For the analytical evaluation reported in the associated article, this worked
artefact represents:

- **CR.4 — Assumption Documentation**

The documented TrustAIoT monitoring, validation, feedback, maintenance,
change-management, and policy-adaptation mechanisms additionally illustrate
how later evidence can be related to the validity conditions of those
assumptions.

Where such evidence invalidates an assumption, a prospective framework
application could invoke **CR.5 — Context Revision Trigger**. CR.5 is not
independently claimed as part of the TrustAIoT retrospective reconstruction
reported in the associated article.

---

## 1. Log information

- System or component: TrustAIoT platform
- Log ID: `TAIOT-ASSUMPTIONS-01`
- Related context record: `TAIOT-CTX-01`
- Paper-supported CR reconstruction:
  - `CR.4 — Assumption Documentation`
  - `CR.6 — Lifecycle Anchoring`
- Paper-supported FR reconstruction:
  - `FR.4 — Iterative Feedback Integration`
  - `FR.6 — Continuity Enforcement`
- Assessment criteria:
  - `P1 — Lifecycle Anchoring`
  - `P2 — Coordinated Contextual and Functional Refinement`
  - `P3 — Continuity and Iterative Feedback`
- Artefact status: Paper-supported retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. CR.4 — Assumption register

The assumptions below are structured retrospective reconstructions of
contextual conditions supported by the documented TrustAIoT material.

They are not presented as verbatim assumptions originally recorded using
CRISP-TAI terminology.

| Assumption ID | Assumption | Type | Validity condition | Rationale / evidence | Related contextual or lifecycle element | Responsible role | Evidence requiring review | Status |
|---|---|---|---|---|---|---|---|---|
| TAIOT-A01 | Platform governance and lifecycle-management mechanisms remain capable of addressing relevant changes during continued operation | Organisational / Operational | Governance, maintenance, update, and change-management mechanisms remain active and applicable as the platform evolves | Documented lifecycle-management, maintenance, and change-management mechanisms | Continued applicability of governance and lifecycle decisions | Platform Owner / relevant governance actor | Material platform change, incident, or failure of lifecycle-management mechanisms | Active |
| TAIOT-A02 | Platform-level trustworthiness requirements continue to be reflected in the operation and evolution of hosted projects | Organisational / Governance | Project-level operation remains connected to applicable platform governance, responsibilities, and policies | Documented relationship between platform governance, lifecycle activities, and project operation | Relationship between platform-level governance and project-level enactment | Platform and project actors | New project conditions, governance deviation, review finding, or material organisational change | Active |
| TAIOT-A03 | Existing regulatory and policy interpretations remain applicable while the relevant regulatory, policy, and operating conditions remain materially compatible | Legal / Regulatory | Relevant regulation, policy, authoritative guidance, and operating context remain materially compatible with the existing interpretation | Regulations, governance inputs, and policy-adaptation mechanisms documented in the case | Continued applicability of regulatory and governance constraints | Relevant governance / compliance actor | Material regulatory, policy, authoritative-guidance, or operating-context change | Active |
| TAIOT-A04 | Monitoring and feedback mechanisms remain available to provide relevant evidence during continued operation | Operational / Evidence | Monitoring, validation, feedback, and responsible review mechanisms remain operational and connected to governance or change-management processes | Documented continuous monitoring, testing and validation, user feedback, and change-management mechanisms | Availability of evidence supporting later review through FR.4 and continuity through FR.6 | Relevant operational and governance actors | Loss or material degradation of monitoring, validation, feedback, or review capability | Active |

These assumptions represent the paper-supported
**CR.4 — Assumption Documentation** reconstruction.

---

## 3. Assumption types

The worked example uses the following contextual categories:

- **Organisational / Operational** — governance, lifecycle management,
  maintenance, and platform evolution
- **Organisational / Governance** — relationships between platform-level and
  project-level governance and responsibilities
- **Legal / Regulatory** — continued applicability of regulatory, policy, or
  authoritative interpretations
- **Operational / Evidence** — availability of monitoring, validation,
  feedback, and review mechanisms

These categories organise the reconstructed assumptions for this worked
example.

They do not constitute a mandatory framework taxonomy.

---

## 4. Validity conditions

CR.4 requires assumptions to remain connected to conditions under which they
can continue to support trustworthiness-related decisions.

For this worked example:

### TAIOT-A01

Remains applicable while governance, lifecycle-management, maintenance, and
change-management mechanisms remain capable of addressing relevant platform
change.

### TAIOT-A02

Remains applicable while hosted projects continue to operate in relation to
the relevant platform-level governance, responsibilities, and policies.

### TAIOT-A03

Remains applicable while regulatory, policy, authoritative, and operating
conditions remain materially compatible with the existing interpretation.

### TAIOT-A04

Remains applicable while monitoring, validation, feedback, and review
mechanisms continue to provide relevant evidence during platform operation.

Making these conditions explicit allows later evidence to be related back to
the contextual records from which trustworthiness-related decisions are
derived.

---

## 5. Evidence sources

TrustAIoT documents multiple mechanisms capable of providing evidence relevant
to the validity of these assumptions.

| Assumption ID | Evidence / signal | Documentary source | Review condition | Responsible role |
|---|---|---|---|---|
| TAIOT-A01 | Platform incidents, maintenance events, change-management evidence, or lifecycle-management failure | Platform operation, maintenance, and change-management mechanisms | Evidence materially challenges continued lifecycle-management capability | Platform / governance actor |
| TAIOT-A02 | Project review, governance deviation, or changed project conditions | Platform and project governance mechanisms | Evidence materially challenges the relationship between platform requirements and project-level enactment | Platform / project actor |
| TAIOT-A03 | Regulatory, policy, or authoritative-guidance change | Regulatory and policy-review mechanisms | Evidence materially affects the existing regulatory or governance interpretation | Governance / compliance actor |
| TAIOT-A04 | Missing, degraded, inconsistent, or contradictory monitoring, validation, or feedback evidence | Monitoring, validation, and feedback mechanisms | Evidence materially affects the availability or reliability of continued observation | Operational / governance actor |

These evidence sources are documented characteristics of the TrustAIoT case.

Their relationship with assumption review is reconstructed retrospectively.

---

## 6. Relationship to CR.6 — Lifecycle Anchoring

Several assumptions have explicit lifecycle dependencies.

- `TAIOT-A01` depends on governance, maintenance, update, and change-management
  mechanisms remaining available during platform evolution.
- `TAIOT-A02` depends on the continued relationship between platform-level
  governance and project-level lifecycle enactment.
- `TAIOT-A03` depends on mechanisms capable of incorporating relevant
  regulatory or policy change.
- `TAIOT-A04` depends on monitoring, validation, feedback, and review
  mechanisms remaining connected to identifiable lifecycle activities.

These dependencies support the paper-supported reconstruction of
**CR.6 — Lifecycle Anchoring**.

The relation is:

**CR.4 assumption and validity condition  
→ CR.6 lifecycle dependency  
→ subsequent Functional Refinement  
→ Process Instantiation**

CR.6 identifies lifecycle dependencies and anchoring conditions. It does not
perform the final TrustAIoT-specific mapping.

---

## 7. Relationship to FR.4 — Iterative Feedback Integration

TrustAIoT provides documented monitoring, validation, and user-feedback
mechanisms capable of producing evidence relevant to existing assumptions.

The paper-supported FR.4 relationship can therefore be represented as:

**monitoring / validation / user evidence  
→ assessment against an existing CR.4 assumption or engineering record  
→ reconsideration where justified**

Examples include:

- Monitoring evidence challenging `TAIOT-A01`
- Project or governance evidence challenging `TAIOT-A02`
- Policy evidence challenging `TAIOT-A03`
- Monitoring or feedback degradation challenging `TAIOT-A04`

The resulting assessment and feedback structure is represented in greater
detail in `feedback-log.md`.

---

## 8. Relationship to FR.6 — Continuity Enforcement

The assumptions also expose conditions relevant to continuity during platform
evolution.

For example:

- Governance and lifecycle-management capability must remain available.
- Platform-level requirements must continue to reach relevant project-level
  activities.
- Regulatory and policy changes must remain capable of propagation.
- Monitoring and feedback mechanisms must remain available during continued
  operation.

These conditions contribute to the paper-supported reconstruction of
**FR.6 — Continuity Enforcement**.

The corresponding continuity requirements and process-specific enactments are
represented through `engineering-representation.md`, `monitoring-plan.md`, and
`traceability-matrix.csv`.

---

## 9. Conditional relationship to CR.5

Where evidence materially invalidates a CR.4 assumption, a prospective
framework application could invoke:

**CR.5 — Context Revision Trigger**

The generic relation is:

**triggering evidence  
→ review of the affected CR.4 assumption  
→ retain / update / reconsider  
→ subsequent Functional Refinement where required**

### Illustrative revision record

- Revision record ID:
- Assumption ID:
- Triggering evidence:
- Validity condition affected:
- Responsible role(s):
- Revision decision:
- Decision rationale:
- Updated assumption, where applicable:
- Downstream Engineering Representation(s) potentially affected:
- Related feedback record:

This structure demonstrates the framework's revision path.

It does **not** establish CR.5 as an additional rule reconstructed for the
TrustAIoT case.

---

## 10. Relationship to Process Instantiation

The original TrustAIoT material documents process-specific mechanisms through
which the requirements associated with these assumptions can be enacted.

Representative mechanisms include:

- BPMN lifecycle activities
- Governance activities
- Testing and validation
- Continuous monitoring
- User-feedback mechanisms
- Maintenance
- Change management
- Platform updates
- Policy adaptation

The relationship is:

**CR.4 assumption  
→ validity condition  
→ FR.4 / FR.6 requirement where applicable  
→ Process Instantiation  
→ documented TrustAIoT lifecycle or operational mechanism**

This separation prevents concrete TrustAIoT mechanisms from being treated as
direct CR.4 outputs.

---

## 11. Revision history

| Version | Date | Assumption / record affected | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|---|
| 0.2.0 | Retrospective reconstruction | Initial worked example | Alignment with revised Lifecycle Refinement Framework and associated analytical evaluation | Assumptions represented through explicit CR.4 validity conditions; CR.5 retained only as a conditional framework path | Repository authors |

---

## 12. Verification and evidence

The paper-supported CR.4 reconstruction is grounded in documented:

- Stakeholder requirements
- Regulatory requirements
- Strategic objectives
- Governance conditions
- Lifecycle-management mechanisms
- Continuous monitoring
- Testing and validation
- User feedback
- Maintenance
- Change management
- Platform updates
- Policy adaptation

Verification means that each reconstructed assumption can be related to:

1. Documentary TrustAIoT evidence
2. An explicit validity condition
3. Evidence capable of challenging that validity condition
4. Relevant lifecycle or functional relationships where applicable

It does not mean that CR.4 was prospectively executed during the original
TrustAIoT project.

---

## 13. Analytical boundary

For TrustAIoT, the associated article supports:

### Contextual Refinement
- **CR.4 — Assumption Documentation**
- **CR.6 — Lifecycle Anchoring**

### Functional Refinement
- **FR.4 — Iterative Feedback Integration**
- **FR.6 — Continuity Enforcement**

### Assessment criteria
- **P1**
- **P2**
- **P3**

This file directly represents the paper-supported **CR.4** reconstruction.

Its references to CR.5 describe a conditional framework relation and do not
extend the canonical case-level rule reconstruction.

---

## 14. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: TrustAIoT
- Repository version: `0.2.0`
- Status: Paper-supported illustrative worked example
- Original project record: No
- Paper-supported CR.4 reconstruction: Yes
- Paper-supported CR.5 reconstruction: No

---

## Notes

This log represents one of the principal paper-supported Contextual Refinement
artefacts for the TrustAIoT case.

Its primary relationship is:

**documented contextual condition  
→ CR.4 assumption  
→ explicit validity condition  
→ later evidence through FR.4  
→ continuity or subsequent review through FR.6 where required**

Where evidence invalidates the contextual assumption, CR.5 provides a
conditional framework path for contextual reconsideration.

The authoritative TrustAIoT analytical boundary remains:

**CR.4 / CR.6  
→ FR.4 / FR.6  
→ documented Process Instantiation  
→ P1 / P2 / P3**
