# Threat Intelligence & Automation  
OSINT Credential Leak Detection and Monitoring Systems

This section of the portfolio showcases real-world threat intelligence work, OSINT-based monitoring, and automated credential leak detection.  
All examples are anonymised but reflect genuine security engineering and GRC responsibilities.

---

## Purpose

The objective of this project is to design and document a proactive monitoring capability that identifies:

- Leaked credentials  
- Exposed API keys, tokens, or secrets  
- Unauthorised code or configuration leaks  
- Company-related data published publicly  
- Third-party or user-generated leaks

This capability supports early detection and reduces the risk of credential abuse, account compromise, and code theft.

---

## Contents

### 1. leaked-credentials-detection-system.md  
A detailed walkthrough of a custom credential-leak detection workflow using:

- Google Custom Search API  
- Automated keyword-based queries  
- JSON parsing and regex analysis  
- Cron-based task scheduling  
- Email or webhook alerting  
- Optional integration with SIEM platforms such as Wazuh

This document covers configuration, logic, automation, and governance considerations.

### 2. osint-monitoring-architecture.md  
A higher-level architectural design covering:

- Multi-source OSINT collection  
- SpiderFoot, PasteHunter, and Shhgit integrations  
- Monitoring of GitHub, Pastebin, and dark-web sources  
- Alert-routing, triage, and severity classification  
- Self-hosted, modular monitoring stack  
- Operational, logging, and compliance requirements

---

## Relevance to GRC and Security Engineering

This project demonstrates capability in:

- Building and documenting an OSINT monitoring pipeline  
- Early detection of leaked credentials and sensitive assets  
- Automating security processes using scripting and APIs  
- Integrating external intelligence feeds with SIEM  
- Designing evidence-ready processes for PCI DSS, ISO 27001, and SOC 2  
- Applying pattern-matching, parsing, and automated alerting  
- Understanding the intersection of GRC, threat intelligence, and engineering

This type of work is directly relevant to roles involving:

- Governance, Risk and Compliance (GRC)  
- Threat Intelligence  
- Security Operations  
- Detection and Response  
- Continuous Monitoring  
- Third-Party and Vendor Risk  
- Security Engineering and tooling automation

---

## High-Level Architecture Overview

            +---------------------------+
            |   OSINT Sources           |
            |  GitHub, Pastebin, CSE    |
            +-------------+-------------+
                          |
                          v
           +-----------------------------+
           |   Leak Monitor Automation   |
           |  (Scripts, Cron, Regex)     |
           +-------------+---------------+
                          |
     +--------------------+----------------------+
     |                                           |
     v                                           v

+----------------+ +----------------------+
| Email/Webhook | | SIEM (e.g., Wazuh) |
| Notifications | | Log Ingestion & IR |
+----------------+ +----------------------+


---

## Governance and Compliance Considerations

This monitoring capability supports adherence to:

- PCI DSS 4.0 (security monitoring, credential protection, threat detection)  
- ISO 27001 (Annex A controls relating to threat intelligence and monitoring)  
- NIST CSF Detect and Respond functions  
- Third-party oversight and supplier assurance  
- Internal Incident Response and Early Warning procedures  

No real organisational data is included.

---

## Status


The system and documentation are fully anonymised.  
Optional enhancements include Slack alerting, integration with HaveIBeenPwned, VirusTotal enrichment, and classification enhancements.

---

