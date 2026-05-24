# SIEM Threat Detection Lab

## Overview

This project demonstrates a Microsoft Sentinel SIEM lab focused on threat detection, attack monitoring, and security event analysis within a Windows environment.

The lab simulates RDP brute-force attacks and enriches Windows Event Logs using PowerShell and geolocation APIs to improve attack visibility and investigation capabilities.

---

## Technologies Used

- Microsoft Sentinel
- Azure Log Analytics
- PowerShell
- Windows Event Viewer
- Windows 10 Virtual Machine
- Kali Linux
- RDP Monitoring

---

## Features

- Detection of failed RDP brute-force attempts
- Geolocation enrichment for attacker IP addresses
- Security event analysis and investigation
- Attack visualization dashboards
- Threat monitoring workflows
- Custom PowerShell log enrichment automation

---

## MITRE ATT&CK Mapping

| Technique | Description |
|---|---|
| T1110 | Brute Force |
| T1021 | Remote Services |
| T1078 | Valid Accounts |

---

## Skills Demonstrated

- SIEM Analysis
- Threat Detection
- Security Monitoring
- Incident Investigation
- Log Analysis
- PowerShell Automation
- Threat Hunting Fundamentals

---

## Project Structure

- `/scripts` → PowerShell enrichment scripts
- `/screenshots` → Sentinel dashboards and alerts
- `/docs` → Incident analysis and MITRE mapping
- `/logs` → Sample security logs

---

## Future Improvements

- Threat intelligence integration
- Automated alerting workflows
- MITRE ATT&CK dashboards
- Advanced detection analytics
- Cloud attack simulation scenarios
