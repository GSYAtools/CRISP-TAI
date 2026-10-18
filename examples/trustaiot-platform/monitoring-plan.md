# Monitoring Plan — TrustAIoT Worked Example

This document is an **illustrative retrospective completion** of the
`monitoring-plan.md` template using documentary evidence from the TrustAIoT
case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

This worked artefact primarily illustrates:

- **FR.6 — Continuity Enforcement**
- **FR.4 — Iterative Feedback Integration**

It also shows how operational evidence may provide input to **FR.3 —
Operational Adjustment** or **CR.5 — Context Revision Trigger** where the
documented conditions for those rules are met.

---

## 1. Monitoring record

- Monitoring plan ID: `TAIOT-MON-01`
- System or component: TrustAIoT platform
- Operational environment: Long-lived AIoT platform with heterogeneous
  components, multiple actors, and evolving operational and governance
  conditions
- Responsible monitoring role(s): Reconstructed operational, platform, and
  governance actors
- Accountable role: Relevant platform-level governance authority
- Related context record: `TAIOT-CTX-01`
- Related Engineering Representation: `TAIOT-ER02`
- Related Process Instantiation: `TAIOT-PI02`
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Monitoring scope

The TrustAIoT case documents monitoring, testing and validation, user
feedback, maintenance, change management, and policy adaptation during
continued platform operation.

These mechanisms provide evidence for retrospectively representing the
following monitoring scope:

| Monitoring item ID | Trustworthiness concern | Element monitored | Element type | Related representation / contextual record | Reason for monitoring |
|---|---|---|---|---|---|
| TAIOT-M01 | Monitoring and continuity | Continued availability of trustworthiness-related monitoring and review mechanisms | Engineering Representation / operational condition | TAIOT-ER02 | Determine whether relevant monitoring and review obligations remain active during platform evolution |
| TAIOT-M02 | Lifecycle governance | Continued operation of maintenance, update, and change-management mechanisms | Operational / lifecycle condition | TAIOT-ER02; TAIOT-A01 | Detect conditions that may affect lifecycle continuity or existing governance decisions |
| TAIOT-M03 | Contextual adaptation | Evidence potentially affecting existing contextual assumptions or governance interpretations | Contextual condition | TAIOT-ER03; TAIOT-A03; TAIOT-A04 | Identify evidence that may require contextual review |
| TAIOT-M04 | Stakeholder feedback | User or stakeholder evidence relevant to existing trustworthiness-related decisions | Feedback condition | TAIOT-ER03; TAIOT-CTX-01 | Preserve a route from stakeholder evidence to review and revision where required |

---

## 3. Monitoring evidence and signals

The retrospective example does not impose universal metrics or thresholds.
It records the types of evidence documented in the TrustAIoT material.

| Monitoring item ID | Evidence / signal | Source | Collection or review condition | Responsible role | Evidence record |
|---|---|---|---|---|---|
| TAIOT-M01 | Monitoring, testing, or validation evidence relevant to existing requirements or controls | Continuous monitoring; testing and validation mechanisms | According to the documented operational or review mechanism | Operational / platform actor | TAIOT-EV01 |
| TAIOT-M02 | Maintenance, update, incident, or change-management evidence | Maintenance and change-management mechanisms | Material event affecting continued operation or existing lifecycle mechanisms | Platform / lifecycle owner | TAIOT-EV02 |
| TAIOT-M03 | Regulatory, policy, governance, or operational change | Governance and policy-review mechanisms | Material change potentially affecting an existing contextual interpretation | Governance / compliance actor | TAIOT-EV03 |
| TAIOT-M04 | User or stakeholder feedback | Documented feedback mechanisms | Relevant feedback concerning existing trustworthiness expectations or platform operation | Relevant platform / governance actor | TAIOT-EV04 |

These signals provide evidence for review. They do not automatically determine
whether the system is trustworthy or whether revision is required.

---

## 4. Continuity requirements

This section retrospectively represents the continuity obligations associated
with `TAIOT-ER02`.

| Element ID | Element requiring continuity | Owner | Monitoring obligation | Review obligation | Update condition | Continuity evidence |
|---|---|---|---|---|---|---|
| TAIOT-CONT01 | Trustworthiness-related monitoring mechanisms | Operational / platform actor | Maintain relevant monitoring during continued operation | Review evidence when relevant conditions occur | Material platform, system, or monitoring change | Monitoring records |
| TAIOT-CONT02 | User and stakeholder feedback mechanisms | Relevant platform / governance actor | Preserve channels capable of providing relevant feedback | Review material feedback affecting existing decisions | Material stakeholder or use-context change | Feedback records |
| TAIOT-CONT03 | Maintenance and update mechanisms | Platform / lifecycle owner | Preserve maintenance and update capability | Review effects of material updates on existing requirements and controls | Maintenance or update affecting relevant system conditions | Maintenance / update records |
| TAIOT-CONT04 | Change-management and policy-adaptation mechanisms | Governance / platform owner | Maintain mechanisms for propagating relevant changes | Review when contextual or governance evidence requires adaptation | Regulatory, policy, organisational, or operational change | Change-management / policy-adaptation records |

These continuity requirements illustrate **FR.6 — Continuity Enforcement**.

---

## 5. Evidence review

When relevant evidence is obtained, it should be assessed against the existing
contextual interpretations and Engineering Representations.

### Illustrative review structure

- Evidence record ID:
- Monitoring item ID:
- Evidence observed:
- Existing contextual interpretation affected:
- Existing assumption affected:
- Existing Engineering Representation affected:
- Responsible reviewer(s):
- Assessment:
  - No relevant deviation
  - Engineering review required
  - Potential contextual change
  - Assumption potentially invalidated
  - Requirement or control potentially unmet
- Rationale:
- Follow-up required:

The documented TrustAIoT monitoring, validation, feedback, and change-
management mechanisms provide the evidential basis for this retrospective
review structure.

---

## 6. Feedback integration

Where evidence is relevant to an existing contextual interpretation or
Engineering Representation, **FR.4 — Iterative Feedback Integration** can be
represented as:

**Operational / evaluation / stakeholder evidence  
→ assessment against existing contextual decisions and Engineering
Representations  
→ contextual reconsideration where required  
→ engineering re-refinement where required**

For this worked example:

- Related feedback record: `feedback-log.md`
- Potentially affected contextual record: `TAIOT-CTX-01`
- Potentially affected assumptions: `TAIOT-A01` to `TAIOT-A04`
- Potentially affected Engineering Representations:
  `TAIOT-ER01` to `TAIOT-ER03`

Where evidence challenges an assumption, constraint, priority, or governance
interpretation, **CR.5 — Context Revision Trigger** determines whether the
affected contextual element is retained, updated, or reconsidered.

---

## 7. Operational adjustment

Where evidence indicates that an operational adjustment is required, the
required response should first be represented as a new or revised Engineering
Representation.

### Illustrative FR.3 record

- Triggering evidence:
- Existing Engineering Representation affected:
- Required operational adjustment:
- New or revised Engineering Representation:
- Responsible role:
- Supporting rationale:
- Related `engineering-representation.md` record:
- Related traceability record:

This illustrates **FR.3 — Operational Adjustment**.

FR.3 does not itself execute a maintenance action, configuration change,
policy change, or other operational intervention. It represents the required
engineering adjustment before its subsequent process-specific enactment.

No specific FR.3 execution is claimed here unless supported by the documentary
evidence for the corresponding TrustAIoT event.

---

## 8. Escalation and decision process

The TrustAIoT material documents governance, feedback, change-management, and
policy-adaptation mechanisms through which relevant evidence can be reviewed.

For this retrospective example:

- Review authority: Relevant reconstructed governance or platform actor
- Escalation basis: Material evidence affecting an existing contextual or
  engineering decision
- Decision authority: Depends on the responsibility and accountability
  boundary represented in `responsibility-map.csv`
- Required documentation: Evidence, affected contextual decision or
  Engineering Representation, review outcome, and any resulting revision

Related worked artefacts:

- `feedback-log.md`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`

---

## 9. Process-specific monitoring instantiation

The monitoring and continuity requirement represented by `TAIOT-ER02` can be
retrospectively mapped to documented TrustAIoT mechanisms.

- Engineering Representation ID: `TAIOT-ER02`
- Instantiation ID: `TAIOT-PI02`
- Framework instantiation: CRISP-TAI
- Target process: CRISP-DM
- Target lifecycle location: Continuous Deployment & Monitoring
- Documented process-specific mechanisms:
  - Continuous monitoring
  - User-feedback mechanisms
  - Maintenance and update procedures
  - Change-management mechanisms
- Operational ownership: Reconstructed platform, operational, and governance
  actors
- Evidence produced: Monitoring, feedback, maintenance, update, and
  change-management records
- Traceability record: `TAIOT-T02`

This is a **retrospective Process Instantiation**. It does not imply that
`TAIOT-ER02` was explicitly formulated before the original TrustAIoT
mechanisms were developed.

---

## 10. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: TrustAIoT
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This monitoring plan represents documented TrustAIoT evidence using the
current CRISP-TAI monitoring and continuity structure.

Its purpose is to illustrate the relationship:

**Engineering Representation  
→ Process Instantiation  
→ operational evidence  
→ FR.4 assessment  
→ CR.5 where contextual reconsideration is required  
→ subsequent Functional Refinement and re-instantiation where necessary**

It does not define universal monitoring metrics, thresholds, or frequencies,
and it does not claim prospective execution of the Lifecycle Refinement
Framework in the original TrustAIoT project.
