# 🔍 KQL Hunting Queries Repository

Welcome to my collection of **Kusto Query Language (KQL) hunting scripts**.  
These queries are designed to help security teams detect threats, investigate anomalies, and strengthen defenses in **Microsoft Sentinel**, **Microsoft Defender**, and other Azure security solutions.

---

## 📖 Overview
This repository contains categorized hunting queries covering:
- **Authentication** → Brute force, impossible travel, unusual logins  
- **Network** → DNS anomalies, port scanning, command & control patterns  
- **Endpoint** → PowerShell obfuscation, ransomware behaviors, process anomalies  
- **Cloud** → Azure AD anomalies, suspicious mailbox rules, risky OAuth apps  

Each query is optimized for **threat hunting**, **incident response**, and **proactive detection** in enterprise environments.

---

## 📂 Repository Structure
```bash
kql-hunting-scripts/
│
├── authentication/   # Sign-in anomalies, brute-force, account misuse
├── network/          # DNS tunneling, lateral movement, port scans
├── endpoint/         # Malware behavior, suspicious commands, persistence
└── cloud/            # Office 365, Azure AD, cloud-native threats

⚠️ Disclaimer

These queries are provided for educational and detection engineering purposes only.
Thresholds, filters, and logic must be adapted to your environment to minimize false positives.
Use responsibly in line with your organization’s security policies.
