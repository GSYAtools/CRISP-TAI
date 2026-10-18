# Context Description

This template supports the documentation of **contextual interpretations**
produced through Contextual Refinement (CR) when applying the Lifecycle
Refinement Framework through CRISP-TAI.

It is intended to make the organisational, regulatory, social, and operational
context of a trustworthiness concern explicit and traceable. It may be created
during initial refinement or updated whenever material contextual changes or
new evidence require reconsideration.

This template primarily supports:

- **CR.1 — Context Interpretation**
- **CR.3 — Principle Prioritisation**
- **CR.4 — Assumption Documentation**
- **CR.5 — Context Revision Trigger**

Dedicated templates such as `responsibility-map.csv`,
`principle-prioritisation.md`, and `assumption-log.md` may be used where more
detailed records are required.

---

## 1. Refinement record

Identify the refinement activity to which this contextual interpretation
belongs.

- Record ID:
- Trustworthiness concern or principle:
- Trigger for contextual interpretation or revision:
- Responsible role(s):
- Supporting stakeholders:
- Date created:
- Last revision date:
- Related record(s), if applicable:

---

## 2. System overview

Provide a concise description of the AI system and the context relevant to the
trustworthiness concern.

- System name:
- High-level purpose:
- Intended users and beneficiaries:
- Affected stakeholders:
- Decision or action supported by the system:
- Intended use:
- Relevant foreseeable use or contextual variation:
- Deployment environment:

---

## 3. Organisational context

Describe the organisational factors relevant to the trustworthiness concern.

- Owning organisation(s):
- Participating teams or units:
- External partners or third parties:
- Existing governance structures:
- Relevant organisational policies or constraints:
- Relevant responsibility or accountability boundaries:

Where detailed responsibility allocation is required, use
`responsibility-map.csv` in support of **CR.2**.

---

## 4. Legal and regulatory context

Identify legal or regulatory factors relevant to the contextual
interpretation.

- Applicable regulation or legal requirement:
- Jurisdiction(s):
- Relevant obligations or constraints:
- Known regulatory uncertainty:
- Interpretation adopted for this refinement:
- Source or evidence supporting the interpretation:

This template records the contextual interpretation of applicable requirements;
it does not constitute a compliance determination or legal certification.

---

## 5. Social and ethical context

Describe relevant social, ethical, or stakeholder-related factors.

- Affected groups or stakeholders:
- Expected benefits:
- Potential harms or adverse effects:
- Ethical concerns relevant to the use context:
- Power asymmetries or dependency relationships:
- Stakeholder expectations or constraints:

---

## 6. Operational context

Describe operational conditions that influence the contextual interpretation.

- Data sources and providers:
- Relevant data characteristics or limitations:
- Model or AI component characteristics:
- Level of autonomy and human involvement:
- Integration with other systems:
- Expected operational lifetime:
- Deployment conditions:
- Monitoring and maintenance constraints:
- Other relevant operational dependencies:

---

## 7. Contextual interpretation

Summarise the contextual meaning assigned to the trustworthiness concern after
considering the organisational, regulatory, social, and operational factors
above.

- Trustworthiness concern:
- Applicable contextual constraints:
- Relevant expectations:
- Affected stakeholders or roles:
- Contextual interpretation:
- Supporting rationale:
- Supporting source(s) or evidence:

This section represents the principal documented output of **CR.1**.

---

## 8. Trustworthiness priorities and trade-offs

Where multiple trustworthiness objectives interact or impose competing
requirements, record the relevant prioritisation or trade-off.

| Principle / concern | Contextual priority | Constraint or competing concern | Rationale | Responsible actor |
|---|---|---|---|---|
| | | | | |

Where a more detailed prioritisation decision is required, use
`principle-prioritisation.md` in support of **CR.3**.

---

## 9. Contextual assumptions

Explicitly identify assumptions on which the contextual interpretation or
related trustworthiness decisions depend.

| Assumption | Validity condition | Affected decision / interpretation | Evidence or rationale |
|---|---|---|---|
| | | | |

Where assumptions require continued management, use `assumption-log.md` in
support of **CR.4**.

---

## 10. Revision conditions

Specify conditions or evidence that should trigger reconsideration of the
current contextual interpretation.

Examples may include:

- Regulatory or policy changes
- Changes in intended use
- Changes in deployment context
- New data sources or material changes in data characteristics
- Changes in affected stakeholders
- Monitoring or evaluation evidence
- Operational incidents or unexpected behaviour
- Invalidated assumptions
- Stakeholder feedback

Record the applicable conditions:

| Revision condition | Affected contextual element | Evidence source | Responsible role |
|---|---|---|---|
| | | | |

When a revision condition occurs, apply **CR.5 — Context Revision Trigger** to
determine whether the contextual interpretation must be retained, updated, or
reconsidered.

---

## 11. Context revision record

Complete this section when the contextual interpretation is reviewed following
a revision trigger.

- Triggering condition or evidence:
- Date of review:
- Responsible role(s):
- Affected assumption(s), constraint(s), priority(ies), or interpretation(s):
- Revision decision:
  - Retain
  - Update
  - Reconsider through a new refinement cycle
- Rationale:
- Resulting contextual interpretation:
- Downstream engineering representation(s) potentially affected:
- Related feedback or traceability record(s):

---

## 12. Verification and evidence

Identify the evidence retained to make the contextual interpretation
inspectable and traceable.

- Contextual source(s):
- Stakeholder information:
- Regulatory or organisational source(s):
- Supporting operational evidence:
- Related responsibility record:
- Related prioritisation record:
- Related assumption record:
- Related revision record:
- Other supporting evidence:

---

## 13. Versioning and ownership

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

This document is a **living contextual refinement artefact**. Its purpose is
not to freeze the system context or prescribe a lifecycle-specific decision,
but to make contextual interpretations, assumptions, priorities, revision
conditions, and supporting evidence explicit and traceable.

The resulting contextual decisions may subsequently provide input to
Functional Refinement (FR), through which process-independent engineering
representations are derived before their process-specific instantiation within
CRISP-TAI.
