# 🛡️ SOC Automation & SIEM Lab (Wazuh)

This repository contains my 1st week's progress of the SOC Internship, focusing on building a defensive laboratory environment and mastering SIEM foundations.

## 🏗️ Lab Architecture
I built a professional sandbox environment using **Oracle VirtualBox** with the following nodes:
- **SIEM Manager:** Ubuntu Server running Wazuh Stack.
- **Attacker Node:** Kali Linux.
- **Endpoint:** Windows 10 (Monitored).

## 🚀 Week 1 Highlights
### **Day 1: Networking & Traffic Analysis**
- Analyzed **ICMP** and **DNS** protocols using **Wireshark**.
- Verified Layer 3 connectivity and packet encapsulation.
- *[Screenshot: Put your Wireshark image here]*

### **Day 2-4: Wazuh Installation**
- Deployed Wazuh Manager using the OVA appliance.
- Configured **Static IPs** and verified services (`wazuh-manager`, `indexer`, `dashboard`).

### **Day 5-7: Agent Deployment & Alert Triage**
- Successfully connected Windows and Kali agents.
- Triggered **Brute Force (SSH)** alerts and monitored them in real-time.
- Performed **File Integrity Monitoring (FIM)** to track unauthorized changes.

## 📊 Key Learnings
- Understanding of the **Client-Server model** in SIEM.
- Mapping alerts to the **MITRE ATT&CK** framework.
- Distinguishing between False Positives and True Positives during **Alert Triage**.

---
*Check the `/Docs` folder for the full detailed technical report.*
