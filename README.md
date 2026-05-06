# 💻 Windows Help Desk Lab (osTicket + Active Directory)

## 🔹 Overview
Built a virtual IT help desk lab using **Windows Server 2022** and a **Windows 10 client** machine within a virtualized environment. 

Configured **Active Directory** and deployed **osTicket** to simulate a real-world help desk workflow including ticket creation, troubleshooting, escalation, resolution, and documentation. This project demonstrates hands-on understanding of enterprise IT support processes and remote troubleshooting methodology.

---

## 🔹 Environment & Lab Architecture
* **OS:** Windows Server 2022 (Domain Controller), Windows 10 Pro (Client)
* **Directory Services:** Active Directory Users & Computers (ADUC)
* **Ticketing System:** osTicket (LAMP stack on Windows via IIS)
* **Virtualization:** Oracle VirtualBox

### **Lab Infrastructure Setup**
| Storage Configuration | Guest Additions | Installation Repository |
| :--- | :--- | :--- |
| ![Storage](add-optical-drive.png) | ![Drivers](cddrive-guest-additions.png) | ![Files](my-installation-files.png) |
| *Configuring Virtual SATA controllers.* | *Ensuring driver compatibility.* | *Pre-staging MySQL, PHP, and osTicket.* |

---

# 🎫 Help Desk Lifecycle & Ticket Scenarios
This section demonstrates the transition from a user reporting an issue to a technician resolving it.

### **1. Business Logic Configuration**
Before handling tickets, I configured the backend infrastructure to mirror an enterprise environment.
* **Departments:** ![Departments](department-list.png) *(Configuring Support, Maintenance, and Hardware tiers)*
* **SLA Plans:** ![SLA](sla-plans.png) *(Setting response time objectives: SEV-A, SEV-B, SEV-C)*
* **Agent Roles:** ![Agent Roles](add-agent-role.png) *(Defining permissions for Help Desk staff)*

### **2. Ticket Scenario 1 – Adobe Licensing Issue**
* **Issue:** User reported a licensing mismatch preventing access to Creative Cloud.
* **Troubleshooting:** Verified licensing portal synchronization and reassigned seats.
* **Resolution:** ![Adobe Fix](adobe-ticket.png)

### **3. Ticket Scenario 2 – VPN Connectivity Issue**
* **Issue:** Remote user unable to connect to the corporate gateway.
* **Troubleshooting:** Conducted DNS flush and verified gateway IP configuration.
* **Resolution:** ![VPN Resolved](vpn-ticket-resolved.png)

### **4. Ticket Scenario 3 – Account Lockout / Password Reset**
* **Issue:** AD Account lockout after multiple failed login attempts.
* **Troubleshooting:** Reset credentials and forced password change via Admin Panel.
* **Resolution:** ![Account Resolved](ticket-resolved.png)

### **5. Final Resolution Summary**
* **Outcome:** Successfully resolved all pending high-priority tickets within SLA.
* **Evidence:** ![Closed Tickets](3-closed-tickets.png)

---

# 🛠️ osTicket Deployment & Infrastructure Troubleshooting
This section showcases the "Service Desk Engineering" side of the lab. Multiple infrastructure hurdles were cleared to get the environment live.

### **1. Core Installation & Database Engineering**
* **Database Setup:** ![Clean Slate](mysql-clean-slate.png) & ![Create Database](create-database.png)
* **Permissions & Security:** ![Read Only](read-only.png) & ![Config Permissions](ost-config-permissions.png) *(Hardening the system post-installation)*
* **Installation Success:** ![Congratulations](congratulations.png) & ![System Online](osticket.png)

### **2. Critical Troubleshooting: Resolving Configuration Failures**
I documented the transition from system failure to a stable environment.

* **Database Connection & Admin Issues:** ![Admin Login Error](admin-login-error.png) & ![Data Admin Recovery](data-admin-recovery.png)
* **Timeout & Performance Tuning:** ![Execution Time](increase-execution-time.png) *(Modifying `php.ini` to handle script execution limits)*
* **Visualizing the "Break":** ![Many Errors](many-errors.png) & ![Detailed Errors](detailed-errors.png) *(Analyzing raw PHP logs for root cause identification)*

### **3. Documented Errors & Resolutions**
* **HTTP 500 & General Failures:** ![Real Error](real-error.png) & ![Error Again](error-again.png)
* **Specific Resolution:** ![osTicket Fix](osticket-fix.png)
* **Final Deployment Success:** ![Success](success.png)

---

## 🔹 Skills Demonstrated
* **AD Management:** User provisioning and account recovery.
* **Technical Troubleshooting:** IIS Module mapping, PHP extension configuration, and MySQL administration.
* **System Optimization:** Performance tuning via `php.ini` and execution time adjustments.
* **Help Desk Operations:** SLA management, department triaging, and ticket lifecycle documentation.

---

## 🚀 Future Improvements
* Integrate Azure AD for hybrid identity management simulations.
* Automate user onboarding via PowerShell scripts.
* Implement Group Policy Objects (GPO) to manage client machine restrictions.
