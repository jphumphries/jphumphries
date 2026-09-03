# Risk Treatment Plan Summary
Previous: [Risk Register Summary](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Oscorp_Risk_Register_Summary.md) | Next: [3 Year Security Program Roadmap](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/Three-Year-Roadmap.md)

## Purpose

The Risk Treatment Plan translates Oscorp's identified cybersecurity risks into specific treatment actions, ownership, implementation timing, evidence requirements, and expected residual risk.

Download [Excel File](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Risk_Management/Oscorp_NIST_CSF_Risk_Treatment_Plan.xlsx)

The plan covers **15 consolidated cybersecurity risks** and connects the Risk Register to the three-year security roadmap.

> **Risk → Related Gaps → Treatment Objective → Treatment Actions → Owner → Evidence → Control Validation → Residual Risk**

------------------------------------------------------------------------

## Treatment Approach

Most identified risks are treated through **mitigation**, using a combination of governance, process, people, and technology to reduce likelihood, impact, or both.

Some specialized capabilities may also be partially **transferred** to qualified third parties. This is most practical for areas such as digital forensics and extended security monitoring.

A risk is not considered treated simply because a policy is approved or a security platform is purchased. Treatment should be:

- Implemented
- Evidenced
- Tested
- Monitored
- Reassessed

Residual-risk values remain **estimates until the proposed controls are implemented and validated**.

------------------------------------------------------------------------

## Highest-Priority Treatments

The plan gives the strongest management attention to these Critical-priority risks:

- **R-001 — Governance & Accountability:** establish formal cybersecurity governance, roles, policies, and executive reporting.
- **R-002 — Enterprise Risk Management:** implement a repeatable cybersecurity risk-management process, risk appetite, and treatment workflow.
- **R-005 — Third-Party Risk:** create a vendor inventory, risk-tiering model, assessment process, and ongoing monitoring.
- **R-007 — Access Control:** implement least privilege, RBAC, access reviews, privileged-account separation, MFA, and stronger identity governance.
- **R-009 — Data Security:** improve data classification, encryption, DLP, key management, and removable-media controls.
- **R-011 — Security Monitoring:** establish logging requirements, centralized monitoring, SIEM, detection rules, and alert ownership.
- **R-012 — Malware & Endpoint Security:** deploy centrally managed endpoint protection and detection.
- **R-013 — Incident Response:** establish incident-response roles, escalation criteria, playbooks, containment procedures, and exercises.

------------------------------------------------------------------------

## Ownership and Evidence

Each treatment should have a defined **treatment owner**, executive or risk sponsor, supporting roles, implementation window, required resources, evidence of completion, and validation cadence.

Examples of expected evidence include:

- Approved governance charters and policies.
- Risk registers and acceptance records.
- Asset and SaaS inventories.
- Access-review and MFA records.
- Conditional Access and privileged-access configurations.
- Endpoint-security coverage reports.
- Logging standards and SIEM rules.
- Incident-response plans and exercise results.
- Vendor assessments and contracts.
- Recovery and lessons-learned reports.

Evidence is necessary to show that a control is operating, not merely planned.

------------------------------------------------------------------------

## Technology Principle

The treatment plan does not treat security products as complete solutions.

- **Microsoft Entra** supports IAM, but least privilege still requires governance and recurring access reviews.
- **Microsoft Sentinel** supports monitoring, but effective detection also requires log sources, detection logic, analysts, escalation, and testing.
- **Drata or another GRC platform** can support evidence and control management, but it does not replace governance, policies, ownership, or control testing.
- **MDR/MSSP and external DFIR providers** can supplement internal capability, but Oscorp still owns the underlying business risk.

------------------------------------------------------------------------

## Key Takeaway

The Risk Treatment Plan is where Oscorp moves from **identifying risk to actively managing it**.

The goal is not to eliminate every cybersecurity risk. It is to reduce material risk to a level management can understand, monitor, and formally accept where appropriate.

> **Assessment Finding → Gap → Business Risk → Treatment → Evidence → Residual Risk → 3-Year Roadmap**

Previous: [Risk Register Summary](https://github.com/jphumphries/jphumphries/blob/175fd1ceac2b639d6b574e73fe6b3a8c9b266439/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Documents/Oscorp_Risk_Register_Summary.md) | Next: [3 Year Security Program Roadmap](https://github.com/jphumphries/jphumphries/blob/main/Projects/Oscorp_NIST-CSF_Program_Capstone_Project/Roadmap/Three-Year-Roadmap.md)
