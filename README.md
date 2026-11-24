# Active-Directory-Home-Lab-Domain-Controller-Deployment-DNS-Troubleshooting
# 🏠 Active Directory Home Lab: Domain Controller Deployment & DNS Troubleshooting

## 📌 Overview

This project documents the deployment, configuration, and troubleshooting of a Windows Active Directory home lab environment. The objective was to gain hands-on experience with enterprise identity management, DNS services, Windows domain administration, and endpoint integration.

The lab consisted of a Windows Server 2019 Domain Controller and a Windows 10 workstation joined to the domain. During deployment, DNS issues impacted domain communication and authentication. These issues were systematically diagnosed and resolved, resulting in a fully operational Active Directory environment.

---

## 🖥️ Lab Environment

### Virtual Infrastructure

| System | Role |
|----------|----------|
| Windows Server 2019 | Domain Controller (DC01) |
| Windows 10 | Domain-Joined Workstation |
| Ubuntu | Future Splunk Deployment |
| Kali Linux | Security Testing |

### Technologies

- VMware Workstation
- Windows Server 2019
- Windows 10
- Active Directory Domain Services (AD DS)
- Microsoft DNS
- PowerShell
- Group Policy Management
- Windows Networking

---

## 🏗️ Lab Architecture

```text
+------------------------+
| Windows Server 2019    |
| DC01                   |
| Active Directory       |
| DNS Server             |
+------------+-----------+
             |
             |
+------------v-----------+
| Windows 10 Client      |
| Domain Joined Endpoint |
+------------------------+

Additional Hosts:
- Kali Linux
- Ubuntu Server
