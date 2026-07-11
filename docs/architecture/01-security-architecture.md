# Volume 1 - Security Architecture & Foundations

## Objectives

Build a scalable Microsoft security monitoring platform capable of:

- Detecting threats
- Investigating incidents
- Automating response
- Supporting SOC operations

## Recommended Architecture

### Identity Layer

Microsoft Entra ID

Monitor:

- Risky sign-ins
- Impossible travel
- MFA failures
- Privileged role assignments

### Endpoint Layer

Microsoft Defender for Endpoint

Monitor:

- Malware execution
- Credential theft
- Lateral movement
- Persistence mechanisms

### Email Layer

Microsoft Defender for Office 365

Monitor:

- Phishing
- Malware attachments
- Business Email Compromise

### Cloud Layer

Microsoft Defender for Cloud

Monitor:

- Azure misconfigurations
- Suspicious cloud activity
- Resource compromise

### SIEM Layer

Microsoft Sentinel

Responsibilities:

- Centralized analytics
- Incident correlation
- Automation
- Reporting

## Reference Documentation

Microsoft Learn:

https://learn.microsoft.com/azure/sentinel/

https://learn.microsoft.com/defender-xdr/

MITRE ATT&CK:

https://attack.mitre.org/

