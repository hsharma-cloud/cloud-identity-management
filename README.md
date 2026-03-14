÷
---

# Azure Identity Security Architecture

Azure identity security was implemented using Microsoft Entra ID and Azure RBAC.

Components configured in this lab:

- Entra ID Users and Groups
- Azure RBAC role assignments
- Conditional Access with MFA
- Privileged Identity Management (PIM)
- Self-Service Password Reset (SSPR)
- App Registration
- Managed Identity
- Azure Key Vault access
- Identity Protection policies

---


# Azure Identity Security Implementation








---

# AWS Identity Security Implementation


## IAM Users

![IAM Users](screenshots/aws/aws-iam-users.png)

---

## IAM Groups

![IAM Groups](screenshots/aws/aws-iam-groups.png)

---

## Cloud Admin Permissions

![Cloud Admin Permissions](screenshots/aws/aws-cloud-admin-permissions.png)

---

## Custom IAM Policy

![Custom IAM Policy](screenshots/aws/aws-custom-policy.png)

---

## EC2 Read Only Policy

![EC2 Policy](screenshots/aws/EC2ReadOnlyPolicy.png)

---

## IAM Role for EC2

![EC2 IAM Role](screenshots/aws/aws-ec2-iam-role.png)

![EC2 Role Overview](screenshots/aws/aws-ec2-role-overview.png)

---

## STS AssumeRole

![Assume Role](screenshots/aws/aws-assume-role.png)

---

## AWS Secrets Manager

![Secrets Manager](screenshots/aws/aws-secrets-manager.png)

---

## IAM Access Analyzer

![Access Analyzer](screenshots/aws/aws-access-analyzer.png)

---

## IAM Credential Security

![IAM Credentials](screenshots/aws/aws-iam-security-credentials.png)

---

## Permission Boundaries

![Permission Boundary](screenshots/aws/DeveloperPermissionBoundary.png)

Components configured in this lab:

- IAM Users
- IAM Groups
- IAM Policies
- Custom JSON Policies
- IAM Roles
- STS AssumeRole
- Secrets Manager
- IAM Access Analyzer
- Permission Boundaries

---


# Security Concepts Demonstrated

Authentication Security
- Multi-factor authentication
- Conditional Access policies

Privileged Access Management
- Just-In-Time access
- Temporary credentials

Authorization
- Role-Based Access Control
- IAM policy evaluation
- Permission boundaries

Workload Identity
- Azure Managed Identity
- AWS IAM Roles

Secret Protection
- Azure Key Vault
- AWS Secrets Manager

Identity Monitoring
- AWS Access Analyzer
- Azure Identity Protection

---

# Technologies Used

Azure
- Microsoft Entra ID
- Azure RBAC
- Conditional Access
- Privileged Identity Management
- Managed Identity
- Azure Key Vault
- Identity Protection

AWS
- IAM Users
- IAM Groups
- IAM Policies
- IAM Roles
- AWS STS
- AWS Secrets Manager
- IAM Access Analyzer
- Permission Boundaries

