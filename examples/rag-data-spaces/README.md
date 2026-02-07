# Example — RAG in Federated Data Spaces

This example illustrates how **CRISP-TAI** can be instantiated in a real-world–motivated
scenario involving **Retrieval-Augmented Generation (RAG)** deployed over **federated Data Spaces (DSs)**.

The example is derived from the architectural and experimental study presented in  
*Guided and Federated RAG: Architectural Models for Trustworthy AI in Data Spaces* :contentReference[oaicite:2]{index=2},
and reinterprets that work from a **process and lifecycle perspective**, focusing on
trustworthiness-related reasoning rather than architectural design or performance evaluation.

---

## Context overview

The system under consideration integrates:

- **Large Language Models (LLMs)** for natural language generation
- **Retrieval-Augmented Generation (RAG)** to ground responses in external documents
- **Federated Data Spaces (DSs)** to ensure data sovereignty, policy enforcement,
  and controlled access across organisations

The deployment context is **policy-sensitive and distributed**, representative of
domains such as healthcare, public administration, or regulatory support.

---

## Stakeholders and roles

The scenario involves the following high-level roles:

- **Data Providers (DPs)**  
  Organisations that publish documents within a Data Space while retaining
  sovereignty and defining usage constraints.

- **Data Consumers (DCs)**  
  Entities that issue queries and generate responses using RAG, while remaining
  responsible for contextualisation and final output.

- **Federators (Fs)**  
  Infrastructure actors that coordinate metadata, enforce policies, and support
  semantic interoperability across the Data Space.

These roles introduce **distributed responsibility and accountability**, making
the explicit allocation of trustworthiness-related decisions a key concern.

---

## Trustworthiness concerns

Based on the analysis and evaluation presented in the paper :contentReference[oaicite:3]{index=3},
the following trustworthiness dimensions are particularly relevant in this scenario:

- **Traceability**  
  Ability to identify the origin of retrieved fragments and link them to generated outputs.

- **Transparency**  
  Visibility into how responses are constructed, especially in federated settings.

- **Data sovereignty and lawfulness**  
  Preservation of data locality and enforcement of usage policies defined by providers.

- **Control delegation**  
  Clear distribution of responsibilities between DPs, DCs, and Fs.

These concerns motivate the application of CRISP-TAI refinement mechanisms.

---

## Application of Contextual Refinement (CR)

In this example, the following Contextual Refinement artefacts are used:

- `context-description.md`  
  Documents the federated governance setting, applicable regulations,
  and operational assumptions of RAG in Data Spaces.

- `responsibility-map.csv`  
  Explicitly allocates trustworthiness-related responsibilities across
  DPs, DCs, and Fs, clarifying accountability boundaries.

- `principle-prioritisation.md`  
  Records the prioritisation of trustworthiness dimensions, highlighting
  traceability and sovereignty as dominant concerns.

- `assumption-log.md`  
  Captures assumptions about data stability, provider behaviour, and
  regulatory interpretation, together with revision triggers.

These artefacts support **CR.1–CR.5**.

---

## Application of Functional Refinement (FR)

Functional Refinement connects the above interpretations to concrete artefacts:

- `artefact-derivation.md`  
  Links contextual interpretations to requirements, design rationales,
  and monitoring specifications.

- `traceability-matrix.csv`  
  Provides explicit traceability between trustworthiness concerns,
  lifecycle decisions, and produced artefacts.

- `monitoring-plan.md`  
  Defines how trustworthiness-related signals (e.g., provenance loss,
  policy updates) are monitored during operation.

- `feedback-log.md`  
  Records feedback from monitoring and review activities and triggers
  contextual or operational revisions when needed.

These artefacts support **FR.1–FR.6**.

---

## Relation to the architectural models

This example does **not** redefine the Guided RAG or Federated RAG architectures
described in the paper :contentReference[oaicite:4]{index=4}.
Instead, it demonstrates how CRISP-TAI can be used to:

- Structure trustworthiness reasoning around those architectures
- Make governance and operational decisions explicit and traceable
- Support evaluability and audit-readiness without introducing new metrics

---

## Purpose of the example

This example is **illustrative**, not exhaustive.

Its goal is to show:

- How CRISP-TAI artefacts are instantiated in a realistic setting
- How trustworthiness reasoning evolves across the lifecycle
- How execution-based insights from the paper can be captured at process level

It is not intended as a reference implementation or a compliance checklist.
