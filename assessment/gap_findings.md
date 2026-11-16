
# Cedar Ridge Services — Security Gap Findings

**Assessment:** NIST CSF 2.0 Gap Assessment
**Organization:** Cedar Ridge Services
**Scope:** 20 selected CSF outcomes

## 1. Assessment Summary

The assessment reviewed security policies and supporting evidence across governance, asset management, access control, security awareness, vulnerability management, monitoring, incident response, and recovery.

The review identified weaknesses requiring corrective action, along with areas where additional evidence is necessary before determining implementation effectiveness.

The findings below consolidate related observations from the Current vs. Target Profile.

## 2. Security Findings

### GF-001 — Inconsistent MFA Enforcement

**CSF Outcome:** PR.AA-03
**Evidence:** evidence/mfa_configuration_export.csv

**Observation:** Three of eight sampled application accounts do not enforce MFA. One account references exception EX-014 without supporting approval evidence.

**Business Impact:** Inconsistent authentication protections increase exposure to unauthorized access if employee credentials are compromised.

**Recommendation:** Establish risk-based MFA requirements across company applications, document approved exceptions, and verify enforcement across the complete account population.

### GF-002 — Vulnerability Remediation Tracking Weaknesses

**CSF Outcome:** ID.RA-01
**Evidence:** evidence/vulnerability_tracking_report.csv

**Observation:** VULN-004 remains open beyond its target date. VULN-006 has no remediation deadline. Supporting vulnerability scan evidence was not supplied.

**Business Impact:** Unresolved vulnerabilities may increase the likelihood of system compromise and disruption to client services.

**Recommendation:** Establish remediation timelines based on severity and business exposure, track overdue vulnerabilities, and require documented verification before closure.

### GF-003 — Incomplete Backup and Recovery Validation

**CSF Outcomes:** PR.DS-11, RC.RP-05
**Evidence:** evidence/backup_restoration_test_results.csv

**Observation:** One restoration test failed, another was not performed, and a completed restoration exceeded its four-hour target. Detailed testing evidence is limited.

**Business Impact:** The organization may experience extended downtime or data loss if recovery procedures do not perform as expected.

**Recommendation:** Define recovery objectives for critical systems, schedule regular restoration tests, investigate failures, and retain testing evidence and reviewer approvals.

### GF-004 — Incomplete Security Awareness Training

**CSF Outcome:** PR.AT-01
**Evidence:** evidence/security_awareness_training.csv

**Observation:** Seven of ten sampled employees completed assigned training. Two employees have overdue training and one was not assigned training.

**Business Impact:** Employees without appropriate security training may be less prepared to recognize phishing attempts and other common threats.

**Recommendation:** Establish consistent training assignments, completion tracking, overdue notifications, and periodic management reporting.

### GF-005 — Incomplete Hardware Asset Records

**CSF Outcome:** ID.AM-01
**Evidence:** evidence/hardware_asset_inventory.csv

**Observation:** LAP-005 is not enrolled in device management, LAP-006 lacks disk encryption, and LAP-007 has no assigned owner or verified security status.

**Business Impact:** Incomplete asset information makes it more difficult to maintain security protections and account for devices containing company information.

**Recommendation:** Maintain assigned asset owners, regularly reconcile the inventory, and investigate devices with missing management or encryption controls.

### GF-006 — Security Governance Documentation Gaps

**CSF Outcomes:** GV.RR-02, GV.PO-01, GV.PO-02
**Evidence:** policies/security_governance_policy.md

**Observation:** The governance policy identifies general responsibilities, but a formal responsibility matrix, documented executive approval, and policy review history were not supplied.

**Business Impact:** Unclear accountability and inconsistent policy oversight may delay security decisions and allow outdated practices to continue.

**Recommendation:** Formalize security ownership, document policy approvals, and establish a recurring review and revision process.

### GF-007 — Incident Response Exercise and Communication Gaps

**CSF Outcomes:** RS.MA-01, RS.CO-02, RS.MI-01
**Evidence:** evidence/incident_response_exercise_results.csv

**Observation:** One planned exercise was not performed. Completed exercises did not demonstrate notification testing, and supporting containment records were limited.

**Business Impact:** Inadequately tested response procedures could delay containment and stakeholder communication during a security incident.

**Recommendation:** Conduct scheduled incident exercises, define notification triggers and responsibilities, and retain documented response decisions and corrective actions.

## 3. Outstanding Evidence

The following areas remain Not Assessed because sufficient evidence has not been provided.

| CSF Outcome | Outstanding Evidence |
|---|---|
| ID.AM-02 | Maintained software and cloud service inventory |
| PR.PS-04 | Audit logging configuration and retention records |
| DE.CM-03 | Security monitoring and alert review records |
| DE.AE-03 | Multi-source security event investigation records |

These items are evidence limitations, not confirmed failures of the underlying security practices.

Additional documentation is required before reaching an implementation conclusion.

## 4. Next Actions

The findings will be evaluated for business impact, urgency, and implementation effort.

A prioritized 90-day improvement roadmap will be developed in the next assessment phase.

Outstanding evidence requests will remain open until sufficient documentation is available for review.
