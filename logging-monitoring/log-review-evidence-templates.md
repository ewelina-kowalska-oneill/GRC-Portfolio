# Logging & Monitoring — Evidence Templates (GRC Portfolio)

Templates below demonstrate compliance with PCI DSS 10.4.2.1 and general log review requirements.

---

## 1. Targeted Risk Analysis Evidence (Log Review Frequency)

**Document Title:** Log Review TRA – Non-Daily Systems  
**Criteria Evaluated:**
- System role importance  
- Sensitivity (internal-only, no cardholder data)  
- Access type (local-only vs remote)  
- Change frequency  
- Threat profile (previous findings, exposure)  

**Risk Result:**  
- Backup servers → Medium → Weekly  
- Dev/Test systems → Low → Monthly  

**Justification:**  
“Systems classified as low-risk due to internal-only exposure and low impact.”

**Approval:**  
Name / Signature / Date

---

## 2. Log Review Checklist Template

| Item | Description | Evidence | Status |
|------|-------------|----------|--------|
| Failed logins | Review repeated authentication failures | Screenshot | ✔ |
| Unauthorized access attempts | Look for privilege escalation attempts | Log extract | ✔ |
| System errors | Identify abnormal events | Log summary | ✔ |
| Configuration changes | Compare with baseline | Change tickets | ✔ |
| Anomalies | Investigate unusual patterns | Ticket link | ✔ |

---

## 3. Log Review Report Template

**System Reviewed:** Internal Reporting Tool  
**Date Range:** 2025-02-01 → 2025-02-28  
**Reviewer:** John Doe  
**Findings:**  
- No anomalies found  
- No failed login spikes  
- Single service restart (ticket linked)

**Outcome:**  
Compliant  
