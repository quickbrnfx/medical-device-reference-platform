# Engineering Decisions

This document records significant engineering decisions made during development of the Connected Physiological Monitor reference platform.

Engineering decisions document the rationale behind design and scope choices that are not readily apparent from the requirements or architecture alone. They provide context for future contributors, support design reviews, and preserve traceability as the platform evolves.

This document is **not** a requirements specification. Requirements describe **what** the system shall do. Engineering decisions explain **why** particular approaches were selected.

---

# DEC-001 — Immutable Monitoring Configuration

**Status**

Accepted

**Category**

Product Scope

---

## Decision

Version 1 of the Connected Physiological Monitor shall not permit modification of the monitoring configuration during an active monitoring session.

Monitoring configuration may only be modified while the system is in the **Ready** operational state.

---

## Rationale

Allowing configuration changes during an active monitoring session introduces significant additional engineering complexity that is outside the scope of the Version 1 reference platform.

Examples include:

- Operational state management
- Risk management
- User interface behavior
- Verification complexity
- Auditability
- Cybersecurity considerations

Restricting configuration changes to the Ready state establishes a simple, deterministic workflow while remaining representative of many clinical monitoring systems.

---

## Impact

This decision affects:

- CA-001 — Monitoring Session Management
- CA-002 — Monitoring State Management
- CA-003 — Monitoring Configuration

---

## Future Considerations

Future platform revisions may evaluate support for selective configuration changes during an active monitoring session, including:

- Parameter selection
- Sensor configuration
- Display configuration
- Other clinically appropriate configuration updates

Such support would require updates to the operational state model, requirements, risk analysis, verification strategy, and user interface.

---

# DEC-002 — Binary Measurement Availability

**Status**

Accepted

**Category**

Product Scope

---

## Decision

Version 1 models physiological measurement availability using two states:

- Available
- Unavailable

---

## Rationale

Binary availability provides sufficient behavior to demonstrate the engineering principles of physiological monitoring while minimizing unnecessary complexity in the initial reference implementation.

More granular availability states would require substantially more sophisticated system behavior, including additional requirements, verification activities, user interface behavior, and alarm management.

---

## Impact

This decision affects:

- CA-005 — Physiological Data Availability
- Future alarm management capabilities
- Future user interface behavior

---

## Future Considerations

Future platform revisions may evaluate additional availability states, such as:

- Initializing
- Degraded
- Temporarily Unavailable

Introducing additional states would require corresponding updates to system requirements, architecture, verification, and risk management artifacts.

# DEC-003 – Revision of User Need UN-002

### Context

Capability decomposition of UN-002 identified that the term "protected" could not be translated into a complete, independent set of engineering responsibilities.

## Decision

Revise UN-002 to express a single stakeholder outcome focused on authorized access to physiological information.

## Rationale

The revised User Need enables complete engineering traceability from stakeholder outcome through capability decomposition, requirements development, and architecture allocation.

## Consequences

- Capability Review can proceed with a single, well-defined Capability Area.
- Functional requirements become directly traceable.
- Other concerns (e.g., information accuracy, availability, patient association) remain open for evaluation in future engineering work.

# DEC-004 — Constraining Capabilities Require Domain Engineering

## Status

Accepted

## Context

During the Requirements Review for CA-010 – Maintain Safe Operation, it was determined that the Capability could not be decomposed into complete, verifiable System Requirements without outputs from the Risk Management discipline.

Unlike purely functional capabilities, safety responsibilities require hazard analysis to identify the specific conditions that the system must detect, prevent, or mitigate.

## Decision

Engineering Capabilities may mature through different engineering workflows.

Functional Capabilities may proceed directly from Capability Review to Requirements Review.

Constraining Capabilities require additional engineering inputs from specialized disciplines before complete System Requirements can be developed.

## Consequences

Capability Reviews remain discipline independent.
Capability Areas remain stable engineering responsibilities.
Risk Management, Cybersecurity, Human Factors, and similar disciplines may generate additional System Requirements within existing Capability Areas.
Requirements Reviews may conclude that additional engineering inputs are required before complete requirements can be established.
