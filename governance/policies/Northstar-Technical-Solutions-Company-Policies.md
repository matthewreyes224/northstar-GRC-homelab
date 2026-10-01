# Northstar Technical Solutions Company Policies

## Table of Contents

1. Information Security Policy
2. Access Control Policy
3. Password and Authentication Standard
4. Risk Management Policy
5. Incident Response Policy
6. Vulnerability Management Policy
7. Backup and Recovery Policy
8. Acceptable Use Policy
9. Data Classification and Handling Policy
10. Third-Party Risk Management Policy

---

## 1. Information Security Policy

### Purpose
Establish the security governance baseline for Northstar Technical Solutions and define how security requirements are translated into implemented, testable controls.

### Current Lab Application
The lab uses pfSense, Windows Server, Hyper-V, and documented control evidence to demonstrate how security governance maps to technical implementation.

### Technical Stakeholder Example
A policy requiring network protection is not satisfied by the existence of a firewall alone. Evidence should show the intended firewall configuration, approved rule purpose, actual rule implementation, and a test demonstrating that unauthorized traffic is blocked.

---

## 2. Access Control Policy

### Purpose
Limit access to systems and information according to business need, administrative role, and least-privilege principles.

### Technical Stakeholder Example
**Privilege escalation** occurs when an attacker or user obtains permissions beyond those originally granted. Role separation, restricted administrative accounts, and controlled group membership reduce the impact of a compromised standard user account.

---

## 3. Password and Authentication Standard

### Purpose
Define authentication requirements that reduce account takeover and credential-abuse risk.

### Technical Stakeholder Example
**Password spraying** uses a small number of commonly used passwords against many accounts to avoid lockout thresholds. **Credential stuffing** instead reuses username/password combinations exposed in other breaches. Authentication controls should address both patterns rather than treating all password attacks as brute force.

---

## 4. Risk Management Policy

### Purpose
Provide a repeatable process to identify, analyze, prioritize, treat, and track technology risks.

### Technical Stakeholder Example
A firewall misconfiguration may be recorded as a risk because the configuration creates a path for lateral movement between systems. The risk record should identify the threat scenario, affected assets, existing controls, likelihood, impact, owner, treatment plan, and residual risk.

---

## 5. Incident Response Policy

### Purpose
Establish responsibilities and procedures for identifying, containing, investigating, recovering from, and documenting security incidents.

### Technical Stakeholder Example
A packet capture showing unexpected outbound connections can support incident triage, but the evidence must be tied to a timeline and affected asset. The technical artifact becomes useful to management when it supports a documented decision such as isolation, escalation, or recovery.

---

## 6. Vulnerability Management Policy

### Purpose
Define how vulnerabilities are identified, evaluated, prioritized, remediated, and verified.

### Technical Stakeholder Example
A **buffer overflow** occurs when a program writes beyond the memory boundary allocated for data, potentially causing a crash or allowing code execution. A vulnerability record should connect the flaw to the affected system, CVE/CVSS information when applicable, exposure, business impact, remediation, and retest evidence.

---

## 7. Backup and Recovery Policy

### Purpose
Protect critical systems and information from loss and support restoration following failure or disruption.

### Current Control State
Automated backup and recovery testing are planned controls in the current lab and must not be represented as operational until evidence exists.

### Technical Stakeholder Example
**RTO** defines how quickly a service must be restored. **RPO** defines how much data loss is tolerable. A backup can complete successfully and still fail the business requirement if restoration takes longer than the RTO or the backup interval exceeds the RPO.

---

## 8. Acceptable Use Policy

### Purpose
Define appropriate use of company systems, accounts, software, and network resources.

### Technical Stakeholder Example
Unauthorized software can introduce supply-chain risk even when the software appears legitimate. A package compromised through **dependency confusion** can cause trusted build or installation processes to retrieve attacker-controlled code.

---

## 9. Data Classification and Handling Policy

### Purpose
Classify information according to sensitivity and define handling requirements appropriate to its value and exposure risk.

### Technical Stakeholder Example
Data handling requirements should extend beyond file permissions. Logging, backups, exports, screenshots, test data, and packet captures can contain the same sensitive information as the original system and must be protected accordingly.

---

## 10. Third-Party Risk Management Policy

### Purpose
Evaluate security and operational risk introduced by vendors, software suppliers, and external service providers.

### Technical Stakeholder Example
A software supplier can create risk through a **software supply-chain compromise** even when Northstar's internal systems are correctly configured. Assessment should consider the vendor's access, data handling, update mechanism, incident notification, dependency chain, and recovery capability.

---

## Framework Alignment

The policy manual is structured around the working lab baseline of NIST CSF 2.0, ISO/IEC 27001:2022, ISO/IEC 27002:2022, and supporting NIST guidance. Policy language does not by itself prove a control is implemented; implementation and evidence are tracked separately.
