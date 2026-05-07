# 💻 Enterprise Help Desk Lab (Active Directory + osTicket)

![Windows Server](https://img.shields.io/badge/Windows_Server-2022-blue)
![Windows 10](https://img.shields.io/badge/Windows_10-Pro-blue)
![Active Directory](https://img.shields.io/badge/Active_Directory-Lab-success)
![osTicket](https://img.shields.io/badge/osTicket-Help_Desk-green)
![VirtualBox](https://img.shields.io/badge/Oracle_VirtualBox-Virtualization-orange)

---

# 🔗 QUICK NAVIGATION (RECRUITER SUMMARY)

## ⚡ Overview
- [Project Overview](#-overview)

## 🧠 Core Competencies
- [Core Skills Demonstrated](#-core-skills-demonstrated)
- [Environment & Architecture](#-environment--lab-architecture)

## 🎫 Help Desk Simulation
- [Ticket Lifecycle Workflow](#-ticket-lifecycle-workflow)
- [Ticket Scenario 1 – Adobe Licensing](#-ticket-scenario-1--adobe-licensing-issue)
- [Ticket Scenario 2 – VPN Issues](#-ticket-scenario-2--vpn-connectivity-issue)
- [Ticket Scenario 3 – Active Directory Lockout](#-ticket-scenario-3--active-directory-account-lockout)
- [Final Resolution Summary](#-final-resolution-summary)

## 🛠 Infrastructure & Deployment
- [osTicket Deployment & Setup](#-osticket-deployment--infrastructure-troubleshooting)
- [Database Configuration](#-core-installation--database-configuration)
- [Permissions & Security](#-permissions--configuration-hardening)
- [Deployment Completion](#-deployment-completion)
- [Error Handling & Troubleshooting](#-critical-troubleshooting--failure-resolution)
- [Final Stable System](#-final-error-resolution--stable-deployment)

## 🧪 Skills Breakdown
- [Active Directory Skills](#active-directory--user-management)
- [Help Desk Operations](#help-desk-operations)
- [Infrastructure Skills](#infrastructure--system-administration)
- [Troubleshooting Skills](#technical-troubleshooting)

## 📘 Reflection
- [What I Learned](#-what-i-learned)
- [Future Improvements](#-future-improvements)
- [Notes](#-notes)

## 🔹 Overview

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

## 🔹 Virtual Lab Infrastructure Setup

This section documents the initial virtual environment preparation and deployment configuration.

| Storage Configuration | Guest Additions & Drivers | Installation Repository |
| :--- | :--- | :--- |
| ![Storage](add-optical-drive.png) | ![Drivers](cddrive-guest-additions.png) | ![Files](my-installation-files.png) |
| *Configuring virtual storage controllers and optical drives within VirtualBox.* | *Installing Guest Additions and compatibility drivers for system stability.* | *Organizing installation packages including MySQL, PHP, IIS components, and osTicket files.* |

---

# 🎫 Help Desk Lifecycle & Ticket Scenarios

This section demonstrates the simulated workflow from ticket creation through troubleshooting, escalation, documentation, and final resolution.

---

## 🔹 Help Desk Backend Configuration

Before handling support tickets, backend infrastructure and business logic were configured to simulate a structured enterprise help desk environment.

### Departments
![Departments](department-list.png)

*Configuring support departments and ticket routing structure.*

### SLA Plans
![SLA](sla-plans.png)

*Creating SLA policies and response priorities for ticket handling.*

### Agent Roles
![Agent Roles](add-agent-role.png)

*Defining permissions and responsibilities for support technicians.*

---

## 🎫 Ticket Scenario 1 – Adobe Licensing Issue

### Scenario
A user reported being unable to access Adobe Creative Cloud applications due to licensing synchronization problems.

### Troubleshooting Process

- Reviewed ticket details and licensing errors within osTicket
- Investigated software licensing configuration
- Simulated reassignment and synchronization of licensing services
- Updated ticket documentation throughout troubleshooting

### Resolution
![Adobe Fix](adobe-ticket.png)

*Full ticket timeline showing troubleshooting workflow, technician communication, and final resolution for Adobe licensing issue.*

---

## 🎫 Ticket Scenario 2 – VPN Connectivity Issue

### Scenario
A remote user reported inability to connect to the corporate VPN gateway.

### Troubleshooting Process

- Reviewed reported VPN gateway and DNS errors
- Investigated network communication and adapter configuration
- Simulated DNS flush and adapter reset procedures
- Documented troubleshooting progress and resolution updates

### Resolution
![VPN Resolved](vpn-ticket-resolved.png)

*Ticket timeline demonstrating troubleshooting and resolution workflow for VPN connectivity issues.*

---

## 🎫 Ticket Scenario 3 – Active Directory Account Lockout

### Scenario
Simulated an Active Directory account lockout after multiple failed login attempts.

### Troubleshooting Process

- Verified account lockout status within Active Directory
- Simulated password reset and account unlock procedures
- Forced password reset through administrative controls
- Documented all actions within ticket workflow

### Resolution
![Account Resolved](ticket-resolved.png)

*Ticket timeline showing Active Directory account recovery and password reset procedures.*

---

## 🔹 Ticket Lifecycle Workflow

The following workflow was used throughout all simulated support scenarios:

1. User submits support request
2. Ticket routed through SLA policy and department assignment
3. Technician reviews issue and begins troubleshooting
4. Troubleshooting actions documented within ticket timeline
5. Escalation procedures simulated when necessary
6. Resolution documented and ticket closed

---

## 🔹 Final Resolution Summary

### Outcome

Successfully completed and documented multiple simulated support tickets involving:

- Active Directory account recovery
- VPN troubleshooting
- Software licensing support
- Ticket escalation workflows
- Resolution documentation
- Help desk lifecycle management

### Closed Ticket Overview
![Closed Tickets](3-closed-tickets.png)

*Overview of completed and resolved ticket scenarios within osTicket.*

---

# 🛠️ osTicket Deployment & Infrastructure Troubleshooting

This section showcases the deployment, configuration, troubleshooting, and stabilization process required to successfully build the environment.

Throughout setup, multiple infrastructure and application-level issues were encountered and resolved involving IIS, PHP, MySQL, permissions, execution limits, and osTicket configuration.

---

## 🔹 Core Installation & Database Configuration

### Database Setup
![Clean Slate](mysql-clean-slate.png)

*Preparing MySQL environment and removing previous configuration conflicts.*

### Database Creation
![Create Database](create-database.png)

*Creating and configuring the osTicket database environment.*

---

## 🔹 Permissions & Configuration Hardening

### File Permissions
![Read Only](read-only.png)

*Adjusting permissions and securing installation files after deployment.*

### Configuration Security
![Config Permissions](ost-config-permissions.png)

*Configuring osTicket settings and securing environment configuration.*

---

## 🔹 Deployment Completion

### Installation Complete
![Congratulations](congratulations.png)

*Successful completion of osTicket installation.*

### System Online
![System Online](osticket.png)

*Fully operational osTicket environment running within the virtual lab.*

---

## 🔹 Critical Troubleshooting & Failure Resolution

This section highlights the troubleshooting methodology used to diagnose and resolve deployment failures.

### Administrative & Database Errors
![Admin Login Error](admin-login-error.png)

*Investigating administrative login and database configuration issues.*

### Performance Tuning
![Execution Time](increase-execution-time.png)

*Adjusting PHP execution limits and configuration settings through php.ini.*

---

## 🔹 Error Identification & Root Cause Analysis

### Multiple Error Investigation
![Many Errors](many-errors.png)

*Reviewing installation and configuration failures during deployment.*

### Detailed Error Analysis
![Detailed Errors](detailed-errors.png)

*Analyzing PHP and system logs to identify failed dependencies and root causes.*

---

## 🔹 Final Error Resolution & Stable Deployment

### HTTP 500 & Application Errors
![Real Error](real-error.png)

*Troubleshooting HTTP 500 and application-level failures.*

### Final Fix Applied
![osTicket Fix](osticket-fix.png)

*Applying configuration fixes and dependency corrections.*

### Stable Deployment Confirmation
![Success](success.png)

*Final successful deployment and stable environment confirmation.*

---

# 🔹 Skills Demonstrated

## Active Directory & User Management

- Password resets and account recovery
- User administration workflows
- Active Directory troubleshooting fundamentals
- Account lockout resolution

## Help Desk Operations

- Ticket lifecycle management
- SLA configuration
- Department routing and escalation structure
- Technical documentation and resolution tracking

## Infrastructure & System Administration

- IIS configuration and troubleshooting
- PHP extension configuration
- MySQL setup and administration
- File permission management
- Windows Server deployment
- Virtualization within Oracle VirtualBox

## Technical Troubleshooting

- Root cause analysis
- Error log investigation
- Service troubleshooting
- Network troubleshooting fundamentals
- System performance tuning

---

# 🧠 What I Learned

- How enterprise help desk environments manage support workflows
- Importance of structured troubleshooting methodology
- Fundamentals of Active Directory administration
- Deployment and maintenance of web-based ticketing systems
- Diagnosing and resolving IIS, PHP, and MySQL configuration issues
- Value of documentation during incident response and resolution
- How backend services interact within enterprise support environments

---

# 🚀 Future Improvements

- Integrate Azure AD for hybrid identity simulations
- Automate account provisioning with PowerShell
- Expand Group Policy troubleshooting scenarios
- Add printer and networking support simulations
- Implement multi-client support environment
- Create PowerShell automation scripts for onboarding tasks

---

# 📌 Notes

All ticket scenarios, troubleshooting activities, infrastructure configurations, and deployments were performed within a controlled virtual lab environment for educational and portfolio purposes to demonstrate hands-on IT support workflows, troubleshooting methodology, and system administration fundamentals.
