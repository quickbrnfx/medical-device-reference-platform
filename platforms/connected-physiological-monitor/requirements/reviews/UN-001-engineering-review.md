# UN-001 Engineering Review

**User Need**

> **UN-001** – The patient needs physiological monitoring to support their care.

**Review Status:** Approved Pending Architecture Update

---

# Objective

Confirm that User Need UN-001 has been completely engineered and is suitable for baseline by reviewing the capability model, functional requirements, and engineering traceability.

---

# Scope

The following engineering artifacts were reviewed.

- User Need (UN-001)
- Capability Areas
- Functional Requirements
- Functional Architecture
- Logical Architecture
- System Interface Architecture
- System Behavior

---

# Review Criteria

The engineering review evaluated whether:

- The capability model completely satisfies User Need UN-001.
- Every capability has a clearly defined engineering responsibility.
- Every capability consumes and produces meaningful engineering information.
- Functional requirements are objective, verifiable, and implementation independent.
- Traceability has been established throughout the engineering lifecycle.
- The architecture accurately reflects the approved capability model.

---

# Capability Completeness Review

Each capability was evaluated to determine whether it:

- Consumes engineering information or system events.
- Produces engineering information required by downstream capabilities.
- Contributes directly to satisfying User Need UN-001.
- Maintains implementation independence.

## Capability Assessment

| Capability | Status | Review Summary |
|------------|--------|----------------|
| CA-001 – Monitoring Session Management | ✅ Complete | Establishes and manages the monitoring session lifecycle. |
| CA-002 – Monitoring State Management | ✅ Complete | Governs system operational behavior throughout monitoring. |
| CA-003 – Monitoring Configuration | ✅ Complete | Establishes the validated monitoring configuration. |
| CA-004 – Physiological Data Acquisition | ✅ Complete | Produces acquired physiological measurements. |
| CA-005 – Physiological Data Availability | ✅ Complete | Determines physiological measurement availability. |
| CA-006 – Physiological Data Processing | ✅ Complete | Produces processed physiological measurements. |
| CA-007 – Physiological Information | ✅ Added | Produces physiological information for downstream system use. |

---

# Review Findings

During capability review it was determined that both **Physiological Data Availability** and **Physiological Data Processing** produced engineering outputs that were not consumed by another capability.

This indicated an incomplete capability model rather than incomplete functional requirements.

To resolve this gap, Capability Area **CA-007 – Physiological Information** was introduced.

This capability:

- Produces physiological information.
- Preserves the relationship between processed physiological measurements and their availability.
- Makes physiological information available for downstream system functions.

The capability intentionally does not define how downstream functions consume the information. Presentation, recording, networking, alarm management, and future capabilities remain outside the scope of User Need UN-001.

---

# Engineering Decisions

## ED-001 — System Boundary

The functional boundary for User Need UN-001 extends beyond physiological measurement processing to include production of physiological information.

### Rationale

Behavioral review identified that processed physiological measurements and physiological measurement availability lacked a downstream consumer.

Introducing Capability Area CA-007 completed the producer-consumer chain while maintaining implementation-independent capability definitions.

---

## ED-002 — Capability Responsibilities

Capabilities describe engineering responsibilities rather than implementation details.

Capabilities intentionally avoid prescribing:

- User interface behavior
- Communication mechanisms
- Data storage
- Network protocols
- Software architecture

These concerns remain the responsibility of downstream engineering disciplines.

---

# Requirements Quality Review

The approved functional requirements were reviewed for engineering quality.

| Review Criterion | Result |
|------------------|--------|
| Objective | ✅ Pass |
| Verifiable | ✅ Pass |
| Traceable | ✅ Pass |
| Implementation Independent | ✅ Pass |
| Capability Coverage | ✅ Pass |
| Internal Consistency | ✅ Pass |

No functional ambiguities requiring engineering changes were identified.

---

# Architecture Impact Review

Approval of Capability Area CA-007 requires updates to the engineering architecture.

The following artifacts shall be updated prior to baseline approval:

- Functional Architecture
- Logical Architecture
- System Interface Architecture
- System Behavior

These updates are architectural refinements only and do not change approved functional behavior.

---

# Review Outcome

| Review Area | Result |
|-------------|--------|
| Capability Model | ✅ Pass |
| Functional Requirements | ✅ Pass |
| Traceability | ✅ Pass |
| Engineering Decisions | ✅ Pass |
| Architecture | ⚠ Update Required |

---

# Actions

| ID | Action | Status |
|----|--------|--------|
| A-001 | Update Functional Architecture to include CA-007. | Open |
| A-002 | Update Logical Architecture to include CA-007. | Open |
| A-003 | Update System Interface Architecture to include Physiological Information. | Open |
| A-004 | Update System Behavior to include production of Physiological Information. | Open |

---

# Review Conclusion

The capability model derived from User Need UN-001 is considered complete.

The introduction of **CA-007 – Physiological Information** resolved the identified producer-consumer gap while preserving implementation independence and architectural flexibility.

Following completion of the required architectural updates, User Need UN-001 is considered suitable for engineering baseline.
