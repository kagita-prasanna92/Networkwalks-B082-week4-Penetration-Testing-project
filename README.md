# Networkwalks-B082-week4-Penetration-Testing
This project focuses on understanding the fundamentals of penetration testing and ethical hacking. The activities involve identifying vulnerabilities, assessing security weaknesses, and analyzing potential risks in an authorized lab environment using industry-standard cybersecurity tools and techniques


---

#  Project Details

|  | Details |
|---|---|
| project type | penetration testing &vulnerability assessment |
| client Name | Mediroza General hospital |
| Target | https://medirozahospital.com |
| Rules | Testing limited to the target domain only ,np social engineering, no denial of service , no testing outside agreed scope |
| Authorization | The client has provided written authorisation to conduct security testing on their web infrastructure |

---


**📌 Project Overview**
---

I performed a practical Penetration Testing Lab using Kali Linux tools

The lab focused on understanding the penetration testing process, including Initial Access, Data Extraction, Attack Simulation, Document Gathering, and Penetration Testing Report preparation. The activities helped strengthen my practical knowledge of ethical hacking, vulnerability assessment, and security testing in an authorized lab environment 

---
**Completed Milestones**

**Milestone 1** — Initial Access and Application Assessment
I performed passive and active reconnaissance, including domain information review, DNS enumeration, service discovery, web technology identification, and directory enumeration.

The assessment identified an authentication and input-handling weakness in a web application. Within the authorized scope, I validated that confidential laboratory-report resources could be accessed without the intended level of protection.

**Skills practiced:**

-Reconnaissance and attack-surface mapping
-Service and web enumeration
-Authentication testing
-Input-handling analysis
-Access-control validation

**Milestone 2** — PDF Protection and Password Recovery
The recovered laboratory reports were protected with PDF encryption. I reviewed their metadata and evaluated the strength of the file passwords through offline testing.

PDFCrack and an industry-standard wordlist were used to recover the passwords. Successful access to the protected report contents was then verified and documented in the private assessment report.

**Skills practiced:**

-File and metadata analysis
-Password-strength assessment
-Offline security testing
-Evidence validation
-Responsible handling of sensitive documents

**Milestone 3** — Sensitive Data Exposure Analysis
By reviewing discoverable web paths and directory configurations, I identified an exposed database backup file.

The backup contained sensitive organizational information, including staff employment and salary records and commercially sensitive shareholder information. The finding demonstrated the risks of storing backups in web-accessible locations without appropriate access controls.

**Skills practiced:**

-Sensitive-file discovery
-Backup exposure analysis
-Data classification
-Business-impact assessment
-Remediation prioritization

**Milestone 4** — Professional Penetration-Testing Report
I consolidated the assessment into a structured penetration-testing report designed for both technical and non-technical readers.

**The report includes:**

-Executive Summary
-Scope and Methodology
-Assessment Limitations
-Findings and Supporting Evidence
-Risk Ratings
-Business Impact Analysis
-Prioritized Remediation Recommendations
-Technical Appendices


**Tool & Techniques**

The engagement involved the following tools and techniques:
Nmap
Gobuster
Wafw00f
Burp Suite
Curl
PDFCrack
ExifTool
Browser-based validation
Linux command-line utilities
Tools were used only within the authorized assessment scope and for educational purposes.

**Key Takeaways**

This engagement helped me strengthen my practical understanding of:

Reconnaissance and attack-surface analysis
Web application security testing
Authentication and access-control weaknesses
SQL injection validation
Password-strength assessment
Sensitive-file exposure
Evidence management
Risk prioritization
Technical report writing
Communicating security findings clearly
The most important outcome was learning to remain methodical when the first approach fails. A successful assessment is not only about finding a weakness; it is also about validating risk responsibly, protecting sensitive information, and providing useful remediation guidance.

**🔒 Disclosure and Data-Handling Statement**

This project was performed in an authorized, controlled educational environment. The public version has been sanitized to protect confidential information.

**The following materials are not included in this repository:**

Patient names or medical information
Passwords or credentials
National identification numbers
Phone numbers or email addresses
Staff salary values
Shareholder names or exact ownership records
Raw database backups
Unredacted screenshots
Private target details or exploit payloads
The complete report is intended only for the authorized internship or academic review process.

**Acknowledgement**

Thank you to the NetworkWalks team for providing a realistic and valuable environment in which to develop practical penetration-testing and professional reporting skills.

**⚠️ Disclaimer**

This repository is for educational and portfolio purposes only. The techniques discussed in the private assessment must never be used against systems without explicit written permission from the owner.
