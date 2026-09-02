# Oscorp NIST 800-53 Assessment & Cybersecurity Program Plan

This project demonstrates how I approached the design of a cybersecurity program from an initial [NIST 800-53 assessment](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/nist-assessment-summary.md) through remediation planning.

The work follows a simple progression:

1. [Executive Summary](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/executive-summary.md)
2. [Consequences of Inaction](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Oscorp_Consequences_of_Inaction_Stakeholder_Brief.md)
3. [NIST Assessment Summary](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/nist-assessment-summary.md)
  - [NIST Assessment — GitHub Version](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/nist-assessment-full-tables.md)
  - [NIST Assessment — Excel](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/GRC%20Mastery%20NIST%20Cyber%20Security%20Assessment_2026.xlsx)
4. [Gap Assessment](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Gap_Analysis/Oscorp_Gap_Assessment_Summary.md)
  - [Gap Assessment — Excel](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Gap_Analysis/Oscorp_NIST_CSF_Gap_Assessment.xlsx)
5. [Risk Methodology](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Risk_Assessment_Methodology.md)
6. [Risk Register Summary](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Oscorp_Risk_Register_Summary.md)
  - [Risk Register — Excel](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Oscorp_NIST_CSF_Risk_Register_2026_1-5_Model.xlsx)
7. [Risk Treatment Plan](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Risk_Management/Oscorp_Risk_Treatment_Plan_Summary.md)
  - [Risk Treatment Plan — Excel](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Risk_Management/Oscorp_NIST_CSF_Risk_Treatment_Plan.xlsx)
8. [3-Year Security Roadmap](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/Three-Year-Roadmap.md)
  - [Year 1](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Strategy/02-year-1-foundation.md)
  - [Year 2](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Strategy/03-year-2-monitoring-automation.md)
  - [Year 3](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Strategy/04-year-3-optimization-assurance.md)

The goal was to move beyond identifying security weaknesses and show how those findings can be translated into **business risk, treatment decisions, ownership, technology requirements, and budget considerations**.

------------------------------------------------------------------------

## Core Principles Addressed

The larger issue is the need for a coordinated security program supported by:

- Clear ownership
- Executive sponsorship
- Formal risk management
- Defined policies and standards
- Reliable asset visibility
- Strong IAM
- Managed endpoints
- Data protection
- Centralized monitoring
- Incident-response capability
- Third-party risk management
- Evidence-based control validation

The roadmap therefore follows this principle:

> **Build the security program first. Add technology where it supports the program. Validate that the resulting controls actually reduce risk.**

------------------------------------------------------------------------

## Project Notes

In this portfolio scenario, some assumptions were necessary to build this out.

- Approximately **250 users** were used for budget modeling.
- Technology recommendations represent proposed solutions, not completed procurement.
- Vendor and consumption-based pricing should be validated before purchase.
- Residual-risk values remain estimates until controls are implemented and tested.
- Production implementation would require additional architecture, legal, privacy, procurement, and business review.

------------------------------------------------------------------------

## Detailed Sections

### 1. Executive Summary

**Start here:** [Executive Summary](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/executive-summary.md)

Provides the high-level business view of the project, including:

- Current cybersecurity posture
- Major business risks
- Risk treatment strategy
- Three-year transformation plan
- Technology direction
- Potential financial impact
- Expected target state

------------------------------------------------------------------------

### 2. NIST Cybersecurity Assessment

**Summary:** [NIST Assessment Summary](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/nist-assessment-summary.md)

**Detailed evidence:** [Full Assessment Tables](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/nist-assessment-full-tables.md)

**Full Assessment:** [NIST 800-53 Assessment](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/GRC%20Mastery%20NIST%20Cyber%20Security%20Assessment_2026.xlsx)

The assessment identified weaknesses across the NIST 800-53 categories. Key concerns included:

- Undefined cybersecurity governance and accountability
- Enterprise risk management
- Asset and software inventory
- Third-party risk
- Access control
- Data security
- Security monitoring
- Endpoint security
- Incident response
- Digital forensics
- Recovery and crisis communications

**What this demonstrates:**  
Current-state assessment, control review, documentation of findings, and identification of security weaknesses.

------------------------------------------------------------------------

### 3. Gap Assessment

**Review:** [Gap Assessment](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Gap_Analysis/Oscorp_Gap_Assessment_Summary.md)

The assessment findings were consolidated into **34 security gaps** and compared against a defined target state.

The gap assessment connects:

``` text
Current State → Target State → Maturity Gap → Risk → Recommended Action
```

It also assigns priority, ownership, and a proposed roadmap phase.

**What this demonstrates:**  
Gap analysis, control maturity assessment, remediation prioritization, and traceability.

------------------------------------------------------------------------

### 4. Risk Assessment Methodology

**Review:** [Risk Assessment Methodology](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Risk_Assessment_Methodology.md)

The project uses a **1–5 likelihood and impact model**:

> **Risk Score = Likelihood × Impact**

| Score | Rating   |
|------:|----------|
|   1–4 | Low      |
|   5–9 | Moderate |
| 10–16 | High     |
| 17–25 | Critical |

**What this demonstrates:**  
A repeatable approach to risk scoring, prioritization, treatment, ownership, and residual-risk evaluation.

------------------------------------------------------------------------

### 5. Risk Register

**Summary:** [Risk Register Summary](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Oscorp_Risk_Register_Summary.md)

**Full Register:** [Risk Register — Excel](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Oscorp_NIST_CSF_Risk_Register_2026_1-5_Model.xlsx)

The assessment and gap findings were consolidated into **15 enterprise cybersecurity risks**, including:

- Governance and accountability
- Enterprise risk management
- Asset and software inventory
- Third-party risk
- Access control
- Data security
- Security monitoring
- Endpoint security
- Incident response
- Digital forensics
- Recovery and crisis communications

The purpose of the register is to convert technical deficiencies into **business risk**.

**What this demonstrates:**  
Risk identification, business-impact analysis, ownership, inherent risk, residual risk, and prioritization.

------------------------------------------------------------------------

### 6. Risk Treatment Plan

**Review:** [Risk Treatment Plan](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Risk_Management/Oscorp_Risk_Treatment_Plan_Summary.md)

The treatment plan defines how Oscorp should respond to each major risk:

``` text
Risk
 ↓
Related Gaps
 ↓
Treatment Objective
 ↓
Treatment Actions
 ↓
Owner
 ↓
Required Resources
 ↓
Evidence
 ↓
Control Validation
 ↓
Residual Risk
```

No risk is considered treated simply because a tool is purchased or a policy is written. Evidence of control implementation and validation is required.

**What this demonstrates:**  
Risk treatment, remediation planning, control ownership, evidence requirements, and validation.

------------------------------------------------------------------------

### 7. Three-Year Security Roadmap

**Review:** [3-Year Security Roadmap](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/Three-Year-Roadmap.md)

The roadmap converts the treatment plan into a phased security program.

#### [Year 1](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Strategy/02-year-1-foundation.md) — Foundation

- Establish cybersecurity leadership
- Build the initial security team
- Formalize governance and risk management
- Improve asset visibility
- Strengthen IAM and endpoint security
- Establish incident-response capability

#### [Year 2](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Strategy/03-year-2-monitoring-automation.md) — Monitoring & Automation

- Implement centralized logging and Microsoft Sentinel
- Expand security operations
- Add MDR/MSSP support
- Introduce GRC automation
- Improve DLP and security-awareness training

#### [Year 3](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Strategy/04-year-3-optimization-assurance.md) — Optimization & Assurance

- Test control effectiveness
- Improve vulnerability and cloud-security management
- Mature privileged access
- Conduct IR and recovery exercises
- Develop metrics and KRIs
- Perform internal audits and remediation validation

**What this demonstrates:**  
Strategic planning, sequencing, staffing, technology selection, budgeting, and long-term security-program development.

------------------------------------------------------------------------

## Supporting Roadmap Files

- [Security Team Growth Plan](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/staffing/security-team-growth-plan.md)
- [Security Technology Architecture](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/technology/security-technology-architecture.md)
- [Technology Evaluation Criteria](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/governance/technology-evaluation-criteria.md)
- [Three-Year Budget](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/financials/three-year-budget.md)
