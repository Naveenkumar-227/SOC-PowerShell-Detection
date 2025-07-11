# SOC-PowerShell-Detection
Mini SOC Project: Detecting suspicious PowerShell with Sysmon
# 🛡️ SOC Project: Detecting Suspicious PowerShell Execution Using Sysmon

## 🔍 Overview
This project demonstrates how to detect suspicious PowerShell activity using Microsoft Sysmon. It mimics a real-world SOC analyst task using Windows telemetry and open-source tools.

## 📌 Detection Use Case
- Monitor PowerShell usage for obfuscation techniques
- Identify `-EncodedCommand`, `IEX`, and `DownloadString` patterns
- Alert on suspicious command-line arguments

## 🛠 Tools Used
- Sysmon v15.15
- Custom Sysmon Config
- Windows Event Viewer
- PowerShell (simulation)

## 📁 Project Contents
- `sysmonconfig-export.xml`: Custom config used for process monitoring
- `screenshots/`: Real Sysmon logs showing detection
- `detection-notes.txt`: Brief explanation of logic and output

## 📸 Screenshots
![Sysmon PowerShell Log](screenshots/e![event 1](https://github.com/user![event 2](https://github.com/user-attachments/assets/9ba68066-30db-41ae-82b8-7b66c59151cf)
-attachments/assets/e27c6cee-3c0b-4cbd-bc1b-6cf67830511e)
vent1.png)

## ✅ Outcome
Detected simulated malicious PowerShell command using Sysmon Event ID 1. Demonstrates basic detection engineering and Windows event log monitoring for blue team operations.

---

#

---
