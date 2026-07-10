<p align="center">
  <img src="assets/images/banner.png" alt="TechNova Enterprise Infrastructure Banner">
</p>

<h1 align="center">TechNova Enterprise Infrastructure</h1>

<p align="center">
  <strong>Production-Grade Windows Server 2019 Enterprise Infrastructure</strong><br>
  Built with Active Directory, PowerShell, Ansible, Vagrant, and Infrastructure as Code.
</p>

<p align="center">

![Windows Server](https://img.shields.io/badge/Windows_Server-2019-0078D6?style=for-the-badge&logo=windows)
![PowerShell](https://img.shields.io/badge/PowerShell-Automation-5391FE?style=for-the-badge&logo=powershell)
![Ansible](https://img.shields.io/badge/Ansible-IaC-EE0000?style=for-the-badge&logo=ansible)
![Vagrant](https://img.shields.io/badge/Vagrant-Automation-1868F2?style=for-the-badge&logo=vagrant)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github)

</p>

---

# 📖 Overview

TechNova Enterprise Infrastructure is a **production-style Microsoft Windows Server 2019 infrastructure project** designed to demonstrate enterprise system administration, infrastructure automation, cybersecurity, and Infrastructure as Code (IaC) best practices.

Unlike traditional homelab projects, this repository follows real enterprise design principles with professional documentation, automation, security hardening, validation procedures, and operational guides.

This project is intended to simulate the IT infrastructure of a medium-sized enterprise and showcase skills expected from a:

- Windows Server Administrator
- Microsoft Infrastructure Engineer
- System Administrator
- DevOps Engineer
- Infrastructure Engineer
- Cybersecurity Engineer

---

# 🎯 Project Objectives

- Design a production-style enterprise infrastructure
- Deploy using Infrastructure as Code
- Automate server configuration
- Implement enterprise security best practices
- Document every configuration
- Create reusable PowerShell automation
- Configure Windows using Ansible
- Validate infrastructure health automatically

---

# 🏢 Enterprise Architecture

The environment simulates a company with approximately **250 employees**.

The infrastructure includes:

- Two Active Directory Forests
- Forest Trust Relationship
- Centralized Authentication
- DNS
- DHCP
- Group Policy
- File Services
- IIS
- WSUS
- Windows Deployment Services
- RRAS VPN
- Network Policy Server (RADIUS)
- PowerShell Automation
- Ansible Automation
- Infrastructure as Code

---

# 🖥 Virtual Infrastructure

| Machine | Operating System | Roles |
|----------|------------------|-------|
| DC01 | Windows Server 2019 | Active Directory, DNS, DHCP, WSUS |
| DC02 | Windows Server 2019 | Active Directory, DNS, WDS |
| SRV01 | Windows Server 2019 | File Server, IIS, RRAS VPN, NPS |
| CLIENT01 | Windows 11 | Administration & Testing |

---

# ⚙ Technology Stack

## Microsoft Technologies

- Windows Server 2019
- Windows 11
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- File Services
- NTFS Permissions
- IIS
- WSUS
- Windows Deployment Services
- RRAS VPN
- Network Policy Server (NPS)

## Automation

- PowerShell
- PowerShell DSC
- Ansible
- WinRM
- Vagrant

## DevOps

- Git
- GitHub
- Markdown
- Draw.io

---

# ✨ Features

- Enterprise Active Directory Design
- Multi-Forest Architecture
- Forest Trust Configuration
- Organizational Units
- Security Groups
- User Management
- Password Policies
- Group Policy Management
- DNS Infrastructure
- DHCP Management
- File Server with NTFS Permissions
- IIS Web Server
- Windows Update Services
- Windows Deployment Services
- Secure VPN Access
- RADIUS Authentication
- PowerShell Automation
- Infrastructure Validation
- Health Monitoring
- Security Hardening
- Enterprise Documentation

---

# 📁 Repository Structure

```text
technova-enterprise-infrastructure/

├── assets/
│   └── images/
│
├── docs/
│   ├── architecture/
│   ├── active-directory/
│   ├── dns/
│   ├── dhcp/
│   ├── gpo/
│   ├── file-services/
│   ├── iis/
│   ├── wsus/
│   ├── wds/
│   ├── vpn/
│   ├── nps/
│   ├── security/
│   ├── operations/
│   ├── troubleshooting/
│   └── testing/
│
├── automation/
│   ├── powershell/
│   ├── ansible/
│   └── vagrant/
│
├── diagrams/
│
├── screenshots/
│
├── reports/
│
├── scripts/
│
├── backup/
│
├── testing/
│
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

---

# 🚀 Deployment Workflow

```
Clone Repository
        │
        ▼
Vagrant Provisioning
        │
        ▼
PowerShell Bootstrap
        │
        ▼
Enable WinRM
        │
        ▼
Ansible Configuration
        │
        ▼
PowerShell Automation
        │
        ▼
Validation Scripts
        │
        ▼
Health Reports
```

---

# 📚 Documentation

| Documentation | Status |
|---------------|--------|
| Enterprise Architecture | 🚧 |
| Network Design | 🚧 |
| Active Directory | 🚧 |
| DNS | 🚧 |
| DHCP | 🚧 |
| Group Policy | 🚧 |
| File Services | 🚧 |
| IIS | 🚧 |
| WSUS | 🚧 |
| WDS | 🚧 |
| VPN | 🚧 |
| NPS | 🚧 |
| Security | 🚧 |
| Operations Guide | 🚧 |
| Troubleshooting | 🚧 |
| Testing | 🚧 |

---

# 📊 Infrastructure Statistics

| Item | Value |
|------|------:|
| Virtual Machines | 4 |
| Active Directory Forests | 2 |
| Windows Servers | 3 |
| Windows Clients | 1 |
| Server Roles | 10+ |
| PowerShell Scripts | 40+ *(Planned)* |
| Ansible Roles | 10+ *(Planned)* |
| Enterprise Documents | 20+ *(Planned)* |

---

# 📷 Screenshots

The completed project will include screenshots of:

- Active Directory
- DNS
- DHCP
- Group Policy
- IIS
- File Server
- VPN
- WSUS
- WDS
- PowerShell Automation
- Ansible Deployment
- Infrastructure Validation
- Enterprise Reports

---

# 🛣 Project Roadmap

## Phase 1

- [x] Repository Initialization
- [x] Enterprise Architecture
- [ ] Network Design
- [ ] Active Directory
- [ ] DNS
- [ ] DHCP

## Phase 2

- [ ] Group Policy
- [ ] File Services
- [ ] IIS
- [ ] WSUS
- [ ] WDS

## Phase 3

- [ ] RRAS VPN
- [ ] NPS
- [ ] PowerShell Automation
- [ ] Ansible Automation

## Phase 4

- [ ] Security Hardening
- [ ] Monitoring
- [ ] Validation
- [ ] Backup
- [ ] Disaster Recovery
- [ ] Operations Guide
- [ ] Troubleshooting Guide

---

# 🔒 Security

The project follows Microsoft security best practices including:

- Least Privilege
- Account Lockout Policies
- Password Policies
- Windows Firewall
- Secure RDP
- Audit Policies
- LAPS
- NTFS Permissions
- VPN Security
- Administrative Separation

---

# 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Please read the **CONTRIBUTING.md** file before submitting changes.

---

# 📄 License

This project is licensed under the MIT License.

See the **LICENSE** file for more information.

---

# 👨‍💻 Author

**Wael Balhoudi**

Master's Student — Windows Administration, Linux, Security & Cloud Computing

GitHub: https://github.com/WaelBalhoudi

LinkedIn: https://www.linkedin.com/in/wael-balhoudi-a89045275/

---

<p align="center">

⭐ If you found this project interesting, consider starring the repository.

</p>
