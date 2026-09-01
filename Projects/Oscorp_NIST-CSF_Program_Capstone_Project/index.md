# Oscorp Cybersecurity Program

This project demonstrates how I approached a cybersecurity program from assessment through remediation planning.

The work follows a simple progression:

[Executive Summary](Documents/executive-summary.md)

[Consequences of Inaction]()

[NIST Assessment Summary](Assessment/nist-assessment-summary.md)
- [NIST Assessment — GitHub Version](Assessment/nist-assessment-full-tables.md)
- [NIST Assessment — Excel](Assessment/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/GRC%20Mastery%20NIST%20Cyber%20Security%20Assessment_2026.xlsx)

[Gap Assessment](Documents/Oscorp_NIST_CSF_Gap_Assessment.xlsx)

[Risk Methodology](ADD-LINK-HERE)

[Risk Register](Risk_Management/Oscorp_NIST_CSF_Risk_Register_2026_1-5_Model.xlsx)

[Risk Treatment Plan](Risk_Management/Oscorp_NIST_CSF_Risk_Treatment_Paln.xlsx)

[3-Year Security Roadmap](Roadmap/Roadmap.md)
- [Year 1](Documents/Strategy/02-year-1-foundation.md)
- [Year 2](Documents/Strategy/03-year-2-monitoring-automation.md)
- [Year 3](Documents/Strategy/04-year-3-optimization-assurance.md)

The goal was to move beyond identifying security weaknesses and show how those findings can be translated into **business risk, treatment decisions, ownership, technology requirements, budget considerations, and long-term improvement**.

---

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

---

## Project Notes

In this portfolio scenario, some assumptions were necessary to build this out.

- Approximately **250 users** were used for budget modeling.
- Technology recommendations represent proposed solutions, not completed procurement.
- Vendor and consumption-based pricing should be validated before purchase.
- Residual-risk values remain estimates until controls are implemented and tested.
- Production implementation would require additional architecture, legal, privacy, procurement, and business review.

---

### 1. Executive Summary

**Start here:** [Executive Summary](https://github.com/jphumphries/jphumphries/blob/274b305e42ab6eb285f996a53eaa1c88efc6082f/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/executive-summary.md)

Provides the high-level business view of the project, including:

- Current cybersecurity posture
- Major business risks
- Risk treatment strategy
- Three-year transformation plan
- Technology direction
- Potential financial impact
- Expected target state

---

### 2. NIST Cybersecurity Assessment

**Summary:** [NIST Assessment Summary](Assessment/nist-assessment-summary.md)

**Detailed evidence:** [Full Assessment Tables](Assessment/nist-assessment-full-tables.md)

**Full Assessment:** [NIST 800-53 Assessment](Assessment/GRC%20Mastery%20NIST%20Cyber%20Security%20Assessment_2026.xlsx)

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

The purpose of the register is to convert technical deficiencies into **business risk**.

---

### 6. Risk Treatment Plan

[Risk Treatment Plan]((Risk_Management/Oscorp_NIST_CSF_Risk_Treatment_Paln.xlsx)

This defines how Oscorp should respond to each major risk. the logic behind the column names in the register are as follows:

```text
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

No threat will ever be fully eliminated, therefore no risk will be fully eliminated but only managed. Each risk is not considered treated simply because a tool is purchased or a policy was written. Controls must be assessed, implemented, and measured for effectiveness in mitaged the associated risks in the register.

---

### 7. Three-Year Security Roadmap

**Review:** [3-Year Security Roadmap](ADD-LINK-HERE)

The roadmap converts the treatment plan into a phased security program.

#### Year 1 — Foundation

- Establish cybersecurity leadership
- Build the initial security team
- Formalize governance and risk management
- Improve asset visibility
- Strengthen IAM and endpoint security
- Establish incident-response capability

#### Year 2 — Detection & Automation

- Implement centralized logging and Microsoft Sentinel
- Expand security operations
- Add MDR/MSSP support
- Introduce GRC automation
- Improve DLP and security-awareness training

#### Year 3 — Assurance & Optimization

- Test control effectiveness
- Improve vulnerability and cloud-security management
- Mature privileged access
- Conduct IR and recovery exercises
- Develop metrics and KRIs
- Perform internal audits and remediation validation

**What this demonstrates:**

Strategic planning, sequencing, staffing, technology selection, budgeting, and long-term security-program development.

---

## Supporting Roadmap Files

- [Roadmap Overview](ADD-LINK-HERE)
- [Year 1 — Foundation](ADD-LINK-HERE)
- [Year 2 — Monitoring & Automation](ADD-LINK-HERE)
- [Year 3 — Optimization & Assurance](ADD-LINK-HERE)
- [Security Team Growth Plan](ADD-LINK-HERE)
- [Security Technology Architecture](ADD-LINK-HERE)
- [Technology Evaluation Criteria](ADD-LINK-HERE)
- [Three-Year Budget](ADD-LINK-HERE)

---

## Project Notes

In this portfolio scenario, some assumptions were necessary to build this out.

- Approximately **250 users** were used for budget modeling.
- Technology recommendations represent proposed solutions, not completed procurement.
- Vendor and consumption-based pricing should be validated before purchase.
- Residual-risk values remain estimates until controls are implemented and tested.
- Production implementation would require additional architecture, legal, privacy, procurement, and business review.

---
