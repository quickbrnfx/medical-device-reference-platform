# Verification

**Status:** Approved

---

# Overview

Verification is the engineering discipline responsible for producing objective evidence that a system satisfies its specified requirements.

Verification evaluates whether an implemented system behaves as intended and demonstrates, through documented evidence, that approved engineering requirements have been satisfied.

Verification answers the engineering question:

> **Did we build the system correctly?**

Verification is a continuous engineering activity that begins during requirements development and concludes with objective evidence supporting system acceptance.

---

# Purpose

The purpose of Verification Engineering is to demonstrate, through objective evidence, that the implemented system satisfies its approved engineering requirements.

Verification provides confidence that engineering decisions have been successfully realized and that the resulting system performs as specified.

Verification does not establish system requirements or determine system architecture. Instead, it evaluates whether those engineering decisions have been correctly implemented.

---

# Scope

This directory contains the engineering artifacts used to plan, design, execute, and document verification activities throughout the Medical Device Engineering Reference repository.

The focus of Verification Engineering is the generation of objective, repeatable, and traceable evidence demonstrating compliance with approved engineering requirements.

---

# Core Concepts

Verification Engineering within this repository is founded on several fundamental principles.

- Verification evaluates implemented behavior against approved requirements.
- Every verification activity produces objective evidence.
- Verification planning begins during requirements development.
- Verification activities remain traceable to System Requirements.
- Verification is performed throughout system development rather than only at project completion.
- Verification demonstrates compliance; it does not define system behavior.

---

# Engineering Artifacts

| Artifact | Engineering Question |
|----------|----------------------|
| Verification Strategy | How will the system be verified? |
| Verification Planning | What evidence must be produced? |
| Test Design | How will objective evidence be generated? |
| Verification Execution | What evidence was collected? |
| Verification Reporting | What conclusions can be drawn from the evidence? |

Each artifact contributes objective evidence supporting the engineering baseline established by the project's approved requirements.

---

# Engineering Flow

## Inputs

Verification Engineering is driven by engineering artifacts produced earlier in the lifecycle, including:

- System Requirements
- Risk Control Requirements
- Product Cybersecurity Requirements
- Human Factors Requirements
- Interface Requirements
- Performance Requirements

---

## Outputs

Verification Engineering produces:

- Verification Strategy
- Verification Plans
- Test Designs
- Verification Records
- Verification Reports
- Objective Evidence

These artifacts collectively demonstrate that approved engineering requirements have been satisfied.

---

# Relationship to Requirements

Requirements establish what the system must accomplish.

Verification produces objective evidence demonstrating that those requirements have been satisfied.

```text
System Requirements
         │
         ▼
Verification Planning
         │
         ▼
Verification Activities
         │
         ▼
Objective Evidence
```

Every verification activity should maintain traceability to one or more approved System Requirements.

---

# Relationship to Quality

Quality defines the desired characteristics of the system.

Verification demonstrates that those characteristics have been achieved where they are expressed as verifiable requirements.

Verification provides objective evidence.

Quality evaluates the significance and adequacy of that evidence.

---

# Relationship to Other Engineering Disciplines

Verification Engineering depends upon engineering work completed throughout the development lifecycle.

```text
Requirements
        │
        ▼
Architecture
        │
        ▼
Implementation
        │
        ▼
Verification
        │
        ▼
Objective Evidence
```

Verification closes the engineering loop by demonstrating that implementation satisfies the approved engineering baseline.

---

# Engineering Principles

Verification should be:

- Planned before implementation whenever practical.
- Objective and repeatable.
- Traceable to approved requirements.
- Based on measurable acceptance criteria.
- Sufficient to support independent engineering review.

Successful verification provides confidence that the implemented system satisfies its documented engineering requirements.

---

# Related Documents

### Upstream

- Requirements Engineering
- System Requirements
- Risk Engineering
- Product Cybersecurity
- Human Factors Engineering

### This Directory

- Verification Strategy
- Verification Planning
- Test Design
- Verification Execution
- Verification Reporting

### Downstream

- Verification Results
- Objective Evidence
- Engineering Release Documentation
