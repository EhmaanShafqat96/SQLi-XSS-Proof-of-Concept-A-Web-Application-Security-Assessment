# SQL Injection & Cross-Site Scripting (XSS) Proof of Concept

## 📖 Project Overview

This repository contains a comprehensive **Proof of Concept (PoC) Report** for two critical web application vulnerabilities: **SQL Injection (SQLi)** and **Reflected Cross-Site Scripting (XSS)**. The assessment was performed as part of the Buildables Fellowship program using the PortSwigger Web Security Academy labs, which provide a safe and legal environment for security research.

The report demonstrates a hands-on approach to identifying, exploiting, and analyzing these common yet dangerous vulnerabilities, following industry-standard guidelines from **OWASP** and **NIST**.

## 🎯 Key Findings

| Vulnerability | Severity | Description |
| :--- | :--- | :--- |
| **SQLI-001: UNION-Based SQL Injection** | `Critical` | Exploited to retrieve sensitive data (usernames & passwords) from other database tables by manipulating input parameters. |
| **XSS-001: Reflected Cross-Site Scripting** | `High` | Injected and executed malicious JavaScript payloads (`<script>alert(1)</script>`) via user-input fields, demonstrating potential for session hijacking. |

## 🛠️ Tools & Methodologies

- **Tools:** Burp Suite, Browser Developer Tools
- **Methodologies:** OWASP Web Security Testing Guide
- **Environment:** PortSwigger Web Security Academy (Authorized Lab)

## 📂 Repository Contents

- `Proof_of_Concept_Report_(SQL_and_XSS).pdf` - The full detailed report.
- `README.md` - This file, providing an overview of the project.

## 📝 Report Highlights

The PDF report includes:
- **Executive Summary & Risk Posture**
- **Technical Breakdown** of each vulnerability
- **Step-by-Step Exploitation** with evidence screenshots
- **Root Cause Analysis**
- **Strategic Remediation Recommendations** (Immediate, Short-term, Ongoing)

## 🔒 Important Disclaimer

**This security assessment was conducted in a controlled, educational environment (PortSwigger Web Security Academy). The vulnerabilities identified are part of intentionally vulnerable lab applications and do not represent real-world systems. This work is for educational and portfolio purposes only.**

## 👨‍💻 Author

**Ehmaan Shafqat**  
- [Email](mailto:emanshafqat9611@gmail.com)

---

*If you found this report useful, please consider giving it a ⭐!*
