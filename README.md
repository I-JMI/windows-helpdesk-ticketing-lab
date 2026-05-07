# 💻 Enterprise Help Desk Lab (Active Directory + osTicket)

![Windows Server](https://img.shields.io/badge/Windows_Server-2022-blue)
![Windows 10](https://img.shields.io/badge/Windows_10-Pro-blue)
![Active Directory](https://img.shields.io/badge/Active_Directory-Lab-success)
![osTicket](https://img.shields.io/badge/osTicket-Help_Desk-green)
![VirtualBox](https://img.shields.io/badge/Oracle_VirtualBox-Virtualization-orange)

---

# 📑 Table of Contents

## 📌 Overview
- [Overview](#overview)

## 🧠 Skills & Setup
- [Core Skills Demonstrated](#core-skills)
- [Environment & Lab Architecture](#environment)
- [Virtual Lab Infrastructure Setup](#lab-setup)

## 🎫 Help Desk Simulation
- [Ticket Lifecycle Workflow](#ticket-workflow)
- [Adobe Licensing Issue](#adobe-ticket)
- [VPN Connectivity Issue](#vpn-ticket)
- [Active Directory Account Lockout](#ad-lockout)
- [Final Resolution Summary](#final-summary)

## 🛠 Infrastructure & Deployment
- [osTicket Deployment & Troubleshooting](#osticket-deployment)
- [Database Setup](#database-setup)
- [Permissions & Security](#permissions)
- [Deployment Completion](#deployment)
- [Error Handling & Root Cause Analysis](#error-handling)
- [Stable System Output](#stable-system)

## 🧪 Skills Breakdown
- [Active Directory User Management](#ad-management)
- [Help Desk Operations](#helpdesk-ops)
- [Infrastructure & System Administration](#infrastructure)
- [Technical Troubleshooting](#troubleshooting)

## 📘 Reflection
- [What I Learned](#what-i-learned)
- [Future Improvements](#future-improvements)
- [Notes](#notes)
---
<a id="overview"></a>
# 🔹 Overview

Built a virtual IT help desk environment using **Windows Server 2022**, **Windows 10 Pro**, **Active Directory**, and **osTicket** within Oracle VirtualBox.

Configured a fully functional help desk workflow to simulate real-world IT support operations including:

- User account management  
- Password resets  
- Ticket escalation  
- SLA handling  
- VPN troubleshooting  
- Software support  
- Active Directory administration  
- Infrastructure troubleshooting  
- Documentation and resolution tracking  

This lab was built from the ground up while diagnosing and resolving multiple deployment, configuration, database, and web service issues throughout the setup process.

The goal of this project was to strengthen hands-on IT support and system administration skills commonly used in entry-level Help Desk, Desktop Support, and IT Support Specialist roles.

---
<a id="core-skills"></a>
# 🔹 Core Skills Demonstrated

- Active Directory Administration  
- Help Desk Ticket Workflow  
- Password Reset & Account Recovery  
- IIS / PHP / MySQL Troubleshooting  
- VPN & Network Troubleshooting  
- Windows Server Administration  
- Virtualization & Lab Deployment  
- Root Cause Analysis  
- Technical Documentation  
- Ticket Lifecycle Management  

---
<a id="environment"></a>
# 🔹 Environment & Lab Architecture

| Component | Technology |
| :--- | :--- |
| Server OS | Windows Server 2022 |
| Client OS | Windows 10 Pro |
| Directory Services | Active Directory Users & Computers (ADUC) |
| Ticketing System | osTicket |
| Web Services | IIS |
| Database | MySQL |
| Scripting / Configuration | PHP |
| Virtualization | Oracle VirtualBox |

---
<a id="lab-setup"></a>
# 🔹 Virtual Lab Infrastructure Setup

| Storage Configuration | Guest Additions & Drivers | Installation Repository |
| :--- | :--- | :--- |
| ![Storage](add-optical-drive.png) | ![Drivers](cddrive-guest-additions.png) | ![Files](my-installation-files.png) |
| Configuring virtual storage controllers and optical drives within VirtualBox. | Installing Guest Additions and compatibility drivers for system stability. | Organizing installation packages including MySQL, PHP, IIS components, and osTicket files. |

---
<a id="ticket-workflow"></a>
# 🎫 Help Desk Lifecycle & Ticket Scenarios

## 🔹 Help Desk Backend Configuration

### Departments
![Departments](department-list.png)

### SLA Plans
![SLA](sla-plans.png)

### Agent Roles
![Agent Roles](add-agent-role.png)

---
<a id="adobe-ticket"></a>
## 🎫 Ticket Scenario 1 – Adobe Licensing Issue

User unable to access Adobe Creative Cloud due to licensing synchronization issue.

### Troubleshooting Process
- Reviewed ticket details in osTicket  
- Investigated licensing configuration  
- Simulated license reassignment  
- Updated ticket documentation  

### Resolution
![Adobe Fix](adobe-ticket.png)

---
<a id="vpn-ticket"></a>
## 🎫 Ticket Scenario 2 – VPN Connectivity Issue

User unable to connect to corporate VPN gateway.

### Troubleshooting Process
- Reviewed VPN error logs  
- Checked network configuration  
- Simulated DNS flush and adapter reset  
- Documented resolution steps  

### Resolution
![VPN Resolved](vpn-ticket-resolved.png)

---
<a id="ad-lockout"></a>
## 🎫 Ticket Scenario 3 – Active Directory Account Lockout

User account locked due to failed login attempts.

### Troubleshooting Process
- Verified account lockout in AD  
- Performed password reset  
- Unlocked account in ADUC  
- Documented resolution  

### Resolution
![Account Resolved](ticket-resolved.png)

---

# 🔹 Ticket Lifecycle Workflow

1. User submits request  
2. Ticket assigned via SLA/department  
3. Technician investigates issue  
4. Troubleshooting documented  
5. Escalation if needed  
6. Ticket resolved and closed  

---
<a id="final-summary"></a>
# 🔹 Final Resolution Summary

Successfully completed multiple enterprise-style support tickets involving:

- Active Directory account recovery  
- VPN troubleshooting  
- Software licensing issues  
- Ticket escalation workflows  
- Full documentation of resolution process  

### Closed Ticket Overview
![Closed Tickets](3-closed-tickets.png)

---
<a id="osticket-deployment"></a>
# 🛠️ osTicket Deployment & Infrastructure Troubleshooting

Built and stabilized a full help desk system involving:

- IIS configuration  
- MySQL database setup  
- PHP backend integration  
- Permission configuration  
- HTTP 500 error resolution  
- System deployment debugging  

---

## 🔹 Core Installation & Database Configuration
<a id="database-setup"></a>
### Database Setup
![Clean Slate](mysql-clean-slate.png)

### Database Creation
![Create Database](create-database.png)

---
<a id="permissions"></a>
## 🔹 Permissions & Configuration Hardening

### File Permissions
![Read Only](read-only.png)

### Configuration Security
![Config Permissions](ost-config-permissions.png)

---
<a id="deployment"></a>
## 🔹 Deployment Completion

### Installation Complete
![Congratulations](congratulations.png)

### System Online
![System Online](osticket.png)

---
<a id="error-handling"></a>
## 🔹 Critical Troubleshooting & Failure Resolution

### Administrative & Database Errors
![Admin Login Error](admin-login-error.png)

### Performance Tuning
![Execution Time](increase-execution-time.png)

---

## 🔹 Error Identification & Root Cause Analysis

### Multiple Errors
![Many Errors](many-errors.png)

### Detailed Errors
![Detailed Errors](detailed-errors.png)

---
<a id="stable-system"></a>
## 🔹 Final Error Resolution & Stable Deployment

### HTTP 500 Error
![Real Error](real-error.png)

### Final Fix Applied
![osTicket Fix](osticket-fix.png)

### Success
![Success](success.png)

---

# 🔹 Skills Demonstrated
<a id="ad-management"></a>
## 🧠 Active Directory – User Management
- User account creation and management  
- Password resets and recovery  
- Account lockout resolution  
- Organizational Unit (OU) structuring  
- Security group assignment  
- Authentication troubleshooting  

---
<a id="helpdesk-ops"></a>
## 🧩 Help Desk Operations
- Ticket lifecycle management  
- SLA-based routing  
- Escalation workflows  
- Documentation of resolutions  

---
<a id="infrastructure"></a>
## 🛠 Infrastructure & System Administration
- Windows Server deployment  
- IIS configuration  
- MySQL + PHP integration  
- VirtualBox environment setup  
- File permission management  

---
<a id="troubleshooting"></a>
## 🔧 Technical Troubleshooting
- Root cause analysis  
- Service failure debugging  
- Log analysis  
- Network troubleshooting  
- Application error resolution  

---
<a id="what-i-learned"></a>
# 🧠 What I Learned

- Enterprise help desk workflows  
- Active Directory administration fundamentals  
- Server deployment and troubleshooting  
- Web service integration (IIS + PHP + MySQL)  
- Importance of structured incident documentation  
- Systematic root cause analysis  

---
<a id="future-improvements"></a>
# 🚀 Future Improvements

- Azure Active Directory integration  
- PowerShell automation for user provisioning  
- Group Policy troubleshooting expansion  
- Printer/network support simulations  
- Multi-client enterprise environment  
- Onboarding automation scripts  

---
<a id="notes"></a>
# 📌 Notes

All configurations, troubleshooting, and ticket scenarios were performed in a controlled virtual lab environment to simulate real-world IT support and system administration workflows for portfolio and hiring demonstration purposes.
