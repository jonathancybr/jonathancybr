[![GitHub stars](https://img.shields.io/github/stars/yourusername/cyber-home-lab)](https://github.com/yourusername/cyber-home-lab)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

### About This Repository

This repository showcases my **hands-on cybersecurity projects**, home lab experiments, and self-directed learning. Every project includes detailed documentation, tools used, methodologies, and lessons learned 

**Focus areas**: Threat Detection, Incident Response, Network Security, SIEM, Forensics, and Blue Team operations.

---

## 📂 Featured Projects

### 1. SIEM Dashboards & Monitoring (Elastic + Wazuh)
**Status**: Completed

- Built a multi-node Elastic Stack + Wazuh lab on Proxmox
- Created custom dashboards for Windows/Linux endpoint monitoring
- Implemented detection rules for common attacks (brute force, ransomware simulation, privilege escalation)
- Integrated custom Sigma rules and MITRE ATT&CK mapping

**Links**:
- [Project Documentation](./Projects/SIEM-Elastic-Wazuh/README.md)
- [Dashboard Screenshots](./Projects/SIEM-Elastic-Wazuh/screenshots/)
- [Custom Detection Rules](./Projects/SIEM-Elastic-Wazuh/rules/)

**Key Skills Demonstrated**: SIEM administration, log analysis, detection engineering, visualization

---

### 2. Packet Captures & Network Traffic Analysis
**Status**: Ongoing

- Captured and analyzed traffic from simulated attacks (Nmap scans, C2 beacons, data exfiltration, etc.)
- Used Wireshark, tcpdump, and NetworkMiner for analysis
- Created write-ups with annotated PCAPs

**Links**:
- [PCAP Analysis Write-ups](./Projects/PCAP-Analysis/)
- [Sample PCAPs](./Projects/PCAP-Analysis/pcaps/) *(password-protected for safety)*

---

### 3. Incident Response & Forensics Labs
**Status**: Completed

- Simulated ransomware, phishing, and lateral movement incidents
- Performed full IR workflow: detection → containment → eradication → recovery
- Memory forensics with Volatility 3
- Disk forensics with Autopsy and FTK Imager
- Created professional **Incident Reports**

**Links**:
- [Incident Response Playbooks](./Projects/Incident-Response/)
- [Sample Incident Reports](./Projects/Incident-Response/reports/)
- [Forensics Artifacts](./Projects/Forensics/)

---

### 4. Additional Home Lab Projects
- **Active Directory Attack & Defense Lab** (using TryHackMe + self-hosted)
- **Vulnerability Management & Remediation** (OpenVAS + custom scripts)
- **SOAR Automation Playbooks** (using Shuffle or TheHive + Cortex)
- **Threat Hunting Exercises** (with custom hypotheses)

---

## 🧪 Home Lab Architecture

![Home Lab Diagram](screenshots/lab-diagram.png)

**Hardware**:
- Dell R730 / Mini PC cluster + Raspberry Pi
- 64GB RAM, Proxmox VE hypervisor

**Core Tools**:
- **SIEM**: Elastic Stack + Wazuh
- **EDR**: Wazuh + Velociraptor
- **Network**: pfSense, Suricata, Zeek
- **Forensics**: Autopsy, Volatility, Remnux
- **Orchestration**: Ansible, Terraform

---

## 🎯 What I Learned / Skills Gained

- Deep understanding of the **Cyber Kill Chain** and **MITRE ATT&CK**
- Practical experience with enterprise security tools
- Writing clear, professional security documentation
- Building detection logic and reducing alert fatigue
- Incident response under time pressure (timed labs)

---

## 📈 Future Projects (Roadmap)

- [ ] Purple Team exercises with Atomic Red Team
- [ ] Cloud security lab (AWS + native security services)
- [ ] Malware analysis lab (safe environment)
- [ ] Threat Intelligence platform integration

---

## 📫 Connect With Me

- LinkedIwww.linkedin.com/in/jonathan-j-akhamie-1139b53a2
- TryHackMe / HackTheBox: `@yourusername`
- Email: akhamiej@gmail.com

---

**"Documenting my journey from beginner to job-ready security professional."**

---

**Last Updated**: May 2026
