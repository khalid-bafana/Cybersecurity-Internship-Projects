# Project 1: Web Application Vulnerability Scanner (OWASP ZAP)

## Introduction
This project demonstrates the use of **OWASP ZAP (Zed Attack Proxy)** to identify vulnerabilities in web applications.  
The target chosen was `http://testphp.vulnweb.com/`, a deliberately vulnerable test site provided for security research.

## Objective
- Install and configure OWASP ZAP.
- Perform an **automated vulnerability scan**.
- Identify and analyze alerts.
- Generate a vulnerability report.

## Tools Used
- **OWASP ZAP 2.16.1**
- **Windows 11 (64-bit)**
- **Java JRE 17**

## Steps Performed
1. Installed OWASP ZAP and configured JRE 17.
2. Selected `http://testphp.vulnweb.com/` as the target.
3. Ran automated scan using:
   - Traditional Spider
   - AJAX Spider
4. Monitored alerts and vulnerabilities discovered.
5. Generated and exported vulnerability report.

##Findings
- 65 URLs crawled successfully.  
- Vulnerabilities detected:
  - **Medium Severity**: `cart.php` (Possible SQL Injection), `infotarist.php` (Input Validation Issue).  
  - **Low Severity**: Information disclosure in multiple files.  

##Screenshots
Screenshots of installation, scan in progress, and alerts are included in the `screenshots/` folder.

##Report
A detailed vulnerability report was generated using OWASP ZAP.  
(See `/scan-results/` folder in this repository.)

##Conclusion
This project shows the ability to use **OWASP ZAP** for scanning web applications and analyzing vulnerabilities.  
The process learned here can be applied to real-world applications for security testing and compliance.
