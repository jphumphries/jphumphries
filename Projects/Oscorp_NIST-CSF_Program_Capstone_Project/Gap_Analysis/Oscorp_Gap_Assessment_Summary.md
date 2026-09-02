# Oscorp Gap Assessment Summary

## Overview

The Oscorp Gap Assessment identifies **34 cybersecurity gaps** across the NIST functions. The overall pattern is clear: Oscorp has some useful security practices in place, but many important controls are either **not implemented, inconsistently implemented, or not formally governed**.

The assessment is designed to connect the current state to a defined target state, assign ownership, link each gap to a related business risk, and sequence remediation into the three-year security roadmap.

>Download Gap Assessment [Excel File](Gap_Anaysis/Oscorp_NIST_CSF_Gap_Assessment.xlsx)

## Assessment Snapshot

| Area                                          | Result |
|-----------------------------------------------|-------:|
| Total gaps                                    | **34** |
| Critical priority                             | **14** |
| High priority                                 | **17** |
| Moderate priority                             |  **2** |
| Low priority                                  |  **1** |
| Failed controls                               | **31** |
| Partial controls                              |  **2** |
| Passing controls retained as improvement gaps |  **1** |

### Maturity Scale

|                   Level | Definition                                                   |
|------------------------:|--------------------------------------------------------------|
| **0 — Not Implemented** | No control or repeatable process exists                      |
|         **1 — Initial** | Ad hoc, informal, or dependent on individual effort          |
|      **2 — Developing** | Partially implemented but inconsistent                       |
|         **3 — Defined** | Documented, assigned, and consistently implemented           |
|         **4 — Managed** | Measured, monitored, tested, and reviewed                    |
|       **5 — Optimized** | Continuously improved using performance and risk information |

The goal is to target **Level 3** with the planned efforts in each category. This will establish a workable foundation before moving to fully mature the implemented controls.

------------------------------------------------------------------------

## Key Findings

### Identify — 12 Gaps

The largest foundational weaknesses are in **governance, asset visibility, risk management, business impact analysis, and third-party oversight**.

Key gaps include: 
- incomplete hardware/software/SaaS inventories
- undocumented network and data flows
- undefined cybersecurity roles
- missing policy structure
- no formal risk-management process
- undefined risk tolerance
- limited Business Impact Analysis capability
- incomplete supplier classification

**Business implication:** 
Oscorp must establish a consistent way to determine what must be protected and who owns that risk. They also must categorize which assets and services are most important and how cybersecurity decisions should be prioritized.

### Protect — 12 Gaps

Protective-control gaps center on **access management, security awareness, data protection, secure configuration, change management, and logging requirements**.

Important deficiencies include inconsistent least privilege and separation of duties, undefined remote-access governance, limited recurring security training, weak encryption/DLP controls, immature secure configuration and SDLC processes, and insufficient removable-media controls.

**Business implication:** Existing technical controls are not consistently supported by formal standards, ownership, and repeatable processes.

### Detect — 4 Gaps

Detection is one of the weakest areas of the current environment.

Oscorp lacks mature centralized logging, SIEM/event correlation, defined detection roles, alert thresholds, tested detection processes, comprehensive endpoint malware protection, and consistent third-party security monitoring.

**Business implication:** Security events may remain undetected longer, increasing investigation time and the potential scope of an incident.

### Respond — 3 Gaps

Incident response represents a major program-level weakness.

The assessment identifies gaps in incident-response planning, investigation and forensic capability, and incident containment/mitigation.

**Business implication:** During a serious event, Oscorp may have to determine roles, authority, escalation, containment, and investigative procedures while the incident is already occurring.

### Recover — 3 Gaps

Recovery is comparatively stronger because Oscorp already has a tested disaster recovery capability.

Remaining gaps focus on **lessons learned, recovery improvement, and crisis/executive communications**.

**Business implication:** Technical recovery may succeed while coordination, communication, and corrective-action processes remain incomplete.

------------------------------------------------------------------------

## Critical Management Priorities

The assessment identifies the following **14 critical-priority gaps**:

- **GAP-005 — Cybersecurity roles and responsibilities:** Create a cybersecurity governance charter and RACI; assign accountable leadership and reporting relationships.
- **GAP-006 — Information security policy framework:** Develop, approve, communicate, and periodically review core information security policies.
- **GAP-008 — Formal cybersecurity risk process:** Adopt the risk methodology and register; define assessment cadence, treatment criteria, and escalation.
- **GAP-010 — Threat, likelihood, impact, and business-impact analysis:** Perform periodic cyber risk assessments and a business impact analysis using the approved methodology.
- **GAP-011 — Third-party inventory and classification:** Create third-party inventory and tiering; identify critical vendors and security dependencies.
- **GAP-014 — Least privilege and separation of duties:** Implement RBAC, access reviews, privileged account separation, and separation-of-duties requirements.
- **GAP-017 — Data at rest and in transit protection:** Classify sensitive data; establish encryption standards; verify implementation across local, cloud, and transmission paths.
- **GAP-018 — Data loss prevention:** Define DLP requirements based on data classification; implement technical and procedural controls in phases.
- **GAP-023 — Security logging requirements:** Establish logging standard and onboard priority systems in phases.
- **GAP-025 — Centralized SIEM and event correlation:** Implement centralized logging/SIEM in phases, beginning with critical identity, endpoint, cloud, and infrastructure sources.
- **GAP-026 — Detection roles, thresholds, escalation, testing, and improvement:** Define detection RACI, severity/threshold criteria, triage workflow, escalation, exercises, and improvement cycle.
- **GAP-027 — Endpoint malware protection:** Deploy EDR/anti-malware; define coverage, configuration, alert handling, and health monitoring.
- **GAP-029 — Cybersecurity incident response plan and execution:** Develop IR plan, severity model, RACI, contacts, playbooks, containment/mitigation procedures, and tabletop exercises.
- **GAP-031 — Incident containment and mitigation:** Develop response playbooks and integrate vulnerability management with incident handling and risk acceptance.

------------------------------------------------------------------------

## 3-Year Compliance Plan

The gap assessment supports a phased remediation sequence:

**Year 1 — Establish the Foundation**

Focus on governance, accountable cybersecurity leadership, formal risk management, asset visibility, third-party governance, IAM, data protection, endpoint security, logging requirements, and foundational incident response.

**Year 2 — Improve Detection and Automation**

Implement centralized monitoring/SIEM, mature detection processes, improve forensic capability, expand third-party monitoring, and automate appropriate GRC and data-protection activities.

**Year 3 — Validate and Improve**

Move from implementation toward control-effectiveness testing, continuous monitoring, internal audit, remediation validation, metrics, exercises, and continuous improvement.

------------------------------------------------------------------------

## Key Takeaways

The most important conclusion from the Gap Assessment is that Oscorp's weaknesses are **interdependent**.

Log sourcing and ownership must be defined before a SIEM solution can honestly be considered. Though I think it possible to do this while getting used to the workflow using a SIEM service, this clearly defines these steps for this exercise. With ownership established, IAM technology can more accurately be used to set least privilege. A GRC platform will not create risk management without defined methodology, ownership, and management oversight.

The remediation strategy therefore prioritizes the following2:
- governance and foundational controls
- monitoring and automation
- assurance and optimization third.

This Gap Assessment serves as the bridge between the original [NIST assessment](Assessment/nist-assessment-summary.md) and the rest of the project.
