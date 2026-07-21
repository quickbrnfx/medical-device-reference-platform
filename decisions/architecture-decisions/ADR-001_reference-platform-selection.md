# ADR-001 — Reference Platform Selection

**Status:** Accepted

**Date:** July 2026

**Decision Makers:** Project Maintainer

---

# Decision Statement

The **Connected Physiological Monitor** is adopted as the Version 1 reference platform for the Medical Device Engineering Reference repository.

This decision establishes the baseline product used throughout the repository to demonstrate modern medical device engineering practices.

---

# Context

The Medical Device Engineering Reference repository requires a representative product capable of demonstrating the complete engineering lifecycle of a modern connected medical device.

The selected reference platform should support the repository's educational objectives while remaining appropriately scoped for iterative development.

Rather than selecting a product based on implementation complexity or personal preference, the project performed a structured engineering evaluation using objective selection criteria.

The complete evaluation is documented in **DA-001 – Reference Platform Selection**, which evaluates multiple candidate products using weighted engineering criteria.

---

# Decision

The project adopts a **Connected Physiological Monitor** as the Version 1 reference platform.

This platform provides the most balanced representation of:

- Systems Engineering
- Requirements Engineering
- System Architecture
- Embedded Systems Engineering
- Product Cybersecurity
- Human Factors Engineering
- Verification Engineering
- Engineering Traceability

while maintaining an achievable implementation scope.

---

# Decision Rationale

The Connected Physiological Monitor provides the strongest overall alignment with the objectives established in the Project Charter.

The supporting Decision Analysis concluded that this platform offers the most balanced opportunity to demonstrate the complete engineering lifecycle without allowing any single engineering discipline to dominate the project.

This decision supports the repository philosophy that implementation exists to validate engineering decisions rather than replace them.

---

# Consequences

## Positive

- Establishes a consistent engineering baseline for all Version 1 artifacts.
- Enables balanced coverage across multiple engineering disciplines.
- Maintains a manageable project scope.
- Supports incremental development.
- Preserves opportunities for future expansion.
- Provides a coherent engineering case study for future contributors.

## Negative

- Advanced clinical workflow concepts remain outside Version 1 scope.
- Larger connected healthcare ecosystems are intentionally deferred.
- Additional reference platforms may be required to demonstrate engineering concepts outside the current system boundary.

---

# Alternatives

Alternative reference platforms were evaluated during DA-001.

The following products remain viable future reference platforms but were not selected for Version 1:

- Connected Patient Monitor
- Connected Diagnostic Device
- Connected Wearable Health Monitor

The engineering rationale supporting these alternatives is documented in DA-001.

---

# Affected Artifacts

This decision establishes the baseline assumptions for:

- Product Definition
- System Requirements
- System Architecture
- Risk Engineering
- Product Cybersecurity
- Human Factors Engineering
- Verification Engineering

Unless superseded by a future architectural decision, all Version 1 engineering artifacts shall assume the Connected Physiological Monitor as the reference platform.

---

# Future Considerations

Future repository milestones may extend the reference platform through additional capabilities, including:

- Additional physiological sensing
- Companion applications
- Cloud connectivity
- Fleet management
- Secure over-the-air updates
- Expanded cybersecurity capabilities
- Advanced verification activities

Future enhancements should be evaluated through separate Decision Analyses and documented using additional Architecture Decision Records where appropriate.

---

# Traceability

## Inputs

- Project Charter
- Engineering Lifecycle
- DA-001 – Reference Platform Selection

## Outputs

- Product Definition
- System Requirements
- System Architecture
- Risk Engineering
- Product Cybersecurity
- Human Factors Engineering
- Verification Strategy

---

# References

- PROJECT_CHARTER.md
- ENGINEERING_LIFECYCLE.md
- DA-001_REFERENCE_PLATFORM_SELECTION.md
- ROADMAP.md

---

# Revision History

| Version | Date | Description |
|----------|------|-------------|
| 1.0 | July 2026 | Initial architectural decision selecting the Version 1 reference platform. |
