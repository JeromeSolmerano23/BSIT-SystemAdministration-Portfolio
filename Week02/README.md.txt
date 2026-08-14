# Enterprise Infrastructure Plan for ABC Startup Solutions

---

## PART 1: Company Profile
- **Company Name:** ABC Startup Solutions
- **Nature of Business:** Software Development
- **Vision:** To provide innovative and reliable software solutions for modern businesses.
- **Mission:** To design scalable, high-performance, and secure applications.
- **Office Location:** Unit 402, Tech Tower, Makati City, Philippines (Fictional)

### Employee Distribution
| Department | Number of Employees |
| :--- | :--- |
| IT Department | 5 |
| HR Department | 4 |
| Finance Department | 5 |
| Sales Department | 6 |
| **Total** | **20** |

---

## PART 2: Enterprise Hardware Inventory
| Asset ID | Hardware | Quantity | Department | Purpose |
| :--- | :--- | :--- | :--- | :--- |
| HW-DESK-01 | High-Performance Desktop PCs | 5 | IT | Software development and heavy workloads |
| HW-LAP-01 | Business Laptops | 15 | HR, Finance, Sales | Portable daily office workstations |
| HW-SRV-01 | Enterprise Rack Server | 1 | IT | On-premise application hosting and active directory |
| HW-RTR-01 | Enterprise Router | 1 | IT / Network | Main routing and gateway |
| HW-SWT-01 | 24-Port Managed Switch | 2 | IT / Network | Network connectivity for devices and local connectivity |
| HW-AP-01 | Wireless Access Point | 2 | Office Wide | Wi-Fi connectivity for mobile/laptop devices |
| HW-PRN-01 | Network Multifunction Printer | 2 | Shared / Office | Shared printing, scanning, and copying |
| HW-UPS-01 | Smart UPS (1500VA) | 3 | Server Room / IT | Power backup for critical infrastructure |
| HW-NAS-01 | NAS Storage (4-Bay) | 1 | IT | Centralized file storage and local network backup |
| HW-EXT-01 | External Backup Hard Drives | 2 | IT | Offline external data backup |
| HW-MON-01 | Dual 27-inch Monitors | 10 | IT | Extended desktop display setup for development |

---

## PART 3: Enterprise Software Inventory
| Software | Version | License | Purpose |
| :--- | :--- | :--- | :--- |
| Windows 11 Pro | Latest 22H2/23H2 | Commercial/OEM | Operating System for end-user workstations |
| Ubuntu Server | 22.04 LTS | Open Source / Free | Operating System for local server hosting |
| Microsoft 365 / Office | Enterprise E3 | Paid Subscription | Productivity suite (Docs, Spreadsheets, Email) |[cite: 1]
| Visual Studio Code | Latest | Open Source / Free | Code editor for developers |[cite: 1]
| Git | Latest | Open Source / Free | Local Version Control System |[cite: 1]
| GitHub Desktop | Latest | Free | GUI client for GitHub repository management |[cite: 1]
| Oracle VirtualBox | Latest | Open Source / Free | Virtualization environment for testing/lab |[cite: 1]
| Google Chrome | Latest | Enterprise Free | Primary Web Browser |[cite: 1]
| Microsoft Defender | Integrated | Included in OS | Endpoint security and real-time protection |[cite: 1]
| AnyDesk | Latest | Commercial License | Remote technical support and troubleshooting |[cite: 1]
| 7-Zip | Latest | Open Source / Free | File archiving and compression utility |[cite: 1]

---

## PART 4: Enterprise Network Inventory[cite: 1]
| Equipment | Specification/Model | Quantity | Purpose |[cite: 1]
| :--- | :--- | :--- | :--- |[cite: 1]
| ISP Modem | Enterprise Fiber Modem | 1 | Converts ISP fiber signal to Ethernet |[cite: 1]
| Router | Enterprise Router (e.g., Cisco/MikroTik) | 1 | Handles internal and external routing |[cite: 1]
| Hardware Firewall | Next-Gen Firewall (e.g., FortiGate) | 1 | Network perimeter defense and traffic filtering |[cite: 1]
| Network Switch | 24-Port Gigabit Managed Switch | 2 | Distributes wired connections to departments |[cite: 1]
| Access Point | Dual-Band Wi-Fi 6 Access Point | 2 | Enterprise wireless network coverage |[cite: 1]
| Patch Panel | 24-Port Cat6 Patch Panel | 2 | Centralized cable organization in rack |[cite: 1]
| Cables | Cat6 Ethernet Cables (100m roll) | 3 Box | Structured network cabling |[cite: 1]
| RJ45 Connectors | Cat6 RJ45 Connectors | 100 pcs | Terminating network cabling |[cite: 1]

---

## PART 5: Network Diagram Description[cite: 1]
*(I-insert ang na-export na image ng iyong diagram gamit ang syntax sa ibaba matapos gumawa sa Draw.io)*[cite: 1]

![Network Topology](diagrams/network-diagram.png)[cite: 1]

---

## PART 6: System Administration Roles[cite: 1]

### 1. Helpdesk Technician[cite: 1]
- **Responsibilities:** Provide tier-1 IT support, troubleshoot user software/hardware problems, manage helpdesk tickets[cite: 1].
- **Skills:** Basic troubleshooting, OS navigation, customer service, hardware maintenance[cite: 1].
- **Common Tools:** Ticketing systems (Jira/Freshdesk), Remote Desktop (AnyDesk/TeamViewer)[cite: 1].
- **Certifications:** CompTIA A+, Microsoft Certified: Modern Desktop Administrator Associate[cite: 1].

### 2. Network Administrator[cite: 1]
- **Responsibilities:** Configure, maintain, and monitor network equipment like routers, switches, and firewalls[cite: 1].
- **Skills:** Subnetting, VLAN configuration, routing protocols, firewall management[cite: 1].
- **Common Tools:** Wireshark, Cisco Packet Tracer, PuTTY, SolarWinds[cite: 1].
- **Certifications:** Cisco CCNA, CompTIA Network+[cite: 1].

### 3. Linux System Administrator[cite: 1]
- **Responsibilities:** Manage and maintain Linux-based servers, perform system updates, configure services, ensure uptime[cite: 1].
- **Skills:** Command-line operations (Bash), shell scripting, user management, server hardening[cite: 1].
- **Common Tools:** SSH, Systemd, Ansible, Docker, Vim/Nano[cite: 1].
- **Certifications:** Red Hat Certified System Administrator (RHCSA), CompTIA Linux+[cite: 1].

### 4. Cloud Administrator[cite: 1]
- **Responsibilities:** Provision and manage cloud resources (Compute, Storage, Networking), monitor usage and security[cite: 1].
- **Skills:** Infrastructure as Code (Terraform), Cloud security, IAM, VPC setup[cite: 1].
- **Common Tools:** AWS Management Console, Azure Portal, Terraform, AWS CLI[cite: 1].
- **Certifications:** AWS Certified Solutions Architect / SysOps Administrator, Microsoft Certified: Azure Administrator[cite: 1].

### How Roles Collaborate[cite: 1]
These four roles work seamlessly together within an IT department to maintain business continuity[cite: 1]. The **Helpdesk Technician** serves as the first point of contact for user issues, escalating network or server problems as needed[cite: 1]. The **Network Administrator** ensures secure, stable network connectivity, which allows local systems managed by the **Linux System Administrator** and cloud infrastructure managed by the **Cloud Administrator** to communicate effectively and safely[cite: 1].

---

## PART 7: Infrastructure Recommendations[cite: 1]
- **Internet Provider:** High-speed Fiber Business Plan (Primary) with a secondary backup Fiber connection for redundancy[cite: 1].
- **Server Specifications:** Dual 8-Core Processors, 64GB RAM, 2TB NVMe RAID-1 Storage for optimal system performance[cite: 1].
- **Backup Strategy:** Implement 3-2-1 Rule (3 copies, 2 different media types, 1 offsite/cloud backup)[cite: 1].
- **Security Recommendations:** Enforce Microsoft Defender Endpoint Security, central firewall rules, and regular vulnerability scans[cite: 1].
- **Password Policy:** Require complex passwords (minimum 12 characters, mixing case, numbers, symbols) with forced changes every 90 days and Multi-Factor Authentication (MFA) enabled[cite: 1].
- **Expansion Plan:** Modular network hardware design (extra ports on switches and capacity in patch panels) to easily add future employees[cite: 1].

---

## PART 8: Personal Reflection[cite: 1]
*(Maglagay ng 300-500 words na personal reflection batay sa iyong tunay na karanasan sa paggawa ng project)*[cite: 1]:
- Ano ang natutunan mo sa pagpaplano ng infrastructure?[cite: 1]
- Aling bahagi (Network Diagram, Inventory, Roles, atbp.) ang pinakamahirap?[cite: 1]
- Bakit mahalaga ang planning bago bumili o mag-deploy ng kagamitan?[cite: 1]