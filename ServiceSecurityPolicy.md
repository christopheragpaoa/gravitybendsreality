# 🛡️ Home & Small Business Cybersecurity Policy

Welcome to the official **Cybersecurity Policy Document** for our hybrid environment consisting of a personal home network and a small startup organization. This policy outlines our commitment to protecting digital assets, ensuring compliance, and preventing unauthorized access or misuse of information.

---

## 📋 Table of Contents
1. [Purpose](#purpose)
2. [Scope](#scope)
3. [Roles & Responsibilities](#roles--responsibilities)
4. [Acceptable Use](#acceptable-use-policy)
5. [Network Security](#network-security)
6. [Device Security](#device-security)
7. [Data Protection](#data-protection)
8. [Incident Response Plan](#incident-response-plan)
9. [Policy Review](#policy-review)
10. [Resources](#resources)

---

## Purpose

> “An ounce of prevention is worth a pound of cure.”  
> — *Benjamin Franklin*

The purpose of this policy is to protect the confidentiality, integrity, and availability of digital assets by outlining standards and practices that reduce cyber risk.

---

## Scope

This policy applies to:
- All household members and employees.
- All devices connected to the network (IoT, phones, computers, servers).
- All cloud services and locally hosted platforms.

---

## Roles & Responsibilities

| Role                | Responsibility                         |
|---------------------|-----------------------------------------|
| **Owner/Admin**     | Enforce policy, maintain systems        |
| **Users**           | Follow policy, report issues            |
| **IT Consultant**   | Provide technical guidance and audits   |

<style>
table {
  border-collapse: collapse;
  width: 100%;
}
th, td {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 8px;
}
th {
  background-color: #f2f2f2;
}
</style>

---

## Acceptable Use Policy

-  Access only authorized systems.
-  Use strong passwords (16+ characters).
-  Lock devices when not in use.
-  Do not download illegal or unverified software.
-  Do not share account credentials.

---

## Network Security

```bash
# Basic firewall setup on Linux
ufw enable
ufw default deny incoming
ufw default allow outgoing
ufw allow ssh

## Device Security

Device Security
Each device must:

-Run updated antivirus and antimalware.
-Use encryption (BitLocker/FileVault).
-Auto-lock after 5 minutes of inactivity.
-Be registered and tracked in inventory.

## Data Protections
Data Classifications:

-Public: Safe to disclose (e.g., website).
-Internal: Non-sensitive (e.g., schedules).
-Confidential: Sensitive data (e.g., PII, credentials).

## Incident Response Plan
F.A.S.T. Framework

-Find the issue
-Alert stakeholders
-Shut down affected services
-Trace the source

Call Incident Hotline: 1-800-ALERT-ME
Email SOC: alert@security.local

## Policy Review

This document is reviewed quarterly and updated to reflect:

- New vulnerabilities
- Organizational changes
- Best practices

## Resources

-Cybersecurity & Infrastructure Security Agency (CISA)
-NIST Cybersecurity Framework
-OWASP Top Ten
-EFF Security Tips


