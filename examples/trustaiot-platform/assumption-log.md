# Assumption Log — TrustAIoT Worked Example

This document is an **illustrative retrospective completion** of the
`assumption-log.md` template using documentary evidence from the TrustAIoT
case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

This worked artefact illustrates:

- **CR.4 — Assumption Documentation**
- **CR.5 — Context Revision Trigger**, where documented evidence challenges
  an existing contextual assumption or interpretation

---

## 1. Log information

- System or component: TrustAIoT platform
- Log ID: `TAIOT-ASSUMPTIONS-01`
- Related context record: `TAIOT-CTX-01`
- Related prioritisation record: `TAIOT-PRIO-01`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Assumption register

The assumptions below are retrospective representations of contextual
conditions supported by the documented TrustAIoT case material.

| Assumption ID | Assumption | Type | Validity condition | Rationale / evidence | Affected contextual decision or interpretation | Responsible role | Revision trigger | Status |
|---|---|---|---|---|---|---|---|---|
| TAIOT-A01 | Platform governance and lifecycle-management mechanisms remain capable of addressing relevant changes during continued operation | Organisational / Operational | Governance, maintenance, update, and change-management mechanisms remain active and applicable as the platform evolves | Documented lifecycle-management, maintenance, and change-management mechanisms | Trustworthiness-related governance and lifecycle decisions remain applicable during platform evolution | Platform Owner / relevant governance actor | Material platform change, incident, or failure of lifecycle-management mechanisms | Active |
| TAIOT-A02 | Platform-level trustworthiness requirements continue to be reflected in the operation and evolution of hosted projects | Organisational / Governance | Project-level operation remains connected to applicable platform governance, responsibilities, and policies | Documented relationship between platform governance, lifecycle activities, and project operation | Platform-level governance decisions can continue to inform project-level enactment | Platform and project actors | New project conditions, governance deviation, review finding, or material organisational change | Active |
| TAIOT-A03 | Existing regulatory and policy interpretations remain applicable until material evidence indicates otherwise | Legal / Regulatory | Relevant regulation, policy, authoritative guidance, and operating context remain materially compatible with the existing interpretation | Regulations, governance inputs, and policy-adaptation mechanisms documented in the case | Existing contextual governance constraints remain applicable | Relevant governance / compliance actor | Material regulatory, policy, or authoritative-guidance change | Active |
| TAIOT-A04 | Monitoring and feedback mechanisms remain available to provide evidence during continued operation | Operational | Monitoring, validation, feedback, and responsible review mechanisms remain operational and connected to governance or change-management processes | Documented continuous monitoring, testing and validation, user feedback, and change-management mechanisms | Contextual assumptions and engineering representations can be reconsidered when relevant evidence emerges | Relevant operational and governance actors | Loss or material degradation of monitoring, feedback, or review capability | Active |

---

## 3. Assumption types

The worked example uses the following contextual categories:

- **Organisational / Governance** — platform and project responsibilities,
  governance structures, and policy relationships
- **Legal / Regulatory** — continued applicability of regulatory or policy
  interpretations
- **Operational** — monitoring, maintenance, feedback, and continued platform
  operation
- **Lifecycle-related** — conditions required for trustworthiness-related
  obligations to remain active during system evolution

These categories describe the assumptions reconstructed from the case; they do
not constitute a mandatory taxonomy.

---

## 4. Assumption review

When documentary or operational evidence challenges an assumption, the
assumption should be reviewed against its documented validity condition.

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

The TrustAIoT case documents monitoring, validation, feedback, maintenance,
change management, and policy adaptation as mechanisms capable of providing
such evidence.

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
during the original TrustAIoT project. The structure illustrates how the
documented monitoring and adaptation mechanisms can be represented using the
current CRISP-TAI artefacts.

---

## 6. Monitoring and evidence sources

| Assumption ID | Evidence / signal | Source | Review condition | Responsible role | Related monitoring requirement |
|---|---|---|---|---|---|
| TAIOT-A01 | Platform incidents, maintenance events, or change-management evidence | Platform operation and maintenance mechanisms | Material event affecting lifecycle-management capability | Platform / governance actor | `TAIOT-ER02` |
| TAIOT-A02 | Governance or project-review evidence | Platform and project governance mechanisms | Material deviation from applicable platform requirements | Platform / project actor | `TAIOT-ER02` |
| TAIOT-A03 | Regulatory or policy change | Regulatory and policy-review mechanisms | Material change affecting the existing interpretation | Governance / compliance actor | `TAIOT-ER03` |
| TAIOT-A04 | Missing, degraded, or contradictory monitoring / feedback evidence | Monitoring, validation, and feedback mechanisms | Evidence suggests that continued observation is no longer reliable | Operational / governance actor | `TAIOT-ER02` |

The related Engineering Representation identifiers are completed in
`engineering-representation.md`.

---

## 7. Revision history

| Version | Date | Assumption / record affected | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|---|
| 0.2.0 | Retrospective reconstruction | Initial worked example | Alignment with revised Lifecycle Refinement Framework | Assumptions represented using CR.4 validity conditions and CR.5 revision structure | Repository authors |

---

## Notes

This log is a **retrospectively completed contextual-refinement artefact**.

The assumptions above are not presented as verbatim statements originally
recorded by the TrustAIoT project. They are structured reconstructions of
contextual conditions supported by the documentary evidence used in the
retrospective analysis.

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

Any downstream engineering response is represented separately as a
process-independent Engineering Representation before process-specific
instantiation.
