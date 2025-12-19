# FUTURE\_CS\_01



OWASP Juice Shop - Penetration Testing Project 🛡️







\## Project Overview

This repository contains a detailed security assessment and penetration testing report for the \*OWASP Juice Shop\* web application. This project was completed as part of my Cyber Security internship at \*Future Intern\*.



The goal was to identify critical security flaws, demonstrate their impact through Proof of Concept (PoC), and provide remediation steps.



\## 🛠️ Tools Used

\* \*Burp Suite Professional/Community\* (Intercepting requests \& SQLi)

\* \*OWASP Juice Shop\* (Vulnerable Web App)

\* \*Kali Linux\*

\* \*Browser Developer Tools\*



\## 🔍 Vulnerabilities Identified



| Severity | Vulnerability Name | Description |

| :--- | :--- | :--- |

| 🔴 Critical | \*SQL Injection\* | Bypassed Admin login using ' OR 1=1 -- payload. |

| 🟠 High | \*IDOR\* | Accessed other users' shopping baskets by changing IDs. |

| 🟠 High | \*DOM XSS\* | Executed malicious scripts via the search bar. |

| 🟠 High | \*Broken Access Control\* | Unauthorized access to the /administration panel. |

| 🟡 Medium | \*Sensitive Data Exposure\* | Downloaded confidential acquisitions.md file. |



\## 🚀 Key Takeaways

\* Deep understanding of \*OWASP Top 10\* vulnerabilities.

\* Hands-on experience with \*Burp Suite Repeater \& Intruder\*.

\* Learning how to document professional security findings for stakeholders.



\## 📄 Full Report

The complete detailed report (including screenshots and remediation steps) is available in this repository as a PDF.



---

\*Note:\* This project was performed in a controlled, legal environment for educational purposes.

