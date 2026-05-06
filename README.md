# 💻 Windows Help Desk Lab (osTicket + Active Directory)

## 🔹 Overview

Built a virtual help desk environment using Windows Server 2022 and a Windows 10 client machine.
Configured Active Directory and implemented an internal ticketing system (osTicket) to simulate real-world IT support scenarios.

This lab demonstrates the ability to troubleshoot and resolve common help desk issues including account lockouts, VPN connectivity problems, and software licensing errors.

---

## 🔹 Environment

* Windows Server 2022 (Domain Controller)
* Windows 10 Client
* VirtualBox / VMware
* Active Directory (ADUC)
* osTicket (internal ticketing system)

---

## 🔹 Skills Demonstrated

* Active Directory user management
* Password resets & account unlocks
* VPN troubleshooting
* Software troubleshooting (licensing issues)
* Ticket documentation and resolution workflow
* Basic networking troubleshooting

---

## 🔹 Lab Architecture

<!-- INSERT ONE IMAGE HERE (your server + client setup if you have it) -->

![Lab Architecture](screenshots/lab-architecture.png)

---

# 🎫 Ticket 1: Adobe License Issue

## Issue

User unable to access Adobe software due to a licensing error.

## Investigation

* Reviewed ticket details in osTicket
* Identified licensing mismatch issue

## Resolution

* Removed and reassigned user license
* Synced changes with system

## Result

User regained access to Adobe software successfully.

## Screenshots

![Ticket Created](screenshots/ticket1-1.png)
*User reports Adobe license issue*

![Investigation](screenshots/ticket1-2.png)
*Reviewing ticket details and identifying problem*

![Fix Applied](screenshots/ticket1-3.png)
*License reassigned and system updated*

![Resolved](screenshots/ticket1-4.png)
*Ticket successfully resolved*

---

# 🎫 Ticket 2: VPN Connection Failure

## Issue

User unable to connect to VPN (Gateway Not Reachable error).

## Investigation

* Reviewed VPN error message
* Checked network configuration

## Resolution

* Reset network adapter
* Flushed DNS cache

## Result

VPN connection restored successfully.

## Screenshots

![Ticket Created](screenshots/ticket2-1.png)
*User reports VPN connection issue*

![Error](screenshots/ticket2-2.png)
*VPN error message displayed*

![Fix Applied](screenshots/ticket2-3.png)
*Network troubleshooting steps performed*

![Resolved](screenshots/ticket2-4.png)
*VPN connection successfully restored*

---

# 🎫 Ticket 3: Account Lockout / Password Reset

## Issue

User unable to log in due to account lockout.

## Investigation

* Verified account status in Active Directory
* Identified lockout due to failed login attempts

## Resolution

* Unlocked account in Active Directory
* Reset user password

## Result

User successfully logged in.

## Screenshots

![Ticket Created](screenshots/ticket3-1.png)
*User reports login issue*

![Active Directory](screenshots/ticket3-2.png)
*Account found locked in ADUC*

![Fix Applied](screenshots/ticket3-3.png)
*Account unlocked and password reset*

![Resolved](screenshots/ticket3-4.png)
*User able to log in successfully*

---

## 🔹 Ticket Dashboard

<!-- OPTIONAL: combine your overview screenshots into one collage -->

![Ticket Dashboard](screenshots/dashboard.png)

---

---

# 🛠️ osTicket Deployment & Troubleshooting

During the setup of the help desk environment, multiple system and configuration issues were encountered and resolved while deploying osTicket and configuring the Windows Server environment.

## Issues Resolved
- IIS configuration problems
- PHP Manager installation issues
- MySQL connection errors
- Missing PHP extensions
- osTicket setup validation failures
- Permission and service configuration issues
- Internal network communication troubleshooting

## Troubleshooting Process
Each issue was researched, tested, and resolved through step-by-step troubleshooting within the virtual lab environment.

## Setup & Troubleshooting Screenshots

![Setup Process](screenshots/setup-1.png)
*Initial Windows Server and IIS configuration*

![PHP Configuration](screenshots/setup-2.png)
*Configuring PHP Manager and required extensions*

![Database Troubleshooting](screenshots/setup-3.png)
*Resolving MySQL connection and configuration issues*

![osTicket Validation](screenshots/setup-4.png)
*Fixing osTicket setup requirements and validation checks*

![Final Deployment](screenshots/setup-5.png)
*Successful osTicket deployment and internal access testing*

---

## 🧠 What I Learned

* How to manage and resolve IT support tickets using a structured workflow
* Troubleshooting authentication and user access issues in Active Directory
* Diagnosing and resolving network connectivity problems
* Communicating technical solutions clearly through ticketing systems

---

## 🚀 Future Improvements

* Add more advanced ticket scenarios (hardware, permissions, group policy)
* Automate common fixes using PowerShell scripts
* Expand lab to include networking simulations

---

## 📌 Notes

All scenarios were created and resolved in a virtual lab environment to simulate real-world help desk responsibilities.
