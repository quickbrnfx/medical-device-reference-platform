# Stakeholder Analysis

**Status:** Approved

---

# Objective

Identify the stakeholders that influence, interact with, develop, verify, validate, manufacture, maintain, regulate, or are otherwise affected by the Connected Physiological Monitor reference platform.

The purpose of this analysis is to understand who has a stake in the system and how their interests influence engineering decisions throughout the system lifecycle.

---

# Definition

A stakeholder is any individual, group, or organization that influences, interacts with, develops, verifies, validates, manufactures, maintains, regulates, or is affected by the system throughout its lifecycle.

---

# Stakeholder Categories

Stakeholders are classified according to the primary engineering perspective they contribute to the development lifecycle.

- Patients
- Users
- Operators
- Developers
- Verification
- Validation
- Manufacturing
- Service & Support
- Clinical
- Quality
- Regulatory

These categories represent distinct engineering viewpoints rather than organizational departments.

---

# Stakeholder Summary

| Stakeholder | Category | Primary Interest | Relationship to System | Influence |
|-------------|----------|------------------|------------------------|:---------:|
| Patient | Patients | Safe and effective physiological monitoring | Subject of physiological monitoring | High |
| Healthcare Provider | Users | Accurate and timely physiological information to support clinical decision-making | Primary user of physiological information | High |
| Clinical Operator | Operators | Efficient setup, configuration, and operation of the device | Operates and configures the system | Medium |
| Systems Engineer | Developers | Complete, consistent, and traceable system definition | Defines system behavior and architecture | High |
| Hardware Engineer | Developers | Reliable and maintainable hardware implementation | Develops hardware components | Medium |
| Embedded Software Engineer | Developers | Reliable implementation of software requirements | Develops embedded software | Medium |
| Human Factors Engineer | Developers | Safe, effective, and intuitive user interaction | Develops usability engineering activities and mitigations for use-related risks | Medium |
| Cybersecurity Engineer | Developers | Secure system architecture and protection of system assets | Develops cybersecurity strategy and security controls | High |
| Reliability Engineer | Developers | Ensure the system achieves its intended reliability, availability, and service life | Develops reliability strategy and engineering requirements | High |
| Safety Engineer | Developers | Ensure hazards are identified, risks are controlled, and the system is acceptably safe | Develops safety strategy, hazard analysis, and risk controls | High |
| Verification Engineer | Verification | Demonstrate that system requirements have been satisfied | Plans and executes verification activities | High |
| Validation Engineer | Validation | Demonstrate that stakeholder needs and intended use have been achieved | Plans and executes validation activities | High |
| Manufacturing Engineer | Manufacturing | Efficient, repeatable, and high-quality production | Develops manufacturing processes | Medium |
| Service Engineer | Service & Support | Maintain system performance throughout its operational lifecycle | Performs installation, maintenance, and service | Medium |
| Clinical Affairs Specialist | Clinical | Ensure the system aligns with intended clinical use, workflows, and patient care practices | Provides clinical guidance throughout development and validation | High |
| Quality Engineer | Quality | Ensure compliance with the Quality Management System and product quality processes | Oversees quality planning and process compliance | High |
| Regulatory Affairs Specialist | Regulatory | Ensure compliance with applicable regulations and support regulatory submissions | Provides regulatory strategy and oversight | High |

---

# Engineering Implications

The identified stakeholders directly influence engineering activities throughout the product lifecycle.

| Engineering Artifact | Primary Stakeholders |
|----------------------|----------------------|
| Operational Context | Patient, Healthcare Provider, Clinical Operator, Clinical Affairs |
| Stakeholder Personas | Patient, Healthcare Provider, Clinical Operator |
| User Research | Patient, Healthcare Provider, Clinical Operator |
| User Needs | Patient, Healthcare Provider, Clinical Affairs |
| System Requirements | Systems Engineering, Safety, Reliability, Clinical, Regulatory |
| System Architecture | Systems Engineering, Hardware, Embedded Software, Cybersecurity |
| Human Factors Engineering | Human Factors Engineer, Patient, Healthcare Provider, Clinical Operator |
| Cybersecurity Engineering | Cybersecurity Engineer, Systems Engineer |
| Verification Planning | Verification Engineer |
| Validation Planning | Validation Engineer |
| Manufacturing Strategy | Manufacturing Engineer |
| Service Strategy | Service Engineer |
| Quality Planning | Quality Engineer |
| Regulatory Strategy | Regulatory Affairs Specialist |

This mapping establishes early traceability between stakeholders and the engineering artifacts developed throughout the remainder of the project.

---

# Observations

- Stakeholders represent distinct engineering, clinical, operational, and regulatory perspectives that influence the development of the system.
- Multiple stakeholders may influence the same engineering decision from different perspectives.
- Separating Clinical, Quality, and Regulatory stakeholders better reflects modern medical device development and avoids combining distinct responsibilities.
- Stakeholder analysis establishes the foundation for stakeholder personas, operational context, user needs, requirements engineering, Human Factors Engineering, cybersecurity engineering, and verification planning.

---

# Engineering Principles

- Stakeholders are identified because they contribute unique engineering perspectives throughout the system lifecycle.
- Stakeholder categories represent engineering viewpoints rather than organizational reporting structures.
- Stakeholder Analysis identifies **who** influences the system; subsequent engineering artifacts describe **how** those influences are realized.
- Stakeholder Analysis should be revisited whenever the product scope, operational environment, or development lifecycle changes.

---

# Traceability

This artifact provides direct input to:

- Operational Context
- Stakeholder Personas
- User Research
- User Needs
- System Requirements
- Human Factors Engineering
- Cybersecurity Engineering
- Verification Planning
- Validation Planning

Stakeholder Analysis serves as one of the foundational engineering artifacts from which subsequent product definition and systems engineering activities are derived.
