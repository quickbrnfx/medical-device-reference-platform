# Requirements Engineering

## Overview

Requirements Engineering transforms stakeholder goals into objective, verifiable system requirements.

It provides the structured process for defining what a system must do while maintaining traceability to the stakeholder needs established during Product Definition.

Requirements define the problem the system must solve without prescribing how the solution is implemented.

---

## Purpose

The purpose of Requirements Engineering is to establish a complete, consistent, and verifiable description of the system's expected behavior and characteristics.

Well-written requirements reduce ambiguity, improve communication across engineering disciplines, and provide the foundation for architecture, implementation, verification, and validation.

---

## Core Concepts

Requirements Engineering within this repository is based on several fundamental concepts.

- Requirements describe system obligations.
- Requirements are derived from stakeholder needs.
- Requirements are solution independent whenever practical.
- Requirements are objectively verifiable.
- Requirements are maintained through traceability.

---

## Engineering Artifacts

| Artifact | Engineering Question |
|----------|----------------------|
| System Requirements | What must the system do? |
| Requirement Characteristics | What makes a good requirement? |
| Verification Methods | How can a requirement be verified? |
| Traceability | How are engineering artifacts connected? |

---

## Relationship to Product Definition

Requirements Engineering begins after Product Definition has established stakeholder goals.

The outputs of Product Definition provide the rationale for every system requirement.

```
Stakeholders
        │
        ▼
User Needs
        │
        ▼
System Requirements
```

Requirements should always be traceable to one or more User Needs.

---

## Relationship to Architecture

Requirements define **what** the system must accomplish.

Architecture determines **how system responsibilities are organized** to satisfy those requirements.

Maintaining this separation improves flexibility and reduces unnecessary coupling between engineering activities.
