# Incident Analysis

## Scenario
A simulated RDP brute-force attack was performed against a Windows 10 virtual machine.

## Detection Process
Microsoft Sentinel collected Windows Security Event ID 4625 logs related to failed login attempts.

PowerShell enrichment scripts extracted source IP addresses and enriched them with geolocation metadata.

## Findings
- Multiple failed authentication attempts detected
- Repeated login attempts from external IP addresses
- Geolocation data identified attack origins

## Security Impact
Brute-force attacks may lead to unauthorized access if weak credentials are used.

## Recommendations
- Enforce MFA
- Restrict RDP exposure
- Implement account lockout policies
- Monitor authentication anomalies
