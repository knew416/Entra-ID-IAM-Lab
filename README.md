# Entra-ID-IAM-Lab

<details>
  <summary>📸 Click to view Entra ID Configuration Screenshots</summary>
  
  ### Group Based Access Control Setup
  <img width="753" height="443" alt="Security Groups" src="https://github.com/user-attachments/assets/3cd41b20-5903-4ce7-8e25-1b6303047d8e" />

  
  ### User Identity Management
  <img width="739" height="617" alt="Users created" src="https://github.com/user-attachments/assets/10ede5ad-03d8-42bb-812f-759802c5ea72" />


  ### Role-Based Access Control
  <img width="621" height="380" alt="Help Desk-assignment" src="https://github.com/user-attachments/assets/d2073e3a-a096-4531-b0c8-1a66166bca1c" />


  ### Enterprise Users
  <img width="1007" height="508" alt="Enterprise Users" src="https://github.com/user-attachments/assets/5586616d-5ed5-415c-a5b4-d4156ad19718" />

  ### Enterprise Applications
  <img width="1079" height="423" alt="Enterprise app- AWS" src="https://github.com/user-attachments/assets/a9fdd488-bfe2-4d7c-90f0-71ee4bba7b9f" />


  ### Monitoring & Audit Logs
  <img width="753" height="580" alt="Monitor Logs" src="https://github.com/user-attachments/assets/b14986a6-1e96-4e18-8bb2-2785c54611fb" />

  <img width="698" height="701" alt="Failed Login- Logs" src="https://github.com/user-attachments/assets/03dcd993-80be-478d-a082-6f2a70fcf304" />

</details>



📌 Project Overview

This lab demonstrates the implementation of Identity and Access Management (IAM) controls using Microsoft Entra ID. The project simulates how an organization can securely manage user identities, enforce access controls, and monitor authentication activity using identity governance best practices.


The focus of this lab is implementing role-based access control, group-based permissions, and baseline identity security protections.

🏢 Business Scenario

A small organization with the following departments requires secure access to internal systems:

Human Resources

Information Technology

Finance

The organization needs to ensure:

Employees only have access to resources required for their role

Administrative privileges follow least privilege principles

Identity security protections such as MFA and modern authentication are enforced

Microsoft Entra ID was used to simulate this identity environment.


👤 User Identity Management

Created multiple user accounts representing employees across departments.

👥 Group-Based Access Control

Security groups were created to manage departmental access.

Security Groups Created

HR-Group

IT-Group

Finance-Group

Users were assigned to groups based on their department, enabling centralized access management and simplified permission assignment.

🛡 Role-Based Access Control (RBAC)

Administrative access was assigned using built-in Entra ID roles following the principle of least privilege.

Roles were assigned only where required to reduce risk of privilege abuse.

RBAC helps organizations:

Limit administrative exposure

Enforce separation of duties

Improve governance and auditability

🔐 Identity Security Controls Implemented

Several baseline security protections were configured to strengthen identity security.

Security Controls

✔ Enabled Security Defaults to enforce Multi-Factor Authentication (MFA)
✔ Blocked legacy authentication protocols
✔ Enforced modern authentication methods

These controls reduce the risk of:

Credential theft

Password-based attacks

Legacy authentication vulnerabilities

🏢 Enterprise Application Access

An enterprise application was configured to simulate Single Sign-On (SSO) access management.

Group-based assignments were used to control which departments could access the application.

This demonstrates how organizations manage:

Application access

Identity federation

Centralized authentication

📊 Monitoring & Audit Logs

Security monitoring was performed by reviewing:

Sign-in logs

Audit activity logs

These logs help security teams detect:

Suspicious login activity

Unauthorized access attempts

Administrative changes

Monitoring identity events is a critical component of IAM governance and incident response.

🧠 Skills Demonstrated

This project demonstrates practical IAM administration skills including:

Microsoft Entra ID administration

Identity lifecycle management

Role-Based Access Control (RBAC)

Group-based access management

Identity security configuration

Security monitoring and audit review

🎯 Key Takeaways

This lab highlights how organizations implement foundational IAM controls to:

Secure user identities

Enforce least privilege access

Strengthen authentication security

Monitor identity-related activity

Proper IAM implementation is essential for reducing security risk and maintaining strong governance across enterprise environments.
