
Cybersecurity Footprinting & Reconnaissance

Week 2 - Project Module 1

A practical cybersecurity reconnaissance project completed in a Kali Linux virtual lab, demonstrating how multiple footprinting and reconnaissance tools can be combined to collect and document publicly observable information.

---

Project Overview

This project focuses on Footprinting and Passive Reconnaissance using Kali Linux.

The assessment documents a controlled educational exercise against the project scope "networkwalks.com". The work covers domain registration information, web technology fingerprinting, DNS resolution, HTTP response headers, Web Application Firewall detection, and DNS record enumeration.

The complete evidence and original screenshots are included in the accompanying PDF report.

---

Project Information

Item| Details
Project| Week 2 - Project Module 1
Topic| Footprinting & Reconnaissance
Environment| Kali Linux Virtual Lab
Assessment Type| Footprinting / Passive Reconnaissance
Target Scope| networkwalks.com
Author| Hamza Ahmad
Internship| Cybersecurity Internship - Cohort B083
Project Date| 17 September 2026

---

Objectives

The main objectives of this project were to:

- Collect publicly available domain-registration information using WHOIS.
- Identify exposed web technologies using WhatWeb.
- Resolve DNS information using nslookup.
- Review HTTP response headers using curl.
- Detect Web Application Firewall technology using WAFW00F.
- Enumerate publicly available DNS records using DNSRecon.
- Document observations and evidence in a professional cybersecurity report.

---

Tools & Techniques

Tool| Purpose
WHOIS| Domain registration and name-server information
WhatWeb| Web technology fingerprinting
nslookup| DNS resolution
curl| HTTP response-header review
WAFW00F| Web Application Firewall detection
DNSRecon| DNS record enumeration

Commands Used

whois networkwalks.com
whatweb networkwalks.com
nslookup networkwalks.com
curl -I https://networkwalks.com
wafw00f networkwalks.com
dnsrecon -d networkwalks.com

---

Methodology

1. WHOIS - Domain Registration

WHOIS was used to review publicly available domain-registration, registrar, status, and name-server information.

2. WhatWeb - Web Technology Fingerprinting

WhatWeb was used to identify technologies and services exposed by the web application.

3. nslookup - DNS Resolution

nslookup was used to resolve the domain and record the addresses returned through DNS.

4. curl - HTTP Header Analysis

curl was used with the "-I" option to inspect HTTP response headers without retrieving the complete webpage.

5. WAFW00F - WAF Detection

WAFW00F was used to determine whether a Web Application Firewall was detected in front of the target.

6. DNSRecon - DNS Enumeration

DNSRecon was used to enumerate publicly available DNS records, including SOA, NS, MX, A/AAAA, TXT/SPF, and SRV records.

---

Key Findings

The exercise produced the following observations:

- Domain registration and name-server information was publicly observable.
- Web-server and application technologies were fingerprintable.
- DNS resolution returned address information for the domain.
- HTTP responses exposed server and application-related headers.
- A ModSecurity (SpiderLabs) Web Application Firewall was detected.
- Multiple DNS record types were publicly resolvable.

These observations demonstrate how publicly observable information can contribute to infrastructure profiling and defensive exposure review.

---

Skills Demonstrated

- Kali Linux
- Passive Reconnaissance
- Footprinting
- WHOIS Analysis
- Web Technology Fingerprinting
- DNS Enumeration
- DNS Analysis
- HTTP Header Analysis
- WAF Detection
- Command-Line Security Tools
- Cybersecurity Documentation
- Security Report Writing
- Evidence Preservation

---

Evidence & Documentation

The complete project report is included in this repository:

"Hamza_Ahmad_Week2_Cybersecurity_Footprinting_Report.pdf"

The PDF contains the methodology, observations, consolidated findings, conclusion, and original project screenshots.

The original screenshots were retained as evidence without cropping, retouching, filtering, or other image editing.

---

Repository Structure

cybersecurity-footprinting-reconnaissance/
│
├── README.md
└── Hamza_Ahmad_Week2_Cybersecurity_Footprinting_Report.pdf

---

Learning Outcome

This project demonstrates the practical use of multiple reconnaissance tools to build a structured understanding of a web-facing environment from publicly observable information.

It also demonstrates the importance of documenting commands, observations, evidence, and security relevance in a clear and professional format.

---

Responsible Use

This project was prepared for cybersecurity education and authorized security testing.

Reconnaissance and security testing should only be performed against systems that are owned by the tester or where explicit permission has been provided.

---

Author

Hamza Ahmad
Cybersecurity Internship - Cohort B083

Project: Week 2 - Footprinting & Reconnaissance
