# Feedback Log — TrustAIoT Worked Example

This document is an **illustrative retrospective completion** of the
`feedback-log.md` template using documentary evidence from the TrustAIoT case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

This worked artefact primarily illustrates:

- **FR.4 — Iterative Feedback Integration**
- **CR.5 — Context Revision Trigger**, where operational, evaluation, policy,
  or stakeholder evidence challenges an existing contextual interpretation

It also illustrates how resulting contextual revisions may require subsequent
Functional Refinement and updated Process Instantiation.

---

## 1. Log information

- Feedback log ID: `TAIOT-FEEDBACK-01`
- System or component: TrustAIoT platform
- Related context record: `TAIOT-CTX-01`
- Related monitoring plan: `TAIOT-MON-01`
- Related Engineering Representations:
  - `TAIOT-ER01`
  - `TAIOT-ER02`
  - `TAIOT-ER03`
- Responsible roles: Reconstructed operational, platform, governance,
  compliance, and stakeholder actors
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Evidence sources

The TrustAIoT material documents several mechanisms through which evidence can
become available during continued platform operation.

Relevant sources include:

- Continuous monitoring
- Testing and validation
- User feedback
- Maintenance and update activities
- Change-management mechanisms
- Regulatory or policy changes
- Governance review
- Policy-adaptation mechanisms

These sources provide evidence for review. They do not automatically determine
that contextual or engineering revision is required.

---

## 3. Feedback entries

The entries below illustrate how documented TrustAIoT evidence sources can be
represented using the current feedback structure.

| Feedback ID | Evidence source | Evidence / observation | Trustworthiness concern | Trigger / collection condition | Related monitoring item | Responsible role | Status |
|---|---|---|---|---|---|---|---|
| TAIOT-F01 | Monitoring / validation | Evidence indicates that an existing monitoring, control, or lifecycle mechanism may no longer satisfy the conditions under which it was defined | Monitoring and continuity | Material monitoring or validation evidence | TAIOT-M01; TAIOT-M02 | Operational / platform actor | Under review |
| TAIOT-F02 | Regulatory / policy review | A material regulatory or policy change may affect an existing contextual governance interpretation | Contextual adaptation | Material regulatory or policy change | TAIOT-M03 | Governance / compliance actor | Under review |
| TAIOT-F03 | User / stakeholder feedback | Material feedback indicates that an existing trustworthiness-related expectation or mechanism may require review | Stakeholder expectations and governance | Relevant user or stakeholder feedback | TAIOT-M04 | Relevant platform / governance actor | Under review |
| TAIOT-F04 | Maintenance / change management | A platform update or maintenance event affects a mechanism associated with an existing Engineering Representation | Lifecycle continuity | Material maintenance, update, or platform change | TAIOT-M02 | Platform / lifecycle owner | Under review |

These entries are **illustrative retrospective representations** of the types
of evidence documented in TrustAIoT. They are not claimed to be verbatim
historical project records.

---

## 4. Assessment against existing refinement records

### TAIOT-F01 — Monitoring or validation evidence

- Existing contextual interpretation potentially affected: `TAIOT-CD02`
- Related assumptions: `TAIOT-A01`, `TAIOT-A04`
- Existing Engineering Representation: `TAIOT-ER02`
- Existing Process Instantiation: `TAIOT-PI02`
- Potential assessment:
  - No relevant deviation
  - Engineering review required
  - Monitoring or continuity requirement potentially unmet
  - Contextual assumption potentially invalidated
- Responsible reviewers: Relevant operational, platform, and governance actors

### TAIOT-F02 — Regulatory or policy evidence

- Existing contextual interpretation potentially affected: `TAIOT-CD03`
- Related assumption: `TAIOT-A03`
- Existing Engineering Representation: `TAIOT-ER03`
- Existing Process Instantiation: `TAIOT-PI03`
- Potential assessment:
  - Existing interpretation remains applicable
  - Contextual governance interpretation requires update
  - Downstream Engineering Representation requires subsequent revision
- Responsible reviewers: Relevant governance and compliance actors

### TAIOT-F03 — User or stakeholder evidence

- Existing contextual interpretation potentially affected: `TAIOT-CD02` or
  `TAIOT-CD03`, depending on the evidence
- Related assumption: `TAIOT-A04`
- Existing Engineering Representation potentially affected:
  `TAIOT-ER02` or `TAIOT-ER03`
- Potential assessment:
  - No relevant deviation
  - Engineering review required
  - Contextual expectations require reconsideration
- Responsible reviewers: Relevant platform, governance, and stakeholder-facing
  actors

### TAIOT-F04 — Maintenance or change-management evidence

- Existing contextual interpretation potentially affected: `TAIOT-CD01` or
  `TAIOT-CD02`
- Related assumptions: `TAIOT-A01`, `TAIOT-A02`
- Existing Engineering Representation potentially affected:
  `TAIOT-ER01` or `TAIOT-ER02`
- Existing Process Instantiation potentially affected:
  `TAIOT-PI01` or `TAIOT-PI02`
- Potential assessment:
  - Existing enactment remains adequate
  - Engineering Representation requires review
  - Process-specific re-instantiation is required
- Responsible reviewers: Relevant platform, lifecycle, and governance actors

These assessments illustrate **FR.4 — Iterative Feedback Integration** by
relating evidence to existing contextual and engineering records before any
revision is performed.

---

## 5. Context revision decision

Where evidence challenges an assumption, constraint, priority, or governance
interpretation, **CR.5 — Context Revision Trigger** determines whether the
affected contextual element should be retained, updated, or reconsidered.

| Feedback ID | Contextual element potentially affected | CR.5 invoked when | Possible revision decision | Related assumption |
|---|---|---|---|---|
| TAIOT-F01 | TAIOT-CD02 | Monitoring or validation evidence challenges an existing contextual assumption | Retain / Update / Reconsider | TAIOT-A01; TAIOT-A04 |
| TAIOT-F02 | TAIOT-CD03 | Regulatory or policy evidence materially affects the existing interpretation | Retain / Update / Reconsider | TAIOT-A03 |
| TAIOT-F03 | TAIOT-CD02 or TAIOT-CD03 | Material stakeholder evidence challenges an existing contextual expectation | Retain / Update / Reconsider | TAIOT-A04 |
| TAIOT-F04 | TAIOT-CD01 or TAIOT-CD02 | Platform or lifecycle change invalidates an existing contextual condition | Retain / Update / Reconsider | TAIOT-A01; TAIOT-A02 |

This table does not claim that all four retrospective feedback types
historically activated CR.5. It records the condition under which CR.5 would
be applicable to the reconstructed evidence.

---

## 6. Engineering update decision

Where the evidence or resulting contextual revision requires an engineering
change, the affected Engineering Representation should be reviewed through
subsequent Functional Refinement.

| Feedback ID | Existing Engineering Representation | Potential engineering response | Applicable FR function | Responsible role |
|---|---|---|---|---|
| TAIOT-F01 | TAIOT-ER02 | Retain or revise monitoring and continuity requirements | FR.3; FR.4; FR.6 as applicable | Operational / platform owner |
| TAIOT-F02 | TAIOT-ER03 | Revise contextual-revision requirement where the governance context has materially changed | FR.4 followed by subsequent FR where required | Governance / compliance owner |
| TAIOT-F03 | TAIOT-ER02 or TAIOT-ER03 | Review monitoring, feedback, or revision requirements affected by stakeholder evidence | FR.4; subsequent FR as required | Relevant platform / governance owner |
| TAIOT-F04 | TAIOT-ER01 or TAIOT-ER02 | Review governance, lifecycle, monitoring, or continuity requirements affected by platform change | FR.3; FR.4; FR.6 as applicable | Platform / lifecycle owner |

Where **FR.3 — Operational Adjustment** is applicable, it represents the
required adjustment as a new or revised Engineering Representation. It does
not itself execute the operational change.

---

## 7. Process-specific propagation

Where an Engineering Representation is revised, its existing process-specific
instantiation may also require review.

| Feedback ID | Engineering Representation | Existing instantiation | Potential propagation | Traceability record |
|---|---|---|---|---|
| TAIOT-F01 | TAIOT-ER02 | TAIOT-PI02 | Review or update monitoring, maintenance, feedback, or change-management enactment | TAIOT-T02 |
| TAIOT-F02 | TAIOT-ER03 | TAIOT-PI03 | Review or update governance review, policy-adaptation, or revision mechanisms | TAIOT-T03 |
| TAIOT-F03 | TAIOT-ER02 / TAIOT-ER03 | TAIOT-PI02 / TAIOT-PI03 | Update the affected operational or revision mechanism where required | TAIOT-T02 / TAIOT-T03 |
| TAIOT-F04 | TAIOT-ER01 / TAIOT-ER02 | TAIOT-PI01 / TAIOT-PI02 | Re-instantiate the affected governance, lifecycle, or continuity mechanism where required | TAIOT-T01 / TAIOT-T02 |

This propagation belongs to subsequent **Process Instantiation**. It is not
part of FR.4 itself.

---

## 8. Evidence-to-decision trace

| Feedback ID | Evidence | Affected contextual element | Affected Engineering Representation | CR.5 decision | Engineering update | Instantiation update |
|---|---|---|---|---|---|---|
| TAIOT-F01 | Monitoring / validation evidence | TAIOT-CD02 | TAIOT-ER02 | Conditional on evidence | Conditional on assessment | TAIOT-PI02 if required |
| TAIOT-F02 | Regulatory / policy change | TAIOT-CD03 | TAIOT-ER03 | Conditional on material contextual impact | Conditional on CR.5 outcome | TAIOT-PI03 if required |
| TAIOT-F03 | User / stakeholder feedback | TAIOT-CD02 / TAIOT-CD03 | TAIOT-ER02 / TAIOT-ER03 | Conditional on contextual impact | Conditional on assessment | TAIOT-PI02 / TAIOT-PI03 if required |
| TAIOT-F04 | Maintenance / platform change | TAIOT-CD01 / TAIOT-CD02 | TAIOT-ER01 / TAIOT-ER02 | Conditional on invalidated contextual conditions | Conditional on assessment | TAIOT-PI01 / TAIOT-PI02 if required |

The use of `Conditional` is deliberate. The documentary evidence supports the
existence of feedback and adaptation mechanisms but does not justify claiming
that every evidence type resulted in a specific historical revision decision.

---

## 9. Closure and follow-up

A reconstructed feedback item should be considered closed only when the
available evidence allows the relevant review path to be represented.

For an actual prospective application, closure should document:

- Whether contextual revision was required
- Whether the relevant Engineering Representation was retained or revised
- Whether process-specific re-instantiation was required
- Whether follow-up monitoring remains necessary
- The responsible role
- Supporting closure evidence

The retrospective TrustAIoT example does not invent closure decisions where
the original documentary evidence does not provide them.

---

## 10. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: TrustAIoT
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This worked feedback log illustrates the evidence-to-decision chain:

**Operational / evaluation / stakeholder evidence  
→ FR.4 assessment  
→ CR.5 where contextual reconsideration is required  
→ updated contextual decision  
→ subsequent Functional Refinement  
→ revised Engineering Representation  
→ updated Process Instantiation where required**

The example deliberately distinguishes between **documented evidence
mechanisms** and **specific historical revision decisions**.

Where the TrustAIoT material supports only the former, this worked example
records the revision path as conditional rather than inventing an outcome.
