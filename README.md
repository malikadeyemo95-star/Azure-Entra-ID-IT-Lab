# Azure Entra ID & Intune IT Support Lab

A hands-on Microsoft 365 and Azure IT administration lab simulating a real enterprise environment. Built to demonstrate practical skills in identity management, access control, device compliance, and IT support workflows using Microsoft Entra ID (Azure AD), Microsoft Intune, and the Microsoft 365 Admin Center.

---

## Lab Overview

This lab simulates the IT infrastructure of a small organisation with three departments: IT Support, HR, and Finance. All configurations were performed in a live Microsoft 365 Business Premium tenant.

**Tools & Platforms Used:**
- Microsoft 365 Admin Center
- Microsoft Entra ID (Azure AD)
- Microsoft Intune
- Azure Portal

---

## What Was Built

### 1. Organisational Structure
- Created 3 Microsoft 365 department groups: `IT-SUPPORT`, `HR-Department`, `Finance-Department`
- Created 6 licensed user accounts and assigned each to their department group
- Assigned M365 Business Premium licenses to all users

### 2. Identity & Access Management
- Enabled **Security Defaults** to enforce MFA across the organisation
- Configured **Self-Service Password Reset (SSPR)** for all users — reducing helpdesk ticket load
- Created a **Conditional Access policy** (`Require MFA for All Users`) targeting all cloud apps, set to Report-only mode for safe monitoring

### 3. Role-Based Access Control (RBAC)
- Assigned the **Helpdesk Administrator** role to Sarah Mitchell (IT Support Technician)
- Demonstrates principle of least privilege — user has only the permissions needed for their role

### 4. User Lifecycle Management
- Simulated a full user offboarding workflow: blocked sign-in for a departing user (James Okafor)
- Restored access to simulate re-onboarding
- Demonstrates the standard IT detect → action → verify workflow

### 5. Device Compliance (Intune)
- Created a Windows 10/11 compliance policy: `Require Device Compliance - Windows`
- Enforced **BitLocker encryption** and **Microsoft Defender** risk score requirements
- Configured noncompliant devices to be marked immediately

### 6. Monitoring & Audit
- Reviewed **Sign-in logs** to verify admin activity and application access
- Reviewed **Audit logs** showing all changes: group membership, SSPR updates, RBAC assignments, policy creation
- Demonstrates ability to investigate security events and produce audit-ready records

---

## IT Support Scenarios Covered

| Scenario | Action Taken |
|----------|-------------|
| New employee onboarding | Created user, assigned license, added to department group |
| MFA enforcement | Enabled Security Defaults + Conditional Access policy |
| Password reset reduction | Configured SSPR for all users |
| Employee offboarding | Blocked sign-in, verified access removal |
| Re-onboarding | Restored sign-in access |
| Role delegation | Assigned Helpdesk Admin role via RBAC |
| Device compliance | Created Intune policy requiring BitLocker + Defender |
| Security investigation | Reviewed sign-in and audit logs |

---

## Skills Demonstrated

- Microsoft Entra ID (Azure AD) administration
- Microsoft Intune device compliance policy configuration
- Conditional Access policy creation and management
- Self-Service Password Reset (SSPR) configuration
- Role-Based Access Control (RBAC)
- User lifecycle management (onboarding, offboarding, re-onboarding)
- Security log review and audit trail analysis
- Microsoft 365 Admin Center user and license management

---

## Screenshots

*(Add your screenshots here in a /screenshots folder — one per task listed above)*

---

## Author

**Adeyemo Malik** — IT Support Engineer | Berlin, Germany  
[LinkedIn](https://linkedin.com/in/malik-adeyemo-a86922339) | [GitHub](https://github.com/malikadeyemo95-star)
