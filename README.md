# Network Threat Hunting & Incident Analysis

A hands-on network threat hunting and incident investigation project based on the **“Traffic Analysis Exercise: First to Last”** from [Malware-Traffic-Analysis.net](https://malware-traffic-analysis.net/2026/08/09/index.html).

This project documents my approach to investigating suspicious network traffic, examining packet-level evidence, identifying indicators of compromise (IOCs), reconstructing an incident timeline, and preparing an incident report.

The objective is to develop practical skills relevant to **Security Operations Center (SOC) analysis, network forensics, threat hunting, and incident response**.

## Objectives

- Investigate suspicious network traffic using packet-capture analysis.
- Analyze network communications and correlate them with security alerts.
- Identify the potentially compromised endpoint using available network evidence.
- Extract and document relevant indicators of compromise (IOCs).
- Maintain structured investigation notes and an evidence log.
- Reconstruct the sequence of events in a timeline.
- Communicate findings through a structured incident report.

## Investigation Workflow

1. **Alert review** — Understand the initial security alerts and investigation scope.
2. **Traffic analysis** — Examine packet-capture evidence and relevant network conversations.
3. **Host identification** — Correlate network activity with available endpoint identifiers.
4. **IOC documentation** — Record relevant indicators with appropriate context.
5. **Evidence management** — Preserve screenshots, investigation notes, and supporting artifacts.
6. **Timeline reconstruction** — Organize significant observations chronologically.
7. **Incident reporting** — Document findings, supporting evidence, limitations, and recommended next steps.

## Repository Structure

```text
network-threat-hunting/
├── broad-analysis/
│   ├── evidence/
│   │   └── screenshots/
│   ├── iocs/
│   │   └── iocs.csv
│   ├── notes/
│   │   ├── case-notes.md
│   │   ├── case-notes.odt
│   │   ├── evidence-log.md
│   │   └── timeline.md
│   ├── report/
│   │   └── incident-report.md
│   └── README.md
└── practice-questions/
    └── TRAFFIC-ANALYSIS-EXERCISE-FIRST-TO-LAST.pdf
```

## Investigation Artifacts

| Artifact | Purpose |
|---|---|
| `case-notes.md` | Investigation observations, hypotheses, and analytical notes |
| `evidence-log.md` | Record of collected evidence and its relevance |
| `timeline.md` | Chronological sequence of significant events |
| `iocs.csv` | Structured record of identified indicators |
| `incident-report.md` | Consolidated findings, supporting evidence, and recommendations |
| `evidence/screenshots/` | Visual evidence supporting the investigation |
| Practice questions PDF | Original exercise reference for the investigation |

## Tools and Techniques

- **Wireshark** — Packet inspection, protocol analysis, and network conversation investigation.
- **PCAP analysis** — Examination of captured network traffic to investigate suspicious activity.
- **IOC analysis** — Structured documentation and contextual assessment of potential indicators.
- **Incident documentation** — Evidence logging, timeline reconstruction, and incident reporting.

*The tools and techniques listed describe the project's intended analytical workflow; the final report should document which tools were actually used.*

## Skills Demonstrated

- Network traffic analysis
- Threat hunting fundamentals
- Network-based incident investigation
- IOC identification and documentation
- Evidence handling and correlation
- Timeline development
- Technical report writing
- Analytical reasoning and hypothesis validation

## Data Source and Attribution

This project is based on the training exercise:

**Traffic Analysis Exercise: First to Last**  
Source: [Malware-Traffic-Analysis.net — 9 August 2026](https://malware-traffic-analysis.net/2026/08/09/index.html)

The original exercise and its associated materials are provided by the source website. This repository documents my own learning process and investigation artifacts.

## Scope and Disclaimer

This is an educational cybersecurity lab exercise using provided training material. It is intended to develop defensive security analysis skills in a controlled, authorized context.

The findings documented here should be interpreted within the scope of the exercise and the available evidence. Indicators and conclusions should not be treated as independently verified threat intelligence without further validation.

---

**Focus:** Network Forensics | Threat Hunting | SOC Analysis | Incident Response | Blue Team

**Status:** Practical learning project — investigation documentation and analysis.
