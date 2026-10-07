# MediConnect Health — Risk Treatment Plan

## 1. Purpose

The purpose of this Risk Treatment Plan is to document how MediConnect Health will address information security risks identified through the ISMS risk assessment process.

The plan defines selected risk treatment options, required remediation actions, responsible risk owners, target completion dates, and methods for validating that risk treatments have been implemented effectively.

Risk treatment activities are prioritized based on the risk ratings and acceptance criteria defined in the MediConnect Health Risk Assessment Methodology.

## 2. Risk Treatment Approach

MediConnect Health uses the following risk treatment options:

- **Mitigate:** Implement or improve controls to reduce the likelihood and/or impact of the risk.
- **Accept:** Formally acknowledge and retain the risk when it falls within the organization's risk acceptance criteria or when further treatment is not justified.
- **Avoid:** Eliminate the activity, system, process, or condition creating the risk.
- **Transfer:** Shift or share portions of the risk through third parties, contractual agreements, insurance, or other mechanisms.

Risk treatment decisions consider the risk level, business requirements, regulatory and contractual obligations, existing controls, treatment feasibility, and the projected residual risk following treatment.## 2. Risk Treatment Approach

MediConnect Health uses the following risk treatment options:

- **Mitigate:** Implement or improve controls to reduce the likelihood and/or impact of the risk.
- **Accept:** Formally acknowledge and retain the risk when it falls within the organization's risk acceptance criteria or when further treatment is not justified.
- **Avoid:** Eliminate the activity, system, process, or condition creating the risk.
- **Transfer:** Shift or share portions of the risk through third parties, contractual agreements, insurance, or other mechanisms.

Risk treatment decisions consider the risk level, business requirements, regulatory and contractual obligations, existing controls, treatment feasibility, and the projected residual risk following treatment.

## 3. Risk Treatment Actions

### R-001 — Unauthorized Administrative Access Due to Missing MFA

**Risk Level:** Critical  
**Treatment Option:** Mitigate  
**Risk Owner:** IAM Manager  
**Target Completion Date:** October 30, 2026

#### Treatment Objective
Reduce the likelihood of unauthorized administrative access by requiring multi-factor authentication for all administrative users accessing the Patient Portal administration environment.

#### Implementation Actions
1. Identify all administrative accounts with access to the Patient Portal administration environment.
2. Configure MFA requirements for administrative access.
3. Enroll all authorized administrative users in the approved MFA method.
4. Test authentication to verify that administrative access cannot be completed using only a username and password.
5. Review administrative access permissions and remove unnecessary or unauthorized access.
6. Document MFA configuration, enrollment, and testing results.

#### Validation
The IAM Manager will provide MFA configuration records and administrator enrollment records. Authentication testing will be performed to verify that administrative users cannot access the environment without completing MFA.

#### Projected Residual Risk
- **Likelihood:** 2 — Unlikely
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 10
- **Risk Level:** High

#### Treatment Status
In Progress

### R-002 — Former Employee Accounts Remain Active

**Risk Level:** High  
**Treatment Option:** Mitigate  
**Risk Owner:** IAM Manager  
**Target Completion Date:** November 6, 2026

#### Treatment Objective
Reduce the risk of unauthorized access by ensuring accounts belonging to terminated employees are promptly disabled and the employee offboarding process consistently triggers access revocation.

#### Implementation Actions
1. Identify and disable all active accounts belonging to former employees.
2. Reconcile active user accounts against current workforce records.
3. Establish a formal HR-to-IAM termination notification process.
4. Define required timeframes for revoking access following termination.
5. Perform periodic account reviews to identify unauthorized or orphaned accounts.
6. Document account revocation and retain evidence of completed offboarding activities.

#### Validation
Review updated account reports and reconcile active accounts against current employee records. Sample terminated employees and verify HR offboarding records or IAM tickets demonstrate timely access revocation.

#### Projected Residual Risk
- **Likelihood:** 1 — Rare
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 5
- **Risk Level:** Moderate

#### Treatment Status
In Progress


### R-003 — Critical Vulnerabilities Not Remediated Timely

**Risk Level:** Critical  
**Treatment Option:** Mitigate  
**Risk Owner:** Vulnerability Management Manager  
**Target Completion Date:** November 13, 2026

#### Treatment Objective
Reduce the likelihood that known critical vulnerabilities can be exploited by establishing and enforcing timely vulnerability remediation requirements.

#### Implementation Actions
1. Establish remediation timeframes based on vulnerability severity.
2. Prioritize critical vulnerabilities affecting high-value or sensitive systems.
3. Assign remediation actions to responsible system owners.
4. Track vulnerabilities that exceed established remediation deadlines.
5. Escalate overdue critical vulnerabilities when required.
6. Rescan affected systems to verify successful remediation.

#### Validation
Review vulnerability scan results, remediation tickets, and vulnerability aging reports. Rescan affected systems to confirm critical vulnerabilities have been remediated.

#### Projected Residual Risk
- **Likelihood:** 2 — Unlikely
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 10
- **Risk Level:** High

#### Treatment Status
In Progress


### R-004 — Third-Party Vendor Lacks Adequate Security Requirements

**Risk Level:** High  
**Treatment Option:** Mitigate  
**Risk Owner:** Third-Party Risk Manager  
**Target Completion Date:** November 20, 2026

#### Treatment Objective
Reduce third-party security and privacy risk by establishing appropriate security requirements and ongoing oversight for vendors processing patient information.

#### Implementation Actions
1. Perform a security risk assessment of the patient communication provider.
2. Identify security and privacy requirements applicable to the vendor relationship.
3. Establish contractual security requirements and incident notification obligations.
4. Document and track remediation of identified vendor security gaps.
5. Establish periodic vendor security reassessments.
6. Maintain evidence of vendor reviews, findings, and remediation activities.

#### Validation
Review the completed vendor risk assessment, contractual security requirements, remediation documentation, and evidence that periodic reassessment has been scheduled.

#### Projected Residual Risk
- **Likelihood:** 2 — Unlikely
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 10
- **Risk Level:** High

#### Treatment Status
In Progress


### R-005 — Security Incidents Not Detected or Escalated Timely

**Risk Level:** High  
**Treatment Option:** Mitigate  
**Risk Owner:** Security Operations Manager  
**Target Completion Date:** November 27, 2026

#### Treatment Objective
Improve MediConnect Health's ability to identify, investigate, and escalate security incidents before they result in greater system or information impact.

#### Implementation Actions
1. Define incident severity and classification criteria.
2. Establish incident escalation requirements and responsibilities.
3. Review and configure appropriate SIEM monitoring and alerting.
4. Define response procedures for security alerts and incidents.
5. Test incident detection and escalation procedures through a simulated scenario.
6. Document testing results and remediate identified process gaps.

#### Validation
Review SIEM alert configurations, incident response procedures, sample incident tickets, escalation records, and results from incident response testing.

#### Projected Residual Risk
- **Likelihood:** 2 — Unlikely
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 10
- **Risk Level:** High

#### Treatment Status
In Progress


### R-006 — Patient Portal Backups Not Adequately Tested

**Risk Level:** High  
**Treatment Option:** Mitigate  
**Risk Owner:** IT Infrastructure Manager  
**Target Completion Date:** December 4, 2026

#### Treatment Objective
Improve the ability to recover the Patient Portal and critical information following a system failure, ransomware incident, or other disruption.

#### Implementation Actions
1. Establish a scheduled backup restoration testing process.
2. Define recovery requirements for critical Patient Portal systems and information.
3. Assign responsibility for performing and documenting restoration tests.
4. Conduct restoration testing using selected backups.
5. Document failures identified during testing and assign remediation actions.
6. Retain evidence demonstrating successful restoration.

#### Validation
Review backup logs, restoration test results, recovery documentation, identified failures, and remediation records. Verify through testing that selected backups can be successfully restored.

#### Projected Residual Risk
- **Likelihood:** 1 — Rare
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 5
- **Risk Level:** Moderate

#### Treatment Status
In Progress


### R-007 — PHI and PII Not Adequately Protected

**Risk Level:** High  
**Treatment Option:** Mitigate  
**Risk Owner:** Information Security Manager  
**Target Completion Date:** December 11, 2026

#### Treatment Objective
Reduce the likelihood of unauthorized access to or disclosure of PHI and PII by strengthening protections around sensitive information.

#### Implementation Actions
1. Identify systems and locations where PHI and PII are stored or processed.
2. Review access permissions for sensitive information.
3. Restrict access based on business need and least privilege.
4. Verify appropriate encryption protections are implemented.
5. Conduct periodic access reviews for systems containing sensitive information.
6. Document identified access issues and remediation activities.

#### Validation
Review the data inventory, access-control configurations, encryption settings, and access-review results. Test a sample of user permissions to verify that access to sensitive information is appropriately restricted.

#### Projected Residual Risk
- **Likelihood:** 2 — Unlikely
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 10
- **Risk Level:** High

#### Treatment Status
In Progress


### R-008 — Cloud Storage Misconfiguration Exposes Sensitive Information

**Risk Level:** High  
**Treatment Option:** Mitigate  
**Risk Owner:** Cloud Infrastructure Manager  
**Target Completion Date:** December 18, 2026

#### Treatment Objective
Reduce the likelihood of sensitive information exposure caused by insecure cloud storage configurations or excessive permissions.

#### Implementation Actions
1. Establish secure configuration requirements for cloud storage.
2. Review existing storage permissions and public-access settings.
3. Restrict access according to least-privilege principles.
4. Remediate identified cloud configuration weaknesses.
5. Implement automated monitoring for insecure configurations where available.
6. Perform periodic cloud permission and configuration reviews.

#### Validation
Review cloud storage permissions, configuration assessment results, remediation records, and monitoring alerts. Test selected storage resources to verify they are not publicly accessible.

#### Projected Residual Risk
- **Likelihood:** 1 — Rare
- **Impact:** 5 — Severe/Critical
- **Risk Score:** 5
- **Risk Level:** Moderate

#### Treatment Status
In Progress
