# Requirement Characteristics

## Overview

Effective System Requirements communicate a single, objective system obligation that can be understood, implemented, and verified consistently across engineering disciplines.

The quality of a requirement directly influences the quality of the resulting architecture, implementation, and verification activities.

---

## Purpose

The purpose of defining requirement characteristics is to establish a consistent standard for writing, reviewing, and maintaining System Requirements.

Applying these characteristics reduces ambiguity, improves communication, and increases confidence that requirements can be successfully implemented and verified.

---

## Core Characteristics

Within this repository, every System Requirement should be:

### Necessary

The requirement contributes directly to satisfying one or more User Needs.

### Clear

The requirement has only one reasonable interpretation.

### Atomic

The requirement expresses a single obligation.

### Verifiable

Objective evidence can determine whether the requirement has been satisfied.

### Traceable

The requirement can be traced to its originating User Need and downstream verification activities.

### Solution Independent

Whenever practical, the requirement defines **what** the system must do rather than **how** it will accomplish it.

---

## Common Issues

Poor requirements often exhibit one or more of the following characteristics:

- Multiple obligations within a single requirement.
- Subjective or ambiguous language.
- Implementation details presented as requirements.
- Missing stakeholder rationale.
- No defined verification approach.
- Lack of traceability.

Identifying and correcting these issues early improves the overall quality of the system specification.

---

## Relationship to Other Artifacts

Requirement Characteristics define the quality standard applied to every System Requirement.

```text
User Needs
      │
      ▼
System Requirements
      │
      ▼
Requirement Reviews
      │
      ▼
Verification
```

These characteristics support consistent requirement development while improving architecture, implementation, and verification activities throughout the engineering lifecycle.
