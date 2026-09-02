# Oscorp Risk Register Summary

## Purpose

The Oscorp Risk Register consolidates the cybersecurity assessment and gap findings into **15 enterprise risks**. Its purpose is to translate technical control deficiencies into business risk so management can prioritize treatment, assign ownership, and track the risk that remains after remediation.

The register uses a **1–5 Likelihood × Impact model**:

> **Risk Score = Likelihood × Impact**

| Score | Rating   |
|------:|----------|
|   1–4 | Low      |
|   5–9 | Moderate |
| 10–16 | High     |
| 17–25 | Critical |

------------------------------------------------------------------------

## Risk Posture at a Glance

| Measure                                       | Result |
|-----------------------------------------------|-------:|
| Total risks                                   | **15** |
| Critical management priority                  |  **8** |
| High management priority                      |  **7** |
| Risks treated primarily through mitigation    | **15** |
| Risks with estimated High residual rating     |  **3** |
| Risks with estimated Moderate residual rating | **12** |

The highest inherent risk scores are concentrated in **security monitoring** and **incident response**, reflecting the increased business exposure created when malicious activity cannot be detected, escalated, contained, and investigated quickly.

------------------------------------------------------------------------

## Critical Management Priorities

- **R-001 — Cybersecurity governance is undefined:** Directly affects the organization's ability to manage every other cybersecurity risk.
- **R-002 — Cybersecurity risk is not formally assessed or governed:** A formal risk process is the foundation for prioritizing limited security resources.
- **R-005 — Third-party and supply-chain security is unmanaged:** Third parties can materially expand the attack surface and introduce risks outside direct organizational control.
- **R-007 — Least privilege and separation of duties are not consistently implemented:** Excessive permissions can turn a single compromised account into a broader security incident.
- **R-009 — Encryption and data-leak protections are insufficient:** This is one of the most direct paths to loss of confidential information.
- **R-011 — Oscorp lacks centralized security monitoring and event correlation:** The absence of centralized detection substantially increases dwell time and limits incident investigation.
- **R-012 — Endpoint protection and malicious-code detection are inadequate:** Endpoint controls provide a practical first line of defense while broader monitoring capabilities mature.
- **R-013 — Incident response roles, procedures, escalation, and containment are undefined:** A security event becomes significantly more damaging when the organization does not know who acts, when, or how.

------------------------------------------------------------------------

## Remaining High-Priority Risks

- **R-003 — Incomplete asset and software inventory**
- **R-004 — Critical communication and data flows are undocumented**
- **R-006 — Critical services and resilience requirements are not formally defined**
- **R-008 — Remote access controls are undefined**
- **R-010 — Configuration, SDLC, and environment separation controls are immature**
- **R-014 — Incident investigation and forensic capability is limited**
- **R-015 — Recovery communications, reputation management, and lessons learned are incomplete**

------------------------------------------------------------------------

## Major Risk Themes

### Governance & Risk Management

Oscorp lacks sufficiently mature cybersecurity governance, defined accountability, and formal enterprise risk-management processes.

**Business concern:** security decisions may remain inconsistent, risks may lack clear owners, and investments may not align to the organization's most significant exposures.

### Asset, Architecture & Third-Party Visibility

The organization has incomplete visibility into hardware, software, SaaS, data flows, critical dependencies, and third-party relationships.

**Business concern:** Oscorp cannot reliably protect, monitor, recover, or prioritize assets and services it does not fully understand.

### Identity & Data Protection

Least privilege, remote access, privileged access, encryption, and Data Loss Prevention require improvement.

**Business concern:** compromised or misused accounts may have broader access than necessary, while sensitive information may be exposed without sufficient preventative or detective controls.

### Secure Configuration & Endpoint Protection

Configuration management, secure development practices, endpoint protection, and change control are not consistently mature.

**Business concern:** vulnerabilities and insecure changes may be introduced into the environment even when other security controls are functioning.

### Security Monitoring & Incident Response

Centralized monitoring, event correlation, detection processes, incident-response procedures, and forensic capability represent some of the most significant weaknesses.

**Business concern:** an incident may be harder to detect, slower to contain, more difficult to investigate, and potentially more damaging to the business.

### Recovery & Crisis Communications

Oscorp has an existing disaster recovery capability, but recovery governance, lessons learned, and crisis communications require further development.

**Business concern:** systems may be restored while business coordination, communications, and corrective-action processes remain incomplete.

------------------------------------------------------------------------

## Treatment Direction

Most risks are assigned a **Mitigate** treatment strategy.

The overall approach is:

1.  Establish accountable cybersecurity leadership and governance.
2.  Formalize risk management and ownership.
3.  Improve asset, software, data-flow, and third-party visibility.
4.  Strengthen IAM, endpoint security, data protection, and configuration management.
5.  Establish incident-response capability.
6.  Define logging requirements and implement centralized monitoring.
7.  Expand investigation, forensic, and recovery capabilities.
8.  Test control effectiveness and reassess residual risk.

For specialized capabilities such as digital forensics and extended monitoring, outside providers may supplement internal resources where building the function entirely in-house would not be practical.

------------------------------------------------------------------------

## Inherent vs. Residual Risk

The Risk Register distinguishes between:

- **Inherent Risk** — exposure before the proposed treatment is implemented.
- **Residual Risk** — the estimated exposure expected to remain after treatment.

Residual-risk scores in this portfolio should be treated as **planning estimates**, not validated outcomes.

A residual score should only be considered reliable after the relevant controls have been:

- Implemented
- Evidenced
- Tested
- Monitored
- Reassessed

This prevents the organization from assuming that risk has been reduced simply because a policy was approved or a security product was purchased.

------------------------------------------------------------------------

## Key Takeaway

The Risk Register is the point where the project moves from **control deficiencies to business risk**.

Instead of treating findings as isolated technical issues, the register shows how weaknesses in governance, access control, data protection, monitoring, incident response, third-party oversight, and recovery can affect the confidentiality, integrity, availability, and resilience of the business.

The project flow is:

> **NIST Assessment → Gap Assessment → Risk Methodology → Risk Register → Risk Treatment Plan → 3-Year Roadmap**

The register provides the prioritization layer that determines **which risks require action first, who should own them, and how remediation should be sequenced**.
