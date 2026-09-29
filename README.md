# Enterprise Identity and Access Management (IAM) Simulation

## 📌 Project Overview
This project simulates an enterprise-grade Identity and Access Management (IAM) environment using **Auth0**. The objective is to demonstrate hands-on proficiency in core identity governance principles, including user lifecycle management, Role-Based Access Control (RBAC), and the enforcement of zero-trust security policies.

## 🎯 Objectives Achieved
* **User Lifecycle Management:** Provisioned and managed digital identities for simulated employees across multiple organizational departments (IT, HR, Finance, Marketing).
* **Role-Based Access Control (RBAC):** Architected a least-privilege access model by mapping users to specific functional roles based on their department requirements.
* **Security & Compliance:** Hardened the authentication perimeter by enforcing mandatory Multi-Factor Authentication (MFA) across the tenant.

## 🛠️ Key Implementations

### 1. User Provisioning & Directory Management
Created a centralized directory of fictional employees representing a standard corporate structure. 
* Provisioned standard username/password credentials.
* Simulated distinct departmental identities (e.g., `admin.iam@example.com`, `finance.auditor@example.com`, `hr.manager@example.com`).

### 2. Role-Based Access Control (RBAC)
Established functional groups to restrict access based on the principle of least privilege:
* **IAM-Administrator:** Granted full administrative access to directory, user lifecycles, and security settings.
* **Finance-Auditor:** Configured for read-only access to financial systems and compliance reports.
* **HR-Manager:** Configured for access to employee onboarding systems and personnel records.
* Successfully mapped provisioned users to their respective security groups.

### 3. Multi-Factor Authentication (MFA) Enforcement
Configured tenant-wide security policies to mitigate credential compromise risks:
* Enabled **One-Time Password (OTP)** authenticators.
* Modified the global authentication policy to **"Always Require Multi-factor Auth,"** ensuring no user can bypass the secondary challenge during login.

## 📸 Evidence & Configuration Screenshots

*(Note: Replace the links below with the actual image files uploaded to this repository)*

### User Directory
<img width="1351" height="630" alt="User Directory" src="https://github.com/user-attachments/assets/b0392bf3-f02f-437f-8f84-3b3acf5e4dad" />

*Centralized view of provisioned identities across the organization.*

### RBAC Roles Configuration
<img width="1338" height="575" alt="RBAC Roles Configuration" src="https://github.com/user-attachments/assets/470cff8a-e6d9-4042-87b4-1df9c2cd7b60" />

*Defined access control roles for IT, HR, and Finance.*

### Role Assignment
<img width="1365" height="632" alt="Role Assignment" src="https://github.com/user-attachments/assets/b4576d8c-056b-4cbc-849f-b5e648fe80eb" />

*Successful assignment of a user identity to the IAM-Administrator role.*

### MFA Security Policy
<img width="1341" height="640" alt="MFA Security Policy" src="https://github.com/user-attachments/assets/7c8156b9-4076-42d5-b792-1b4c58fc3fd5" />

*Tenant-wide enforcement of OTP Multi-Factor Authentication.*
