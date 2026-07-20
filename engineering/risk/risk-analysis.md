# Risk Analysis

**Status:** Draft

---

# Objective

Risk Analysis identifies, evaluates, and documents conditions that could result in unacceptable risk throughout the system lifecycle.

It provides a structured engineering assessment that supports informed design decisions, enables traceability, and defines risk controls necessary to achieve an acceptable level of risk.

---

# Relationship to Risk Engineering

Risk Engineering is the engineering discipline responsible for understanding and controlling product risk.

Risk Analysis is the primary engineering output of that discipline.

The Risk Analysis captures the engineering knowledge generated during risk evaluation and provides traceable inputs to Requirements, Architecture, Verification, and other engineering disciplines.

---

# Purpose

The purpose of Risk Analysis is to:

- Identify conditions that may result in unacceptable risk.
- Evaluate the significance of identified risks.
- Define appropriate risk controls.
- Identify derived engineering requirements.
- Identify verification activities necessary to demonstrate the effectiveness of implemented controls.
- Document residual risk following implementation of risk controls.

Risk Analysis supports engineering decision-making throughout system development and evolves as the system design matures.

---

# Engineering Inputs

Risk Analysis is informed by engineering information produced by multiple disciplines.

Typical inputs include:

- Product Definition
- Intended Use
- Operational Context
- User Needs
- System Requirements
- System Architecture
- Interface Definitions
- Operational Scenarios
- Cybersecurity Analysis (when applicable)
- Human Factors Analysis (when applicable)

---

# Engineering Outputs

Risk Analysis produces engineering information that influences multiple disciplines.

| Output | Purpose |
|---------|---------|
| Identified Risks | Documents conditions requiring evaluation. |
| Risk Controls | Defines measures intended to reduce identified risks. |
| Derived Requirements | Introduces new engineering requirements when necessary. |
| Architectural Constraints | Influences system organization and design decisions. |
| Verification Objectives | Identifies evidence required to demonstrate effective risk control. |
| Residual Risk Information | Documents remaining risk following implementation of controls. |

---

# Information Flow

```text
Product Definition
        │
        ▼
System Requirements
        │
        ▼
System Architecture
        │
        ▼
    Risk Analysis
    │     │      │
    ▼     ▼      ▼
Requirements Architecture Verification
 Updates      Updates
```

Risk Analysis is iterative and should be revisited whenever significant engineering changes occur.

---

# Traceability

Risk Analysis should remain traceable to the engineering information from which it was derived.

Likewise, identified risk controls should remain traceable to:

- System Requirements
- Architectural Decisions
- Verification Activities

Maintaining traceability supports engineering change assessment, impact analysis, and objective evidence throughout the engineering lifecycle.

---

# Relationship to Requirements

Risk Analysis may identify the need for additional or modified System Requirements.

These derived requirements ensure that identified risks are addressed through explicit engineering expectations.

---

# Relationship to Architecture

Architecture defines how the system is organized.

Risk Analysis evaluates whether the architecture adequately controls identified risks and may introduce architectural constraints or design modifications.

Architecture and Risk Analysis evolve together throughout system development.

---

# Relationship to Verification

Verification provides objective evidence that implemented risk controls perform as intended.

Each implemented risk control should be supported by one or more verification activities appropriate to the associated level of risk.

---

# Engineering Principles

Risk Analysis is an engineering activity that supports informed decision-making.

The objective is not to eliminate all risk, but to understand risk, reduce it where appropriate, and ensure remaining risk is visible, justified, and supported by objective engineering evidence.

Risk Analysis should remain independent of any specific analysis technique or documentation methodology, allowing organizations to apply approaches appropriate to their engineering processes while producing consistent engineering outputs.
