# Oscorp Cybersecurity Program

## Consequences of Inaction / Risk of Deferral

### Stakeholder Purpose

The cybersecurity gaps identified in Oscorp's assessment are interconnected. Leaving them unresolved does not only preserve today's risk; as the company adds users, systems, vendors, cloud services, and data, several gaps can become harder and more expensive to correct.

This document summarizes the **business consequences of delaying treatment**. It does not predict that a specific incident will occur. It explains the exposure that remains when identified risks are left untreated.

------------------------------------------------------------------------

## Executive View

Oscorp's largest concern is not the absence of one security product. The larger issue is that weaknesses in governance, asset visibility, access control, data protection, monitoring, incident response, and third-party oversight can reinforce one another.

The result is a security environment where an incident may be:

- **More likely to occur** because foundational controls are incomplete.
- **Harder to detect** because monitoring and logging are immature.
- **Slower to contain** because incident-response roles and procedures are not fully established.
- **More difficult to investigate** because evidence and forensic processes are limited.
- **More disruptive to the business** because dependencies, recovery priorities, and communications are not fully defined.

------------------------------------------------------------------------

## Key Consequences of Deferral

| Area                              | If Remediation Is Deferred                                                                               | Potential Business Effect                                                                                              |
|-----------------------------------|----------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| **Governance & Risk Management**  | Risk ownership, priorities, and acceptance decisions remain inconsistent.                                | Security spending may remain reactive, and significant risks may remain unresolved without clear accountability.       |
| **Asset & Software Visibility**   | Hardware, software, SaaS, data flows, and critical dependencies remain incomplete.                       | Oscorp may fail to protect, monitor, patch, recover, or budget for technology it does not fully understand.            |
| **Identity & Access**             | Least privilege, privileged access, and remote-access controls remain inconsistent.                      | A compromised or misused account may provide broader access than necessary and increase the scope of an incident.      |
| **Data Protection**               | Encryption, DLP, removable-media, and information-handling controls remain immature.                     | Sensitive business information may be exposed, lost, or moved without sufficient control or visibility.                |
| **Monitoring & Detection**        | Centralized logging, event correlation, detection rules, and alert ownership remain immature.            | Malicious activity may remain undetected longer, increasing attacker dwell time and potential impact.                  |
| **Incident Response & Forensics** | Roles, escalation, containment, investigation, and evidence handling remain incomplete.                  | Oscorp may lose critical time deciding how to respond while an incident is already in progress.                        |
| **Third-Party Risk**              | Vendors are not consistently inventoried, classified, assessed, and monitored.                           | A supplier security failure may affect Oscorp even when internal controls are functioning correctly.                   |
| **Recovery & Communications**     | Recovery priorities, lessons learned, crisis communications, and reputation processes remain incomplete. | Technical recovery may occur without effective business coordination, stakeholder communication, or corrective action. |

------------------------------------------------------------------------

## The Compounding Effect

The roadmap is intentionally sequenced because later capabilities depend on earlier ones.

``` text
Incomplete Asset Visibility
          ↓
Incomplete Logging Coverage
          ↓
Reduced Detection Capability
          ↓
Slower Incident Identification
          ↓
More Difficult Containment & Investigation
          ↓
Greater Potential Business Impact
```

A second example:

``` text
Undefined Governance
        ↓
Unclear Risk Ownership
        ↓
Delayed Remediation
        ↓
Inconsistent Security Investment
        ↓
Persistent Control Gaps
```

This means that delaying foundational work can also reduce the value of later technology investments.

For example:

- A SIEM provides limited value without defined log sources, detection rules, alert ownership, and response procedures.
- Microsoft Entra does not establish least privilege without access policies, ownership, reviews, and exception handling.
- A GRC platform does not create governance without an approved risk process, control ownership, evidence standards, and management oversight.

------------------------------------------------------------------------

## Risk of Deferral by Time Horizon

| Time Horizon       | Management Exposure                                                                                                                             |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **0-6 Months**     | Unclear ownership, excessive access, incomplete inventories, weak incident preparedness, and inconsistent risk decisions remain active.         |
| **6-18 Months**    | Growth in users, vendors, cloud services, and data can make existing gaps more difficult to manage and increase implementation complexity.      |
| **18-36 Months**   | Technical debt, unresolved risk, monitoring gaps, vendor dependency, and control-validation requirements can accumulate across the environment. |
| **Beyond 3 Years** | Oscorp risks maintaining a reactive model in which security improvements are driven by incidents rather than planned risk management.           |

------------------------------------------------------------------------

## What Management Should Decide

Not every risk must be eliminated, and not every gap requires immediate remediation. Management can choose to:

- **Mitigate** - implement controls that reduce likelihood or impact.
- **Transfer** - shift part of the exposure through qualified service providers or insurance.
- **Avoid** - stop the activity creating unacceptable exposure.
- **Accept** - formally retain the risk when additional treatment is not justified.

The key requirement is that **deferral should not become accidental risk acceptance**.

Any material risk that is deferred should have:

- A named risk owner.
- Business justification for the delay.
- Current risk level.
- Expected consequences.
- Compensating controls, where available.
- Approval authority.
- A review or expiration date.

------------------------------------------------------------------------

## Stakeholder Conclusion

The assessment does not mean Oscorp is certain to experience a major cybersecurity incident. It shows that several weaknesses currently increase either the likelihood or potential impact of one.

The strongest concern is the **combination of gaps**. Incomplete asset visibility, inconsistent access controls, limited monitoring, immature incident response, and unclear governance can create a situation where an incident is harder to prevent, detect, contain, investigate, and recover from.

The purpose of the three-year roadmap is therefore not to eliminate cybersecurity risk. It is to give Oscorp a repeatable way to:

> **Understand risk → assign ownership → prioritize investment → implement controls → validate effectiveness → make informed decisions about the risk that remains.**

From a stakeholder perspective, the most important decision is not whether every gap is closed immediately. It is whether **material risks are being actively managed, owned, funded, monitored, and formally accepted when treatment is deferred**.
