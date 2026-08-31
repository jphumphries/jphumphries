# Oscorp Cybersecurity Program

This project demonstrates how I approached a cybersecurity program from assessment through remediation planning.

The work follows a simple progression:

[Executive Summary](https://github.com/jphumphries/jphumphries/blob/274b305e42ab6eb285f996a53eaa1c88efc6082f/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/executive-summary.md)

      ↓

[NIST Assessment](https://github.com/jphumphries/jphumphries/blob/3b001d67cf1737432e24a3a49dfb61c54fd81988/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/GRC%20Mastery%20NIST%20Cyber%20Security%20Assessment_2026.xlsx)
- [Assement Summary]()
- [NIST Assessment(Github Version]()

      ↓
      
[Gap Assessment]()

      ↓

[Risk Methodology]()

      ↓

[Risk Register]()

      ↓

[Risk Treatment Plan]()

      ↓

[3-Year Security Roadmap]()


The goal was to move beyond identifying security weaknesses and show how those findings can be translated into **business risk, treatment decisions, ownership, technology requirements, budget considerations, and long-term improvement**.

This repository documents a complete cybersecurity improvement program for Oscorp, moving from initial assessment through risk analysis, treatment planning, and a three-year security roadmap.

The project follows this sequence:

``` text
NIST Cybersecurity Assessment
            ↓
      Gap Assessment
            ↓
Risk Assessment Methodology
            ↓
        Risk Register
            ↓
    Risk Treatment Plan
            ↓
  3-Year Security Roadmap
            ↓
     Executive Summary
```

The goal is to show how control findings can be translated into **business risk, treatment decisions, accountable ownership, technology requirements, budget considerations, and measurable improvement**.

------------------------------------------------------------------------

## Quick Review for Hiring Managers

If you only have a few minutes, review the project in this order:

1.  **`executive-summary.md`** — business problem, major risks, treatment approach, three-year strategy, financial impact, and expected target state.
2.  **`risk-register.xlsx`** — consolidated cybersecurity risks, scoring, ownership, priorities, treatment direction, and residual-risk estimates.
3.  **`risk-treatment-plan.xlsx`** — how each risk will be reduced, who owns the work, what evidence should exist, and how effectiveness should be validated.
4.  **`3-year-security-roadmap/README.md`** — how the security program grows over time through people, process, and technology.
5.  **`gap-assessment.xlsx`** — detailed traceability from current-state deficiencies to target-state improvements.

For a deeper review, continue through the supporting assessment and methodology files below.

------------------------------------------------------------------------

# Repository Walkthrough

## 1. NIST Cybersecurity Assessment

### `nist-assessment-summary.md`

**Purpose:** Provides a readable summary of the assessment across **Identify, Protect, Detect, Respond, and Recover**.

**What it shows:**

- Existing security strengths
- Major control deficiencies
- Pass/fail/unknown assessment results
- Plain-language interpretation of the findings
- Image placeholders for the original assessment tables

**What to look for:** This file demonstrates the ability to move beyond simply recording whether a control passes or fails and explain **why the condition matters to the organization**.

### `nist-assessment-full-tables.md`

**Purpose:** Preserves the detailed assessment content for reviewers who want to inspect individual controls, questions, comments, and recommendations.

**What to look for:** This provides traceability. Later risks and recommendations are grounded in identifiable assessment conditions rather than created independently.

------------------------------------------------------------------------

## 2. Gap Assessment

### `gap-assessment.xlsx`

**Purpose:** Translates individual assessment findings into clearly defined security capability gaps.

The assessment consolidates **34 gaps** across Identify, Protect, Detect, Respond, and Recover.

**Key fields include:**

- Gap ID
- NIST function/category
- Current state
- Target state
- Current maturity
- Target maturity
- Related Risk ID
- Recommended action
- Priority
- Responsible owner
- Roadmap phase
- Business/security rationale

**What to look for:** The gap assessment separates **control maturity from risk severity**. Several control gaps may contribute to one larger business risk, and an immature control is not automatically the organization's highest risk.

------------------------------------------------------------------------

## 3. Risk Assessment Methodology

### `risk-assessment-methodology.md`

**Purpose:** Defines the repeatable method used to evaluate cybersecurity risk.

The project uses a **1–5 likelihood and impact model**:

| Score | Level     |
|------:|-----------|
|     1 | Very Low  |
|     2 | Low       |
|     3 | Moderate  |
|     4 | High      |
|     5 | Very High |

> **Risk Score = Likelihood × Impact**

| Risk Score | Rating   |
|-----------:|----------|
|        1–4 | Low      |
|        5–9 | Moderate |
|      10–16 | High     |
|      17–25 | Critical |

**What it shows:** likelihood criteria, impact criteria, scoring thresholds, treatment options, residual-risk methodology, ownership, monitoring expectations, and roadmap linkage.

**What to look for:** The methodology gives the Risk Register a defined basis instead of assigning ratings without a repeatable standard. Residual-risk values are planning estimates until proposed controls are implemented and tested.

------------------------------------------------------------------------

## 4. Risk Register

### `risk-register.xlsx`

**Purpose:** Consolidates the assessment and gap findings into **15 enterprise cybersecurity risks**.

Major risk areas include:

- Governance and accountability
- Enterprise risk management
- Asset and software inventory
- Data and network mapping
- Third-party risk
- Business continuity
- Access control
- Remote access
- Data security
- Configuration and change management
- Security monitoring
- Malware and endpoint security
- Incident response
- Digital forensics
- Recovery and crisis communications

**What it shows:** risk descriptions, business impact, inherent likelihood/impact, risk scores, treatment direction, ownership, NIST traceability, priorities, target implementation periods, and estimated residual risk.

**What to look for:** The Risk Register changes the discussion from *“Oscorp does not have a SIEM”* to *“Oscorp has limited centralized monitoring and event correlation, increasing the likelihood that malicious activity could remain undetected and increasing the potential impact of an incident.”*

That distinction is central to the project: **technology deficiencies are translated into business risk before solutions are selected.**

------------------------------------------------------------------------

## 5. Risk Treatment Plan

### `risk-treatment-plan.xlsx`

**Purpose:** Defines how Oscorp should respond to each major cybersecurity risk.

``` text
Risk
 ↓
Related Gaps
 ↓
Treatment Objective
 ↓
Treatment Actions
 ↓
Accountable Owner
 ↓
People / Technology Requirements
 ↓
Evidence
 ↓
Control Validation
 ↓
Residual Risk
```

**Key fields include:** Risk ID, related Gap IDs, treatment strategy, objective, actions, treatment owner, executive sponsor, supporting roles, implementation window, resources/technology, evidence of completion, validation/monitoring, and residual-risk rationale.

**What to look for:** A risk is not considered treated simply because technology is purchased or a policy is written. Treatment should be **implemented, evidenced, tested, monitored, and reassessed**.

------------------------------------------------------------------------

## 6. Three-Year Cybersecurity Roadmap

### `3-year-security-roadmap/README.md`

**Purpose:** Turns assessment findings, risks, and treatments into an actionable transformation plan.

The roadmap uses a modeled organization of approximately **250 users** for budgeting purposes.

### First 90 Days

Establish accountable cybersecurity leadership and validate priorities, resources, and technology requirements.

### Year 1 — Foundation

Focus on security leadership, governance, policy, risk management, asset visibility, business impact analysis, third-party governance, IAM, endpoint security, and foundational incident response.

Initial team:

| Role                        | Primary Responsibility                                                                      |
|-----------------------------|---------------------------------------------------------------------------------------------|
| Cybersecurity / GRC Manager | Program leadership, risk governance, strategy, policy, budget planning, executive reporting |
| GRC Analyst                 | Risk, assessments, policy, TPRM, compliance, control testing, evidence                      |
| Security / IAM Engineer     | Entra, IAM, MFA, Conditional Access, RBAC, endpoint/security configuration                  |
| Security Analyst            | Vulnerability management, endpoint security, monitoring, investigations, incident response  |

### Year 2 — Detection & Automation

Focus on centralized logging, Microsoft Sentinel, security operations expansion, MDR/MSSP support, detection engineering, GRC automation, DLP, and recurring security-awareness training.

### Year 3 — Assurance & Optimization

Focus on continuous control monitoring, vulnerability management, penetration testing, cloud posture, privileged-access maturity, third-party reassessment, IR/recovery exercises, metrics/KRIs, internal audit, control-effectiveness testing, and remediation verification.

**What to look for:** The roadmap intentionally places **leadership, governance, risk management, and foundational controls before advanced security tooling**.

------------------------------------------------------------------------

## 7. Roadmap Supporting Files

Inside `3-year-security-roadmap/`:

### `docs/strategy/01-roadmap-overview.md`

Planning assumptions, first 90 days, and implementation sequence.

### `docs/strategy/02-year-1-foundation.md`

Governance, IAM, asset management, endpoint security, staffing, and foundational incident response.

### `docs/strategy/03-year-2-monitoring-automation.md`

SIEM, detection, security operations, MDR/MSSP, GRC automation, training, and data protection.

### `docs/strategy/04-year-3-optimization-assurance.md`

Testing, vulnerability management, cloud posture, security metrics, audit, and continuous improvement.

### `docs/staffing/security-team-growth-plan.md`

Shows how the security team grows into more specialized GRC, engineering, and operations functions.

### `docs/technology/security-technology-architecture.md`

Maps security capabilities to proposed technologies such as Entra ID, Intune, Defender, Sentinel, Purview, Azure Key Vault, Defender for Cloud, Drata, Azure Backup, MDR/MSSP, and external DFIR support.

### `docs/governance/technology-evaluation-criteria.md`

Defines the questions that should be answered before purchasing a security platform:

1.  Which Gap IDs does it address?
2.  Which Risk IDs does it reduce?
3.  Which NIST outcomes does it support?
4.  What evidence demonstrates effectiveness?
5.  What residual risk remains?
6.  Does the solution make operational and financial sense?

### `docs/financials/three-year-budget.md`

Provides preliminary staffing, licensing, managed-service, testing, training, and implementation estimates. Costs are treated as **planning assumptions rather than final vendor quotes**.

------------------------------------------------------------------------

## 8. Executive Summary

### `executive-summary.md`

**Purpose:** Concludes the project by translating the detailed work into an executive-level view of:

- Current cybersecurity posture
- Major business risks
- Treatment strategy
- Three-year transformation
- Technology direction
- Financial impact
- Expected target state
- Management considerations

**What to look for:** This demonstrates the ability to communicate technical and GRC findings to leadership without requiring an executive to read every assessment control or spreadsheet.

------------------------------------------------------------------------

# Key Project Conclusion

Oscorp's largest cybersecurity problem is **not the absence of one particular security product**.

The larger issue is the absence of a coordinated cybersecurity program supported by:

- Clear ownership
- Executive sponsorship
- Formal risk management
- Defined policies and standards
- Reliable asset visibility
- Strong identity controls
- Managed endpoints
- Data protection
- Centralized monitoring
- Incident-response capability
- Third-party risk management
- Evidence-based control validation

The three-year plan therefore follows this principle:

> **Build the security program first. Add technology where it supports the program. Validate that the resulting controls actually reduce risk.**

------------------------------------------------------------------------

# Skills Demonstrated

This portfolio project demonstrates work across:

- NIST-based cybersecurity assessment
- NIST CSF program planning
- Governance, Risk, and Compliance
- Risk assessment methodology
- Risk-register development
- Risk scoring and prioritization
- Residual-risk analysis
- Gap assessment
- Control maturity analysis
- Risk treatment planning
- Cybersecurity policy and governance
- Third-Party Risk Management
- Identity and Access Management planning
- Incident-response planning
- Security monitoring strategy
- Security technology evaluation
- Cybersecurity roadmap development
- Budget and resource planning
- Control testing and evidence requirements
- Executive cybersecurity communication
- ISO 27001 readiness planning

------------------------------------------------------------------------

# Project Assumptions & Limitations

This is a portfolio scenario rather than a production engagement.

Key assumptions include:

- Approximately **250 users** for licensing and budget modeling.
- Proposed technology represents a recommended direction rather than completed procurement.
- Vendor pricing should be validated before purchase.
- Consumption-based services such as SIEM require real usage measurements before final budgets are approved.
- Residual-risk scores are estimates until treatments are implemented and operating effectiveness is tested.
- Production technology selection would require additional architecture, integration, legal, privacy, procurement, and business review.

These assumptions are documented so estimated information is not presented as established fact.

------------------------------------------------------------------------

# Final Perspective

The purpose of this project is not to show that every cybersecurity problem can be solved with a framework or a collection of security tools.

It demonstrates a repeatable decision-making process:

> **Understand the environment → identify deficiencies → determine business risk → prioritize treatment → assign ownership → implement controls → gather evidence → test effectiveness → reassess risk.**

That process keeps cybersecurity investment connected to business priorities as the organization changes.

------------------------------------------------------------------------

## Suggested Review Paths

**5-minute review:**  
`executive-summary.md` → `risk-register.xlsx` → `3-year-security-roadmap/README.md`

**15-minute review:**  
Add `gap-assessment.xlsx` and `risk-treatment-plan.xlsx`.

**Full technical/GRC review:**  
Begin with the NIST assessment and follow the complete sequence from assessment through executive summary.
