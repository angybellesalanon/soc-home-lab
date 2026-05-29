**Objective:**
This project aims to build a **SOC (Security Operations Center) home lab** using VMware to simulate real-world cyber attacks and practice detection, monitoring, and incident response.

**Environment Setup:**
- Virtualization: VMware
- Attacker Machine: Kali Linux
- Target Machine: Windows 10
- SIEM Server: Ubuntu + Wazuh

**Activities Performed**
- Network scanning using Nmap to identify active hosts and exposed services
- Enumeration of open ports and services
- Simulation of cyber attacks:
       - Brute force attack
- Log collection and correlation using Wazuh SIEM
- Detection of suspicious and malicious activities
- Generation and monitoring of security alerts
- Log analysis and incident investigation
- Implementation of basic incident response actions

**Detection & Analysis**

During the simulation, multiple failed login attempts were detected, indicating a brute force attack.

  - Identification of attacker IP address
  - Correlation of logs through Wazuh
  - Alert generation based on suspicious behavior
  - Analysis of attack patterns and timeline

Tools & Technologies
Wazuh (SIEM)
Nmap
Kali Linux
VMware
Linux & Windows systems

Screenshots
Wazuh Dashboard
Security Alerts
Logs Analysis

Key Learnings
Understanding of SOC operations
Hands-on experience with SIEM tools
Detection of brute force attacks
Log correlation and analysis
Incident handling basics

Future Improvements
Add more attack scenarios (phishing, malware)
Integrate additional tools (Splunk, ELK)
Automate detection with scripts
