# Splunk-Attack-Simulation-Lab

## T1059.001 - PowerShell Execution

### Attack Simulation

Executed PowerShell commands on the endpoint to simulate adversary activity.

```powershell
Get-Process
Get-Service
---

## T1059.001 - PowerShell Execution

### Attack Simulation

Executed PowerShell commands on the endpoint to simulate adversary activity.

```powershell
Get-Process
Get-Service

# Splunk Attack Simulation Lab

## Overview

This project demonstrates adversary attack simulations and detection engineering using Splunk Enterprise and Sysmon telemetry.

The objective is to execute common attacker techniques and validate detection coverage using Splunk SPL searches.

---

## Simulated Techniques

| MITRE ATT&CK | Technique |
|--------------|-----------|
| T1059.001 | PowerShell |
| T1087 | Account Discovery |

---

## T1059.001 - PowerShell Execution

### Attack Simulation

```powershell
Get-Process
Get-Service
