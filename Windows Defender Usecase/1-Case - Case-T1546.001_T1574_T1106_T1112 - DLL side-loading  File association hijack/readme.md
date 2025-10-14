🛡️ Microsoft Defender Use Cases

This folder contains SOC Tier-1 detection and investigation cases based on alerts from Microsoft Defender for Endpoint (MDE).
Each case shows how to validate Defender detections using Advanced Hunting, MITRE ATT&CK mapping, and standard incident-response steps.

🎯 Purpose

Practice Tier-1 alert triage and documentation in Microsoft Defender.

Build real-world examples of defense evasion, persistence, and execution detections.

Use KQL (Advanced Hunting) to verify alerts, analyze behavior, and identify false positives.

Create a consistent portfolio of Defender detection workflows aligned with MITRE ATT&CK.

🧰 Data Sources

Microsoft Defender for Endpoint Alerts

Advanced Hunting tables:

DeviceProcessEvents

DeviceImageLoadEvents

DeviceRegistryEvents

DeviceNetworkEvents

OSINT validation: VirusTotal, AbuseIPDB, FortiGuard

🧩 Case Structure

Each Defender case includes:

Incident Summary – Short overview of what Defender detected.

MITRE ATT&CK Mapping – Key techniques (Suggested & Confirmed).

Investigation Steps – Tier-1 hunting queries and checks.

Evidence – Screenshots, hashes, registry or network logs.

Result & Recommended Actions – Containment and next steps.

⚙️ Typical Tier-1 Workflow

Review Defender alert details (device, user, time).

Run Advanced Hunting queries for process, registry, and network events.

Verify IoCs (hashes, file names) using OSINT sources.

Classify as True / False Positive.

Document results using the Defender case template.

📘 MITRE Framework Alignment

Defender alerts are mapped to MITRE ATT&CK techniques for clarity and consistency.
Common tactics: Persistence, Defense Evasion, Execution, Discovery.

🧱 Naming Convention

Case-<MITRE_ID> – <Short Description>
Example: Case-T1546.001 – DLL Side-loading via File Association

👤 Author

Ali Yilmaz
SOC & Incident Response | Microsoft Defender Lab