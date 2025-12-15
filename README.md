# Active Directory Basics — Security Overview

## Overview
Active Directory (AD) is a Windows service used by organizations to centrally manage users, computers, and permissions within a network. This repository documents core Active Directory concepts with a focus on why they are important from a security perspective.

Understanding Active Directory is critical because it controls authentication, authorization, and access to sensitive systems across an enterprise environment.

---

## Key Concepts

### User and Group Management
Active Directory organizes users into groups to manage permissions efficiently. Instead of assigning permissions to individual users, access is typically granted through group membership.

This allows administrators to control what users can access based on their role within the organization.

---

### Authentication and Authorization
Active Directory handles authentication by verifying a user’s identity when they log in, and authorization by determining what resources they are allowed to access.

If authentication or authorization is misconfigured, unauthorized users may gain access to systems or data they should not have.

---

### Administrative Privileges
Administrators in Active Directory have elevated privileges that allow them to manage users, computers, and security settings.

Because of this, administrative accounts are high-value targets for attackers.

---

## Security Relevance
Active Directory is a common target for attackers because compromising it can provide control over an entire network. Gaining access to privileged accounts allows attackers to change permissions, escalate privileges, and access sensitive information.

Many large security incidents begin with attackers abusing Active Directory misconfigurations rather than exploiting advanced vulnerabilities.

---

## Common Risks and Misconfigurations
- Excessive administrative privileges
- Poor group management
- Weak password policies
- Lack of monitoring for permission changes
- Users assigned more access than necessary

These issues can allow attackers to move laterally across systems or escalate privileges.

---

## Key Takeaways
- Active Directory is central to enterprise security
- Least privilege is essential for reducing risk
- Small configuration mistakes can lead to major security incidents
- Monitoring and proper access control are critical for defense

---

## Tools and Learning Platforms
- TryHackMe
- Windows environments
- Active Directory concepts and labs

---

## Next Steps
- Explore Active Directory attack techniques
- Practice identifying misconfigurations
- Learn basic monitoring and detection strategies
