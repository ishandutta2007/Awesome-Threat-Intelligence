# Awesome-Threat-Intelligence

# Top Threat Intelligence Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cyber Threat Intelligence, Adversary Tracking & Security Operations*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Threat Intelligence**. These tools enable security teams to collect, analyze, enrich, and operationalize threat data—including indicators of compromise (IOCs), adversary tactics, techniques, and procedures (TTPs), malware intelligence, and vulnerability exploitation context—to proactively defend against cyber threats.

**Examples** include ServiceNow Threat Intelligence, Recorded Future, Mandiant Threat Intelligence, CrowdStrike Falcon Intelligence, ThreatConnect, Anomali, Palo Alto Networks Unit 42, Cyware, Cisco Talos, and Flashpoint (the category leaders).

**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted threat intelligence platforms, OSINT collection, IOC management, and STIX/TAXII sharing—ideal for SOC teams, threat analysts, and organizations building sovereign threat intelligence programs without per-feed licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Threat Intelligence](https://www.servicenow.com/)**  
  Threat Intelligence Security Center built natively on the Now Platform, providing threat hunting, modeling, analysis, and monitoring with CMDB context for business-aware risk assessment; integrates with SIEM, EDR, and firewall tools, and includes customizable threat scoring and threat-specific playbooks .

- **[Recorded Future](https://www.recordedfuture.com/)**  
  Intelligence platform named a Leader in Forrester Wave for External Threat Intelligence Services (Q3 2026); provides real-time risk scores, 200+ network intelligence points of presence, MITRE ATT&CK mapping for 350+ malware families, and agentic AI-powered workflows for detection and response .

- **[Mandiant Threat Intelligence](https://www.mandiant.com/)**  
  Frontline intelligence from Mandiant incident response and FireEye telemetry; offers free tier with known indicators and MITRE ATT&CK pivot views, plus paid subscriptions for Security Operations, Vulnerability, and Digital Threat Monitoring with finished intelligence reports .

- **[CrowdStrike Falcon Intelligence](https://www.crowdstrike.com/)**  
  Adversary intelligence platform tracking 281+ adversaries with personalized threat intelligence, real-time IOCs, malware analysis, brand/fraud monitoring, and pre-built YARA/Snort detection rules; includes Threat AI agents for autonomous reasoning and hunting .

- **[ThreatConnect](https://threatconnect.com/)**  
  Threat intelligence platform with AI summarization for documents and reports, ThreatAssess scoring, and CAL Automated Threat Library; recent releases add AI-powered document parsing and MITRE ATT&CK classification .

- **[Anomali](https://www.anomali.com/)**  
  AI-powered security and IT operations platform with ThreatStream for TIP functionality, ThreatStream Analytics (AQL query language), ThreatRadar dashboards, and premium feeds from Flashpoint, CrowdStrike, Intel471, and Mandiant .

- **[Palo Alto Networks Unit 42](https://unit42.paloaltonetworks.com/)**  
  Threat research and intelligence from Palo Alto's Unit 42 team; recently launched Continuous Frontier AI Defense, an agentic offensive security service using defender-grade frontier models to discover and validate exploitable exposures before weaponization .

- **[Cyware](https://www.cyware.com/)**  
  Intelligence Suite (formerly Intel Packaged Solution) built on Cyware Intel Exchange TIP; includes automated ingestion, deduplication, STIX/TAXII sharing, integrated sandbox, sectoral feeds, dark web domain sightings, and compromised credential management .

- **[Cisco Talos](https://talosintelligence.com/)**  
  Threat intelligence from Cisco's Talos group, including Talos Threat Hunting service that proactively searches endpoint, firewall, and identity telemetry for stealthy attacker behavior below alert thresholds, with human-validated findings delivered to customers .

- **[Flashpoint](https://flashpoint.io/)**  
  Primary-source threat intelligence with deep dark web and criminal community coverage; 2026 capabilities include threat-informed EASM (mapping external attack surface to actively exploited vulnerabilities), Business-Aligned PIRs, and Managed Attribution browser for safe underground research .

## Open-Source GitHub Projects

- **[MISP](https://github.com/MISP/MISP)**  
  The leading open-source threat intelligence sharing platform (AGPL-3.0); enables structured IOC storage, correlation, and sharing across organizations using STIX/TAXII standards; widely deployed by CERTs, ISACs, and SOC teams globally for collaborative threat intelligence.

- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  
  Open-source cyber threat intelligence platform (Apache 2.0) built on STIX 2.1; provides a knowledge graph for structuring, storing, and visualizing threat data, with connectors to MISP, MITRE ATT&CK, and major feeds; ~6,000+ GitHub stars.

- **[TheHive](https://github.com/TheHive-Project/TheHive)**  
  Open-source security incident response platform (AGPL-3.0) that integrates with MISP for threat intelligence enrichment; enables case management, observable analysis, and collaborative investigation with Cortex analyzers.

- **[SpiderFoot](https://github.com/smicallef/spiderfoot)**  
  Leading open-source OSINT automation platform (MIT) with 200+ modules for reconnaissance; aggregates intelligence from DNS, WHOIS, threat feeds, Shodan, VirusTotal, and more; includes web UI, CLI, and REST API for automated threat surface discovery.

- **[IntelOwl](https://github.com/intelowlproject/IntelOwl)**  
  Open-source intelligence aggregation platform (AGPL-3.0) for SOC and CERT teams; queries 100+ analyzers (VirusTotal, AbuseIPDB, GreyNoise, etc.) in parallel to enrich observables and accelerate triage.

- **[Yeti](https://github.com/yeti-platform/yeti)**  
  Open-source threat intelligence repository and analysis platform (Apache 2.0); provides a unified interface for observables, TTPs, and indicators, with graph-based correlation and a REST API for automation.

- **[ThreatIngestor](https://github.com/InQuest/ThreatIngestor)**  
  Open-source tool (MIT) for extracting and aggregating threat intelligence from various sources (Twitter, RSS, arbitrary web pages); supports multiple output backends including MISP and Slack; ideal for building custom feed ingestion pipelines.

- **[IntelMQ](https://github.com/certtools/intelmq)**  
  Open-source solution (AGPL-3.0) for IT security teams to collect and process security feeds; developed by CERTs for automating incident handling and threat intelligence processing with a modular bot architecture.

### Additional Strong Open-Source Options

- **STIX/TAXII Libraries** — Open specifications and libraries (e.g., `stix2` Python library) for working with Structured Threat Information Expression and Trusted Automated Exchange of Intelligence Information.
- **Sigma** — Open standard and toolset for writing detection rules in a generic format, convertible to SIEM queries; maintained by SigmaHQ with a large rule repository.
- **YARA** — Pattern-matching tool for malware identification and classification; essential for building detection signatures from threat intelligence.
- **SecureFlow Intel** — OSINT threat intelligence platform built on SpiderFoot with 200+ reconnaissance modules and web UI .

**Frameworks for building custom systems**: Combine **MISP** for threat intelligence sharing and IOC management, **OpenCTI** for STIX-based knowledge graph analysis, **TheHive** for incident response case management, and **SpiderFoot** or **IntelOwl** for automated OSINT enrichment in a fully self-hosted threat intelligence platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Threat intelligence platforms handling sensitive security data must comply with applicable regulations and information sharing agreements (TLP markings, ISAC participation rules, etc.).
- Self-hosted open-source solutions require proper security hardening, feed management, and integration with existing SIEM/SOAR workflows.
- Verify license terms for commercial use; MISP uses AGPL-3.0, OpenCTI uses Apache 2.0, and SpiderFoot uses MIT.

---

**Made for SOC analysts, threat intelligence teams, security researchers, and incident responders.**  
Let's make threat intelligence more open, actionable, and collaborative.
