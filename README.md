# SAML Single Sign-On Lab with Microsoft Entra ID

<p>
  <img src="https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge" alt="Microsoft Entra ID" />
  <img src="https://img.shields.io/badge/SAML_2.0-3076BE?style=for-the-badge" alt="SAML 2.0" />
  <img src="https://img.shields.io/badge/Single_Sign--On-0078D4?style=for-the-badge" alt="Single Sign-On" />
  <img src="https://img.shields.io/badge/Claims_Mapping-5089F7?style=for-the-badge" alt="Claims Mapping" />
  <img src="https://img.shields.io/badge/Access_Control-111827?style=for-the-badge" alt="Access Control" />
</p>

## Overview

This lab explores SAML-based Single Sign-On (SSO) configuration for a custom enterprise application in Microsoft Entra ID.

The work covers application creation, SAML settings, attribute mapping, user assignment, and authentication testing.

## Lab Objectives

- Configure an enterprise application for SAML authentication.
- Define the application identifier and reply URL.
- Configure the attributes sent to the application.
- Assign users to the application.
- Test the authentication flow.

## Configuration Steps

### 1. Enterprise Application Creation

Created a custom enterprise application in Microsoft Entra ID and selected SAML as the sign-on method.

### 2. Basic SAML Configuration

Configured the application’s SAML settings:

| Setting | Purpose |
| --- | --- |
| Identifier (Entity ID) | Identifies the service provider |
| Reply URL (Assertion Consumer Service URL) | Specifies where Entra ID sends the SAML response |

### 3. Attribute Mapping

Configured user attributes and claims to provide identity information to the application.

### 4. User Assignment

Assigned test users to the enterprise application to manage access.

### 5. Authentication Testing

Tested the authentication flow to evaluate the configuration.

The screenshots below document configuration and user assignment. A successful end-to-end sign-in is not documented here.

## Skills Demonstrated

- Microsoft Entra ID enterprise application administration
- SAML-based SSO configuration
- Application identifiers and reply URLs
- User attribute and claim mapping
- Application access assignment
- Authentication testing

## Key Takeaways

This lab helped me understand how application identifiers, reply URLs, user claims, and access assignments support SAML authentication.

It also reinforced the importance of validating the complete sign-in flow before considering an SSO integration complete.

## Configuration Screenshots

<details>
<summary>View SAML SSO configuration screenshots</summary>

### Enterprise Application Creation

<img width="908" alt="Custom enterprise application in Microsoft Entra ID" src="https://github.com/user-attachments/assets/fc45b90f-f53c-45f4-99c9-2c0393904c76" />

### Identifier and Reply URL

<img width="920" alt="SAML identifier and reply URL settings" src="https://github.com/user-attachments/assets/5fa883b3-be29-4d65-b5fa-1ac3bbc68bd0" />

### SAML Configuration

<img width="939" alt="Enterprise application SAML configuration" src="https://github.com/user-attachments/assets/7448ebbe-8099-4995-b045-7647aca42170" />

### User Assignment

<img width="946" alt="Test users assigned to the enterprise application" src="https://github.com/user-attachments/assets/8d3fcb87-0c81-4a49-9f4c-eabf94c9fc7e" />

</details>
Proper IAM implementation is essential for reducing security risk and maintaining strong governance across enterprise environments.
