# Task-03_CyberSecurityintern
 TASK-NO-3-Perform-a-Basic-Vulnerability-Scan-on-Your-PC
📌 Overview
This repository contains the results of a vulnerability assessment performed using basic vulnerability assessment,Nessus Essentials, a popular vulnerability scanner. The scan was conducted on a local/target machine to identify security weaknesses, understand the risk posture, and recommend remediations for discovered issues.

🧰 Tools Used
✅ Nessus Essentials (Free vulnerability scanner by Tenable)
✅ Localhost Scan (Target IP)
🖥️ Operating System: Linux-based
🛠️ Procedure
Installed Nessus Essentials and activated the free license.
Set up the scan target as machine's IP
Ran a Full System Scan.
Analyzed the results, focusing on CVSS scores and severity.
Documented vulnerabilities and researched possible fixes.
🚨 Summary of Findings
The scan detected a total of 27 vulnerabilities, broken down by severity:

🔴 Critical: 0
🟠 High: 0
🟡 Medium: 13
🔵 Low: 3
⚪ Info: 115
Top Vulnerabilities
Plugin Name	Severity	CVSS v3.0	Description
Remote Desktop Protocol Server Man-in-the-Middle Weakness	Medium	6.5	The RDP service is susceptible to MITM attacks due to weak encryption.
SSL Certificate Cannot Be Trusted	Medium	6.5	The SSL certificate used is self-signed or not trusted.
SSH Terrapin Prefix Truncation (CVE-2023-48795)	Medium	5.9	A protocol weakness allowing for prefix truncation in SSH connections.

## 📚 Concepts Covered

- 🔍 Vulnerability Scanning vs. Penetration Testing
- 📈 Understanding CVSS Scores
- 🧠 Identifying Real vs. Informational Findings
- 🛡️ Best Practices in Patch Management and System Hardening
