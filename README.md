# PCAD Incident Response Investigation

## Overview
This project documents a full cyber attack lifecycle against a Windows Server 2022 host (PCAD).

The investigation was conducted using Splunk SIEM and Windows Event Logs.

---

## Attack Lifecycle

1. Reconnaissance
2. Port Scanning
3. Brute Force Attack
4. Initial Access via WinRM
5. Persistence
6. Privilege Escalation
7. Defense Evasion
8. Full RDP Control

---

## Tools Used

- Splunk SIEM
- Sysmon
- Hydra
- Evil-WinRM
- CrackMapExec
- Nmap
- Remmina
- Windows Event Logs

---

## Key Event IDs

| Event ID | Description |
|----------|-------------|
| 4625 | Failed Login |
| 4624 | Successful Login |
| 4720 | User Creation |
| 4732 | Added to Administrators |
| 4688 | Process Creation |

---

## MITRE ATT&CK Techniques

- T1595.001 - Active Scanning
- T1110.001 - Brute Force
- T1078.003 - Valid Accounts
- T1136.001 - Create Account
- T1562.001 - Defense Evasion
- T1021.001 - Remote Desktop Protocol

---

## Screenshots

Add Splunk dashboard screenshots here.

---

## Author

Omar Ragab
