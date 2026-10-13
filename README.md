# MedTech Solutions Penetration Test Report

## Overview
This repository contains the penetration test report conducted for MedTech Solutions between May 15–22, 2024. The assessment evaluated external infrastructure, cloud environment, and web applications.

## Methodology
- NIST SP 800-115
- OWASP Testing Guide
- MITRE ATT&CK Framework

## Key Findings
- 2 Critical vulnerabilities (Insecure API authentication, Weak database access controls)
- 3 High severity issues (Authentication weaknesses, Cloud misconfigurations, Session management flaws)
- 4 Medium severity issues (Security misconfigurations, Information disclosure, Weak headers, Minor access control issues)

## Recommendations
- Enforce secure API authentication and authorization
- Remove default database credentials
- Implement Multi-Factor Authentication (MFA)
- Strengthen cloud IAM policies
- Regular vulnerability assessments and penetration tests

## Repository Contents
- `PenTest_Report.pdf` – Full penetration test report
- `Findings_Report.xlsx` – Detailed vulnerability findings
- `Vulnerability_Scan_Report.pdf` – Scan results
- `Attack_Path_Analysis.docx` – Exploitation paths

## Author
Prepared by Innocent Utu (Junior Penetration Tester)
