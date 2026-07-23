# Capability Review

**Artifact ID:** REVIEW-CAPABILITY-XXX

**Status:** Draft

---

# Engineering Question

> Has the User Need been decomposed into a complete, non-overlapping, and implementation-independent set of engineering Capability Areas?

---

# Objective

The Capability Review validates the engineering capability decomposition for a User Need before functional requirements are derived.

This review ensures the proposed Capability Areas completely satisfy the User Need, remain implementation independent, and provide an appropriate basis for functional requirements development.

This review does not derive functional requirements or prescribe implementation decisions.

---

# Review Context

Capability Reviews are performed after User Needs have been established and before functional requirements are developed.

Approval of this review establishes the Capability Area baseline for the associated User Need and authorizes functional requirements derivation.

---

# User Need

| ID | Description |
|----|-------------|
| **UN-XXX** | <User Need Description> |

---

# Proposed Capability Areas

| ID | Capability Area | Status |
|----|-----------------|--------|
| **CA-XXX** | <Capability Area> | Proposed |

---

# Capability Evaluation

| Candidate Capability | Decision | Engineering Rationale |
|----------------------|----------|-----------------------|
| <Capability> | Accepted / Rejected | <Engineering rationale> |

---

# Review Checklist

## 1. User Need Coverage

### Engineering Question

Does the proposed capability decomposition completely satisfy the User Need?

### Acceptance Criteria

- Every Capability Area contributes directly to the User Need.
- Collectively, the Capability Areas satisfy the complete User Need.
- No aspect of the User Need remains unallocated.

### Result

☐ Pass

☐ Rework Required

### Engineering Assessment

---

## 2. Capability Independence

### Engineering Question

Does each Capability Area represent a unique engineering responsibility?

### Acceptance Criteria

- Capability Areas represent distinct engineering responsibilities.
- Responsibilities do not overlap.
- Responsibilities are independently allocatable.

### Result

☐ Pass

☐ Rework Required

### Engineering Assessment

---

## 3. Implementation Independence

### Engineering Question

Do the Capability Areas avoid prescribing implementation?

### Acceptance Criteria

- Capability Areas describe engineering responsibilities.
- No implementation mechanisms are specified.
- Capability Areas remain technology independent.

### Result

☐ Pass

☐ Rework Required

### Engineering Assessment

---

## 4. Engineering Responsibility

### Engineering Question

Does each Capability Area represent an appropriate engineering responsibility?

### Acceptance Criteria

- Each Capability Area answers a distinct engineering question.
- Each Capability Area represents a system responsibility.
- Each Capability Area can be independently allocated and verified.

### Result

☐ Pass

☐ Rework Required

### Engineering Assessment

---

## 5. Capability Completeness

### Engineering Question

Have all necessary engineering responsibilities been identified?

### Acceptance Criteria

- Capability decomposition is complete.
- No required Capability Areas are missing.
- No unnecessary Capability Areas exist.

### Result

☐ Pass

☐ Rework Required

### Engineering Assessment

---

# Review Findings

## Finding XXX

### Topic

<Subject>

### Observation

<Observation>

### Engineering Assessment

<Engineering reasoning>

### Resolution

<Resolution>

### Disposition

Resolved / Open

---

# Review Decision

## Capability Status

☐ Capability Areas Approved

☐ Approved with Minor Corrections

☐ Engineering Rework Required

---

## Requirements Readiness

| Status | Description |
|---------|-------------|
| Ready | Capability may proceed directly to Requirements Review. |
| Pending Domain Engineering | Additional engineering discipline(s) must provide inputs before complete requirements can be developed. |

Selected Status:

Pending Domain Engineering

---

# Approval Summary

<Summary>

---

# Exit Criteria

Capability Review is complete when:

- All review checklist items pass.
- All review findings are resolved.
- Capability Area baseline is approved.
- Functional requirements development is authorized.

---

# Review Status

**Status:** Draft
