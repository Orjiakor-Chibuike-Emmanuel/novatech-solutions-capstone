# NovaTech Solutions Security Assessment (Capstone Project)

**Project Overview**  
Conducted a comprehensive end-to-end security assessment for NovaTech Solutions, a fictional technology consulting company that experienced multiple suspicious security events.

**Scope & Objectives**
- Network architecture analysis
- SOC alert and log investigation
- Vulnerability assessment & reconnaissance
- Risk assessment
- Security recommendations

**Tools & Techniques Used**
- Network Traffic Log Analysis
- Authentication Log Analysis
- Nmap scan interpretation
- SIEM Alert Triage
- Risk Assessment Methodology

**Key Findings**
- Brute-force attack on Web Server from external IP (203.0.113.45)
- Successful lateral movement from Web Server to Database Server (root login)
- Exposed MySQL port 3306 and FTP with anonymous login
- Outdated Apache 2.4.29 on Web Server
- Weak password policy and lack of MFA

**Risk Assessment Summary**
Created a detailed risk register highlighting High-risk assets including Web Server, Database Server, and File Server.

**Recommendations Implemented**
- Enable MFA on all critical accounts
- Restrict database access (port 3306)
- Disable anonymous FTP
- Upgrade outdated software
- Configure HTTPS on the web server
- Restrict SSH access

**Skills Demonstrated**
- Full incident response workflow
- Log analysis and threat hunting
- Vulnerability interpretation
- Risk assessment and reporting
- Professional security documentation

**Outcome**  
Provided NovaTech Solutions with actionable recommendations to significantly reduce their attack surface and improve overall security posture.

**This capstone project integrated all skills learned throughout the TS Academy Cybersecurity program.**
