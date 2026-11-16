
# Control and Business Risk Rationale

**Company:** Cedar Ridge Services  
**Framework:** NIST CSF 2.0  
**Assessment Scope:** 20 selected outcomes

## 1. Purpose

This document explains why the selected cybersecurity outcomes matter to Cedar Ridge Services and identifies the security practices that should be assessed.

The company has approximately 50 employees, relies heavily on cloud services, and has a small IT team with shared cybersecurity responsibilities.

The risks below are potential business exposures, not confirmed assessment findings.

## 2. Governance

| CSF ID | Business Risk | Control or Practice to Evaluate |
|---|---|---|
| GV.RR-02 | Unclear security responsibilities could delay decisions and leave important tasks unassigned. | Documented security roles and assigned responsibilities |
| GV.PO-01 | Without an approved security policy, employees may follow inconsistent security practices. | Management-approved cybersecurity policy |
| GV.PO-02 | Outdated policies may not address changes in technology, business operations, or threats. | Periodic policy reviews and documented approvals |

## 3. Identify

| CSF ID | Business Risk | Control or Practice to Evaluate |
|---|---|---|
| ID.AM-01 | Untracked laptops could expose company or client information if lost or improperly managed. | Hardware asset inventory |
| ID.AM-02 | Unknown applications could introduce security vulnerabilities or unauthorized data sharing. | Software and cloud application inventory |
| ID.RA-01 | Unidentified vulnerabilities could be exploited before the IT team addresses them. | Vulnerability scanning and tracking |
| ID.RA-05 | Without consistent risk evaluation, limited security resources may be spent on lower-priority issues. | Risk assessment methodology |

## 4. Protect

| CSF ID | Business Risk | Control or Practice to Evaluate |
|---|---|---|
| PR.AA-01 | Former employees may retain application access after termination. | Account provisioning and deprovisioning procedures |
| PR.AA-03 | Stolen passwords could allow unauthorized access to company systems. | Authentication requirements and MFA enforcement |
| PR.AA-05 | Excessive permissions could expose sensitive information or allow unauthorized changes. | Least-privilege access and periodic access reviews |
| PR.AT-01 | Employees may fall victim to phishing or mishandle sensitive information. | Security awareness training |
| PR.DS-11 | Inadequate backups or untested recovery processes could cause prolonged business disruption. | Backup management and restoration testing |
| PR.PS-04 | Missing or poorly retained logs could prevent investigation of security incidents. | Audit logging and retention procedures |

## 5. Detect

| CSF ID | Business Risk | Control or Practice to Evaluate |
|---|---|---|
| DE.CM-03 | Suspicious account or system activity may go unnoticed. | Security monitoring and alert review procedures |
| DE.AE-03 | Separate security alerts may not reveal a larger attack without correlation. | Multi-source event investigation procedures |

## 6. Respond

| CSF ID | Business Risk | Control or Practice to Evaluate |
|---|---|---|
| RS.MA-01 | An untested incident response process could delay investigation and decision-making. | Incident response plan and tabletop exercises |
| RS.CO-02 | Delayed incident notifications could prevent stakeholders from taking necessary action. | Incident notification and escalation procedures |
| RS.MI-01 | Failure to contain a security incident could increase its impact on company systems. | Incident containment procedures |

## 7. Recover

| CSF ID | Business Risk | Control or Practice to Evaluate |
|---|---|---|
| RC.RP-01 | Unclear recovery procedures could extend downtime after an incident. | Documented recovery plan and recovery exercises |
| RC.RP-05 | Systems might be returned to operation without confirming they are functioning correctly. | Post-recovery system validation |

## 8. Assessment Approach

For each selected outcome, the assessment will:

1. Identify the relevant company process or security practice.
2. Review the related policy and supporting evidence.
3. Determine what is currently implemented.
4. Compare the current practice with the company's desired outcome.
5. Document any gaps or limitations in the evidence.
6. Recommend improvements based on business risk.

A control will not be considered effective solely because a policy exists. Where applicable, supporting evidence will be needed to demonstrate implementation and operation.
