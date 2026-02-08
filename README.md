# Suricata-IDS-Wazuh-SIEM
# Suricata IDS + Wazuh SIEM Home Lab

## 📌 Project Overview

This project demonstrates a fully functional **home lab intrusion detection environment** using:

- Suricata (Network IDS)
- Wazuh (SIEM & Log Analysis)
- Ubuntu Server (Monitoring Node)
- Simulated Attack Machine
- Multiple Target Machines

The lab was built to simulate real-world network attacks and monitor, detect, and analyze malicious traffic using open-source security tools.

---

## 🎯 Objectives

- Deploy Suricata IDS in a home lab environment
- Monitor live network traffic
- Detect malicious or suspicious behavior
- Forward IDS logs to Wazuh SIEM
- Analyze alerts and investigate attack patterns
- Simulate attacker behavior for detection validation

---

## 🛠 Tools & Technologies

- **Suricata IDS**
- **Wazuh Server**
- **Wazuh Agent**
- **Ubuntu Server**
- **Virtual Machines (Lab Environment)**
- **Linux Networking**
- **Custom & Community Rules**

---

## 🏗 Lab Architecture

Attack Machine  
        ↓  
Ubuntu Server (Suricata IDS + Wazuh Agent)  
        ↓  
Wazuh Server (SIEM)  
        ↓  
Target Machines  

### Components

• **Attack Machine**
  - Used to simulate network-based attacks
  - Performed scans and suspicious activity

• **Ubuntu Monitoring Server**
  - Runs Suricata IDS
  - Monitors network traffic
  - Sends logs to Wazuh Server

• **Wazuh Server**
  - Centralized SIEM
  - Correlates Suricata alerts
  - Provides alert visibility and analysis

• **Target Machines**
  - Simulated internal endpoints

---

## 🔎 Detection Capabilities

- Port scanning detection
- Suspicious traffic detection
- IDS rule-based alerting
- Network anomaly monitoring
- Signature-based detection

---

## 🔄 Workflow

1. Attack machine generates malicious traffic
2. Suricata inspects packets in real time
3. Alerts are generated based on rule matches
4. Logs are forwarded to Wazuh
5. Wazuh correlates and displays alerts
6. Analyst investigates alerts in SIEM dashboard

---

## 🧠 Skills Demonstrated

- IDS deployment and configuration
- Network traffic analysis
- Log forwarding and SIEM integration
- Alert investigation
- Threat detection validation
- Blue team lab simulation
- Linux server administration

---

## 🚀 Future Improvements

- Add Zeek for deeper network visibility
- Create custom Suricata detection rules
- Integrate with SOAR for automated response
- Add MITRE ATT&CK mapping to alerts

