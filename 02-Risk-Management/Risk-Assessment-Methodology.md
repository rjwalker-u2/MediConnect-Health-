# MediConnect Health
## Information Security Risk Assessment Methodology

**Document Owner:** Information Security  
**Version:** 1.0  
**Classification:** Internal

---

## 1. Purpose

The purpose of this document is to establish a consistent approach for identifying, analyzing, evaluating, and prioritizing information security risks within the MediConnect Health Information Security Management System (ISMS).

This methodology supports ISO/IEC 27001-aligned risk management by establishing defined criteria for evaluating the likelihood and impact of risks affecting the confidentiality, integrity, and availability of information and systems.

The methodology applies to the people, processes, information assets, technologies, and third-party dependencies identified within the MediConnect Health ISMS scope.

## 2. Risk Assessment Process

MediConnect Health follows a structured risk assessment process:

1. **Identify:** Identify information assets, threats, vulnerabilities, and potential risk scenarios.
2. **Analyze:** Evaluate each risk based on its likelihood and potential business impact.
3. **Evaluate:** Calculate risk scores and compare them against established risk acceptance criteria.
4. **Prioritize:** Determine which risks require attention based on their severity and business significance.
5. **Treat:** Select appropriate risk treatment options and assign responsible risk owners.
6. **Monitor:** Review risks, track treatment activities, and reassess risks when circumstances change.

Risk assessments are performed when significant changes occur and as part of the organization's established risk review schedule.

## 3. Impact Criteria

MediConnect Health evaluates the potential impact of an information security risk using a five-level scale.

| Rating | Impact Level | Description |
|---|---|---|
| 1 | Insignificant | Minimal effect on business operations, information, or systems. No significant impact to sensitive information. |
| 2 | Minor | Limited operational or information impact that can be resolved through normal business processes. |
| 3 | Moderate | Noticeable impact to business operations, systems, or sensitive information that may require management attention and remediation. |
| 4 | Major | Significant impact involving sensitive information, critical systems, business operations, compliance obligations, or external stakeholders. |
| 5 | Severe/Critical | Severe impact involving PHI/PII exposure, prolonged disruption of critical services, significant regulatory or legal consequences, or substantial harm to the organization or affected individuals. |

## 4. Likelihood Criteria

MediConnect Health evaluates the likelihood of an information security risk using a five-level scale.

| Rating | Likelihood Level | Description |
|---|---|---|
| 1 | Rare | The risk scenario is highly unlikely to occur and would require exceptional circumstances. |
| 2 | Unlikely | The risk scenario could occur but is not expected under normal circumstances. |
| 3 | Possible | The risk scenario could reasonably occur based on existing threats, vulnerabilities, and environmental conditions. |
| 4 | Likely | The risk scenario has a strong possibility of occurring due to credible threats, known weaknesses, or insufficient controls. |
| 5 | Almost Certain | The risk scenario is expected to occur or there is strong evidence that it is already occurring or imminent. |

## 5. Risk Scoring

MediConnect Health calculates risk using the following formula:

**Risk Score = Likelihood × Impact**

Risk scores range from 1 to 25 and are categorized according to the following severity levels:

| Risk Score | Risk Level | General Response |
|---|---|---|
| 1–4 | Low | Risk may be accepted and monitored through normal business processes. |
| 5–9 | Moderate | Risk should be monitored and treatment considered based on business context. |
| 10–16 | High | Risk treatment should be prioritized and tracked to completion. |
| 17–25 | Critical | Immediate management attention and prioritized risk treatment are required. |

## 6. Risk Treatment

MediConnect Health selects risk treatment actions based on the severity, business impact, and context of identified risks.

Available risk treatment options include:

- **Mitigate:** Implement or improve controls to reduce the likelihood or impact of the risk.
- **Accept:** Formally acknowledge and retain the risk when it falls within approved risk acceptance criteria.
- **Avoid:** Discontinue or modify the activity that creates the risk.
- **Transfer:** Transfer or share portions of the financial or operational impact through contractual arrangements, insurance, or third-party agreements.

Risk treatment decisions must identify appropriate actions, responsible owners, and expected completion timelines. Following treatment, the remaining residual risk should be reassessed and documented.

## 7. Inherent and Residual Risk

MediConnect Health evaluates risk before and after the consideration or implementation of security controls.

- **Inherent Risk:** The level of risk that exists before considering the effectiveness of risk treatment and applicable security controls.

- **Residual Risk:** The level of risk that remains after security controls and risk treatment measures have been implemented and evaluated.

Residual risk is reassessed using the established likelihood and impact criteria. Risks that remain above the organization's approved risk acceptance threshold require additional treatment, formal risk acceptance, or further management review.

## 8. Risk Ownership

Each identified information security risk must be assigned to an appropriate risk owner.

The risk owner is the individual or business function with responsibility and authority over the area affected by the risk. Risk owners are responsible for reviewing identified risks, supporting treatment decisions, coordinating remediation activities, and monitoring the risk within their area of responsibility.

Information Security and GRC personnel support the risk management process by identifying, assessing, documenting, monitoring, and reporting risks but do not automatically own risks identified within other business or technology functions.

## 9. Risk Acceptance

Risk acceptance decisions must follow established approval requirements based on the residual risk level.

| Residual Risk Level | Required Acceptance Authority |
|---|---|
| Low | Risk Owner |
| Moderate | Department Manager or Risk Owner |
| High | Senior Management with Information Security/GRC review |
| Critical | Executive Leadership with Information Security/GRC review |

Risk acceptance must be documented and include the identified risk, business justification, current controls, residual risk level, approving authority, and planned review date.

Critical risks should generally be prioritized for additional treatment. Formal acceptance of a Critical risk requires documented executive approval and justification.

## 10. Risk Monitoring and Review

Information security risks are monitored and reviewed to ensure that risk ratings, controls, treatment activities, and residual risk levels remain appropriate.

Risks should be reassessed:

- At established periodic review intervals.
- When significant technology or system changes occur.
- When new third-party relationships or integrations are introduced.
- Following significant security incidents.
- When new vulnerabilities or threats could materially affect the risk.
- When existing controls are significantly changed or determined to be ineffective.
- When business, regulatory, or compliance requirements materially change.

Risk owners, with support from Information Security and GRC personnel, are responsible for ensuring that identified risks remain current and that treatment activities are appropriately tracked.

## 11. Risk Documentation

Identified information security risks must be documented and maintained within the MediConnect Health Risk Register.

Each risk record should include, as applicable:

- Unique Risk ID
- Risk title and description
- Affected asset, system, process, or third party
- Threat and vulnerability or control weakness
- Potential business and security impact
- Inherent likelihood rating
- Inherent impact rating
- Inherent risk score and severity
- Existing controls
- Selected risk treatment
- Risk owner
- Remediation or treatment actions
- Target completion date
- Treatment status
- Residual likelihood rating
- Residual impact rating
- Residual risk score and severity
- Validation or control effectiveness testing results
- Risk acceptance or approval information, when applicable
- Risk review date
