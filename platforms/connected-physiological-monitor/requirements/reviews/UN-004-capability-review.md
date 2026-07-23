# Capability Review

## Document Information

| Field | Value |
|--------|-------|
| Review ID | REVIEW-CAPABILITY-004 |
| User Need | UN-004 |
| Proposed Capability | CA-010 – Maintain Safe Operation |
| Review Status | Approved |
| Review Type | Capability Review |

---

# Engineering Question

> Does the proposed Capability Area represent the single engineering responsibility required to satisfy the User Need?

---

# Objective

Determine whether the proposed Capability Area accurately represents the engineering responsibility required to satisfy the User Need while remaining implementation independent, distinct from existing capabilities, and suitable for decomposition into System Requirements.

---

# Review Context

## User Need

**UN-004**

> The patient needs physiological monitoring without compromising their safety.

---

# Proposed Capability Area

| ID | Capability Area |
|----|-----------------|
| CA-010 | Maintain Safe Operation |

---

# Capability Evaluation

| Engineering Question | Acceptance Criteria | Result | Engineering Assessment |
|----------------------|--------------------|:------:|------------------------|
| Does the Capability satisfy the User Need? | Represents the engineering responsibility required to satisfy the User Need without prescribing implementation. | ✅ Pass | "Maintain Safe Operation" expresses the enduring engineering responsibility required to support safe physiological monitoring. |
| Is the Capability implementation independent? | Does not reference architecture, hardware, software, standards, or implementation mechanisms. | ✅ Pass | The Capability defines **what** responsibility exists rather than **how** it will be achieved. |
| Is the Capability an engineering responsibility? | Expresses a responsibility rather than a system property or design solution. | ✅ Pass | Safe operation is an engineering responsibility. Safety itself remains an emergent system property resulting from multiple engineering disciplines. |
| Is the Capability distinct from existing Capability Areas? | Does not duplicate previously approved engineering responsibilities. | ✅ Pass | The Capability is independent of physiological monitoring, information management, and future engineering disciplines such as Fault Management or Alarm Management. |
| Can the Capability be decomposed into System Requirements? | Supports derivation of observable and verifiable system behaviors. | ✅ Pass | Multiple functional behaviors can be derived without constraining implementation or architecture. |

---

# Review Findings

## Finding 1

The User Need expresses a desired stakeholder outcome rather than a specific system function.

The approved Capability Area establishes the engineering responsibility necessary to achieve that outcome without prescribing implementation.

---

## Finding 2

Safety is an emergent engineering property.

The Capability establishes responsibility for maintaining safe operation while allowing Risk Management, Human Factors, Cybersecurity, Verification, and Architecture to contribute additional requirements as the engineering definition matures.

---

## Finding 3

Capability Areas represent stable engineering responsibilities.

Future safety-related requirements generated through Risk Analysis shall be allocated to this Capability Area unless they introduce an entirely new engineering responsibility.

---

# Review Decision

The review concludes that the proposed Capability Area appropriately represents the engineering responsibility required to satisfy UN-004.

The Capability:

- satisfies the User Need
- remains implementation independent
- is distinct from existing Capability Areas
- supports future decomposition into System Requirements
- provides a stable engineering responsibility for future engineering disciplines

---

# Approved Capability

| ID | Capability Area |
|----|-----------------|
| CA-010 | Maintain Safe Operation |

---

# Approval Summary

| Item | Status |
|------|:------:|
| User Need Coverage | ✅ Approved |
| Capability Independence | ✅ Approved |
| Implementation Independence | ✅ Approved |
| Engineering Responsibility | ✅ Approved |
| Capability Completeness | ✅ Approved |

---

# Exit Criteria

- ✅ Engineering responsibility approved
- ✅ Capability Review completed
- ✅ Capability approved for Requirements Review
