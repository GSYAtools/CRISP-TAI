# Principle Prioritisation

This template records how applicable **trustworthiness principles or concerns
are prioritised, balanced, or traded off** within a specific organisational,
regulatory, social, and operational context.

It primarily supports **CR.3 — Principle Prioritisation** and is closely
related to:

- `context-description.md`
- `responsibility-map.csv`
- `assumption-log.md`

The purpose of this artefact is **not** to define universal priorities, but to
make context-dependent prioritisation and trade-off decisions explicit,
traceable, justified, and revisable.

---

## 1. Prioritisation record

Identify the decision for which explicit prioritisation is required.

- Record ID:
- System or component:
- Trigger for prioritisation:
- Decision context:
- Applicable trustworthiness principles or concerns:
- Responsible role(s):
- Accountable role:
- Supporting stakeholders:
- Date of decision:
- Related context record:
- Related responsibility record:

Typical triggers include competing trustworthiness objectives or a contextual
condition requiring an explicit priority, balance, or acceptable trade-off.

---

## 2. Applicable trustworthiness principles or concerns

Identify the trustworthiness principles or concerns relevant to the decision.

The applicable principles may originate from the trustworthiness taxonomy,
regulatory or organisational requirements, domain-specific governance
knowledge, or other structured trustworthiness sources used by the project.

| Principle / concern | Why applicable | Contextual constraint or expectation | Responsible / affected role |
|---|---|---|---|
| | | | |

This section identifies the concerns considered. It does not yet constitute the
prioritisation decision.

---

## 3. Tensions and dependencies

Identify any competing requirements, dependencies, or tensions among the
applicable trustworthiness principles or concerns.

| Tension ID | Principles / concerns involved | Nature of tension | Relevant contextual constraints | Affected stakeholders |
|---|---|---|---|---|
| | | | | |

Examples may include:

- Fairness vs. predictive performance
- Transparency vs. confidentiality or intellectual-property constraints
- Privacy vs. data utility
- Robustness vs. computational or operational constraints

Examples are illustrative only; the relevant tensions depend on the specific
context.

---

## 4. Prioritisation or trade-off decision

For each identified tension or prioritisation requirement, document the
context-specific decision.

| Decision ID | Principles / concerns | Priority, balance, or trade-off adopted | Applicable constraints | Rationale | Accountable actor |
|---|---|---|---|---|---|
| | | | | | |

The decision may establish:

- A priority among competing concerns
- A balance between concerns
- An acceptable trade-off
- A constraint that cannot be overridden
- A condition under which the decision must be reconsidered

The selected decision should be justified by the contextual information
available at the time of refinement.

---

## 5. Decision rationale

Provide any additional reasoning required to understand and reconstruct the
prioritisation decision.

Consider, where applicable:

- Organisational objectives
- Regulatory or legal constraints
- Operational conditions
- Stakeholder expectations
- Responsibility and accountability boundaries
- Documented assumptions
- Available evidence
- Consequences of alternative prioritisation choices

- Rationale:
- Alternatives considered:
- Reason alternatives were not selected:
- Supporting evidence or source(s):
- Related assumption(s):

This section should provide sufficient information for the decision to be
subsequently reviewed and independently inspected.

---

## 6. Resulting contextual decision

Summarise the output of CR.3.

- Affected principles or concerns:
- Adopted priority, balance, or trade-off:
- Contextual rationale:
- Applicable constraints:
- Responsible actor(s):
- Accountable actor:
- Assumptions on which the decision depends:
- Revision conditions:
- Related contextual record(s):

Where the decision subsequently requires engineering operationalisation, this
contextual output should be provided as input to Functional Refinement before
any process-specific lifecycle mapping is performed.

---

## 7. Review and revision conditions

Specify conditions or evidence that may invalidate or require reconsideration
of the prioritisation decision.

Examples include:

- Regulatory or policy changes
- Changes in organisational objectives
- Changes in intended use or deployment context
- Material changes in data or system behaviour
- Monitoring or evaluation evidence
- Operational incidents
- Stakeholder feedback
- Invalidated assumptions

| Revision condition | Affected decision | Evidence source | Responsible role |
|---|---|---|---|
| | | | |

Link relevant assumptions to `assumption-log.md`.

When a revision condition occurs, **CR.5 — Context Revision Trigger** should be
used to determine whether the prioritisation must be retained, updated, or
reconsidered.

---

## 8. Verification and evidence

Record the evidence retained to make the prioritisation decision traceable and
inspectable.

- Related context record:
- Related responsibility record:
- Related assumption record:
- Supporting organisational source(s):
- Supporting regulatory source(s):
- Stakeholder evidence:
- Other supporting evidence:
- Related subsequent engineering representation(s), where available:

---

## 9. Versioning and ownership

- Document owner:
- Accountable role:
- Current version:
- Date created:
- Last revision date:

### Revision history

| Version | Date | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|
| | | | | |

---

## Notes

This artefact is intentionally **context-specific, process-independent, and
non-normative**.

Different systems, domains, organisations, or contextual conditions may
legitimately lead to different prioritisation outcomes. The value of this
template lies in making the adopted decision, its constraints, rationale,
responsibilities, assumptions, and revision conditions explicit rather than in
enforcing uniform priorities across projects.

The prioritisation decision is a **contextual refinement output**. Any
engineering representation required to operationalise it should subsequently be
derived through Functional Refinement and only then mapped to lifecycle-specific
elements during Process Instantiation.
