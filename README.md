# 🔐 Active Directory Lab — User Management & Domain Administration

A home lab project focused on building and managing an Active Directory environment for user account management, group policy configuration, and domain-level administration.

---

## 🎯 Project Goals

- Set up Active Directory in a lab environment
- Create and manage user accounts and security groups
- Configure Group Policy Objects (GPOs) for centralized management
- Understand domain structure, organizational units (OUs), and trust relationships
- Practice user authentication and permission management across networked systems

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Windows Server | Domain controller hosting Active Directory |
| Active Directory Domain Services (ADDS) | Directory service and user management |
| Group Policy Editor (gpEdit.msc) | GPO configuration and application |
| Active Directory Users and Computers | User and group management interface |
| Domain Name System (DNS) | Domain name resolution for AD |
| Windows domain-joined machines | Client systems authenticating to AD |

---

## 📋 What I Did

### 1. Active Directory Setup
Configured a Windows Server instance as a domain controller with Active Directory Domain Services installed. Set up a test domain to serve as the foundation for user and group management.

### 2. User Account Management
Created multiple user accounts with different permission levels and organizational structures. Practiced:
- User account creation and configuration
- Password policies and account lockout settings
- User properties and contact information management
- Bulk user creation workflows

### 3. Security Groups & Organizational Units
Organized users into security groups and organizational units (OUs) for hierarchical management. Configured group membership to control access to resources and services.

### 4. Group Policy Configuration
Applied Group Policy Objects (GPOs) to enforce security baselines and system configurations across domain-joined machines:
- Password complexity requirements
- Account lockout policies
- Software restriction policies
- Windows Firewall settings
- User rights assignments

### 5. Domain Authentication Testing
Verified that domain-joined client machines could authenticate against the Active Directory domain controller. Tested user login, credential validation, and access to shared resources.

### 6. Troubleshooting & Verification
Tested common AD scenarios:
- User password resets from the domain controller
- Group membership changes and their effect on access
- GPO application delays and refresh cycles
- Domain trust verification

---

## 🧠 Key Skills Demonstrated

- Active Directory Domain Services (ADDS) installation and configuration
- User and group account management
- Organizational Unit (OU) structure and design
- Group Policy Object (GPO) creation and application
- Password and account lockout policy configuration
- Domain authentication and credential verification
- Windows Server administration basics
- Understanding of domain vs workgroup environments
- Troubleshooting AD-related issues

---

## 💡 What I Took Away

Active Directory is the backbone of how organisations manage Windows systems at scale. This project gave me hands-on experience with the core concepts that show up constantly in IT support and infrastructure roles — user management, password resets, group membership changes, and policy application.

Understanding how AD works makes supporting domain-connected machines much easier, and it's a skill that directly transfers to real-world IT environments.
