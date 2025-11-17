# Access Control — Evidence Templates (GRC Portfolio)

Demonstrates compliance with PCI DSS 7.2.5.1 and 8.6.3.

---

## 1. System Access Review Template

**Account Inventory:**  
List of all application/system accounts under review.

**Per-Account Documentation:**
- Account name  
- Owner  
- Privileges  
- Last login  
- Is access appropriate? (Yes/No)  
- Remediation required?  
- Reviewer signature  

---

## 2. Sample Completed Entry

| Account | Owner | Privileges | Appropriate | Action |
|--------|-------|------------|-------------|--------|
| api_service | DevOps Team | Read-write | Yes | None |
| legacy_admin | Unknown | Full admin | No | Remove account |

---

## 3. Password Rotation Evidence Template

**Evidence Includes:**
- TRA defining rotation frequency  
- Password vault export  
- Linux/PAM config extract  
- Password age report  
- Ticket showing reset executed  

**Example Justification:**  
“Quarterly rotation applied to high-risk privileged accounts; annual rotation for low-risk system accounts.”  
