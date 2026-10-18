# Engineering Representation — TrustAIoT Worked Example

This document is a **supporting retrospective representation** using the
`engineering-representation.md` template and documentary evidence from the
TrustAIoT case.

It is not an original TrustAIoT project record and does not imply prospective
application of CRISP-TAI.

The analytical evaluation reported in the associated article reconstructs:

- **CR.4 — Assumption Documentation**
- **CR.6 — Lifecycle Anchoring**
- **FR.4 — Iterative Feedback Integration**
- **FR.6 — Continuity Enforcement**

It does **not** independently reconstruct
**FR.1 — Engineering Representation Derivation** for the TrustAIoT case.

Accordingly, this file uses process-independent Engineering Representations to
make the paper-supported CR.4 / CR.6 / FR.4 / FR.6 relationships inspectable
without extending the analytical rule coverage reported in the associated
article.

---

## 1. Representation record

- Record group ID: `TAIOT-ER`
- System or component: TrustAIoT platform
- Primary concerns:
  - Lifecycle governance
  - Lifecycle anchoring
  - Monitoring
  - Feedback
  - Continuity
  - Adaptation during platform evolution
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
- Related context record:
  - `TAIOT-CTX-01`
- Related assumption records:
  - `TAIOT-A01`
  - `TAIOT-A02`
  - `TAIOT-A03`
  - `TAIOT-A04`
- Artefact function: Supporting process-independent representation
- Artefact status: Retrospective worked-example representation
- Repository version: `0.2.0`

---

## 2. Paper-supported contextual basis

The Engineering Representations in this file organise requirements associated
with the paper-supported CR.4 and CR.6 reconstruction.

### CR.4 — Assumption Documentation

The relevant contextual assumptions concern:

- Continued availability of platform governance and lifecycle-management
  mechanisms
- Continued relationship between platform-level requirements and hosted
  projects
- Continued applicability of regulatory and policy interpretations
- Continued availability of monitoring, validation, feedback, and review
  mechanisms

These are represented through `TAIOT-A01` to `TAIOT-A04`.

### CR.6 — Lifecycle Anchoring

The documented TrustAIoT material identifies lifecycle dependencies involving:

- Governance activities
- Testing and validation
- Deployment and operation
- Continuous monitoring
- User feedback
- Maintenance
- Change management
- Platform updates
- Policy adaptation

These dependencies constrain where the relevant requirements must subsequently
be enacted.

CR.6 does not perform the final TrustAIoT-specific mapping.

---

## 3. Supporting Engineering Representations

| Representation ID | Representation type | Engineering Representation | Paper-supported function represented | Rationale |
|---|---|---|---|---|
| TAIOT-ER01 | Lifecycle governance and anchoring representation | Trustworthiness-related governance obligations shall remain relatable to identifiable responsibilities and lifecycle activities through which they can be enacted and reviewed during platform evolution | CR.6; supports P1 and P2 | Makes the lifecycle dependency explicit without prescribing the final TrustAIoT-specific activity or artefact |
| TAIOT-ER02 | Monitoring and feedback representation | Relevant monitoring, validation, and stakeholder-feedback evidence shall remain available for assessment against existing contextual assumptions and engineering records during continued platform operation | FR.4; supports P2 and P3 | Represents the evidence-to-review capability required for iterative feedback without prescribing a specific monitoring technology |
| TAIOT-ER03 | Continuity and adaptation representation | Trustworthiness-related monitoring, review, maintenance, responsibility, and update obligations shall remain active or be reconsidered when material platform, organisational, regulatory, or policy change occurs | FR.6; supports P2 and P3 | Represents continuity during platform evolution independently of the specific maintenance, change-management, or policy-adaptation mechanism |

These are **supporting process-independent Engineering Representations**.

Their use in this worked example does not imply that FR.1 is independently
reconstructed for TrustAIoT.

---

## 4. TAIOT-ER01 — Lifecycle governance and anchoring

- Representation type: Lifecycle governance and anchoring representation
- Paper-supported basis:
  - `CR.6 — Lifecycle Anchoring`
- Related assumptions:
  - `TAIOT-A01`
  - `TAIOT-A02`
  - `TAIOT-A03`
- Relevant concerns:
  - Governance
  - Accountability
  - Lifecycle integration
  - Regulatory and organisational dependencies
- Verification condition: Relevant trustworthiness-related obligations can be
  related to identifiable responsibilities and lifecycle activities in the
  documented TrustAIoT process
- Documentary basis:
  - BPMN lifecycle activities
  - Process inputs and outputs
  - Governance structures
  - Platform and project responsibilities
  - Testing and validation activities

The representation does not prescribe a specific BPMN activity or lifecycle
location.

Those mappings belong to Process Instantiation.

---

## 5. TAIOT-ER02 — Monitoring and feedback

- Representation type: Monitoring and feedback representation
- Paper-supported basis:
  - `FR.4 — Iterative Feedback Integration`
- Related assumptions:
  - `TAIOT-A01`
  - `TAIOT-A02`
  - `TAIOT-A04`
- Relevant concerns:
  - Monitoring
  - Validation
  - User feedback
  - Evidence review
- Verification condition: Relevant operational, validation, or stakeholder
  evidence can be related back to existing contextual assumptions or
  engineering records
- Documentary basis:
  - Continuous monitoring
  - Testing and validation results
  - User-feedback mechanisms
  - Governance and review mechanisms

The representation expresses the required evidence-to-review capability.

It does not itself determine whether a contextual or engineering revision is
required.

---

## 6. TAIOT-ER03 — Continuity and adaptation

- Representation type: Continuity and adaptation representation
- Paper-supported basis:
  - `FR.6 — Continuity Enforcement`
- Related assumptions:
  - `TAIOT-A01`
  - `TAIOT-A02`
  - `TAIOT-A03`
  - `TAIOT-A04`
- Relevant concerns:
  - Continued monitoring
  - Maintenance
  - Change management
  - Responsibility continuity
  - Platform updates
  - Policy adaptation
- Verification condition: Relevant trustworthiness-related obligations remain
  active or are explicitly reconsidered during material platform,
  organisational, regulatory, or policy change
- Documentary basis:
  - Maintenance procedures
  - Change-management mechanisms
  - Platform updates
  - Continuous monitoring
  - Policy-adaptation mechanisms

The representation expresses continuity requirements independently of the
specific TrustAIoT mechanisms used to enact them.

---

## 7. Relationship to FR.4 — Iterative Feedback Integration

`TAIOT-ER02` provides the principal supporting representation for the
paper-supported FR.4 reconstruction.

The documented relation is:

**monitoring / validation / user evidence  
→ assessment against existing contextual assumptions or engineering records  
→ reconsideration where justified**

Representative evidence includes:

- Continuous monitoring results
- Testing and validation evidence
- User feedback
- Governance or review evidence

Where evidence challenges a CR.4 assumption, contextual reconsideration may be
required.

A possible relationship with CR.5 remains conditional and does not add CR.5
to the canonical TrustAIoT rule reconstruction.

---

## 8. Relationship to FR.6 — Continuity Enforcement

`TAIOT-ER03` provides the principal supporting representation for the
paper-supported FR.6 reconstruction.

The documented TrustAIoT material supports continuity through:

- Continued monitoring
- Maintenance
- Change management
- Platform updates
- Responsibility mechanisms
- Policy adaptation

The reconstructed relation is:

**existing trustworthiness-related obligation  
→ continued operation or material change  
→ obligation remains active or is reconsidered  
→ updated Process Instantiation where required**

This is distinct from simply observing that the platform continues to operate.

FR.6 concerns continuity of the relevant trustworthiness-related obligations.

---

## 9. Relationship between FR.4 and FR.6

The two paper-supported Functional Refinement functions are complementary.

**FR.4** concerns how later evidence is integrated into existing contextual
and engineering records.

**FR.6** concerns whether relevant trustworthiness-related obligations remain
active or are reconsidered during continued operation and evolution.

In TrustAIoT, the relationship can be represented as:

**monitoring / validation / user evidence  
→ FR.4 assessment  
→ review or re-refinement where justified  
→ FR.6 continuity of relevant obligations  
→ Process Instantiation update where required**

This relation provides the principal paper-supported evidence for P3.

---

## 10. Documented Process Instantiation

The original TrustAIoT material documents process-specific mechanisms through
which the supporting Engineering Representations can be retrospectively
mapped.

| Representation ID | Instantiation ID | Documented lifecycle location or mechanism | Documented process-specific enactment |
|---|---|---|---|
| TAIOT-ER01 | TAIOT-PI01 | Governance and lifecycle activities | BPMN activities, governance procedures, process inputs and outputs, platform/project responsibility structures, testing and validation activities |
| TAIOT-ER02 | TAIOT-PI02 | Continued operation, monitoring, validation, and feedback | Continuous monitoring mechanisms, testing and validation results, user-feedback mechanisms, and review activities |
| TAIOT-ER03 | TAIOT-PI03 | Maintenance, change, and adaptation activities | Maintenance procedures, change-management mechanisms, platform updates, responsibility mechanisms, and policy adaptation |

These mappings are **retrospective Process Instantiations**.

The documented mechanisms are not themselves process-independent Engineering
Representations.

---

## 11. Relationship to P1 — Lifecycle Anchoring

`TAIOT-ER01` helps make the P1 relationship inspectable:

**CR.6 lifecycle dependency  
→ TAIOT-ER01  
→ TAIOT-PI01  
→ identifiable TrustAIoT lifecycle activity or mechanism**

P1 is supported by the ability to connect trustworthiness-related obligations
with documented lifecycle locations.

---

## 12. Relationship to P2 — Coordinated Contextual and Functional Refinement

The three supporting representations help expose the coordination between
contextual and functional refinement.

For example:

**TAIOT-A04 through CR.4  
→ monitoring / feedback evidence  
→ TAIOT-ER02 / FR.4**

and:

**CR.6 lifecycle dependency  
→ TAIOT-ER01  
→ TAIOT-ER03 / FR.6  
→ documented lifecycle enactment**

These relationships provide inspectable evidence for P2 without claiming
independent FR.1 reconstruction.

---

## 13. Relationship to P3 — Continuity and Iterative Feedback

`TAIOT-ER02` and `TAIOT-ER03` jointly expose the principal P3 relationship:

**monitoring / validation / user feedback  
→ FR.4  
→ review where justified  
→ FR.6  
→ maintenance / change management / policy adaptation  
→ continued or updated Process Instantiation**

TrustAIoT provides explicit documentary evidence for these mechanisms.

---

## 14. Conditional contextual revision

Where FR.4 evidence materially invalidates a contextual assumption represented
through CR.4, a prospective application could invoke:

**CR.5 — Context Revision Trigger**

The conditional relation is:

**evidence  
→ affected CR.4 assumption  
→ CR.5 where contextual reconsideration is justified  
→ subsequent Functional Refinement**

This does not establish CR.5 as an additional TrustAIoT reconstruction claim.

---

## 15. Revision conditions

| Evidence or change condition | Representation potentially affected | Documentary source |
|---|---|---|
| Material governance, organisational, or lifecycle change | TAIOT-ER01; TAIOT-ER03 | Governance / organisational / lifecycle evidence |
| Material change in monitoring, validation, or feedback capability | TAIOT-ER02; TAIOT-ER03 | Operational / validation / feedback evidence |
| Regulatory or policy change | TAIOT-ER01; TAIOT-ER03 | Regulatory / policy evidence |
| Maintenance or change-management failure | TAIOT-ER03 | Maintenance / change-management evidence |
| User or stakeholder evidence challenges an existing assumption | TAIOT-ER02; potentially TAIOT-ER03 | User / stakeholder feedback |

These conditions connect documented evidence with possible review.

They do not imply automatic revision.

---

## 16. Verification and evidence

The supporting Engineering Representations are grounded in documented:

- Stakeholder requirements
- Regulations and strategic objectives
- Governance structures
- BPMN lifecycle activities
- Process inputs and outputs
- Testing and validation
- Continuous monitoring
- User feedback
- Change-management procedures
- Maintenance and update procedures
- Policy-adaptation mechanisms

Verification in this worked example means that each representation can be
related to:

1. A paper-supported CR.4 or CR.6 contextual relationship, or a
   paper-supported FR.4 or FR.6 functional relationship
2. Documentary TrustAIoT evidence
3. A documented process-specific enactment

It does not mean that FR.1 was prospectively or retrospectively reconstructed
as an independent TrustAIoT case-level rule.

---

## 17. Analytical boundary

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

This engineering-representation artefact is a **supporting repository
representation**.

Its existence does not add:

- FR.1
- FR.2
- FR.3
- FR.5

to the paper-supported TrustAIoT reconstruction.

---

## 18. Versioning and ownership

- Artefact type: Supporting retrospective completion of a CRISP-TAI v0.2.0
  template
- Source case: TrustAIoT
- Repository version: `0.2.0`
- Status: Supporting worked-example representation
- Original project record: No
- Paper-supported FR.1 reconstruction: No
- Paper-supported FR.4 reconstruction: Yes
- Paper-supported FR.6 reconstruction: Yes

---

## Notes

This artefact uses Engineering Representations to make the TrustAIoT
refinement and instantiation chain inspectable without extending the rule
coverage reported in the associated article.

Its principal structure is:

**CR.4 assumptions + CR.6 lifecycle dependencies  
→ supporting process-independent representations  
→ FR.4 feedback integration + FR.6 continuity  
→ documented Process Instantiation  
→ P1 / P2 / P3**

The distinction between representation and enactment remains:

**TAIOT-ER01 / TAIOT-ER02 / TAIOT-ER03  
≠  
BPMN activities / monitoring mechanisms / maintenance procedures /
policy-adaptation mechanisms**

The latter are documented TrustAIoT-specific instantiations.
