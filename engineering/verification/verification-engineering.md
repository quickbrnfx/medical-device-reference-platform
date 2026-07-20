# Verification Engineering

**Status:** Approved

---

# Objective

Verification Engineering provides objective evidence that approved engineering requirements have been correctly implemented.

Verification answers a single engineering question:

> **Did we build the system correctly?**

Verification evaluates implementation against approved requirements.

It does not determine whether the correct requirements were selected.

---

# Definition

Verification is the systematic process of demonstrating, through objective evidence, that specified engineering requirements have been satisfied.

Verification activities should be planned before implementation whenever practical.

---

# Engineering Philosophy

Verification demonstrates compliance.

Verification does not create quality.

Quality is established through sound engineering decisions, architecture, implementation, and risk management.

Verification provides objective evidence that those engineering activities achieved their intended outcomes.

---

# Verification Lifecycle

```text
Approved Requirements
        │
        ▼
Verification Planning
        │
        ▼
Verification Design
        │
        ▼
Verification Execution
        │
        ▼
Results Review
        │
        ▼
Objective Evidence
```

---

# Verification Principles

Verification activities should be:

- Planned
- Objective
- Repeatable
- Traceable
- Independent whenever practical

Every verification activity should trace directly to one or more approved requirements.

---

# Sources of Verification

Verification is derived from:

- System Requirements
- Risk Controls
- Cybersecurity Requirements
- Human Factors Requirements
- Regulatory Requirements
- Interface Requirements
- Performance Requirements

Verification shall not introduce new engineering requirements.

---

# Verification Methods

The repository recognizes four primary verification methods.

## Inspection

Verification through examination of documentation, hardware, software, or physical characteristics.

Examples:

- Documentation review
- Label inspection
- Configuration review

---

## Analysis

Verification using engineering calculations, simulations, or analytical methods.

Examples:

- Timing analysis
- Memory utilization
- Fault tree analysis
- Performance modeling

---

## Demonstration

Verification through observation of system behavior without detailed measurement.

Examples:

- User workflow demonstration
- Alarm acknowledgement
- Startup sequence

---

## Test

Verification using controlled procedures that produce measurable results.

Examples:

- Functional testing
- Environmental testing
- Performance testing
- Electrical safety testing

---

# Verification Planning

Verification planning should define:

- Verification objective
- Associated requirements
- Verification method
- Acceptance criteria
- Test environment
- Required equipment
- Test data
- Responsibilities

Planning should occur before implementation whenever practical.

---

# Verification Traceability

Every verification activity should maintain traceability.

```text
Stakeholder Need
        │
        ▼
System Requirement
        │
        ▼
Verification Activity
        │
        ▼
Objective Evidence
```

Traceability ensures that every approved requirement has corresponding verification evidence.

---

# Verification Results

Verification records should document:

- Procedure executed
- Test environment
- Test configuration
- Results obtained
- Deviations
- Pass/Fail determination
- Objective evidence

Verification records should be sufficient to support independent review.

---

# Common Verification Errors

Avoid:

- Verifying implementation instead of requirements.
- Creating tests without approved requirements.
- Subjective acceptance criteria.
- Combining multiple requirements into a single verification without maintaining traceability.
- Modifying requirements during verification.

---

# Engineering Principles

Verification demonstrates engineering compliance.

Verification should be planned before implementation.

Every approved requirement should have a defined verification method.

Objective evidence—not opinion—determines verification success.

---

# Related Documents

- ENGINEERING_LIFECYCLE.md
- REQUIREMENTS_ENGINEERING.md
- SYSTEM_REQUIREMENTS.md
- REQUIREMENTS_TRACEABILITY.md
