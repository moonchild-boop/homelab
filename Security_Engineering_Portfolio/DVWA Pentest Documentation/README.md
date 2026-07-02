# DVWA Web Application Penetration Test

## Overview

This project documents a complete web application penetration test conducted against the **Damn Vulnerable Web Application (DVWA)** within a controlled VirtualBox homelab environment.

The objective of this exercise was to simulate a professional web application security assessment by following a structured penetration testing methodology—from reconnaissance and enumeration through exploitation, evidence collection, risk assessment and remediation.

The report is written in a consulting style to demonstrate not only technical exploitation but also the ability to communicate security findings to technical and non-technical stakeholders.

---

## Lab Environment

| Component | Description |
|-----------|-------------|
| Attacker | Kali Linux |
| Target | Ubuntu Server |
| Application | DVWA |
| Network | Isolated VirtualBox Homelab |

---

## Objectives

- Perform reconnaissance and service enumeration
- Discover hidden web resources
- Identify and exploit common web application vulnerabilities
- Assess business impact
- Produce remediation recommendations
- Document findings in a professional penetration testing report

---

## Methodology

The assessment followed a structured penetration testing process:

1. Reconnaissance
2. Service Enumeration
3. Web Enumeration
4. Vulnerability Assessment
5. Exploitation
6. Risk Analysis
7. Remediation Planning
8. Report Writing

---

## Tools Used

- Nmap
- Gobuster
- Burp Suite
- Firefox
- DVWA
- Kali Linux
- Ubuntu Server

---

## Vulnerabilities Identified

| Vulnerability | Severity |
|--------------|----------|
| OS Command Injection | High / Critical |
| SQL Injection | Critical |
| Reflected Cross-Site Scripting (XSS) | Medium |
| Local File Inclusion | High |
| Exposed Directories & Configuration Files | High Risk |

---

## Skills Demonstrated

### Offensive Security

- Network reconnaissance
- Service enumeration
- Directory brute forcing
- HTTP interception
- Payload crafting
- Manual web application testing

### Security Analysis

- Vulnerability validation
- Risk assessment
- Attack impact analysis
- Root cause identification

### Reporting

- Executive Summary
- Technical Findings
- Risk Ratings
- Evidence Collection
- Business Impact Assessment
- Remediation Recommendations

---

## Key Learning Outcomes

This project reinforced several core cybersecurity concepts including:

- Web application attack surfaces
- Secure input validation
- Principle of Least Privilege
- Secure software development practices
- Professional penetration testing documentation
- Translating technical findings into business risk

---

## Repository Contents

```
DVWA-Pentest/

│── README.md
│── DVWA Pentest Report.pdf
│── Screenshots/
```

---

## Disclaimer

This assessment was conducted **solely within an isolated laboratory environment** using DVWA, an intentionally vulnerable application created for security education.

No production systems, third-party networks or unauthorized assets were targeted.

---

## Author

**Aisha Duze**

Cybersecurity | GRC | AI Governance | Data & Digital Transformation

Building practical security skills across offensive security, governance, risk management and security architecture.
