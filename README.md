# Sam Jackson

**SOC Analyst Intern @ LOG(N) Pacific · MSc Cyber Security Technology**

Hypothesis → evidence → timeline → report. This profile documents defensive
security work (threat hunting, detection engineering, vulnerability management
and incident response) done in Azure: in LOG(N) Pacific's cyber range during my
internship, and in a SOC lab I built myself from an empty subscription. Each
project says what was real, what was simulated, and where AI helped.

## 🔍 Featured Work

| Project | Summary | Stack |
|---|---|---|
| [Haldane SOC Lab](https://github.com/SamJ-01/haldane-soc-lab) | A fictional company built from code in my own Azure tenant, then secured, monitored, attacked and reported on end to end. Vulnerabilities 67 → 58 with no High/Medium left; 6 KQL detections deployed as code and tested; an approval-gated response playbook; a purple-team exercise where my rules caught 3 of 4 attacks that Defender's built-in detections missed. [Final report](https://github.com/SamJ-01/haldane-soc-lab/blob/main/docs/08-report.md) | Sentinel · Defender for Endpoint · KQL · Bicep · Active Directory · Nessus · Logic Apps |
| [Patch Notes](https://github.com/SamJ-01/patch-notes) | **Live at [patchnoteslab.com](https://patchnoteslab.com/).** A free learning site for people getting into cyber security and IT: 26 browser labs, guided missions, simulated SOC shifts, exam prep, and a daily news and CVE feed prioritised with CISA KEV and EPSS. Rebuilt and deployed every day by GitHub Actions. | Python (stdlib) · JavaScript · GitHub Actions/Pages |
| [Operation Silent Corridor](https://github.com/SamJ-01/threat-hunt-silent-corridor) | LOG(N) Pacific threat-hunt challenge: used KQL against Sysmon telemetry to trace a multi-stage intrusion (credential theft → lateral movement → ntds.dit exfiltration → anti-forensics). Write-up, IOCs and queries, ATT&CK-mapped. | KQL · Sysmon · Azure Log Analytics |
| [netscan-report](https://github.com/SamJ-01/netscan-report) | Python CLI that wraps nmap, risk-rates exposed services and generates HTML/Markdown/JSON reports. Validated in a scan → harden → re-scan lab, where real-world testing exposed (and fixed) an SMB severity bug. | Python · nmap · pytest |
| [KQL Detection Library](https://github.com/SamJ-01/kql-detection-library) | Nine detection queries organised by ATT&CK tactic, each with hypothesis, false-positive profile, response steps and an honest validation status. | KQL · Sentinel · MDE |
| [MDE Detection & Automated Response](https://github.com/SamJ-01/mde-detection-automation) | Defender custom detections with gated automated response (device isolation, investigation package), plus a tested, approval-gated isolation script. | Defender for Endpoint · Python |

## 🧰 Toolset

**SIEM/EDR:** Microsoft Sentinel, Defender for Endpoint / XDR, Azure Log Analytics, Sysmon
**Detection & hunting:** KQL, MITRE ATT&CK, PEAK framework
**Vuln management:** Tenable Nessus, nmap, Group Policy hardening, CVE/EPSS prioritisation
**Cloud & identity:** Azure, Bicep (infrastructure as code), Active Directory, Logic Apps
**Scripting:** Python, PowerShell, Bash, SQL

## 🎓 Background

- MSc Cyber Security Technology, Northumbria University (in progress)
- Google Cybersecurity Professional Certificate
- CompTIA Security+ (in progress)

📫 samandrejackson@gmail.com · [LinkedIn](https://www.linkedin.com/in/samuel-jackson-46b33a1b7)
