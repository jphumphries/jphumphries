# Risk Assessment Methodology
Previous: [NIST Assessment Summary](Assessment/nist-assessment-summary.md) | Next: [Gap Assessment](Gap_Analysis/Oscorp_Gap_Assessment_Summary.md)

> **Project:** Oscorp Cybersecurity Program  
> **Framework:** NIST 800-53 Cybersecurity Framework 
> **Artifact:** Risk Assessment Methodology  
> **Related Deliverable:** `[Oscorp_NIST_CSF_Risk_Register_2026_Strong.xlsx](Assessment/Oscorp_NIST-CSF_Program_Capstone_Project/Assessment/GRC%20Mastery%20NIST%20Cyber%20Security%20Assessment_2026.xlsx)`

## 1. Purpose

This methodology establishes a consistent, risk-based approach for identifying, evaluating, prioritizing, treating, and monitoring cybersecurity risks within the Oscorp case-study environment.

The assessment uses the **NIST Cybersecurity Framework (CSF)** to evaluate the current state of cybersecurity controls and translate identified deficiencies into business-relevant risks. The methodology is intended to support practical decision-making by considering not only technical exposure, but also business criticality, available personnel, budget, implementation complexity, operational requirements, and dependencies between security initiatives.

> **Core principle:** Security improvements should reduce meaningful business risk while remaining practical, measurable, and sustainable for the organization.

---

## 2. Scope

The assessment covers the five NIST CSF functions used in the source assessment:

- **Identify**
- **Protect**
- **Detect**
- **Respond**
- **Recover**

The resulting risk register addresses areas including:

- Cybersecurity governance and accountability
- Enterprise cybersecurity risk management
- Asset and software inventory
- Network and data-flow visibility
- Third-party and supply-chain risk
- Business continuity and resilience
- Identity and access management
- Remote access
- Data protection and encryption
- Secure configuration and change management
- Security monitoring and event detection
- Endpoint and malware protection
- Incident response
- Digital forensics and investigation
- Recovery communications and lessons learned

---

## 3. Assessment Process

The assessment follows a traceable progression from control evidence to remediation planning.

```text
Current-State Assessment
          ↓
Identify Control Deficiencies
          ↓
Develop Risk Statements
          ↓
Assess Likelihood + Impact
          ↓
Calculate Inherent Risk
          ↓
Select Risk Treatment
          ↓
Estimate Residual Risk
          ↓
Prioritize Remediation
          ↓
3-Year Cybersecurity Roadmap
```

### 3.1 Evaluate Current State

Existing cybersecurity practices are reviewed against applicable NIST CSF categories using the information provided in the Oscorp case study.

### 3.2 Identify Control Deficiencies

A deficiency is recorded where a control is absent, incomplete, inconsistently implemented, or not sufficiently demonstrated by the available evidence.

### 3.3 Convert Findings Into Risks

Assessment findings are translated into risk statements describing the potential consequence of the underlying weakness.

**Example**

| Element | Example |
|---|---|
| Finding | No centralized security monitoring solution is operating. |
| Control weakness | Security events are not centrally aggregated and correlated. |
| Risk | Malicious activity may remain undetected, increasing the likelihood and potential impact of unauthorized access or data compromise. |

This distinction prevents the assessment from becoming a checklist and connects control deficiencies to potential business consequences.

---

## 4. Risk Statement Development

Each risk should communicate:

1. **What condition exists?**
2. **What could happen because of it?**
3. **What business or security objective could be affected?**

The risk register therefore documents the:

- Risk ID
- Risk domain
- Risk title
- Risk description
- Primary business/security impact
- Likelihood
- Impact
- Inherent risk score
- Treatment decision
- Treatment plan
- Risk owner
- NIST CSF function
- NIST CSF category
- Proposed residual risk
- Priority
- Target implementation period
- Business rationale

Risk statements should be understandable to both technical stakeholders and business leadership.

---

## 5. Likelihood Assessment

Likelihood represents the estimated probability that a risk event could occur under the organization's current conditions.

Factors considered include:

- Existing controls
- Exposure of the affected asset or information
- Accessibility of the affected environment
- Threat activity
- Nature and severity of the control weakness
- Frequency or recurrence of similar exposure
- Ability to prevent or detect the event
- Third-party dependencies
- Existing operational practices

### Likelihood Scale

| Rating | Score | Working Definition |
|---|---:|---|
| **Low** | 1 | Unlikely to occur under current conditions. |
| **Medium** | 2 | Possible and credible. |
| **High** | 4 | Likely to occur or recurring exposure exists. |
| **Very High** | 5 | Highly likely, broadly exposed, or capable of creating significant exposure. |

Likelihood ratings in this project represent analytical judgments based on the available case-study evidence.

---

## 6. Impact Assessment

Impact represents the potential consequence to Oscorp if the risk materializes.

The assessment considers the **CIA triad** as well as broader business consequences.

### Confidentiality

Potential unauthorized disclosure of information such as:

- Intellectual property
- Confidential project information
- Employee or customer information
- Credentials
- Business-sensitive data

### Integrity

Potential unauthorized modification, corruption, or destruction of:

- Business information
- Applications
- System configurations
- Financial or operational data
- Security records

### Availability

Potential disruption or loss of:

- Critical services
- Applications
- Infrastructure
- Data
- Business operations

### Business Consequences

Where applicable, impact also considers:

- Financial loss
- Operational disruption
- Regulatory consequences
- Legal exposure
- Reputational damage
- Loss of intellectual property
- Customer or partner impact

### Impact Scale

| Rating | Score | Working Definition |
|---|---:|---|
| **Low** | 1 | Limited operational or informational impact. |
| **Medium** | 2 | Material impact to a business process, asset, or stakeholder. |
| **High** | 4 | Significant financial, operational, regulatory, or reputational impact. |
| **Very High** | 5 | Severe enterprise-level impact or major loss of critical information or services. |

---

## 7. Inherent Risk Calculation

**Inherent risk** represents the estimated risk exposure before proposed additional treatment is implemented.

The scoring model used in the risk register is:

```text
Risk Score = Likelihood × Impact
```

### Risk Matrix

| Likelihood \\ Impact | Low (1) | Medium (2) | High (4) | Very High (5) |
|---|---:|---:|---:|---:|
| **Low (1)** | 1 | 2 | 4 | 5 |
| **Medium (2)** | 2 | 4 | 8 | 10 |
| **High (4)** | 4 | 8 | 16 | 20 |
| **Very High (5)** | 5 | 10 | 20 | 25 |

### Risk Rating Thresholds

| Score | Rating |
|---:|---|
| **1–8** | Low |
| **9–15** | Moderate |
| **16–25** | High |

**Example:** High likelihood (4) × High impact (4) = **16 — High Risk**.

The numerical score creates consistency and comparability across risks. It does **not** replace professional judgment or management decision-making.

---

## 8. Risk Treatment

Each assessed risk should be assigned an appropriate treatment strategy.

### Mitigate

Implement controls or process improvements intended to reduce likelihood, impact, or both.

Examples include MFA, least-privilege access, encryption, centralized logging, endpoint protection, incident-response procedures, and security awareness training.

### Transfer

Shift a portion of the financial or operational exposure to another party through mechanisms such as insurance, contractual requirements, or outsourced services.

Transfer does not remove Oscorp's responsibility for understanding and governing the underlying risk.

### Accept

Management knowingly accepts the risk because it falls within approved risk tolerance or because further treatment is not justified by cost, feasibility, or business impact.

Risk acceptance should be documented and approved by an appropriate authority.

### Avoid

Discontinue or materially change the activity creating the risk when the exposure cannot be reduced to an acceptable level or the business benefit does not justify the exposure.

---

## 9. Business-Aligned Treatment Decisions

Risk treatment should not be based solely on technical severity.

Treatment recommendations should consider:

- Risk severity
- Business criticality
- Regulatory or contractual obligations
- Available personnel
- Budget
- Implementation complexity
- Implementation timeline
- Dependencies between initiatives
- Operational disruption
- Existing security capabilities
- Expected reduction in risk

A technically ideal solution may not always be the best immediate business decision. For example, an organization with limited security personnel may initially use a managed security service rather than immediately building a fully staffed internal security operations center.

The preferred treatment is therefore one that produces meaningful risk reduction while remaining realistic for the organization to implement and sustain.

---

## 10. Residual Risk

**Residual risk** represents the estimated risk remaining after existing and proposed controls are considered.

```text
Identified Weakness
        ↓
    Inherent Risk
        ↓
    Risk Treatment
        ↓
Existing + Proposed Controls
        ↓
    Residual Risk
        ↓
Compare With Risk Tolerance
```

Residual risk should be reassessed after treatment is implemented and evidence exists to demonstrate control effectiveness.

If residual risk remains above Oscorp's approved risk tolerance, management should consider:

- Additional mitigation
- Transfer
- Avoidance
- Formal risk acceptance

> **Portfolio note:** The residual ratings in the Oscorp risk register are proposed estimates of the expected effect of treatment. They are not validated measurements of implemented controls.

---

## 11. Risk Prioritization

Risk scores provide an initial basis for prioritization, but roadmap sequencing also considers business context.

Prioritization factors include:

1. Inherent risk severity
2. Business criticality
3. Confidentiality, integrity, and availability impact
4. Regulatory or contractual exposure
5. Existing compensating controls
6. Remediation feasibility
7. Resource requirements
8. Dependencies on other initiatives
9. Time required to reduce exposure
10. Expected risk reduction

This means a risk with a lower numerical score may occasionally be addressed before a higher-scoring risk when it is a prerequisite for other initiatives, represents a quick reduction in exposure, or enables broader security improvements.

### Foundational Dependencies

For Oscorp, governance, enterprise risk management, asset visibility, access control, and incident-response planning are treated as foundational capabilities because weaknesses in these areas affect multiple downstream controls.

Centralized monitoring and SIEM capabilities are then introduced as organizational processes, asset visibility, logging requirements, and response responsibilities mature.

---

## 12. Risk Ownership

Each risk should have an accountable owner with sufficient authority to understand and manage the business exposure.

The risk owner is responsible for:

- Understanding the risk
- Coordinating treatment activities
- Monitoring changes in exposure
- Tracking remediation progress
- Escalating unresolved issues
- Supporting risk-acceptance decisions
- Providing evidence that treatment has been implemented

The cybersecurity function may advise on technical controls, but ownership of business risk ultimately belongs with the appropriate business or executive stakeholder.

---

## 13. Monitoring and Review

The risk register should operate as a living management tool rather than a one-time assessment.

Risks should be reviewed periodically and following significant events, including:

- Major technology changes
- Organizational changes
- New or emerging threats
- Security incidents
- Changes to critical business processes
- New regulatory or contractual requirements
- Completion of major remediation activities
- Changes in business priorities
- Changes in risk appetite or tolerance

Treatment status, target dates, ownership, and residual risk should be updated as new evidence becomes available.

---

## 14. NIST CSF Alignment

The NIST CSF provides the structure for evaluating Oscorp's cybersecurity capabilities.

| NIST CSF Function | Assessment Focus |
|---|---|
| **Identify** | Governance, risk management, assets, business environment, supply chain, and risk assessment |
| **Protect** | Access control, data security, awareness, configuration, maintenance, and protective technology |
| **Detect** | Continuous monitoring, event analysis, and detection processes |
| **Respond** | Incident response, communications, analysis, mitigation, and improvements |
| **Recover** | Recovery planning, communications, improvements, and restoration of capabilities |

The risk register maps each consolidated risk to the relevant NIST CSF function and categories, preserving traceability between assessment evidence and remediation.

---

## 15. Assessment-to-Risk Traceability

The `Risk Traceability` worksheet in the related risk register documents representative source findings used to develop each consolidated risk.

The methodology follows:

```text
Assessment Evidence
        ↓
Control Deficiency
        ↓
Consolidated Risk
        ↓
Likelihood + Impact
        ↓
Inherent Risk
        ↓
Treatment Plan
        ↓
Proposed Residual Risk
        ↓
Roadmap Initiative
```

This allows a reviewer to understand **why a risk exists, which assessment evidence supports it, and how the recommended remediation addresses it**.

---

## 16. Assumptions and Limitations

This assessment was completed as a **simulated GRC case study** using the information provided in the Oscorp scenario and associated NIST cybersecurity assessment materials.

The source assessment provides evidence regarding the current state of cybersecurity controls. However, complete quantitative information was not available for every risk, including:

- Actual financial-loss estimates
- Current threat intelligence
- Historical incident frequency
- Detailed asset valuations
- Exact remediation costs
- Complete staffing constraints
- Formal organizational risk appetite and tolerance

Where information was unavailable, **likelihood, impact, treatment priority, and proposed residual risk were estimated using professional judgment**.

Accordingly, the risk ratings and treatments in this repository are **illustrative portfolio analysis**, not an official assessment of a real organization.

In a production engagement, ratings and treatment decisions would be validated through stakeholder interviews, technical evidence, business-impact information, control testing, and management approval.

---

## 17. Relationship to the 3-Year Roadmap

The risk register serves as a primary input into Oscorp's cybersecurity roadmap.

### Year 1 — Establish the Foundation

Prioritize governance, enterprise risk management, asset visibility, access control, data protection, incident-response planning, endpoint protection, and other foundational/high-risk deficiencies.

### Year 2 — Build Security Maturity

Expand centralized logging and SIEM capabilities, detection processes, third-party risk management, investigation/forensics, secure configuration, and broader control maturity.

### Year 3 — Optimize and Sustain

Focus on automation, continuous monitoring, recurring control validation, recovery improvements, lessons learned, and continuous improvement.

Roadmap placement should be revisited as risk exposure, resources, dependencies, and business priorities change.

---

## 18. Methodology Summary

This methodology connects the individual elements of the Oscorp engagement into a defensible risk-management process:

> **NIST CSF → Current-State Assessment → Control Deficiency → Business Risk → Treatment → Residual Risk → Prioritization → 3-Year Roadmap**

The objective is not simply to determine whether a cybersecurity control passes or fails. The objective is to understand **what the deficiency means to the business, how significant the resulting risk is, what can realistically be done about it, and when that remediation should occur**.

Previous: [NIST Assessment Summary](Assessment/nist-assessment-summary.md) | Next: [Gap Assessment](Gap_Analysis/Oscorp_Gap_Assessment_Summary.md)
