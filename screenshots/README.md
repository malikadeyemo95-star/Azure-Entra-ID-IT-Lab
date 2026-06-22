# Screenshot Evidence Index

These screenshots are ordered as an end-to-end Microsoft 365 / Entra ID and
Intune support workflow. The sequence is designed to show not only that settings
were clicked, but that the work followed a realistic admin process:
provisioning, licensing, group-based access, account lifecycle management,
least-privilege role delegation, MFA policy configuration, audit validation, and
endpoint compliance setup.

| # | Filename | Evidence value |
| --- | --- | --- |
| 1 | `01-csv-user-upload.png` | Shows bulk user provisioning through CSV upload, a realistic method for onboarding multiple employees. |
| 2 | `02-license-assignment.png` | Shows Germany as the user location and Microsoft 365 Business Premium selected, proving users were prepared with service access. |
| 3 | `03-users-created.png` | Confirms the six lab users were created successfully and given temporary passwords. |
| 4 | `04-it-support-group-members.png` | Shows James Okafor and Sarah Mitchell assigned to the IT-SUPPORT group. |
| 5 | `05-hr-department-members.png` | Shows Laura Becker and Tom Fischer assigned to the HR-Department group. |
| 6 | `06-finance-department-members.png` | Shows Anna Kovacs and David Muller assigned to the Finance-Department group. |
| 7 | `07-user-blocked.png` | Shows James Okafor marked as sign-in blocked after access restriction. |
| 8 | `08-block-confirmed.png` | Shows Microsoft 365 confirmation that the user is blocked from signing in and sessions will be signed out. |
| 9 | `09-user-unblocked.png` | Shows the unblock sign-in workflow, proving the account lifecycle action can be reversed after verification. |
| 10 | `10-sarah-helpdesk-role.png` | Shows Sarah Mitchell's profile with the Helpdesk Administrator role visible. |
| 11 | `11-rbac-role-assignment.png` | Shows the Helpdesk Administrator role selected in admin role management, proving least-privilege delegation. |
| 12 | `12-conditional-access-grant.png` | Shows the Conditional Access grant control requiring MFA before access is allowed. |
| 13 | `13-conditional-access-policy.png` | Shows the policy targeting all users and all cloud apps in Report-only mode for safe testing. |
| 14 | `14-audit-logs.png` | Shows audit log entries for admin activity such as role, group, user, and policy changes. |
| 15 | `15-intune-compliance-basics.png` | Shows the Microsoft Intune compliance policy creation workflow. |
| 16 | `16-intune-policy-created.png` | Shows the Windows 10/11 compliance policy basics screen for `Require Device Compliance - Windows`. |
