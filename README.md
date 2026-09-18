
Cybersecurity Footprinting and Reconnaissance
Week 2 - Project Module 1
Prepared by: Hamza Ahmad
Cybersecurity Internship: Cohort B083
Environment: Kali Linux Virtual Lab
Assessment: Footprinting / Passive Reconnaissance
Project Date: 17 September 2026
Target: networkwalks.com

Project Overview
This project documents a controlled reconnaissance exercise using Kali Linux to collect publicly observable information about networkwalks.com.

The exercise covered domain registration information, web technology fingerprinting, DNS resolution, HTTP response headers, WAF detection, and DNS record enumeration.

The original screenshots supplied with the project report are retained as evidence.

Objectives
Collect public domain-registration information with WHOIS.
Fingerprint web technologies with WhatWeb.
Resolve the domain with nslookup.
Review HTTP response headers with curl.
Identify detected Web Application Firewall technology with WAFW00F.
Enumerate publicly available DNS records with DNSRecon.
Document the results in a professional security report.
Tools Used
WHOIS - Domain registration and name-server information.
WhatWeb - Web technology fingerprinting.
nslookup - DNS resolution.
curl - HTTP response-header review.
WAFW00F - Web Application Firewall detection.
DNSRecon - DNS record enumeration.
Commands Used
whois networkwalks.com
whatweb networkwalks.com
nslookup networkwalks.com
curl -I https://networkwalks.com
wafw00f networkwalks.com
dnsrecon -d networkwalks.com
 
Key Observations
WHOIS output provided registrar and name-server information.
WhatWeb identified web technologies including Apache, WordPress and Bootstrap.
nslookup resolved the domain and returned an IP address during the exercise.
curl returned HTTP response information and application-related headers.
WAFW00F detected ModSecurity (SpiderLabs).
DNSRecon identified publicly available DNS records, including SOA, NS, MX, A/AAAA, TXT/SPF and SRV records.
Security Relevance
The exercise demonstrates how publicly observable information can help build a structured picture of a web-facing environment.

The findings can support infrastructure profiling, web technology exposure review, DNS and hosting analysis, HTTP header review, and defensive security assessment.

Evidence
The complete evidence and original screenshots are included in:

Hamza_Ahmad_Week2_Cybersecurity_Footprinting_Report.pdf

The project report contains seven original screenshots. They were retained without cropping, retouching, filtering, or other image editing.

Skills Demonstrated
Kali Linux
Passive reconnaissance
Footprinting
WHOIS analysis
Web technology fingerprinting
DNS enumeration
HTTP header analysis
WAF identification
Cybersecurity documentation
Security report writing
Responsible Use
This project was prepared for cybersecurity education and authorized lab practice.

Security testing and reconnaissance should only be performed against systems owned by the tester or systems for which explicit permission has been provided.

Project Report
See the PDF file in this repository for the complete project methodology, observations, findings, and screenshot evidence.

Author: Hamza Ahmad
Cybersecurity Internship - Cohort B083
