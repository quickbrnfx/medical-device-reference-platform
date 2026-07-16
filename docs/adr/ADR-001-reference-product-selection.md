# ADR-001 — Reference Product Selection

**Status:** Accepted

**Date:** July 2026

**Decision Makers:** Project Maintainer

---

# Context

The Medical Device Reference Platform requires a representative reference product that demonstrates the complete engineering lifecycle of a modern connected medical device.

The selected product should enable demonstration of:

- Systems Engineering
- Embedded Systems Engineering
- Product Cybersecurity
- Human Factors & Usability
- Verification Engineering
- Requirements Engineering
- System Architecture
- Engineering Traceability

while remaining appropriately scoped for Version 1.

Rather than selecting a product based on personal preference or implementation complexity, an objective evaluation was performed using a structured decision framework.

Four candidate products were evaluated across seven engineering criteria:

1. Systems Engineering
2. Product Cybersecurity
3. Human Factors & Usability
4. Verification Engineering
5. Project Scope
6. Embedded Systems Engineering
7. Engineering Case Study

The evaluation methodology and results are documented in:

- `docs/product/REFERENCE_PRODUCT_SELECTION.md`

---

# Decision

The Medical Device Reference Platform will use a **Connected Physiological Monitor** as the Version 1 reference product.

---

# Decision Principles

This decision was guided by the following principles:

- Demonstrate engineering decisions before implementation details.
- Prefer balanced engineering coverage over maximum product complexity.
- Maintain a clear and well-defined Version 1 system boundary.
- Optimize for a complete engineering case study rather than the largest possible product.
- Preserve opportunities for future expansion without compromising the current engineering narrative.

---

# Decision Drivers

The Connected Physiological Monitor consistently demonstrated the strongest balance between:

- Coverage of the engineering lifecycle
- Project scope
- Systems Engineering
- Embedded Systems Engineering
- Product Cybersecurity
- Human Factors & Usability
- Verification Engineering
- Educational value
- Long-term extensibility

The evaluation determined that the selected product naturally supports all engineering disciplines identified in the Project Charter while maintaining a focused and coherent engineering narrative.

Unlike several alternatives, no single engineering discipline dominates the project, allowing implementation to remain a validation of engineering decisions rather than the primary objective.

---

# Alternatives Considered

## Connected Patient Monitor

### Strengths

- Rich systems engineering problem
- Excellent systems integration opportunities
- Strong verification engineering
- Complex clinical workflows
- Comprehensive human factors engineering

### Trade-offs

- Significantly larger project scope
- Greater implementation complexity
- Increased effort required to maintain a focused Version 1 engineering narrative

---

## Connected Diagnostic Device

### Strengths

- Well-defined engineering problem
- Clear system boundaries
- Highly manageable project scope
- Straightforward engineering narrative

### Trade-offs

- Narrower representation of engineering disciplines
- Fewer interacting subsystems
- Less opportunity to demonstrate continuous system behavior

---

## Connected Wearable Health Monitor

### Strengths

- Excellent embedded systems engineering opportunities
- Strong cybersecurity considerations
- Modern connected device architecture
- Low-power system design
- Wireless communications

### Trade-offs

- Broader mobile and cloud ecosystem
- Greater emphasis on companion software
- Requires disciplined system boundary management to maintain Version 1 focus

---

# Consequences

## Positive

- Balanced representation of modern medical device engineering.
- Strong alignment with the Project Charter.
- Clear progression from concept through verification.
- Well-suited to incremental development.
- Supports future expansion without requiring major architectural changes.
- Enables a complete engineering case study that remains understandable to future contributors.

## Negative

- Some advanced clinical workflow concepts will remain outside the scope of Version 1.
- Future project phases may be required to demonstrate broader connected ecosystem concepts.
- Certain engineering topics, such as large-scale clinical integration, will be intentionally deferred.

---

# Future Considerations

Future project milestones may extend the reference platform through:

- Additional physiological sensing capabilities
- Companion desktop or mobile applications
- Cloud connectivity
- Fleet management
- Secure over-the-air updates
- Expanded cybersecurity capabilities
- Additional verification activities

These capabilities should be evaluated independently and incorporated only when they strengthen the project's engineering objectives and remain consistent with the established guiding principles.

---

# References

- `docs/project/PROJECT_CHARTER.md`
- `docs/product/REFERENCE_PRODUCT_SELECTION.md`
- `docs/roadmap/ROADMAP.md`

---

# Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | July 2026 | Initial architectural decision selecting the Version 1 reference product. |
