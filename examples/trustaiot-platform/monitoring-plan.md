# Monitoring Plan — TrustAIoT Worked Example

This document is an **illustrative retrospective completion** of the
`monitoring-plan.md` template using documentary evidence from the TrustAIoT
case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

For the analytical evaluation reported in the associated article, this worked
artefact represents evidence supporting:

- **FR.4 — Iterative Feedback Integration**
- **FR.6 — Continuity Enforcement**

The monitoring, validation, feedback, maintenance, change-management, and
policy-adaptation mechanisms documented in TrustAIoT provide the evidential
basis for these reconstructed functions.

Where such evidence invalidates a contextual assumption, a prospective
framework application could invoke **CR.5 — Context Revision Trigger**.
CR.5 is not independently claimed as part of the TrustAIoT retrospective
reconstruction.

---

## 1. Monitoring record

- Monitoring plan ID: `TAIOT-MON-01`
- System or component: TrustAIoT platform
- Operational environment: Long-lived AIoT platform with heterogeneous
  components, multiple actors, and evolving operational and governance
  conditions
- Related context record:
  - `TAIOT-CTX-01`
- Related assumptions:
  - `TAIOT-A01`
  - `TAIOT-A02`
  - `TAIOT-A03`
  - `TAIOT-A04`
- Related Engineering Representations:
  - `TAIOT-ER02` — Monitoring and feedback representation
  - `TAIOT-ER03` — Continuity and adaptation representation
- Related Process Instantiations:
  - `TAIOT-PI02`
  - `TAIOT-PI03`
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

## 2. Documented monitoring scope

The TrustAIoT case documents monitoring, testing and validation, user
feedback, maintenance, change management, and policy adaptation during
continued platform operation.

These mechanisms provide evidence for representing the following monitoring
and continuity relations:

| Monitoring item ID | Trustworthiness concern | Element observed | Related representation | Reason for observation |
|---|---|---|---|---|
| TAIOT-M01 | Monitoring and validation | Operational, testing, or validation evidence relevant to existing trustworthiness-related records | TAIOT-ER02 | Provide evidence that can be assessed against existing contextual assumptions or engineering records |
| TAIOT-M02 | Stakeholder feedback | User or stakeholder evidence relevant to existing trustworthiness-related expectations | TAIOT-ER02 | Preserve a route from stakeholder evidence to review where justified |
| TAIOT-M03 | Lifecycle continuity | Continued availability of monitoring, maintenance, update, and change-management mechanisms | TAIOT-ER03 | Determine whether relevant trustworthiness-related obligations remain supported during platform evolution |
| TAIOT-M04 | Regulatory and policy adaptation | Regulatory, policy, governance, or organisational change | TAIOT-ER02; TAIOT-ER03 | Provide evidence for review and continued adaptation of affected obligations |

These relations are grounded in mechanisms documented in the original
TrustAIoT material.

---

## 3. Monitoring evidence and signals

The retrospective example does not impose universal metrics, thresholds, or
monitoring frequencies.

It records the types of evidence documented in TrustAIoT.

| Monitoring item ID | Evidence / signal | Source | Collection or review condition | Responsible role | Evidence record |
|---|---|---|---|---|---|
| TAIOT-M01 | Monitoring, testing, or validation evidence relevant to existing requirements or controls | Continuous monitoring; testing and validation mechanisms | According to the documented operational or review mechanism | Operational / platform actor | TAIOT-EV01 |
| TAIOT-M02 | User or stakeholder feedback | Documented feedback mechanisms | Relevant feedback concerning existing trustworthiness expectations or platform operation | Relevant platform / governance actor | TAIOT-EV02 |
| TAIOT-M03 | Maintenance, update, incident, or change-management evidence | Maintenance and change-management mechanisms | Material event affecting continued operation or an existing lifecycle mechanism | Platform / lifecycle owner | TAIOT-EV03 |
| TAIOT-M04 | Regulatory, policy, governance, or organisational change | Governance and policy-review mechanisms | Material change potentially affecting an existing contextual assumption or continuing obligation | Governance / compliance actor | TAIOT-EV04 |

These signals provide evidence for review.

They do not automatically determine whether a contextual assumption,
Engineering Representation, or process-specific mechanism must change.

---

## 4. FR.4 — Iterative Feedback Integration

TrustAIoT documents several evidence sources that can be related back to
existing contextual and engineering records.

The reconstructed FR.4 relation is:

**monitoring / validation / stakeholder evidence  
→ assessment against existing contextual assumptions or engineering records  
→ reconsideration where justified**

Relevant evidence includes:

- Continuous monitoring
- Testing and validation results
- User feedback
- Governance evidence
- Regulatory or policy evidence

For this worked example:

- Related assumptions:
  - `TAIOT-A01`
  - `TAIOT-A02`
  - `TAIOT-A03`
  - `TAIOT-A04`
- Principal supporting Engineering Representation:
  - `TAIOT-ER02`
- Related feedback artefact:
  - `feedback-log.md`

FR.4 integrates evidence into the refinement process.

It does not imply that every monitoring observation produces a revision.

---

## 5. Evidence review

Relevant evidence can be assessed against existing contextual assumptions and
supporting Engineering Representations.

### Review structure

- Evidence record ID:
- Monitoring item ID:
- Evidence observed:
- Existing assumption potentially affected:
- Existing Engineering Representation potentially affected:
- Responsible reviewer(s):
- Assessment:
  - Existing relation remains supported
  - Additional evidence is required
  - Assumption may require review
  - Engineering Representation may require review
  - Process Instantiation may require review
- Rationale:
- Follow-up required:

The documented TrustAIoT monitoring, validation, feedback, maintenance, and
change-management mechanisms provide the evidential basis for this
retrospective review relation.

---

## 6. Relationship to CR.4 assumptions

Monitoring and feedback evidence can be related to the validity conditions
represented through CR.4.

| Evidence item | Assumption potentially affected | Review relation |
|---|---|---|
| TAIOT-M01 | TAIOT-A01; TAIOT-A04 | Monitoring or validation evidence may challenge existing operational or evidence-related assumptions |
| TAIOT-M02 | TAIOT-A02; TAIOT-A04 | Stakeholder feedback may challenge platform/project or evidence-related assumptions |
| TAIOT-M03 | TAIOT-A01; TAIOT-A02; TAIOT-A04 | Maintenance or change evidence may challenge assumptions concerning lifecycle-management or continued operation |
| TAIOT-M04 | TAIOT-A01; TAIOT-A03 | Regulatory, policy, governance, or organisational change may challenge existing contextual assumptions |

This provides an inspectable relationship between the paper-supported CR.4 and
FR.4 reconstructions.

---

## 7. FR.6 — Continuity Enforcement

TrustAIoT provides documentary evidence that relevant trustworthiness-related
obligations must remain active or be reconsidered during continued platform
operation and evolution.

The principal supporting representation is:

`TAIOT-ER03 — Continuity and adaptation representation`

The reconstructed FR.6 relation is:

**existing trustworthiness-related obligation  
→ continued operation or material change  
→ obligation remains active or is explicitly reconsidered  
→ Process Instantiation remains valid or is updated where required**

This concerns continuity of trustworthiness-related obligations, not merely
continued technical operation.

---

## 8. Continuity requirements

| Element ID | Element requiring continuity | Owner | Continuity obligation | Review condition | Documented continuity evidence |
|---|---|---|---|---|---|
| TAIOT-CONT01 | Trustworthiness-related monitoring mechanisms | Operational / platform actor | Relevant monitoring remains available during continued operation | Material platform, system, or monitoring change | Continuous monitoring records |
| TAIOT-CONT02 | User and stakeholder feedback mechanisms | Relevant platform / governance actor | Relevant feedback channels remain available and connected to review | Material stakeholder or use-context change | Feedback mechanisms and records |
| TAIOT-CONT03 | Maintenance and update mechanisms | Platform / lifecycle owner | Maintenance and update capability remains available for relevant trustworthiness-related obligations | Maintenance or update affecting relevant system conditions | Maintenance and update procedures |
| TAIOT-CONT04 | Change-management and policy-adaptation mechanisms | Governance / platform owner | Relevant changes can be propagated through documented adaptation mechanisms | Regulatory, policy, organisational, or operational change | Change-management and policy-adaptation mechanisms |
| TAIOT-CONT05 | Relevant responsibility relationships | Platform / governance actors | Responsibility for continuing trustworthiness-related obligations remains identifiable during platform evolution | Material organisational or responsibility change | Governance and responsibility records |

These continuity requirements support the paper-reconstructed
**FR.6 — Continuity Enforcement**.

---

## 9. Relationship between FR.4 and FR.6

FR.4 and FR.6 interact without collapsing into a single function.

**FR.4** provides the evidence-integration relation:

**evidence  
→ assessment  
→ review where justified**

**FR.6** provides the continuity relation:

**existing obligation  
→ continued operation or change  
→ obligation remains active or is reconsidered**

For TrustAIoT, the combined relation can therefore be represented as:

**monitoring / validation / user evidence  
→ FR.4 assessment  
→ review or re-refinement where justified  
→ FR.6 continuity of affected obligations  
→ updated Process Instantiation where required**

This relationship provides the principal paper-supported evidence for P3.

---

## 10. Conditional relationship to CR.5

Where FR.4 evidence materially invalidates an assumption represented through
CR.4, a prospective framework application could invoke:

**CR.5 — Context Revision Trigger**

The conditional relation is:

**evidence  
→ affected CR.4 assumption  
→ CR.5 where contextual reconsideration is justified  
→ subsequent Functional Refinement**

CR.5 is therefore a possible framework path following evidence review.

It is **not** independently claimed as part of the TrustAIoT retrospective
rule reconstruction.

---

## 11. Engineering and operational review boundary

Where evidence indicates that an existing Engineering Representation or
process-specific mechanism may no longer be adequate, further review may be
required.

For example:

- `TAIOT-ER02` may require review if monitoring, validation, or feedback
  capability materially changes.
- `TAIOT-ER03` may require review if maintenance, change-management, update,
  responsibility, or policy-adaptation capability materially changes.

This monitoring plan does **not** claim independent reconstruction of:

- FR.1 — Engineering Representation Derivation
- FR.2 — Decision Traceability
- FR.3 — Operational Adjustment
- FR.5 — Shift-Left Integration

Any resulting engineering change would need to be represented through the
appropriate refinement and subsequent Process Instantiation.

---

## 12. Documented Process Instantiation

The monitoring and continuity representations can be retrospectively mapped
to documented TrustAIoT mechanisms.

### TAIOT-ER02 — Monitoring and feedback

- Instantiation ID: `TAIOT-PI02`
- Documented lifecycle locations:
  - Testing and validation
  - Continued operation
  - Monitoring
  - Feedback and review
- Documented mechanisms:
  - Continuous monitoring
  - Testing and validation results
  - User-feedback mechanisms
  - Review activities
- Traceability record:
  - `TAIOT-T02`

### TAIOT-ER03 — Continuity and adaptation

- Instantiation ID: `TAIOT-PI03`
- Documented lifecycle locations:
  - Maintenance
  - Change management
  - Platform updates
  - Policy adaptation
- Documented mechanisms:
  - Maintenance procedures
  - Change-management mechanisms
  - Platform-update mechanisms
  - Responsibility mechanisms
  - Policy-adaptation mechanisms
- Traceability record:
  - `TAIOT-T03`

These are **retrospective Process Instantiations**.

They do not imply prospective CRISP-TAI execution during the original
TrustAIoT project.

---

## 13. Relationship to assessment criteria

### P1 — Lifecycle Anchoring

The monitoring and continuity mechanisms are connected to identifiable
TrustAIoT lifecycle activities.

P1 is principally exposed through CR.6 and the documented Process
Instantiation relationships.

### P2 — Coordinated Contextual and Functional Refinement

CR.4 assumptions and CR.6 lifecycle dependencies can be connected to FR.4
evidence integration and FR.6 continuity requirements.

### P3 — Continuity and Iterative Feedback

This monitoring plan provides particularly direct evidence for P3 through the
documented relationship among:

- Monitoring
- Validation
- User feedback
- Maintenance
- Change management
- Policy adaptation

---

## 14. Verification and evidence

The paper-supported monitoring and continuity reconstruction is grounded in
documented:

- Continuous monitoring
- Testing and validation
- User feedback
- Maintenance
- Change management
- Platform updates
- Governance mechanisms
- Policy adaptation

Verification means that:

1. Relevant evidence sources can be identified.
2. Those sources can be related to existing contextual or engineering records.
3. Continuity obligations can be related to documented lifecycle mechanisms.
4. Process-specific enactments can be identified.

It does not mean that FR.4 or FR.6 were prospectively executed during the
original TrustAIoT project.

---

## 15. Analytical boundary

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

This monitoring plan directly represents evidence supporting FR.4 and FR.6.

It does not add CR.5, FR.1, FR.2, FR.3, or FR.5 to the canonical case-level
reconstruction.

---

## 16. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: TrustAIoT
- Repository version: `0.2.0`
- Status: Paper-supported illustrative worked example
- Original project record: No
- Paper-supported FR.4 reconstruction: Yes
- Paper-supported FR.6 reconstruction: Yes

---

## Notes

This monitoring plan represents documented TrustAIoT evidence using the
current CRISP-TAI monitoring and continuity structure.

Its paper-supported relationship is:

**CR.4 assumptions + CR.6 lifecycle dependencies  
→ FR.4 evidence integration + FR.6 continuity  
→ documented Process Instantiation  
→ P1 / P2 / P3**

Where evidence invalidates an existing contextual assumption, CR.5 remains a
conditional framework path rather than an additional case-level rule claim.

The artefact does not define universal monitoring metrics, thresholds, or
frequencies and does not claim prospective execution of the Lifecycle
Refinement Framework in the original TrustAIoT project.
