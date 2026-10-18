# Assumption Log

This template records **contextual assumptions** on which trustworthiness-related
interpretations or decisions depend.

It primarily supports:

- **CR.4 — Assumption Documentation**
- **CR.5 — Context Revision Trigger**

Its purpose is to make assumptions, their validity conditions, dependencies,
revision triggers, and subsequent revision decisions explicit, traceable, and
revisable over time.

Assumptions may concern organisational, regulatory, social, technical, data,
human, or operational conditions. They should be reviewed whenever relevant
evidence or a predefined revision condition challenges their continued validity.

---

## 1. Log information

- System or component:
- Log ID:
- Document owner:
- Accountable role:
- Date created:
- Last revision date:
- Related context record:

---

## 2. Assumption register

Each assumption should be documented as a discrete entry.

| Assumption ID | Assumption | Type | Validity condition | Rationale / evidence | Affected contextual decision or interpretation | Responsible role | Revision trigger | Status |
|---|---|---|---|---|---|---|---|---|
| EXAMPLE-A01 | Training data remains sufficiently representative of the intended operating population | Data | Population and acquisition conditions remain materially consistent with those considered during refinement | Available historical and contextual evidence | Contextual interpretation concerning data suitability | Data Owner | Material data or population drift | Active |
| EXAMPLE-A02 | Human operators remain able to review system outputs under the intended operating conditions | Human / Organisational | Workload, expertise, and operational procedures remain compatible with the expected oversight function | Current operating procedure and stakeholder information | Contextual interpretation concerning human oversight | Operations Lead | Material change in workload, staffing, or operating procedure | Active |
| EXAMPLE-A03 | The adopted regulatory interpretation remains applicable | Legal / Regulatory | Applicable regulation and authoritative guidance remain materially unchanged | Current regulatory source and documented interpretation | Contextual decision based on the applicable legal constraint | Governance / Legal Owner | Regulatory or authoritative guidance change | Active |

The example rows are illustrative. Replace or remove them when using the
template.

---

## 3. Assumption types

Indicative categories include:

- **Organisational** — governance structures, responsibilities, available
  resources, organisational practices
- **Legal / regulatory** — applicability or interpretation of legal and
  regulatory requirements
- **Social / stakeholder** — stakeholder behaviour, expectations, affected
  groups, or use conditions
- **Data-related** — quality, stability, representativeness, provenance, or
  availability
- **Technical** — relevant system, model, infrastructure, or integration
  conditions
- **Human** — user behaviour, expertise, oversight capacity, or interaction
  conditions
- **Operational** — deployment conditions, monitoring capability, maintenance,
  or incident-response assumptions

This categorisation is indicative and may be adapted to the relevant context.

---

## 4. Assumption review

When an assumption is reviewed, record the evidence against its documented
validity condition.

- Assumption ID:
- Review date:
- Triggering condition or evidence:
- Responsible role(s):
- Current validity condition:
- Evidence considered:
- Assessment:
  - Remains valid
  - Potentially invalid
  - Invalid
  - Uncertain
- Affected contextual decision(s) or interpretation(s):
- Related engineering representation(s), where available:
- Supporting evidence or record:

A review does not automatically imply contextual revision. Where the evidence
challenges an assumption or another contextual element, apply **CR.5 —
Context Revision Trigger** to determine whether reconsideration is required.

---

## 5. Context revision decision

Where CR.5 is activated, document the resulting decision.

- Revision record ID:
- Assumption ID:
- Triggering condition or evidence:
- Affected contextual interpretation:
- Other affected contextual elements:
- Responsible role(s):
- Revision decision:
  - Retain
  - Update
  - Reconsider through a new refinement cycle
- Decision rationale:
- Updated assumption or validity condition, where applicable:
- Updated contextual interpretation, where applicable:
- Downstream engineering representation(s) potentially affected:
- Subsequent refinement required:
- Related feedback or traceability record:

This record preserves the relationship between the evidence that triggered
review, the affected contextual interpretation, and any subsequent refinement
cycle.

---

## 6. Monitoring and evidence sources

For assumptions requiring continued observation, identify how relevant evidence
will be obtained.

| Assumption ID | Evidence / signal | Source | Review condition | Responsible role | Related monitoring requirement |
|---|---|---|---|---|---|
| | | | | | |

Monitoring requirements represented through Functional Refinement may be linked
here where applicable. The assumption itself remains a contextual refinement
artefact.

---

## 7. Revision history

| Version | Date | Assumption / record affected | Trigger / reason | Change | Responsible role |
|---|---|---|---|---|---|
| | | | | | |

---

## Notes

This log is a **living contextual refinement artefact**. Its role is not to
eliminate uncertainty, but to make assumptions and the conditions under which
they remain valid explicit and inspectable.

Explicit assumption management supports:

- Traceability between contextual assumptions and trustworthiness decisions
- Identification of conditions requiring contextual reconsideration
- Connection between operational evidence and contextual revision
- Systematic propagation of revised contextual decisions into subsequent
  Functional Refinement where required

An assumption is not itself a process-specific lifecycle artefact. Where a
revision changes the engineering response required from the system, the updated
contextual decision should be propagated through Functional Refinement before
the resulting engineering representation is subsequently instantiated within
CRISP-TAI.
