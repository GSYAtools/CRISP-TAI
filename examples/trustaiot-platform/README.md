# Worked Example — TrustAIoT

This directory provides an **illustrative worked example** showing how the
reusable CRISP-TAI repository templates can be populated retrospectively using
documentary evidence from the TrustAIoT case examined in the associated
research article.

The example is based on material documented in:

*TrustAIoT: A framework for building trustworthy AIoT platforms*.

It represents that material using the **v0.2.0 CRISP-TAI artefact structure**.

This example does **not** imply that the Lifecycle Refinement Framework or
CRISP-TAI was prospectively applied during the original development of
TrustAIoT. The completed artefacts are retrospective representations intended
to illustrate how the current templates can be used.

---

## Example scope

TrustAIoT concerns a long-lived AI-enabled Internet of Things platform
supporting multiple projects and stakeholders.

Relevant characteristics documented in the case include:

- Edge–fog–cloud architectural organisation
- Heterogeneous devices and AI-enabled components
- Multiple organisational and governance actors
- Stakeholder requirements
- Regulatory and strategic constraints
- BPMN lifecycle activities
- Defined process inputs and outputs
- Testing and validation
- Continuous monitoring
- User feedback
- Change-management and maintenance processes
- Policy adaptation during platform evolution

Within the analytical evaluation reported in the associated article, this
evidence supports reconstruction of:

- **CR.4 — Assumption Documentation**
- **CR.6 — Lifecycle Anchoring**
- **FR.4 — Iterative Feedback Integration**
- **FR.6 — Continuity Enforcement**

The case provides analytical evidence for:

- **P1 — Lifecycle Anchoring**
- **P2 — Coordinated Contextual and Functional Refinement**
- **P3 — Continuity and Iterative Feedback**

P4 — Cross-Domain Adaptability is assessed through comparison of the three
retrospective applications rather than through TrustAIoT alone.

---

## Paper-supported reconstruction

The principal analytical structure for this case is:

**Documented contextual assumptions and lifecycle dependencies  
→ CR.4 / CR.6  
→ FR.4 / FR.6  
→ documented Process Instantiation  
→ P1 / P2 / P3**

TrustAIoT provides particularly rich lifecycle evidence because the original
material documents not only contextual and governance conditions but also
monitoring, feedback, maintenance, change management, and policy adaptation.

This allows the retrospective analysis to examine both lifecycle anchoring and
the preservation and revision of trustworthiness-related obligations during
continued platform operation.

---

## How to interpret the files in this directory

The files in this directory are **completed examples of the reusable
templates** provided under `/templates`.

They should be read as retrospective or illustrative representations of
documented case evidence, not as original TrustAIoT project records.

Two categories of worked artefact should be distinguished.

### Paper-supported reconstruction

The following repository artefacts directly represent functions reconstructed
in the associated article:

- `assumption-log.md` — CR.4
- lifecycle-anchoring information represented across the worked artefacts —
  CR.6
- `monitoring-plan.md` and `feedback-log.md` — FR.4 and FR.6

### Supporting repository representations

Other templates are used to make the overall reconstruction inspectable,
including:

- `context-description.md`
- `responsibility-map.csv`
- `principle-prioritisation.md`
- `engineering-representation.md`
- `traceability-matrix.csv`

Their inclusion does **not** imply that additional CR or FR rules are
independently reconstructed for TrustAIoT in the associated article.

Template availability must not be interpreted as rule coverage.

---

## Contextual Refinement worked artefacts

### `context-description.md`

Provides structured contextual information derived from stakeholder
requirements, regulations, strategic objectives, governance conditions, and
the operational characteristics documented in TrustAIoT.

This information supports the paper-reconstructed CR.4 assumptions and CR.6
lifecycle dependencies.

The existence of this context description does not by itself imply independent
reconstruction of CR.1.

### `responsibility-map.csv`

Illustrates how documented governance and operational responsibilities can be
represented using the reusable responsibility template.

This is a supporting repository representation and does not imply independent
paper-supported reconstruction of CR.2.

### `principle-prioritisation.md`

Illustrates how trustworthiness concerns or contextual priorities documented
in TrustAIoT can be represented using the reusable prioritisation template.

Its inclusion does not imply independent paper-supported reconstruction of
CR.3.

### `assumption-log.md`

Represents the paper-supported reconstruction of
**CR.4 — Assumption Documentation**.

It makes explicit contextual assumptions and validity conditions derived from
documented:

- Stakeholder requirements
- Regulations
- Strategic objectives
- Governance conditions
- Operational conditions

Where later evidence challenges such an assumption, the repository can also
illustrate a conditional relationship with CR.5.

That conditional relationship does not make CR.5 an additional rule
reconstructed for TrustAIoT in the associated article.

---

## Lifecycle anchoring

TrustAIoT provides paper-supported evidence for
**CR.6 — Lifecycle Anchoring**.

The original material documents identifiable lifecycle activities and
locations through:

- BPMN lifecycle activities
- Process inputs and outputs
- Testing and validation
- Deployment and operation
- Continuous monitoring
- Maintenance
- Change management
- Policy adaptation

These elements allow trustworthiness-related requirements to be related to
identifiable lifecycle locations.

CR.6 constrains where subsequent enactment must occur.

The final mapping to TrustAIoT-specific activities or mechanisms belongs to
**Process Instantiation**, not to CR.6 itself.

---

## Functional Refinement worked artefacts

### `engineering-representation.md`

Provides a supporting representation of the process-independent engineering
requirements reconstructed from the documented TrustAIoT evidence.

This artefact helps distinguish:

**required engineering capability**

from:

**TrustAIoT-specific lifecycle or operational mechanism**.

Its use does not imply that FR.1 is independently reconstructed as a
case-level rule in the analytical evaluation reported in the associated
article.

### `traceability-matrix.csv`

Provides the principal inspectable mapping across:

**contextual record  
→ Engineering Representation  
→ lifecycle anchoring  
→ Process Instantiation  
→ documented TrustAIoT lifecycle artefact or operational mechanism**

The matrix supports repository traceability.

Its use does not by itself imply independent reconstruction of FR.2 or other
rules represented by fields in the reusable schema.

### `monitoring-plan.md`

Represents documented monitoring and continuity evidence associated with the
paper-supported reconstruction of:

- **FR.4 — Iterative Feedback Integration**
- **FR.6 — Continuity Enforcement**

Relevant original evidence includes:

- Continuous monitoring
- Testing and validation results
- Maintenance
- Continued operation
- Platform updates

The artefact distinguishes technical or operational evidence from the
refinement decisions that may follow from it.

### `feedback-log.md`

Represents the paper-supported feedback relationship associated with
**FR.4 — Iterative Feedback Integration** and its connection with continued
trustworthiness-related obligations represented through FR.6.

Relevant original evidence includes:

- Monitoring results
- Validation evidence
- User feedback
- Change management
- Maintenance
- Policy adaptation

Where such evidence challenges an existing contextual assumption, a
prospective refinement path may involve CR.5.

This conditional path does not extend the canonical TrustAIoT reconstruction
beyond CR.4, CR.6, FR.4, and FR.6.

---

## Documented Process Instantiation

The original TrustAIoT material provides identifiable process-specific
mechanisms through which the reconstructed contextual and functional
requirements can be retrospectively mapped.

Representative evidence includes:

- BPMN lifecycle activities
- Defined process inputs and outputs
- Architectural components and module specifications
- Testing and validation activities
- Continuous monitoring mechanisms
- User-feedback mechanisms
- Change-management procedures
- Maintenance and update procedures
- Policy-adaptation mechanisms

These elements are treated as **documented Process Instantiation evidence**.

They are not presented as artefacts prospectively generated by CRISP-TAI.

---

## Relationship to P1 — Lifecycle Anchoring

TrustAIoT supports P1 through the documented relationship between reconstructed
trustworthiness-related requirements and identifiable lifecycle activities and
mechanisms.

The relevant relation is:

**CR.6 anchoring condition  
→ process-independent requirement  
→ Process Instantiation  
→ documented TrustAIoT lifecycle activity or mechanism**

This is the principal lifecycle-anchoring evidence contributed by the case.

---

## Relationship to P2 — Coordinated Contextual and Functional Refinement

TrustAIoT supports P2 because contextual assumptions and lifecycle conditions
can be connected to functional requirements concerning feedback and
continuity.

Representative relationships include:

**CR.4 contextual assumption  
→ later monitoring / validation / user evidence  
→ FR.4 feedback relation**

and:

**CR.6 lifecycle dependency  
→ FR.6 continuity requirement  
→ documented lifecycle enactment**

These relations remain analytically distinct from their final process-specific
instantiation.

---

## Relationship to P3 — Continuity and Iterative Feedback

TrustAIoT provides the strongest evidence among the three retrospective
applications for P3.

The original material documents:

- Continuous monitoring
- Testing and validation results
- User feedback
- Maintenance
- Change management
- Platform updates
- Policy adaptation

These mechanisms provide evidence that trustworthiness-related information and
obligations can persist during continued operation and that later evidence can
inform subsequent review and change.

The reconstructed relation is:

**operational / validation / user evidence  
→ FR.4 feedback integration  
→ review or re-refinement where required  
→ FR.6 continuity of relevant obligations  
→ updated Process Instantiation where required**

---

## Canonical retrospective application record

The methodological reconstruction of this case is documented separately in:

`/logs/trustaiot-retrospective-application.md`

That record defines the canonical analytical boundary for TrustAIoT:

- CR reconstruction:
  - **CR.4**
  - **CR.6**
- FR reconstruction:
  - **FR.4**
  - **FR.6**
- Assessment criteria:
  - **P1**
  - **P2**
  - **P3**

Where an example-level template contains additional fields or illustrative
relationships, the canonical retrospective application record and the
associated research article determine which rules and assessment criteria are
actually supported by the analytical evaluation.

---

## Relationship to the original TrustAIoT material

The original TrustAIoT material remains the evidential source for the
retrospective reconstruction.

The completed templates in this directory:

- Do not replace the original architectural or process descriptions
- Do not constitute original TrustAIoT project documentation
- Do not demonstrate prospective execution of CRISP-TAI
- Do not constitute independent empirical validation
- Do not imply reconstruction of every CR or FR rule represented by the
  reusable template structure
- Do provide an illustrative and inspectable representation of how documented
  contextual, lifecycle, monitoring, feedback, maintenance, and
  policy-adaptation evidence can be structured using the current CRISP-TAI
  artefacts

---

## Purpose of the worked example

This example is intended primarily to illustrate:

1. Explicit representation of contextual assumptions through CR.4
2. Lifecycle anchoring through CR.6
3. Iterative evidence integration through FR.4
4. Continuity of trustworthiness-related obligations through FR.6
5. Separation between process-independent refinement and TrustAIoT-specific
   Process Instantiation
6. Traceability across contextual records, Engineering Representations,
   lifecycle activities, monitoring evidence, feedback, and subsequent change
7. Use of supporting repository templates without converting template
   availability into unsupported rule-coverage claims

It should therefore be used as an **illustrative worked example**, not as a
prescriptive reference implementation or as evidence that CRISP-TAI was
prospectively executed during the original TrustAIoT development.
