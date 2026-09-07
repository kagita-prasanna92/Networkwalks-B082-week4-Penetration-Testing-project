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

**🔎 Milestone 1** — Initial Access and Application Assessment
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

