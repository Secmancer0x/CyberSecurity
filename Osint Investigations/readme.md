🛡️ OSINT Incident Reports

This repository contains a collection of OSINT-based incident reports I created as part of my SOC Analyst training and hands-on practice.
Each report follows a professional SOC-style template including:

Incident Title & Summary

Indicators of Compromise (IoCs)

OSINT Analysis (VirusTotal, AbuseIPDB, CyberChef, crt.sh, Proofpoint, etc.)

Findings & MITRE ATT&CK Mapping

Decision (True/False Positive) with Justification

Recommended Actions

References & Screenshots

📑 Purpose

To demonstrate practical skills in threat investigation and incident reporting.

To showcase the ability to map real-world alerts to MITRE ATT&CK techniques.

To provide a portfolio of security analysis work that can be shared with recruiters, SOC managers, and the wider cybersecurity community.

🧰 Tools Used

VirusTotal – Malware & domain analysis

AbuseIPDB – IP reputation & threat intelligence

CyberChef – Data decoding & analysis

crt.sh – Certificate transparency logs

Proofpoint – Email security analysis

MITRE ATT&CK – Threat mapping framework

⚡ Example Case: Phishing Email

Title: Suspicious Phishing Email – Capital One Impersonation

Technique: MITRE ATT&CK T1566.002 (Spearphishing Link)

Summary:
A phishing email impersonating Capital One was received, containing a malicious link hosted on a compromised WordPress site. OSINT analysis confirmed malicious infrastructure hosted in China.

Decision: True Positive

Recommended Actions: Block sender IP, enforce SPF/DKIM/DMARC, raise user awareness.

📌 Notes

All sensitive/internal data has been anonymized.

Reports are for educational and portfolio purposes only.

Indicators of Compromise (IoCs) are real-world but gathered from publicly available OSINT sources.