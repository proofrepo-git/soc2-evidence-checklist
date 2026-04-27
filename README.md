# SOC 2 Type II Evidence Checklist

A comprehensive, open-source checklist of evidence items organized by AICPA Trust Services Criteria (TSC). Use this as a starting point for SOC 2 Type II audit preparation.

Built and maintained by [ProofRepo](https://proofrepo.com) — audit evidence collection on autopilot.

---

## How to Use This Checklist

1. **Copy this repo** or fork it to track your own audit readiness
2. **Check off items** as you collect evidence for each control
3. **Customize** — add or remove items based on your auditor's request list
4. **Map to your controls** — each section maps to a TSC category

> **Pro tip:** [ProofRepo](https://proofrepo.com) automates evidence collection for SOC 2, ISO 27001, HIPAA, and more. Skip the spreadsheet — send one link, get organized evidence back.

---

## CC: Common Criteria (Security)

### CC1 — Control Environment

- [ ] Organization chart with reporting lines
- [ ] Board of Directors meeting minutes (or equivalent governance body)
- [ ] Code of conduct / ethics policy (signed by employees)
- [ ] Background check policy and evidence of execution
- [ ] Job descriptions for key roles (security, engineering, compliance)
- [ ] Employee handbook or onboarding documentation
- [ ] Security awareness training completion records
- [ ] Annual performance review process documentation

### CC2 — Communication and Information

- [ ] Internal communication policy (security updates, incidents)
- [ ] External communication policy (customer notifications, breach disclosure)
- [ ] System description document (for auditor / SOC 2 report)
- [ ] Data flow diagrams
- [ ] Network architecture diagrams
- [ ] Asset inventory (hardware, software, data stores)
- [ ] Third-party communication procedures

### CC3 — Risk Assessment

- [ ] Risk assessment policy and methodology
- [ ] Annual risk assessment report
- [ ] Risk register with identified risks, likelihood, impact, and mitigations
- [ ] Fraud risk assessment
- [ ] Risk acceptance documentation (for residual risks)
- [ ] Vendor/third-party risk assessment process

### CC4 — Monitoring Activities

- [ ] Continuous monitoring policy
- [ ] Internal audit schedule and reports
- [ ] Management review of control effectiveness
- [ ] Exception and deficiency tracking log
- [ ] Penetration test reports (annual)
- [ ] Vulnerability scan reports (quarterly or continuous)
- [ ] SOC 2 readiness assessment (if first audit)

### CC5 — Control Activities

- [ ] Information security policy (master policy document)
- [ ] Logical access policy
- [ ] Change management policy
- [ ] Incident response policy
- [ ] Data classification policy
- [ ] Encryption policy
- [ ] Acceptable use policy
- [ ] Remote work / BYOD policy

### CC6 — Logical and Physical Access Controls

- [ ] User access provisioning procedures
- [ ] User access review logs (quarterly)
- [ ] Terminated user access revocation evidence
- [ ] Multi-factor authentication (MFA) configuration evidence
- [ ] Role-based access control (RBAC) matrix
- [ ] Privileged access management procedures
- [ ] SSH key / API key rotation policy and evidence
- [ ] Password policy configuration screenshots
- [ ] Physical access controls (badge logs, visitor logs, data center access)
- [ ] Firewall rules and network segmentation evidence
- [ ] VPN configuration and access logs
- [ ] Endpoint protection / MDM enrollment evidence

### CC7 — System Operations

- [ ] System monitoring and alerting configuration (PagerDuty, Datadog, etc.)
- [ ] Incident response plan
- [ ] Incident response test / tabletop exercise results
- [ ] Incident log (all security incidents during audit period)
- [ ] Malware / antivirus protection evidence
- [ ] Patch management policy and evidence of patching cadence
- [ ] Capacity planning documentation
- [ ] System uptime / SLA reports

### CC8 — Change Management

- [ ] Change management policy
- [ ] Change advisory board (CAB) meeting notes or approval records
- [ ] Code review evidence (pull request approvals)
- [ ] CI/CD pipeline configuration (automated testing, deployment gates)
- [ ] Release management procedures
- [ ] Emergency change procedures
- [ ] Separation of duties evidence (dev vs. prod access)
- [ ] Version control system access and branch protection rules

### CC9 — Risk Mitigation (Vendor Management)

- [ ] Vendor management policy
- [ ] Critical vendor inventory list
- [ ] Vendor SOC 2 reports or equivalent security assessments
- [ ] Vendor contracts with security/privacy clauses
- [ ] Annual vendor review documentation
- [ ] Subservice organization monitoring procedures
- [ ] Business associate agreements (BAAs) where applicable

---

## A: Availability

- [ ] Business continuity plan (BCP)
- [ ] Disaster recovery plan (DRP)
- [ ] BCP/DRP test results (annual)
- [ ] Recovery time objective (RTO) and recovery point objective (RPO) definitions
- [ ] Backup policy and schedule
- [ ] Backup restoration test results
- [ ] Infrastructure redundancy documentation (multi-AZ, failover)
- [ ] Uptime monitoring and SLA adherence reports
- [ ] Capacity planning and scaling procedures
- [ ] Incident communication plan for outages

---

## PI: Processing Integrity

- [ ] Data processing procedures and workflows
- [ ] Input validation controls
- [ ] Output reconciliation procedures
- [ ] Error handling and correction procedures
- [ ] Quality assurance / QA testing documentation
- [ ] Data integrity monitoring and alerting
- [ ] Processing accuracy reports or dashboards
- [ ] SLA compliance reports

---

## C: Confidentiality

- [ ] Data classification policy
- [ ] Encryption at rest evidence (database, storage, backups)
- [ ] Encryption in transit evidence (TLS/SSL certificates, HTTPS enforcement)
- [ ] Data retention and disposal policy
- [ ] Data disposal evidence (certificate of destruction, secure wipe logs)
- [ ] NDA / confidentiality agreements (employees and contractors)
- [ ] DLP (Data Loss Prevention) configuration or controls
- [ ] Sensitive data access logging

---

## P: Privacy

- [ ] Privacy policy (public-facing)
- [ ] Privacy impact assessment
- [ ] Data subject access request (DSAR) procedures
- [ ] Consent management procedures
- [ ] Data processing agreements (DPAs) with vendors
- [ ] Personal data inventory / data mapping
- [ ] Privacy training records
- [ ] Cookie / tracking consent implementation
- [ ] Data breach notification procedures
- [ ] Cross-border data transfer documentation (if applicable)

---

## Bonus: Audit-Day Prep

- [ ] System description document finalized
- [ ] Control owner matrix (who owns what)
- [ ] Evidence organized by control ID
- [ ] Prior year findings remediation evidence
- [ ] Management assertion letter drafted
- [ ] Auditor access provisioned (read-only)
- [ ] Point of contact list for auditor questions
- [ ] Timeline and milestones agreed with auditor

---

## About This Checklist

This checklist covers the five Trust Services Criteria categories defined by the AICPA for SOC 2 Type II engagements. It is meant as a **starting point** — your auditor will provide a specific request list tailored to your environment.

**Not every item applies to every organization.** Work with your auditor to determine which TSC categories are in scope (Security is always required; Availability, Processing Integrity, Confidentiality, and Privacy are optional).

### Contributing

Found something missing? Open a PR or issue. This is a community resource.

### License

MIT — use it however you want.

---

**Want to automate evidence collection instead of tracking it in a spreadsheet?**
Check out [ProofRepo](https://proofrepo.com) — built for vCISOs, compliance consultants, and audit firms.
# soc2-evidence-checklist
Open-source SOC 2 Type II evidence checklist organized by Trust Services Criteria. Free resource for auditors, vCISOs, and compliance teams.
