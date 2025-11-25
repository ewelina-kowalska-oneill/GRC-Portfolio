# Cyber Incident Response Plan  
**XXXXX**

---

## 1. Introduction

### 1.1 Context
Cyber security involves protecting the confidentiality, availability, and integrity of information processed, stored, or transmitted through electronic systems. Threats include:

- external attackers  
- malicious insiders  
- accidental human error  
- misconfigurations  
- system vulnerabilities  

This plan supports **XXXXX** in responding to and recovering from cyber incidents.

### 1.2 Purpose
To provide a structured approach to managing cyber incidents and coordinating detection, response, containment, eradication, communication, and recovery.

This plan is based on **NIST SP 800-61: Computer Security Incident Handling Guide**.

### 1.3 Authority
This plan is maintained by the designated security leadership (e.g., CISO, IT Security Lead) and approved by executive leadership.

### 1.4 Review
The plan must be reviewed annually, or following any major incident.

---

## 2. Terminology & Definitions

### **Cyber Event**
A situation that *may* become an incident but has no confirmed impact.

Examples:
- multiple failed logins  
- antivirus disabled  
- suspicious user activity  
- unexpected server restart  

### **Cyber Incident**
A confirmed breach of confidentiality, integrity, or availability.

Examples:
- ransomware  
- malware infection  
- credential compromise  
- DDoS attack  
- data breach  

Incidents are classified by severity and impact.

---

## 3. Common Cyber Incidents and Responses

| Type | Description | Initial Response |
|------|-------------|------------------|
| **Ransomware** | Encrypts/locks data | Isolate device; preserve logs |
| **Malware** | Virus/worm/trojan | Remove from network; analyse logs |
| **DDoS** | Overwhelms services | Engage provider; filter traffic |
| **Phishing** | Credential theft | Reset passwords; review logs |
| **Data Breach** | Unauthorised access | Contain; notify relevant teams |

---

## 4. Roles and Responsibilities

### 4.1 Incident Management Team (IMT)
The IMT manages analysis, containment, eradication, communication, and recovery.

Typical roles:
- **Incident Manager** — overall coordination  
- **Technical Lead** — investigation, forensics  
- **Communications Lead** — internal & external messaging  
- **Legal Advisor** — compliance & regulatory review  
- **Business Continuity Lead** — recovery coordination  
- **Record Keeper** — logs, decisions, evidence  

### 4.2 Senior Executive Management Team (SEMT)
Activated for major incidents.

Responsibilities:
- strategic direction  
- stakeholder engagement  
- resource allocation  
- critical decision-making  

---

# 5. Incident Response Process  
*Based on NIST SP 800-61.*

---

## 5.1 Step 1: Detection and Analysis

### **Detection sources**
- monitoring systems  
- IDS/IPS alerts  
- anomalous logs  
- user reports  
- threat intelligence  
- external notifications  

### **Common Indicators**
- suspicious authentication attempts  
- unexpected network spikes  
- files modified or missing  
- anti-malware alerts  
- system failures without explanation  

### **Analysis Tasks**
- validate the incident  
- determine affected systems  
- assess scope and severity  
- gather logs/evidence  
- document findings  
- consult SMEs  

---

## Incident Classification Levels

1. **Cyber Event** – no impact  
2. **Cyber Incident** – minor impact  
3. **Significant Incident** – major operational/data impact  
4. **Cyber Emergency** – severe / critical services affected  

---

## 5.2 Step 2: Containment and Eradication

### **Resolution Action Plan Includes**
- immediate containment  
- threat eradication  
- system restoration  
- communication requirements  
- resource needs  

### **Evidence to Preserve**
- disk images  
- memory captures  
- logs  
- packet captures  
- screenshots  
- config files  
- cost impact documents  

A secure evidence log must be maintained.

---

## 5.3 Step 3: Communications & Engagement

### **Internal Communications**
Should outline:
- what happened  
- systems affected  
- expected user actions  
- who to contact  

### **External Communications**
May involve:
- regulators  
- law enforcement  
- clients/customers  
- partners  
- media (if necessary)  

All communications require approval by designated leadership.

---

## 5.4 Step 4: Recover

Recovery includes:
- restoring normal operations  
- monitoring restored systems  
- verifying vulnerability remediation  
- coordinating with continuity and IT teams  

Stand-down is authorised once recovery is complete.

---

## 5.5 Step 5: Learn and Improve

A Post-Incident Review must cover:
- timeline of events  
- what worked / what did not  
- gaps in procedures  
- required improvements  
- follow-up actions  
- updates to this plan  

---

# Appendices

---

## **Appendix A — Situation Update Template**

- Date & time  
- Status (New / In Progress / Resolved)  
- Incident type  
- Classification  
- Scope  
- Impact  
- Severity  
- Notifications made  
- Additional notes  
- Next update schedule  

---

## **Appendix B — Incident Log Template**

Record:
- timestamp  
- actions taken  
- decisions & rationale  
- technical observations  
- responsible person  

---

## **Appendix C — Resolution Action Plan Template**

| Category | Action | Owner | Status |
|----------|--------|--------|--------|
| Contain | | | |
| Eradicate | | | |
| Recover | | | |
| Communications | | | |

---

## **Appendix D — Evidence Register Template**

- collection date/time  
- collector  
- item details  
- storage location  
- chain-of-custody notes  

---

## **Appendix E — Assets & Key Contacts Template**

Includes:
- network and subnet details  
- remote access methods  
- firewall and switch information  
- backup and DR data  
- contact details for key personnel  

---

# **End of Document**
