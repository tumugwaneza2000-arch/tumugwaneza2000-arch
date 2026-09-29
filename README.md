<h1>Hi, I'm Marie! Junior IT Infrastructure & Cybersecurity<h1>

<h2>Professional Summary</h2>

Detail-oriented AAS Cybersecurity Graduate with deep foundational knowledge in operating systems, network configuration, and enterprise user management. Proven ability to build virtualized testing environments, manage Active Directory domains, and troubleshoot hardware/software configurations. Eager to bring strong technical problem-solving capabilities and client-focused support to an entry-level IT Service Desk team.

<h3>Education & Core Training</h3>

• Associate of Applied Science (AAS) in Cybersecurity | Graduation Year: 2025
• Core Technical Coursework: Introduction to Networking, Linux Administration, Windows Server Configuration, Enterprise Technical Support.

<h4>Technical Skill Inventory</h4>

• Operating Systems: Windows 10/11, Windows Server 2022, Linux (Ubuntu)
• Enterprise Management: Active Directory, User Account Provisioning, Group Policy Objects (GPOs)
• Networking Basics: DHCP, DNS, IP Addressing (IPv4), Subnetting, Basic Router Configuration
• Core Tools & Tasks: VirtualBox/VMware, Remote Desktop Protocol (RDP), Ticket System Workflows, Hardware Troubleshooting

<h5>Hands-on Technical Projects</h5>

Project 1: Enterprise Sandbox — Windows Server & Active Directory Deployment

• Tools Used: Oracle VirtualBox, Windows Server 2022 ISO, Windows 10/11 Enterprise ISO
• Project Documentation: Link to GitHub / Notion Write-up
1. Scenario & Goal
To gain practical, enterprise-grade system administration experience, I built a private sandbox environment simulating a basic corporate network. The goal was to deploy a centralized Windows Domain Controller, configure network infrastructure protocols (DHCP/DNS), and practice managing organizational endpoints.
2. Environment Architecture
• Virtualization Host: Configured Oracle VirtualBox on a local machine.
• Domain Controller (DC): Deployed a virtual machine running Windows Server 2022, promoted it to a Domain Controller, and established a private local domain (internal.local).
• Workstation Endpoint: Deployed a separate virtual machine running Windows 10 to serve as the corporate client computer.
• Internal Network: Configured a isolated virtual switch to keep all testing traffic local and prevent conflicts with my home internet.
3. Step-by-Step Implementation
• IP Addressing & DNS: Assigned a static IPv4 address to the Domain Controller and configured it as the primary DNS server for the network.
• Active Directory Setup: Installed the Active Directory Domain Services (AD DS) role. Created an organizational unit (OU) structure dividing users by department (e.g., HR, IT, Finance).
• Automation Practice: Wrote a short PowerShell script to automatically generate 20 dummy user accounts with unique passwords and forced login requirements.
• Client Domain Join: Configured the network settings on the Windows 10 workstation to point to the server's DNS, then successfully joined the workstation to the internal.local domain.
4. Results & Key Takeaways
• Gained practical experience handling User Account Management tasks like resetting passwords, unlocking accounts, and editing group memberships.
• Understood how DHCP leases and DNS resolution work together to keep client machines connected to company servers.


Project 2: Technical Skills Validation — TryHackMe Pre-Security & Networking Fundamentals
• Platform Used: TryHackMe Learning Management System
• Path Completed: Pre-Security / Introduction to Cyber Security
• Verification: Link to TryHackMe Profile/Badges
1. Scenario & Goal
To bridge the gap between classroom theory and practical execution, I utilized the interactive labs on TryHackMe to study network architecture, data transmission, and system vulnerabilities. This project documents my structured self-education pathway.
2. Core Competencies Learned & Tested
• Network Topology & Traffic: Completed modules on how the internet works, breaking down the OSI Model, data packets, and protocols like HTTP, FTP, and SSH.
• System Logging & OS Utility: Utilized browser-based Linux environments to practice advanced file searching, system metric verification, and review authentication log files (/var/log/auth.log).
• Network Troubleshooting Utilities: Mastered fundamental diagnostic commands—such as using ping to test availability, traceroute to map packet routing hops, and nslookup to troubleshoot broken DNS configurations.
3. Key Takeaways
• Developed the hands-on diagnostic vocabulary required to effectively communicate network bugs and operating system issues in a ticket escalation framework.
• Demonstrated a committed habit of self-directed technical learning, staying current with core infrastructure concepts.
