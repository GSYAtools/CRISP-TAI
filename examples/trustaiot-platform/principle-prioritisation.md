# Principle Prioritisation — TrustAIoT Worked Example

This document is an **illustrative retrospective completion** of the
`principle-prioritisation.md` template using documentary evidence from the
TrustAIoT case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

This worked artefact illustrates how trustworthiness concerns identified in
the original case can be represented through **CR.3 — Principle
Prioritisation** where the documentary evidence supports an explicit
context-dependent prioritisation or trade-off.

---

## 1. Prioritisation record

- Record ID: `TAIOT-PRIO-01`
- System or component: TrustAIoT platform
- Trigger for prioritisation: Multiple trustworthiness concerns must be
  considered within a long-lived, heterogeneous, and governed AIoT platform
- Decision context: Platform-level governance and continued operation
- Responsible role(s): Reconstructed governance actors
- Accountable role: Platform-level governance authority
- Related context record: `TAIOT-CTX-01`
- Related responsibility record: `TAIOT-R01` to `TAIOT-R05`
- Artefact status: Retrospective worked-example representation

---

## 2. Applicable trustworthiness principles or concerns

The TrustAIoT material identifies multiple trustworthiness concerns relevant
to platform governance and evolution.

| Principle / concern | Why applicable | Contextual constraint or expectation | Relevant actor(s) |
|---|---|---|---|
| Lawfulness | Platform operation is subject to regulatory and governance requirements | Trustworthiness-related decisions must remain aligned with applicable requirements as the platform evolves | Platform Owner; Compliance Team |
| Robustness | AIoT operation involves heterogeneous devices and technical dependencies | Relevant controls and monitoring must remain effective under changing operational conditions | Platform Architecture Team; Project Teams |
| Explainability / transparency | Human-centred governance and oversight require understandable system behaviour and decisions | Explanation-related expectations must be reflected in relevant engineering and governance mechanisms | Platform Owner; Platform Architecture Team; Project Teams |
| Sustainability | Long-lived AIoT operation introduces lifecycle and resource considerations | Platform evolution and device lifecycle management may require continued consideration of long-term impacts | Platform Owner; Platform Architecture Team |
| Accountability | Multiple platform and project actors participate in governance and operation | Responsibility and accountability boundaries must remain explicit across organisational and technical layers | Platform Owner; Compliance Team; Project Teams |

These concerns are reconstructed from the documented case material. Their
presence does not by itself establish a formal priority ordering.

---

## 3. Tensions and dependencies

The retrospective reconstruction identifies dependencies among the concerns
above, but the available repository evidence does not support assigning a
universal numerical or ordinal ranking to all of them.

Representative dependencies include:

| Tension / dependency | Concerns involved | Contextual consideration | Retrospective interpretation |
|---|---|---|---|
| Regulatory alignment and platform evolution | Lawfulness; accountability | Governance and policy requirements may evolve during long-term operation | Regulatory and governance constraints must remain revisable |
| Human-centred operation and technical complexity | Explainability / transparency; robustness | Heterogeneous AIoT components may complicate explanation and oversight | Explanation-related requirements must be represented without ignoring operational constraints |
| Long-term platform evolution | Sustainability; robustness; accountability | Maintenance, device evolution, and organisational change affect continued operation | Continuity and revision mechanisms are required |

These dependencies are illustrative reconstructions and should not be
interpreted as quantified trade-offs established by the original project.

---

## 4. Prioritisation or trade-off decision

The documentary evidence used in this retrospective example supports the
importance of the identified concerns but does **not** provide sufficient basis
for reconstructing a complete `High / Medium / Low` ordering across all
principles.

Accordingly, this worked example records a **contextual prioritisation
constraint** rather than inventing a numerical or ordinal ranking:

> Trustworthiness-related governance decisions must preserve applicable
> regulatory and accountability constraints while maintaining the monitoring,
> feedback, and continuity mechanisms required for long-lived AIoT operation.

Where explanation, robustness, sustainability, or other concerns interact,
their relative treatment should be justified against the applicable context
rather than inferred from this retrospective example.

---

## 5. Decision rationale

The reconstructed prioritisation constraint is supported by:

- Regulatory and governance inputs documented in TrustAIoT
- Platform-level responsibility structures
- Long-lived and evolving operation
- Continuous monitoring and feedback
- Maintenance and change-management mechanisms
- Policy adaptation during platform evolution

### Alternatives not reconstructed

The available evidence does not justify retrospectively assigning fixed
priority levels to every trustworthiness concern.

For this reason, the worked example does not reproduce the `High / Medium`
ranking used in the earlier repository version.

---

## 6. Resulting contextual decision

- Affected concerns: Lawfulness, accountability, robustness,
  explainability/transparency, sustainability, and related platform-level
  trustworthiness concerns
- Adopted contextual decision: Applicable regulatory and governance
  constraints must be preserved while relevant operational trustworthiness
  mechanisms remain monitorable, revisable, and continuous
- Applicable constraints: Regulatory, organisational, architectural,
  operational, and lifecycle conditions
- Responsible actors: Reconstructed platform governance and technical actors
- Related assumptions: `TAIOT-A01`, `TAIOT-A02`, `TAIOT-A03`
- Related context record: `TAIOT-CTX-01`

Where this contextual decision requires engineering operationalisation, the
required response is represented separately through
`engineering-representation.md`.

---

## 7. Review and revision conditions

| Revision condition | Affected decision | Evidence source | Responsible role |
|---|---|---|---|
| Material regulatory or policy change | Regulatory and governance prioritisation constraints | Regulatory / policy evidence | Compliance / governance actor |
| Material platform or architectural change | Operational trustworthiness priorities or dependencies | Platform change evidence | Platform Architecture Team |
| Monitoring or validation evidence challenging existing expectations | Relevant contextual decision or assumption | Monitoring / validation evidence | Platform and governance actors |
| Material change in stakeholder expectations | Human-centred or governance concerns | User / stakeholder feedback | Relevant governance actor |
| Maintenance or lifecycle change affecting continuity | Long-term governance and operational constraints | Maintenance / change-management evidence | Platform Owner |

Where such evidence challenges the existing contextual decision,
**CR.5 — Context Revision Trigger** should determine whether it is retained,
updated, or reconsidered.

---

## 8. Verification and evidence

Supporting documentary evidence includes:

- Stakeholder requirements
- Regulatory and governance inputs
- Strategic objectives
- Platform governance structures
- Monitoring and validation mechanisms
- User-feedback mechanisms
- Maintenance and change-management procedures
- Policy-adaptation mechanisms

Related worked artefacts:

- `context-description.md`
- `responsibility-map.csv`
- `assumption-log.md`
- `engineering-representation.md`
- `traceability-matrix.csv`

---

## 9. Versioning and ownership

- Artefact type: Retrospectively completed CRISP-TAI v0.2.0 template
- Source case: TrustAIoT
- Repository version: `0.2.0`
- Status: Illustrative worked example
- Original project record: No

---

## Notes

This artefact demonstrates an important property of retrospective application:
**absence of documentary evidence should not be replaced by inferred
prioritisation**.

The original TrustAIoT material supports identification of relevant
trustworthiness concerns and contextual dependencies. This worked example
therefore records only the prioritisation or constraint that can be supported
by that evidence.

Any subsequent Engineering Representation derived from this contextual
decision remains process-independent until mapped through Process
Instantiation.
