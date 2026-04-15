# Homelab Project 1: Foundation and Active Directory Security Lab

## Overview
Built and secured an Active Directory lab environment to develop hands-on experience in identity and access management, system hardening, and security monitoring. Configured user accounts and Group Policy Objects, enforced least privilege access controls, and analyzed Windows Security Event Logs to monitor authentication activity and identify potential security threats.

## Enironment
- Windows Server (Domain Controller)
- Windows Client (Domain-Joined Workstation)
- Kali Linux (Attack Simulation System)
- Active Directory Domain: corp.local

## Key Components
- DC1 (Domain Controller)
- CLIENT1 (Domain-Joined Workstation)
- KALI1 (Attacker Security Testing Machince)
- Organization Units: Employees, IT, Workstations

## Security Implementation
### Identity and Access Management
- Created users, groups and organizational units
- Implemented role-based access control using security groups (e.g., Employees_Group)
- Enforced least privilege for all users and resource access 

### Group Policy Hardening
- Configured password policies
- Enforced account lockout threshholds to mitigate bruteforce, dictionary, and hybrid attacks.
- Applied user restrictions using Group Policy Management

### File System Security
- Secure sensitive directories and ensured the oppropriate users had access (e.g., HR-Confidential)
- Removed inherited permissions and applied explicit New Technology File System access controls
- Implemented group-based permissions to simplify access management

## Monitoring and Detection
### Advanced Audit Policies Configured
- Logon and logoff auditing
- Credential validation monitoring
- Account lockout tracking
- Object access auditing

### Key Security Events Analyzed
- 4624 - Successful logon
- 4625 - Failed logon attempt
- 4740 - Account lockout
- 4663 - File access activity

## Attack Simulation

## Screenshots

## Key Takeaways

## Skills Demonstrated

## Project Status
