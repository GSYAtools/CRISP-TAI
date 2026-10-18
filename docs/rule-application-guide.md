
### Typical entry points
- Requirements and design activities
- Definition of monitoring and operational procedures
- Review of feedback from system operation

### Artefacts involved
- `artefact-derivation.md`
- `traceability-matrix.csv`
- `monitoring-plan.md`
- `feedback-log.md`

### Practical guidance
- Apply **FR.1** when interpretations lead to new or updated artefacts.
- Use **FR.2** to maintain traceability across lifecycle phases.
- Activate **FR.3** for operational adjustments.
- Use **FR.4** to propagate feedback into revised assumptions or priorities.
- Apply **FR.5** for shift-left integration.
- Use **FR.6** to ensure lifecycle continuity.

---

## 4. Navigating the refinement cycle

A typical CRISP-TAI refinement cycle:

1. Contextual interpretation and prioritisation (CR)
2. Artefact derivation and traceability (FR)
3. Monitoring and operation (FR)
4. Feedback and revision (FR → CR)

This cycle can be entered at different points depending on system maturity.

---

## 5. Common pitfalls

- Treating rules as checklists rather than reasoning support
- Ignoring assumptions once deployment begins
- Failing to connect monitoring signals back to governance decisions
- Allowing trustworthiness artefacts to become stale

---

## 6. Using the examples

The examples in `/examples` illustrate how CR and FR rules are applied in practice:

- RAG in Data Spaces — distributed governance and provenance
- Federated Learning — early operational monitoring and feedback
- TrustAIoT — platform-level lifecycle governance

Use these examples as guidance, not as prescriptive templates.

---

## Notes

CRISP-TAI is intentionally flexible.
Its value lies in **structuring coordination and reasoning**, not in enforcing
uniform practices across systems or organisations.
