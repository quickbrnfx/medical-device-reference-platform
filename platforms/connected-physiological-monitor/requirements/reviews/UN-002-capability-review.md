# UN-002 Capability Review

**Artifact ID:** REVIEW-CAPABILITY-002

**Status:** Engineering Rework Required

---

# Engineering Question

> Has User Need UN-002 been decomposed into a complete, non-overlapping, and implementation-independent set of engineering Capability Areas?

---

# Objective

The Capability Review validates the engineering capability decomposition for User Need UN-002 before functional requirements are derived.

This review ensures the proposed Capability Areas completely satisfy the User Need, remain implementation independent, and provide an appropriate basis for requirements development.

This review does not derive requirements or prescribe implementation decisions.

---

# Review Context

Capability Reviews are performed before functional requirements are developed.

Approval of this review establishes the Capability Area baseline for the associated User Need and authorizes functional requirements derivation.

---

# User Need

| ID | Description |
|----|-------------|
| **UN-002** | The patient needs their physiological information to remain protected throughout monitoring. |

---

# Proposed Capability Areas

| ID | Capability Area | Status |
|----|-----------------|--------|
| CA-008 | Manage Access to Physiological Information | Accepted |
| CA-009 | Maintain Physiological Information Integrity | Under Review |

---

# Review Checklist

## 1. User Need Coverage

### Acceptance Criteria

- Every Capability Area contributes directly to UN-002.
- Collectively, the Capability Areas satisfy the complete User Need.
- No aspect of the User Need remains unallocated.

**Result**

☐ Pass

☒ Fail

**Comments**

The review could not demonstrate that all aspects of the term *protected* are represented by the proposed Capability Areas.

---

## 2. Capability Independence

### Acceptance Criteria

- Each Capability Area represents a distinct engineering responsibility.
- Capability Areas do not overlap.
- Responsibilities are clearly separated.

**Result**

☒ Pass

☐ Fail

**Comments**

Manage Access to Physiological Information represents an independent engineering responsibility.

Maintain Physiological Information Confidentiality was evaluated and removed because it duplicated Access Management responsibilities.

---

## 3. Implementation Independence

### Acceptance Criteria

- Capability Areas describe engineering responsibilities.
- Capability Areas do not prescribe implementation mechanisms.
- Capability Areas remain technology independent.

**Result**

☒ Pass

☐ Fail

---

## 4. Engineering Responsibility

### Acceptance Criteria

- Each Capability Area answers a distinct engineering question.
- Each Capability Area represents a system responsibility.
- Each Capability Area is independently allocatable and verifiable.

**Result**

☐ Pass

☒ Fail

**Comments**

The review did not establish an independent engineering responsibility for all aspects of the User Need.

---

## 5. Information Lifecycle Coverage

### Acceptance Criteria

The Capability Areas collectively address physiological information throughout monitoring, including:

- Information creation
- Information access
- Information presentation
- Information storage
- Information communication
- Information retention
- Session completion

**Result**

☐ Pass

☒ Fail

**Comments**

The review was unable to demonstrate that the current Capability Areas completely address the lifecycle implied by the User Need.

---

# Review Findings

## Finding 001

### Topic

Capability Decomposition

### Observation

Maintain Physiological Information Confidentiality was evaluated as an independent Capability Area.

Requirements derivation demonstrated that confidentiality did not introduce an independent engineering responsibility beyond Manage Access to Physiological Information.

### Resolution

The Confidentiality capability was removed.

### Status

Resolved

---

## Finding 002

### Topic

Capability Completeness

### Observation

Capability decomposition converged on Access Management as the only clearly identifiable engineering responsibility.

No additional independent responsibilities could be established with sufficient engineering justification.

### Status

Open

---

## Finding 003

### Topic

User Need Scope

### Observation

The term *protected* encompasses multiple potential stakeholder concerns that could not be uniquely decomposed into independent Capability Areas.

### Recommendation

Review the wording of User Need UN-002 before continuing requirements development.

### Status

Open

---

# Review Decision

## Capability Status

☐ Capability Areas Approved

☐ Approved with Minor Corrections

☒ Engineering Rework Required

---

# Approval Summary

The Capability Review successfully established Access Management as an independent engineering responsibility.

However, the review could not demonstrate that the proposed Capability Areas completely satisfy User Need UN-002.

The wording of the User Need should be reviewed before establishing the Capability Area baseline and proceeding to functional requirements development.

---

# Exit Criteria

Capability Review may be closed when:

- All review findings are resolved.
- Capability decomposition is complete.
- Capability Areas are approved.
- Functional requirements development is authorized.

---

# Review Status

**Status:** Engineering Rework Required
