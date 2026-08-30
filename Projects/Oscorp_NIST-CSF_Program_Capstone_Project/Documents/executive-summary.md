# Oscorp Cybersecurity Program Executive Summary

Working as a consultant for Oscorp revealed weaknesses in business security that are critical to the survival of the business. The most pressing issue at hand was the lack of a proper team in place to construct and run a comprehensive program. Thus, starting with governance structure was key to developing policy and procedures to manage cybersecurity risk across the organization.

Through assessment, weaknesses were found in each of the categories within the NIST 800-53 framework. Existing controls proved to be inadequate or in the hands of an IT team ill-equipped in the areas of personnel and procedure to carry out necessary tasks to mitigate vulnerabilities. A lack of proper controls and ownership of specified areas of the existing program left the door open for an uncoordinated and unfocused approach to handling incoming threats.

Using the assessment findings found in the gap assessment, risk register, and treatment plan, an improvement program was designed to reduce the risks associated with Oscorp’s business dealings. The subsequent three-year roadmap prioritizes building a capable team meant to focus on establishing governance before building out this new program’s foundation.

To accomplish this, the use of NIST CSF 2.0 to help establish governance was necessary. The proposed strategy holds to the following general progression:

1.  **Establish Leadership and Governance**
2.  **Understand Risk and Categorize Assets**
3.  **Strengthen Identity, Endpoint Protection, and Data Protection**
4.  **Build Incident Response → Improve Monitoring and Detection**
5.  **Automate Appropriate Compliance Activities**
6.  **Test and Continuously Improve controls**
7.  **Position the Business for eventual ISO 27001 readiness**

## Current Cybersecurity Posture

Oscorp is not without some useful tools in place to mitigate security threats:

- Vulnerability scanning is already performed
- A Disaster Recovery Plan exists to bolster availability

However, Oscorp’s existing security measures were found to be immature in both design and implementation. The most pressing matter is the lack of leadership accountable to the success or failure of security practices. Roles and responsibilities were not adequately defined, and a lack of formal policies reveals holes in process and overall security posture.

Asset visibility is incomplete without proper documentation and management leading to a lack of accountability to these investments. Given the size of Oscorp, the lack of inventory management whether it’s physical inventory or software and data flow creates a dangerous situation from a security and fiscal standpoint. This in addition to having no technological hierarchy of priority.

Identity & Access Management is another area in need of structure and improvement. Princinple of Least Privilege, separation of duties, remote access, and privileged access control are inconsistently implemented in various areas within the business. This increases the potential for abuse of privilege and the compromise of internal systems and data.

Data protection at Oscorp is currently an afterthought. Endpoints are lacking protection against removable-media, and data both in motion and at rest are lacking developed protection against internal and external threat actors.

Detection capabilities represent one of Oscorp’s largest technical weaknesses. The organization does not currently have mature centralized security logging, event correlation, alert thresholds, or SIEM capabilities. Without these capabilities, suspicious activity may be more difficult to identify and investigate.

Incident response presents a related concern. The following areas require development from foundation to implementation:

- Roles
- Escalation procedures
- Investigation requirements
- Containment procedures
- Cybersecurity incident communications

These areas not being sufficiently established increase the possibility that a manageable security event could become more damaging because the organization is not prepared to respond quickly and consistently.

There exists no standard with which to assess the security value of Third-party vendors. They and suppliers are not consistently inventoried, classified, assessed, and monitored based on the level of risk they introduce to the business.

The goal of the proposed program is therefore not to replace everything Oscorp currently does, but to organize existing strengths within a more complete cybersecurity program.

## Risk Assessment Results

The assessment findings were consolidated into 15 cybersecurity risks within the Oscorp Risk Register. These risks represent potential business exposure rather than simply highlighting individual technical deficiencies.

Several areas require urgent attention from management:

- Cybersecurity governance and accountability
- Enterprise cybersecurity risk management
- Third-party and supply-chain risk
- Identity and access control
- Data security
- Security monitoring
- Malware and endpoint security
- Incident response

Given the secrecy around the projects being conducted at Oscorp, Incident Response and Monitoring have been given high scores because of their potential impact on the company’s ability to identify, contain, and respond to security events.

These areas hold an intrinsic connection to asset visibility, for if the company isn’t aware of what technology to protect and how then they remain vulnerable to threats. This can potentially occur in areas unseen, beginning with but not limited to:

- Insufficient Access Controls
- Weak Endpoint Protection
- Lack of adequate logging
- Immature Incident Response processes

This lends credibility to the decision to focus on building up a cybersecurity program overall as opposed to simply grafting new tools and security products.

## Risk Treatment Strategy

The Risk Treatment Plan establishes how Oscorp should respond to the risks identified during the assessment.

Most identified risks are recommended for **mitigation**, meaning Oscorp should implement controls that reduce either the likelihood of the risk occurring, the potential impact, or both. Realistically, no security measure will ever be 100% effective in eradicating threats but reducing the potential of threats to a manageable level will surely put Oscorp in a defensive position.

Some specialized risks can also be partially transferred to qualified outside providers. For example, building a complete internal digital forensics capability may not be practical during these early stages. Maintaining access to a qualified digital forensics and incident-response provider would provide specialized expertise without requiring Oscorp to immediately build an entire forensic team. This also has a direct impact on Oscorp’s bottom line and need to keep facilities up and running. 24/7 monitoring can be offloaded to a Managed Security Service Provider or MDR company as opposed to maintaining a large internal Security Operations Center.

The overall treatment process follows the structure:

**Assessment Finding → Security Gap → Business Risk → Risk Treatment → Control Implementation → Evidence → Control Validation → Residual Risk**

This distinction is important. We don’t want Oscorp to unnecessarily invest in a security platform which does not automatically mitigate the associated risk.

For example, deploying a SIEM does not by itself create an effective security monitoring program. Oscorp’s cybersecurity team must also determine which systems generate security logs, what activity should trigger alerts, who monitors those alerts, how incidents are escalated, how investigations are conducted, and how the effectiveness of the process will be tested.

The same principle applies to governance and compliance platforms. These systems can help manage controls, evidence, assessments, and compliance activities, but they cannot replace security leadership, policies, risk ownership, technical controls, or control testing.

## Three-Year Cybersecurity Transformation

### Year 1 — Establish the Foundation

The first year should focus primarily on building the cybersecurity function and addressing foundational weaknesses.

Oscorp should establish a four-person security team consisting of:

**Cybersecurity / GRC Manager** — responsible for security program leadership, strategy, budget planning, NIST implementation, risk governance, policies, and executive reporting.

**GRC Analyst** — responsible for assessments, risk register, gap assessments, policies, third-party risk, compliance activities, control testing, and evidence.

**Security Engineer / IAM Engineer** — responsible for identity and access management, Microsoft Entra, MFA, Conditional Access, privileged access, endpoint configuration, and related technical controls.

**Security Analyst** — responsible for vulnerability management, endpoint security, monitoring, investigation, and incident-response activities.

The Cybersecurity/GRC Manager should report to the CTO, with the CTO serving as the executive sponsor for the program.

Year 1 priorities should include governance and policy development, cybersecurity risk management, risk appetite and tolerance, business impact analysis, asset and software inventory, third-party governance, identity and access management, endpoint protection, and foundational incident response.

Microsoft Entra ID, Intune, and Defender are proposed as important components of the technical foundation. Based on the 250-user planning assumption, the roadmap estimates approximately $66,000 annually for core Microsoft security licensing.

The objective at the end of Year 1 is not simply to have new software deployed. Oscorp should be able to demonstrate that cybersecurity responsibilities are assigned, risks are actively managed, important assets are known, access is better controlled, endpoints are managed, and personnel understand how to respond to cybersecurity incidents.

### Year 2 — Improve Detection and Automation

After the foundational controls are established, Year 2 should focus on monitoring, detection, incident investigation, data protection, and appropriate compliance automation.

Microsoft Sentinel is proposed as Oscorp’s initial SIEM platform. Sentinel would centralize important security information and help the security team identify and investigate suspicious activity.

Sentinel should not be deployed until Oscorp has defined logging requirements, alert ownership, severity levels, escalation procedures, and incident-response responsibilities.

Because Sentinel pricing depends heavily on data ingestion and usage, the roadmap uses an estimated planning range rather than treating its cost as fixed.

The internal security team should also expand with the addition of a Security Analyst II / SOC Analyst. This position would support Sentinel monitoring, alert triage, threat detection, investigation, and incident response.

Even with this additional employee, the internal team would not be large enough to reasonably provide complete 24-hour monitoring. Oscorp should therefore consider an MDR/MSSP to provide additional coverage during nights, weekends, holidays, and major incidents.

Year 2 is also the proposed point for introducing a GRC automation platform. Drata has been identified as a potential option, but final selection should depend on a formal product evaluation, demonstration, integration requirements, and vendor quote.

Microsoft Purview should also be evaluated to improve data classification, information protection, auditing, and Data Loss Prevention.

### Year 3 — Optimize and Validate

By Year 3, the cybersecurity program should begin moving from implementation toward validation and continuous improvement.

The primary question changes from:

**“Did we implement the control?”**

to:

**“Is the control actually working?”**

Year 3 activities should therefore emphasize continuous control monitoring, penetration testing, vulnerability management, cloud security posture management, privileged-access maturity, third-party reassessments, incident-response exercises, recovery exercises, security metrics, Key Risk Indicators, internal audits, control-effectiveness testing, and remediation verification.

As Oscorp’s cloud environment grows, Microsoft Defender for Cloud can also be evaluated to improve visibility into cloud assets, security configurations, vulnerabilities, and compliance requirements.

The security team should continue to mature during this period. The Cybersecurity/GRC Manager may develop into a Director of Cybersecurity & GRC, while additional specialization is introduced within security engineering and security operations.

By the end of Year 3, Oscorp should have moved from an environment where many cybersecurity activities are informal or reactive toward one where controls are documented, assigned, monitored, tested, and improved.

## Technology Strategy

The recommended technology architecture favors Microsoft security products where they provide an appropriate fit for the identified requirements.

| Security Capability                | Proposed Solution                       |
|------------------------------------|-----------------------------------------|
| Identity, MFA & Conditional Access | Microsoft Entra ID                      |
| Endpoint Protection                | Microsoft Defender                      |
| Device Management                  | Microsoft Intune                        |
| Security Monitoring / SIEM         | Microsoft Sentinel                      |
| Data Protection / DLP              | Microsoft Purview                       |
| Key & Secret Management            | Azure Key Vault                         |
| Cloud Security Posture             | Microsoft Defender for Cloud            |
| GRC Automation                     | Drata — subject to evaluation           |
| Backup & Recovery                  | Azure Backup + existing DR capabilities |
| 24×7 Monitoring                    | MDR/MSSP                                |
| Digital Forensics                  | External specialist support             |

Technology purchases should remain tied to documented security requirements.

Before approving a major platform, Oscorp should determine which gaps it addresses, which risks it reduces, which NIST outcomes it supports, what evidence will demonstrate effectiveness, and what residual risk remains after implementation.

This approach helps prevent unnecessary technology spending while maintaining a clear connection between security investments and business risk.

## Financial Impact

The roadmap provides a preliminary three-year budget based on the modeled 250-user organization.

| Year       | Preliminary Planning Range                       |
|------------|--------------------------------------------------|
| **Year 1** | **Approximately $746K–$806K + GRC platform**   |
| **Year 2** | **Approximately $976K–$1.11M + GRC platform**  |
| **Year 3** | **Approximately $1.15M–$1.32M + GRC platform** |

Personnel represents the largest portion of the investment, with the security team estimated at approximately $600,000 in Year 1, $750,000 in Year 2, and $900,000 in Year 3.

Other costs include Microsoft security licensing, SIEM usage, vulnerability and cloud-security capabilities, managed security services, incident-response and forensic support, training, penetration testing, and implementation contingency.

These figures should be treated as planning estimates rather than approved budgets. Several services are consumption-based or require vendor quotes, including Microsoft Sentinel usage, GRC automation, MDR/MSSP services, and some cloud security capabilities.

Actual costs should be validated as Oscorp establishes its final number of users, endpoints, cloud workloads, log-ingestion volume, data-retention requirements, and third-party service requirements.

## Expected Three-Year Target State

Successful execution of the roadmap should leave Oscorp with a significantly more mature cybersecurity program.

By the conclusion of Year 3, Oscorp should have:

- Clearly defined cybersecurity leadership and accountability.
- A formal cybersecurity risk-management process.
- Documented risk appetite and risk-treatment procedures.
- Improved hardware, software, SaaS, and cloud asset visibility.
- Better understanding of critical business systems and dependencies.
- Centralized identity and access management.
- MFA, Conditional Access, and improved privileged-access controls.
- Managed endpoint protection.
- Stronger data classification and Data Loss Prevention capabilities.
- Formal third-party risk management.
- Centralized security logging and monitoring.
- Defined security detection and escalation processes.
- Documented and tested incident-response procedures.
- Access to specialist incident-response and digital forensics support.
- Improved cloud security governance.
- Repeatable vulnerability management.
- Tested recovery capabilities.
- Defined security metrics and Key Risk Indicators.
- Recurring security-awareness training.
- Evidence-based control testing and internal audit processes.
- A formal process for validating remediation and reassessing residual risk.

The result should not be viewed as the completion of cybersecurity work. Instead, Oscorp should have the structure needed to manage cybersecurity as an ongoing business risk.

## Management Conclusion

Oscorp’s primary cybersecurity challenge is not the absence of a particular security product. The larger issue is the need for an organized security program with clearly assigned responsibility, executive support, repeatable risk-management processes, appropriate technical controls, and evidence that those controls are working.

The proposed three-year roadmap addresses this problem by starting with people and governance before expanding into more advanced security technology.

This sequence is intentional.

Without clear ownership, asset visibility, access controls, logging requirements, and incident-response procedures, investments in advanced security platforms would provide limited value. Establishing these foundations first gives Oscorp a stronger basis for deploying monitoring, automation, cloud security, and assurance capabilities later in the program.

The roadmap also recognizes that Oscorp does not need to build every cybersecurity capability internally. Managed monitoring and specialized digital forensics services can supplement the internal team where doing so provides a more practical use of available resources.

Cybersecurity risk cannot be completely eliminated. Oscorp instead needs the ability to identify risk, understand its potential business impact, determine whether the risk is acceptable, implement appropriate treatment when it is not, and verify that those treatments are effective.

Successful execution of this roadmap should move Oscorp from a largely reactive and inconsistently governed security environment toward a more defined, measurable, and risk-driven cybersecurity program.

Long-term success will depend on continued executive sponsorship, clearly assigned risk ownership, appropriate funding, regular control testing, and continued reassessment as Oscorp’s business, technology, and threat environment change.

Ultimately, the goal of the program is not simply to meet a framework or purchase security tools. It is to give Oscorp a sustainable process for **understanding cybersecurity risk, making informed decisions about that risk, and protecting the business as it continues to develop.**
