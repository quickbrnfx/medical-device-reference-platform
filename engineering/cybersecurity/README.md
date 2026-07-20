# Cybersecurity

**Status:** Draft

---

# Overview

Engineering Cybersecurity is the discipline of designing systems that protect assets, maintain intended functionality, and remain resilient in the presence of intentional or unintentional threats.

Cybersecurity is not a feature added after implementation. It is an engineering concern that influences system requirements, architecture, implementation, and verification throughout the system lifecycle.

Effective Cybersecurity Engineering enables systems to continue fulfilling their intended purpose despite evolving threats and operating environments.

---

# Purpose

The purpose of Engineering Cybersecurity is to incorporate security considerations into engineering decisions from initial concept through system retirement.

Applying cybersecurity principles throughout development enables engineering teams to:

- Protect critical system assets.
- Reduce system vulnerabilities.
- Improve operational resilience.
- Support informed engineering tradeoffs.
- Preserve stakeholder trust.

---

# Engineering Question

> **How can the system continue to operate as intended in the presence of cybersecurity threats?**

---

# Core Concepts

Engineering Cybersecurity within this repository is based on several fundamental concepts.

- Security should be engineered into the system from the beginning.
- Security decisions should be informed by risk.
- Systems should assume that failures and attacks are possible.
- Security controls should support, rather than unnecessarily hinder, system operation.
- Cybersecurity should remain traceable to stakeholder needs and system requirements.
- Cybersecurity Engineering is iterative and evolves alongside the system design.

---

# Engineering Outputs

| Engineering Output | Engineering Question |
|--------------------|----------------------|
| Security Objectives | What must be protected? |
| Security Analysis | What cybersecurity conditions could compromise the system? |
| Secure Architecture | How should the system resist identified cybersecurity concerns? |
| Security Verification | How do we demonstrate cybersecurity objectives have been achieved? |

---

# Traceability

Cybersecurity Engineering should remain traceable to stakeholder needs, system requirements, architectural decisions, and verification activities.

Maintaining traceability supports engineering change assessment, impact analysis, and objective engineering evidence throughout the engineering lifecycle.

---

# Relationship to Architecture

Architecture defines how the system is organized.

Cybersecurity Engineering evaluates whether that architecture appropriately protects system assets, establishes trust boundaries, and supports the system's security objectives.

Cybersecurity Engineering may introduce architectural constraints, design modifications, or derived requirements that improve the system's security posture.

```text
                System Requirements
                        │
                        ▼
                System Architecture
                  ▲            │
                  │            ▼
            Security Analysis
                  │
                  ▼
        Architecture Updates
```

Architecture and Cybersecurity Engineering continuously refine one another throughout system development.

---

# Relationship to Risk

Cybersecurity Engineering identifies conditions that could compromise the trustworthiness of the system through intentional or unauthorized actions.

These findings may become inputs to Risk Engineering when cybersecurity concerns have implications for system safety, effectiveness, or product performance.

Although closely related, Cybersecurity Engineering and Risk Engineering answer different engineering questions and produce distinct engineering outputs.

---

# Relationship to Verification

Verification provides objective evidence that engineering requirements have been satisfied.

Cybersecurity Verification demonstrates that implemented security controls satisfy defined security objectives and remain effective under expected operating conditions.

Security controls should remain traceable to verification activities.

---

# Engineering Principles

Cybersecurity Engineering supports engineering decisions by identifying conditions that could compromise system trustworthiness.

Engineering teams should evaluate cybersecurity throughout system development rather than treating it as a one-time activity.

Security controls should remain traceable from identified cybersecurity concerns through implementation and verification.

Cybersecurity Engineering should remain independent of specific technologies, standards, or implementation techniques while producing consistent engineering outputs.

Cybersecurity is an engineering discipline integrated throughout development—not an isolated phase performed after implementation.
