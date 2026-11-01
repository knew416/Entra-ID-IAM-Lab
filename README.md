# Microsoft Entra ID: Identity and Access Management Lab

## Overview

This lab simulates a small organization's identity environment using Microsoft Entra ID. It covers user administration, departmental security groups, role-based access control, baseline security settings, enterprise application assignments, and log review.

## Business Scenario

An organization with Human Resources, IT, and Finance departments needs to manage employee access while limiting administrative privileges.

The lab focuses on:

- Organizing users by department.
- Managing access through security groups.
- Assigning administrative roles according to least privilege.
- Configuring baseline authentication protections.
- Reviewing sign-in activity and administrative changes.

## Environment

| Component | Purpose |
| --- | --- |
| Microsoft Entra ID | Identity and access administration |
| Test user accounts | Simulated employees across three departments |
| Security groups | Departmental access management |
| Built-in directory roles | Administrative access control |
| Enterprise application | Application access assignment |
| Sign-in and audit logs | Authentication and change review |

## Configuration

### 1. User Administration

Created test user accounts representing employees in Human Resources, IT, and Finance.

### 2. Group-Based Access Management

Created departmental security groups and added the appropriate users.

| Security Group | Department |
| --- | --- |
| HR-Group | Human Resources |
| IT-Group | Information Technology |
| Finance-Group | Finance |

Group membership provides a central way to manage departmental application assignments.

### 3. Role-Based Access Control

Assigned built-in Microsoft Entra ID administrative roles, including Helpdesk Administrator, to support specific responsibilities.

The configuration demonstrates using a role appropriate to the task rather than granting broad administrative access.

### 4. Baseline Identity Security

Enabled Security Defaults as the tenant's baseline identity protection.

This setting provides Microsoft-managed protections for MFA registration, MFA requirements, and blocking legacy authentication.

### 5. Enterprise Application Access

Configured an enterprise application and used group-based assignments to organize access.

This portion of the lab focuses on application assignment. An assignment alone does not demonstrate a completed SSO integration.

### 6. Sign-In and Audit Log Review

Reviewed sign-in logs and audit logs to examine authentication activity and directory changes.

The screenshots include a failed sign-in event, demonstrating how logs can support access troubleshooting. A failed sign-in alone does not establish malicious activity.

## Skills Demonstrated

- Microsoft Entra ID user and group administration
- Group-based application assignment
- Built-in administrative role assignment
- Least privilege access configuration
- Security Defaults configuration
- Sign-in and audit log review
- IAM documentation

## Key Takeaways

This lab helped me understand how user accounts, security groups, administrative roles, application assignments, and authentication protections work together.

It also reinforced the importance of reviewing logs and distinguishing between a configured control and a verified outcome.

## Configuration Screenshots

<details>
<summary>View lab screenshots</summary>

### Departmental Security Groups

<img width="753" alt="Departmental security groups in Microsoft Entra ID" src="https://github.com/user-attachments/assets/3cd41b20-5903-4ce7-8e25-1b6303047d8e" />

### Test User Accounts

<img width="739" alt="Test user accounts created in Microsoft Entra ID" src="https://github.com/user-attachments/assets/10ede5ad-03d8-42bb-812f-759802c5ea72" />

### Helpdesk Administrator Role Assignment

<img width="621" alt="Helpdesk Administrator role assignment" src="https://github.com/user-attachments/assets/d2073e3a-a096-4531-b0c8-1a66166bca1c" />

### Enterprise Application Users

<img width="1007" alt="Users assigned to the enterprise application" src="https://github.com/user-attachments/assets/5586616d-5ed5-415c-a5b4-d4156ad19718" />

### Enterprise Application Configuration

<img width="1079" alt="AWS enterprise application configuration" src="https://github.com/user-attachments/assets/a9fdd488-bfe2-4d7c-90f0-71ee4bba7b9f" />

### Log Review

<img width="753" alt="Microsoft Entra ID monitoring logs" src="https://github.com/user-attachments/assets/b14986a6-1e96-4e18-8bb2-2785c54611fb" />

### Failed Sign-In Event

<img width="698" alt="Failed sign-in event details" src="https://github.com/user-attachments/assets/03dcd993-80be-478d-a082-6f2a70fcf304" />

</details>
Proper IAM implementation is essential for reducing security risk and maintaining strong governance across enterprise environments.
