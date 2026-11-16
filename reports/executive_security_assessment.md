# Cedar Ridge Services

## Executive Cybersecurity Assessment Report

**Assessment Framework:** NIST Cybersecurity Framework 2.0
**Assessment Date:** November 16, 2026
**Prepared For:** IT Manager and Executive Management
**Assessment Scope:** 20 selected NIST CSF 2.0 outcomes
**Status:** Final Assessment — Remediation Plan Pending Approval

---

## 1. Executive Summary

Cedar Ridge Services completed a cybersecurity gap assessment to evaluate existing security practices and identify opportunities to strengthen the organization's security posture.

The assessment reviewed security policies and supporting evidence across governance, asset management, access control, vulnerability management, monitoring, incident response, and recovery.

Of the 20 NIST CSF outcomes evaluated, 16 were classified as Partially Implemented and four remained Not Assessed due to insufficient supporting evidence.

Seven security findings were documented. Three were prioritized as High based on potential business impact, urgency, and implementation effort:

1. Vulnerability remediation tracking weaknesses
2. Inconsistent multi-factor authentication enforcement
3. Incomplete backup and recovery validation

These weaknesses could increase exposure to unauthorized access, service interruptions, and delayed recovery during security incidents.

A 90-day remediation roadmap has been developed to address the highest-priority concerns, improve security processes, and validate corrective actions.

## 2. Assessment Overview

The assessment compared Cedar Ridge Services' documented security practices against selected NIST CSF 2.0 outcomes.

The review included four security policies, six supporting evidence datasets, and an evidence request register covering 20 selected outcomes.

Implementation conclusions were based on the evidence reviewed rather than assumptions about company-wide control effectiveness.

### Implementation Results

| Implementation Status |     Outcomes |
| --------------------- | -----------: |
| Implemented           |            0 |
| Partially Implemented |           16 |
| Not Implemented       |            0 |
| Not Assessed          |            4 |
| **Total**       | **20** |

The results indicate that several cybersecurity practices are established but require stronger documentation, more consistent implementation, or additional supporting evidence.

The four Not Assessed outcomes require further investigation before conclusions can be reached.

## 3. Highest-Priority Security Findings

### Priority 1 — Vulnerability Remediation Tracking

**Finding:** GF-002
**Priority:** High
**Responsible Owner:** Engineering Lead

The vulnerability tracking report identified an overdue critical vulnerability affecting a cloud-hosted application. Another high-severity vulnerability had no documented remediation deadline.

**Business Risk:** Delayed remediation could increase the likelihood of system compromise, unauthorized access, or disruption to client-facing services.

**Recommended Action:** Investigate overdue vulnerabilities immediately, establish risk-based remediation deadlines, and require documented verification before closing remediation activities.

### Priority 2 — Inconsistent MFA Enforcement

**Finding:** GF-001
**Priority:** High
**Responsible Owner:** IT Administrator

Three of eight sampled application accounts did not enforce multi-factor authentication. One account referenced an exception without supporting approval documentation.

**Business Risk:** Inconsistent authentication safeguards may increase exposure to unauthorized access if employee credentials are compromised.

**Recommended Action:** Review company-wide MFA coverage, strengthen authentication requirements based on risk, and establish formal exception approval and review procedures.

### Priority 3 — Backup and Recovery Validation

**Finding:** GF-003
**Priority:** High
**Responsible Owner:** IT Manager

Backup restoration evidence identified one failed test, one scheduled test that was not performed, and one restoration that exceeded its recovery-time target.

**Business Risk:** Inadequately validated recovery processes could lead to prolonged downtime and disruption of critical business operations.

**Recommended Action:** Investigate failed restoration tests, establish recovery objectives, perform scheduled recovery testing, and retain documented validation evidence.

## 4. Additional Security Findings

Four additional findings were assigned Medium priority.

| Finding | Area                      | Recommended Improvement                                            |
| ------- | ------------------------- | ------------------------------------------------------------------ |
| GF-005  | Hardware Asset Management | Correct missing asset ownership and security configuration records |
| GF-007  | Incident Response         | Improve incident communication procedures and tabletop exercises   |
| GF-006  | Security Governance       | Formalize security responsibilities and policy review approvals    |
| GF-004  | Security Awareness        | Address overdue training and improve assignment tracking           |

Although these findings are lower in overall priority, several corrective actions may be achievable using existing personnel and company tools.

## 5. Outstanding Assessment Evidence

Four NIST CSF outcomes could not be fully evaluated because supporting documentation was not supplied.

| CSF Outcome | Evidence Required                                 |
| ----------- | ------------------------------------------------- |
| ID.AM-02    | Software and cloud service inventory              |
| PR.PS-04    | Audit logging configuration and retention records |
| DE.CM-03    | Security monitoring and alert review records      |
| DE.AE-03    | Multi-source security investigation records       |

These outcomes remain Not Assessed. Missing evidence does not establish that the underlying security practices are absent.

Management should assign responsibility for obtaining the documentation and reassess these outcomes once sufficient evidence is available.

## 6. Proposed 90-Day Remediation Strategy

The remediation plan is organized into three phases, beginning November 16, 2026 and concluding February 13, 2027.

### Phase 1 — Immediate Risk Reduction

**November 16 – December 15, 2026**

Address urgent vulnerabilities, review MFA coverage and exceptions, investigate failed backup testing, and resolve immediate asset inventory and training weaknesses.

Obtain outstanding evidence for the four Not Assessed outcomes.

### Phase 2 — Control Improvements

**December 16, 2026 – January 14, 2027**

Strengthen authentication procedures, recovery objectives, incident response communications, and security governance.

Formalize control ownership, exception handling, and required approval procedures.

### Phase 3 — Validation and Management Review

**January 15 – February 13, 2027**

Retest applicable security controls, review remediation evidence, update assessment results, and present remaining risks to management.

The roadmap contains 16 proposed tasks with assigned owners, target dates, and evidence requirements.

All activities remain planned until implementation and verification are documented.

## 7. Management Decisions Required

The following decisions are recommended for management review:

1. Approve the remediation priorities and proposed 90-day roadmap.
2. Confirm IT and engineering resources available for corrective actions.
3. Authorize immediate investigation and mitigation of overdue critical vulnerabilities.
4. Approve revised MFA requirements and exception management procedures.
5. Establish recovery objectives for critical business systems.
6. Review unresolved risks and determine appropriate treatment if remediation cannot be completed as planned.

Management should also establish regular progress reporting and escalation procedures for missed deadlines.

No remediation approvals or formal risk acceptance decisions are assumed in this report.

## 8. Conclusion

The assessment identified opportunities for Cedar Ridge Services to strengthen its cybersecurity program through more consistent control implementation, improved documentation, and stronger remediation oversight.

The immediate priorities are vulnerability remediation, authentication security, and backup recovery assurance.

The proposed 90-day roadmap provides a structured approach to addressing these concerns while considering the company's limited IT resources.

Implementing the recommended actions, obtaining outstanding evidence, and validating corrective measures will help management make more informed cybersecurity risk decisions.

---


## Supporting Documents

- [Current vs. Target Assessment](../assessment/current_target_profile.csv)
- [Security Gap Findings](../assessment/gap_findings.md)
- [Risk Prioritization Matrix](../assessment/risk_prioritization.csv)
- [90-Day Remediation Roadmap](../assessment/remediation_roadmap.csv)
- [Management Decisions & Resource Planning](../assessment/management_decisions.md)
- [Evidence Request Register](../evidence/evidence_request_register.csv)

*Portfolio case study based on a fictional organization and synthetic assessment evidence.*
