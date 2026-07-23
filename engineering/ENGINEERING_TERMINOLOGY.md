# Engineering Terminology

## Overview

Engineering Terminology establishes a controlled vocabulary for engineering artifacts throughout the repository.

Consistent terminology reduces ambiguity, improves traceability, and promotes consistent interpretation across User Needs, Capability Areas, System Requirements, Architecture, Verification, and Design Reviews.

The definitions in this document establish the intended engineering meaning of commonly used terms. They are not intended to replace domain-specific terminology introduced by applicable standards or product requirements.

---

# Purpose

Engineering terminology supports:

- Consistent engineering communication
- Repeatable requirements development
- Clear capability decomposition
- Objective verification planning
- Reduced ambiguity during design reviews

Whenever practical, engineering artifacts should use terminology defined within this document.

---

# Engineering Verbs

## Acquire

**Definition**

Obtain information or data from an external source.

**Examples**

- Acquire physiological measurements.
- Acquire user input.

---

## Analyze

**Definition**

Examine information to derive engineering conclusions according to defined logic or criteria.

Analysis does not imply clinical judgment or decision making.

**Examples**

- Analyze physiological information.
- Analyze communication status.

---

## Evaluate

**Definition**

Compare information against predefined criteria to determine whether specified conditions have been satisfied.

Evaluation produces engineering results based on objective criteria.

**Examples**

- Evaluate physiological information against predefined clinical criteria.
- Evaluate battery status against operational limits.

---

## Identify

**Definition**

Determine that predefined conditions have been satisfied based on evaluated information.

Identification establishes that a specified engineering condition exists.

Identification does not imply notification, diagnosis, or operator communication.

**Examples**

- Identify clinically significant physiological changes.
- Identify sensor failures.

---

## Manage

**Definition**

Control, coordinate, or maintain the state of a system resource, function, or process.

Management may include multiple subordinate behaviors such as verification, maintenance, enforcement, or coordination.

**Examples**

- Manage access to physiological information.
- Manage patient monitoring sessions.

---

## Monitor

**Definition**

Continuously observe information or system state for changes over time.

Monitoring does not imply interpretation or response.

**Examples**

- Monitor physiological signals.
- Monitor communication status.

---

## Notify

**Definition**

Communicate information to an external actor or external system.

Notification occurs after engineering determination has been made.

Notification does not perform analysis or identification.

**Examples**

- Notify the clinical operator of an abnormal condition.
- Notify a connected system of device status.

---

## Provide

**Definition**

Make information available to an external actor or system.

Providing information does not imply analysis or interpretation.

**Examples**

- Provide physiological information.
- Provide system status.

---

## Verify

**Definition**

Confirm that specified conditions or prerequisites have been satisfied before allowing an engineering action to proceed.

Verification is performed by the system during operation and is distinct from Verification & Validation (V&V) activities performed during development.

**Examples**

- Verify user authorization.
- Verify system configuration.

---

# Engineering Principles

The following principles guide terminology selection throughout the repository.

## Responsibilities vs. Behaviors

Capability Areas describe **engineering responsibilities**.

System Requirements describe **observable system behaviors**.

---

## Outcome vs. Communication

Identification and notification represent different engineering responsibilities.

A system may identify a condition without communicating it.

Notification depends upon prior identification.

---

## Implementation Independence

Engineering terminology should describe **what** the system is responsible for, not **how** the responsibility is implemented.

Technology, algorithms, software architecture, communication protocols, and implementation mechanisms belong in later engineering artifacts.

---

# Document Maintenance

Engineering terminology evolves as the engineering methodology matures.

New terminology should be added only when repeated engineering use demonstrates a need for standardized definitions.

Existing definitions should remain stable to preserve consistency across repository artifacts.
