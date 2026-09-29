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
![User Directory](./WhatsApp%20Image%202026-09-29%20at%207.07.21%20PM.jpeg)
*Centralized view of provisioned identities across the organization.*

### RBAC Roles Configuration
![Roles List](./WhatsApp%20Image%202026-09-29%20at%207.20.10%20PM.jpeg)
*Defined access control roles for IT, HR, and Finance.*

### Role Assignment
![Role Assignment](./WhatsApp%20Image%202026-09-29%20at%207.20.38%20PM.jpeg)
*Successful assignment of a user identity to the IAM-Administrator role.*

### MFA Security Policy
![MFA Policy](./WhatsApp%20Image%202026-09-29%20at%207.19.11%20PM.jpeg)
*Tenant-wide enforcement of OTP Multi-Factor Authentication.*
