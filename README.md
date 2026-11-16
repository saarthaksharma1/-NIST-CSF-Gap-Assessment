# NIST CSF 2.0 Gap Assessment

### Cedar Ridge Services | Cybersecurity Risk & Compliance Project

A NIST Cybersecurity Framework (CSF) 2.0 gap assessment of Cedar Ridge Services, a fictional 50-employee IT services company.

The assessment evaluates existing security policies and supporting evidence, identifies weaknesses in cybersecurity practices, and develops a risk-based remediation plan aligned with business priorities.

## Project Overview

The objective was to assess how effectively Cedar Ridge Services manages cybersecurity risks across its operations.

I evaluated 20 selected NIST CSF 2.0 outcomes across all six functions: Govern, Identify, Protect, Detect, Respond, and Recover.

The assessment included:

- Reviewing company security policies and supporting evidence.
- Comparing current cybersecurity practices against target outcomes.
- Evaluating control implementation and identifying security gaps.
- Prioritizing findings based on business impact, urgency, and remediation effort.
- Developing a 90-day remediation roadmap and executive management report.

## Assessment Results

| Assessment Metric | Result |
|---|---|
| NIST CSF Outcomes Evaluated | 20 |
| Partially Implemented | 16 |
| Not Assessed | 4 |
| Documented Security Findings | 7 |
| High-Priority Findings | 3 |
| Proposed Remediation Tasks | 16 |

Four outcomes remained Not Assessed because sufficient supporting evidence was unavailable. Missing documentation was not automatically treated as evidence of a failed control.

## Key Security Findings

The assessment identified three high-priority areas requiring management attention.

**1. Vulnerability Remediation**

An overdue critical cloud application vulnerability and incomplete remediation deadlines highlighted weaknesses in vulnerability management.

**2. Multi-Factor Authentication**

Three of eight sampled accounts lacked MFA enforcement, and an authentication exception required additional approval evidence.

**3. Backup and Recovery**

Restoration testing identified a failed test, a missed exercise, and a recovery that exceeded its target recovery time.

Additional findings involved hardware inventory accuracy, security awareness training, security governance, and incident response readiness.

## Remediation Strategy

A 90-day remediation roadmap was developed to address the identified findings and outstanding assessment evidence.

| Phase | Timeline | Focus |
|---|---|---|
| Phase 1 | Nov 16 – Dec 15, 2026 | Immediate risk reduction |
| Phase 2 | Dec 16, 2026 – Jan 14, 2027 | Security control improvements |
| Phase 3 | Jan 15 – Feb 13, 2027 | Validation and management review |

Each proposed action includes an assigned owner, target date, priority, and evidence required to demonstrate completion.

## Project Documentation

### Assessment

- [NIST CSF Outcome Mapping](assessment/csf_outcome_mapping.md)
- [Assessment Methodology](assessment/assessment_methodology.md)
- [Control and Business Risk Rationale](assessment/control_risk_rationale.md)
- [Current vs. Target Assessment](assessment/current_target_profile.csv)
- [Security Gap Findings](assessment/gap_findings.md)
- [Risk Prioritization Matrix](assessment/risk_prioritization.csv)
- [90-Day Remediation Roadmap](assessment/remediation_roadmap.csv)
- [Management Decisions and Resource Planning](assessment/management_decisions.md)

### Executive Reporting

- [Executive Security Assessment Report](reports/executive_security_assessment.md)

### Supporting Documentation

- [Company Profile](company/company_profile.md)
- [Evidence Request Register](evidence/evidence_request_register.csv)

The `policies/` directory includes four cybersecurity policies, while `evidence/` contains six supporting security datasets.

## Tools and Skills

**Framework:** NIST Cybersecurity Framework 2.0

**Tools:** Microsoft Excel, CSV, Markdown, VS Code, Git, GitHub

**Skills Demonstrated:** Security risk assessment, control evaluation, policy analysis, evidence review, NIST CSF mapping, gap analysis, remediation prioritization, and executive reporting.

---

*This project is a portfolio case study involving a fictional organization and synthetic security evidence. Findings and recommendations demonstrate an assessment methodology rather than results from a live enterprise engagement.