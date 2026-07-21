# Engineering Decision Log

**Status:** Approved

---

# Purpose

The Engineering Decision Log serves as the authoritative index of significant engineering decisions made throughout the Medical Device Engineering Reference repository.

Each accepted decision is recorded once and linked to the supporting engineering analysis, resulting Architecture Decision Record (ADR), and affected engineering outputs.

The Decision Log provides traceability between engineering questions, engineering analyses, architectural decisions, and downstream engineering work.

---

# Engineering Philosophy

Engineering decisions should be:

- Objective
- Traceable
- Justified
- Reviewable

Significant engineering decisions should be supported by documented analysis before implementation begins.

Where appropriate:

- **Decision Analyses (DAs)** evaluate engineering alternatives and trade-offs.
- **Architecture Decision Records (ADRs)** document the accepted engineering decision and establish the engineering baseline.

---

# Decision Lifecycle

```text
Engineering Question
        │
        ▼
Decision Analysis (Optional)
        │
        ▼
Architecture Decision Record
        │
        ▼
Engineering Outputs
        │
        ▼
Verification
```

Not every engineering decision requires a formal Decision Analysis.

Routine decisions may be documented directly using an Architecture Decision Record when additional analysis is unnecessary.

---

# Decision Register

| ID | Decision | Status | Analysis | ADR | Affects |
|----|----------|--------|----------|-----|---------|
| DEC-001 | Select Version 1 Reference Platform | Accepted | DA-001 | ADR-001 | Product Definition, Requirements Engineering, System Architecture, Verification |

---

# Decision Status

The following status values are used throughout the repository.

| Status | Meaning |
|---------|---------|
| Proposed | Decision has been identified and is under evaluation. |
| Accepted | Decision has been approved and becomes part of the engineering baseline. |
| Superseded | Decision has been replaced by a newer accepted decision. |
| Deprecated | Decision is retained for historical traceability but is no longer recommended for future work. |

---

# Creating New Decisions

Create a **Decision Analysis (DA)** when:

- Multiple viable alternatives exist.
- Trade-offs require objective evaluation.
- The decision has significant technical or architectural impact.
- Future contributors would benefit from understanding the engineering rationale.

Create an **Architecture Decision Record (ADR)** when:

- Recording an accepted engineering decision.
- Establishing or updating the engineering baseline.
- Communicating downstream engineering impacts.

Every accepted engineering decision should be recorded in the Decision Register.

---

# Traceability

Engineering decisions should maintain traceability to:

- Engineering Question
- Supporting Decision Analysis (if applicable)
- Architecture Decision Record
- Affected Engineering Outputs
- Verification Activities

Maintaining traceability supports engineering transparency, impact analysis, and objective engineering evidence throughout the engineering lifecycle.

---

# Related Documents

- `engineering/ENGINEERING_LIFECYCLE.md`
- `engineering/ENGINEERING_FRAMEWORK.md`
- `trade-studies/`
- `architecture-decisions/`
