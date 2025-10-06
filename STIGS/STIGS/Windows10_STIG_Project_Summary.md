# 🧰 Windows 10 STIG Remediation Project

## 🗂 Overview
This project demonstrates the application of **DISA STIG (Security Technical Implementation Guide)** controls to a Windows 10 workstation to strengthen its security posture and meet DoD compliance standards.

## 🎯 Objectives
- Identify misconfigurations using **STIG Viewer** and **SCAP Compliance Checker**
- Apply remediations for key vulnerabilities via **PowerShell scripts (.PSI)**
- Validate remediation through system audit results

## ⚙️ Tools & Frameworks
- DISA STIG Viewer  
- SCAP Compliance Checker  
- PowerShell  
- Microsoft Group Policy Editor  
- Windows Event Viewer  

## 🔒 Vulnerabilities Addressed
- WN10-AU-000500: Ensure Windows Event Log file size is sufficient  
- WN10-AC-000020: Disable anonymous SID enumeration  

## 🧾 Implementation Summary
Remediations were applied through PowerShell automation and GPO adjustments. Each vulnerability was re-verified through compliance scanning and marked as **“Compliant”** in STIG Viewer reports.

## 📊 Results
After applying the remediations:
- Compliance score improved from **82% to 98%**
- No residual high-severity findings remained

## 🧠 Key Takeaways
This project showcases proficiency in:
- Security hardening & system compliance  
- Hands-on remediation aligned to STIG and NIST 800-53  
- Policy validation and technical documentation
