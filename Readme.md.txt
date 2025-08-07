![Status](https://img.shields.io/badge/status-active-brightgreen)
![Security+](https://img.shields.io/badge/certification-in--progress-blue)


# SOC-Analyst-Lab

This repository is part of my transition into the cybersecurity field, with a focus on practical SOC (Security Operations Center) analyst skills. It contains hands-on labs, detection rules, log analysis, and case studies aligned with real-world threats and MITRE ATT&CK tactics.

## 🧠 Objectives

- Develop practical SOC analyst skills
- Simulate real-world detection scenarios
- Practice log analysis and alert triage
- Build Sigma rules and custom detections
- Improve familiarity with tools like Wireshark, Suricata, and SIEM platforms

---

## 📁 Repo Structure

SOC-Analyst-Lab/
│
├── Logs/ # Raw log files & parsed examples (Apache, auth, PowerShell, etc.)
     01_rdp_auth_success_localhost_1149.evtx
     02_DSRM_password_change_t1098.evtx
├── SIEM-Rules/ # Sigma detection rules + explanations
├── Tools/ # CLI tools (tcpdump, netstat, PowerShell monitoring etc.)
├── CaseStudies/ # MITRE ATT&CK mapped incidents and IOC walkthroughs

    01_[RDP Localhost Login (Event ID 1149)](CaseStudies/case-rdp-auth-localhost-1149.md):  
  A successful RDP login from localhost using user `admin01`, classified as normal behavior.
  
    02_DSRM_Password_Change_EventID_4794.md


├── Screenshots/ # Visual examples and findings
└── README.md # This file


---

## 🔧 Tools & Concepts Used

- Sigma (SIEM detection rules)
- Wireshark & tcpdump
- Linux auditd / syslog
- MITRE ATT&CK framework
- Log parsing with bash tools
- Basic YARA and Suricata signatures

---

## 🚀 Upcoming Additions

- SOC alert handling scenarios
- Malware traffic detection examples
- Mini PCAP-based investigations
- Visual SIEM dashboards

---

## 💼 About Me

I’m currently preparing for the CompTIA Security+ exam and gaining practical experience in security operations. This repository reflects my learning path toward becoming a SOC Analyst and, in the long term, advancing into Red Teaming and threat hunting roles.

---

> 💬 Feel free to fork, clone, or contribute ideas if you're also building your SOC journey!


---