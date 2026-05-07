# 💻 Enterprise Help Desk Lab (Active Directory + osTicket)

![Windows Server](https://img.shields.io/badge/Windows_Server-2022-blue)
![Windows 10](https://img.shields.io/badge/Windows_10-Pro-blue)
![Active Directory](https://img.shields.io/badge/Active_Directory-Lab-success)
![osTicket](https://img.shields.io/badge/osTicket-Help_Desk-green)
![VirtualBox](https://img.shields.io/badge/Oracle_VirtualBox-Virtualization-orange)

---

# 🔗 QUICK NAVIGATION

## 📌 Overview
- [Overview](#overview)

## 🧠 Skills & Environment
- [Core Skills](#core-skills-demonstrated)
- [Environment & Architecture](#environment--lab-architecture)
- [Virtual Lab Setup](#virtual-lab-infrastructure-setup)

## 🎫 Help Desk Simulation
- [Ticket Workflow](#ticket-lifecycle-workflow)
- [Adobe Ticket](#ticket-scenario-1--adobe-licensing-issue)
- [VPN Ticket](#ticket-scenario-2--vpn-connectivity-issue)
- [Active Directory Ticket](#ticket-scenario-3--active-directory-account-lockout)
- [Final Summary](#final-resolution-summary)

## 🛠 Infrastructure
- [osTicket Deployment](#osticket-deployment--infrastructure-troubleshooting)
- [Database Setup](#core-installation--database-configuration)
- [Security & Permissions](#permissions--configuration-hardening)
- [Error Handling](#critical-troubleshooting--failure-resolution)
- [Final System State](#final-error-resolution--stable-deployment)

## 📘 Reflection
- [What I Learned](#what-i-learned)
- [Future Improvements](#future-improvements)
- [Notes](#notes)

---

## 📌 Overview

Built a virtual IT Help Desk environment using **Windows Server 2022**, **Windows 10 Pro**, **Active Directory**, and **osTicket** within Oracle VirtualBox.

Simulated real-world IT support operations including:

- User account management and password resets  
- Active Directory administration and account lockout resolution  
- Ticket escalation and SLA-based workflows  
- VPN and network troubleshooting  
- Software licensing support scenarios  
- Infrastructure deployment and system debugging  
- Full ticket documentation and resolution tracking  

This project was built from the ground up while resolving real deployment issues across IIS, PHP, MySQL, and osTicket, simulating enterprise-level IT troubleshooting workflows.

---

# 🧠 CORE SKILLS DEMONSTRATED

- Active Directory Administration (ADUC)
- Help Desk Ticket Lifecycle Management
- Password Reset & Account Recovery
- SLA-Based Ticket Routing & Escalation
- Windows Server Administration
- IIS / PHP / MySQL Deployment & Troubleshooting
- Network & VPN Troubleshooting
- Root Cause Analysis
- Technical Documentation
- Virtualization (Oracle VirtualBox)

---

# 🏗 ENVIRONMENT & LAB ARCHITECTURE

| Component | Technology |
| :--- | :--- |
| Server OS | Windows Server 2022 |
| Client OS | Windows 10 Pro |
| Directory Services | Active Directory Users & Computers |
| Ticketing System | osTicket |
| Web Server | IIS |
| Database | MySQL |
| Backend | PHP |
| Virtualization | Oracle VirtualBox |

---

# 🖥 VIRTUAL LAB SETUP

| Storage Setup | Guest Additions | Installation Files |
| :--- | :--- | :--- |
| ![Storage](add-optical-drive.png) | ![Drivers](cddrive-guest-additions.png) | ![Files](my-installation-files.png) |

Configured full virtual infrastructure including OS installation, drivers, and deployment packages for enterprise simulation.

---

# 🎫 TICKET LIFECYCLE WORKFLOW

1. User submits support request  
2. Ticket assigned via SLA and department routing  
3. Technician begins troubleshooting  
4. Actions documented in real time  
5. Escalation if required  
6. Resolution documented and ticket closed  

---

# 🎫 TICKET SCENARIOS

## Adobe Licensing Issue
User unable to access Adobe Creative Cloud due to licensing sync failure.  
Resolved via simulated license reassignment and service troubleshooting.

## VPN Connectivity Issue
Remote user unable to connect to corporate VPN.  
Resolved through DNS troubleshooting and adapter reset simulation.

## Active Directory Account Lockout
User account locked after multiple failed login attempts.  
Resolved using ADUC password reset and account unlock procedures.

---

# 🏁 FINAL RESOLUTION SUMMARY

Successfully completed multiple enterprise-style support tickets involving:

- Active Directory recovery
- VPN troubleshooting
- Software licensing issues
- Ticket escalation workflows
- Full resolution documentation

---

# 🛠 OSTICKET DEPLOYMENT & TROUBLESHOOTING

Built and stabilized a full osTicket help desk environment involving:

- IIS web server configuration
- PHP and MySQL installation
- Database creation and integration
- Permission and configuration fixes
- HTTP 500 error resolution
- System deployment stabilization

---

# 🔧 TROUBLESHOOTING & ROOT CAUSE ANALYSIS

Resolved multiple infrastructure issues including:

- Web service failures (IIS)
- Database connectivity issues (MySQL)
- PHP configuration errors
- Permission and access issues
- Application deployment failures

---

# 🧠 WHAT I LEARNED

- How enterprise IT help desks structure ticket workflows  
- Active Directory identity and access management fundamentals  
- Real-world server deployment and troubleshooting  
- IIS, PHP, and MySQL integration in enterprise environments  
- Importance of documentation in incident resolution  
- Root cause analysis and systematic troubleshooting  

---

# 🚀 FUTURE IMPROVEMENTS

- Azure Active Directory integration  
- PowerShell automation for user provisioning  
- Group Policy troubleshooting lab expansion  
- Network/printer support simulation  
- Multi-client enterprise environment  
- Onboarding automation scripts  

---

# 📌 NOTES

All configurations, troubleshooting, and ticket scenarios were performed in a controlled virtual lab environment to simulate real-world IT support and system administration workflows for portfolio and hiring demonstration purposes.
