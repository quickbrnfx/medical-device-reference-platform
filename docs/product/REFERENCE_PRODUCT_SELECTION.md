# Reference Product Selection


| Section                | Status         |
| ---------------------- | -------------- |
| Objective              | ✅              |
| Selection Criteria     | ✅              |
| Evaluation Methodology | ✅              |
| Candidate Products     | ✅              |
| Evaluation Results     | 🟡 In Progress |
| Recommendation         | ⬜              |
| Final Decision         | ⬜              |


## Objective

The objective of this document is to evaluate candidate reference products using consistent engineering criteria and document the rationale for selecting the product that best demonstrates the engineering process defined in the Project Charter.

## Selection Criteria

| ID | Criterion             | Why it Matters                                             |
| -- | --------------------- | ---------------------------------------------------------- |
| C1 | Systems Engineering   | Drives requirements, architecture, and traceability.       |
| C2 | Product Cybersecurity | Creates meaningful security decisions.                     |
| C3 | Human Factors         | Requires user interaction and workflow considerations.     |
| C4 | Verification          | Can be realistically verified.                             |
| C5 | Embedded Development  | Requires enough firmware to support the engineering story. |
| C6 | Project Scope         | Achievable by one engineer within a reasonable timeframe.  |
| C7 | Engineering Demonstration | Clearly demonstrates engineering reasoning and tradeoffs.  |

# Evaluation Methodology

## Criterion Weights

| ID | Criterion | Weight |
|----|-----------|:------:|
| C1 | Systems Engineering | 5 |
| C2 | Product Cybersecurity | 5 |
| C3 | Human Factors | 5 |
| C4 | Verification | 5 |
| C5 | Project Scope | 5 |
| C6 | Embedded Development | 4 |
| C7 | Engineering Demonstration | 5 |

---

## Scoring Scale

| Score | Meaning |
|-------|---------|
| 1 | Poor Fit |
| 2 | Weak Fit |
| 3 | Adequate Fit |
| 4 | Strong Fit |
| 5 | Excellent Fit |

Weighted Score = Score × Weight

---

## Scoring Rubrics

### C1 – Systems Engineering

**Question**

> How well does this product naturally support systems engineering activities throughout its lifecycle?

| Score | Definition |
|-------|------------|
| 5 | Naturally requires substantial requirements development, architecture, interface definition, trade studies, traceability, risk management, and verification planning. |
| 4 | Requires most systems engineering activities but with lower complexity. |
| 3 | Requires some systems engineering but has limited architectural depth. |
| 2 | Minimal systems engineering required. |
| 1 | Mostly implementation-focused with little systems engineering value. |

Observations
- The Connected Physiological Monitor provides the richest standalone systems engineering problem.
- The Patient Monitor and Wearable Health Monitor both require substantial systems engineering, but for different reasons.
- The Connected Diagnostic Device remains a strong candidate but generally has a narrower systems context.
- All four candidates require meaningful systems engineering; none were eliminated by this criterion.

Lessons Learned
- Systems engineering value is driven by the interactions between subsystems rather than the complexity of any individual component.
- It is important to evaluate systems engineering independently of project scope to avoid biasing the results.
- A product does not need to be the most complex system to provide a valuable systems engineering case study.

### C2 – Product Cybersecurity

**Question**

> How well does this product create opportunities to demonstrate secure-by-design engineering throughout the product lifecycle?

| Score | Definition                                                                                                                                                                                                |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **5** | Naturally requires identity, authentication, authorization, secure communications, secure update mechanisms, threat modeling, trust boundaries, and security verification as core engineering activities. |
| **4** | Requires several significant product cybersecurity activities but with fewer interacting trust boundaries or security mechanisms.                                                                         |
| **3** | Requires basic product security considerations but security is not a primary architectural driver.                                                                                                        |
| **2** | Requires only limited product security decisions.                                                                                                                                                         |
| **1** | Product cybersecurity plays a minimal role in the engineering process.                                                                                                                                    |


Observations

- Cybersecurity is a first-order engineering concern for all connected medical device categories.
- Continuous connectivity generally increases the number of trust boundaries and security considerations.
- Diagnostic devices present a narrower cybersecurity problem than continuous monitoring products.

Lessons Learned
- Product cybersecurity is driven more by system interactions than by the sensing technology itself.
- Separating cybersecurity from project scope helped produce more objective scores.

C3 – Human Factors & Usability

Question

How well does this product create opportunities to demonstrate human factors engineering and usability engineering throughout the product lifecycle?

Score Definitions
Score	Definition
5	Human factors are a primary engineering driver, requiring user research, workflow analysis, use-related risk analysis, iterative usability evaluation, and design validation.
4	Human factors significantly influence product design and verification but are not the dominant engineering driver.
3	Human factors contribute to the design but are limited in scope or complexity.
2	Human interaction is relatively simple and requires minimal human factors analysis.
1	Human factors have little influence on engineering decisions.

---

## Candidate Products

| ID | Candidate | Summary | Representative Example |
|----|-----------|---------|------------------------|
| P1 | Connected Physiological Monitor | Acquires physiological measurements and securely communicates them for monitoring and analysis. | Multi-parameter vital signs monitor |
| P2 | Connected Patient Monitor | Aggregates data from multiple sources to present patient status, alarms, and device information. | Bedside patient monitor |
| P3 | Connected Diagnostic Device | Performs diagnostic measurements and presents results to support clinical decision making. | Point-of-care diagnostic analyzer |
| P4 | Connected Wearable Health Monitor | Continuously collects physiological data in a wearable form factor for remote monitoring. | Wearable ECG or health monitoring patch |


---

# Evaluation Results

### C1 – Systems Engineering

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **4** | ✅      |
| P3 – Connected Diagnostic Device       | **4** | ✅      |
| P4 – Connected Wearable Health Monitor |   ⬜   |        |

### C2 – Product Cybersecurity

| Candidate                              | Score | Status |
| -------------------------------------- | :---: | ------ |
| P1 – Connected Physiological Monitor   | **5** | ✅      |
| P2 – Connected Patient Monitor         | **5** | ✅      |
| P3 – Connected Diagnostic Device       | **4** | ✅      |
| P4 – Connected Wearable Health Monitor |   ⬜   |        |


---

# Recommendation

*(Pending.)*

---

# Final Decision

*(Pending.)*
