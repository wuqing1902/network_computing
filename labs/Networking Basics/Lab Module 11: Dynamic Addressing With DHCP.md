# Lab Module 11: Dynamic Addressing With DHCP

## Overview
This module focuses on configuring Dynamic Host Configuration Protocol (DHCP) on a wireless router to automatically assign IP addresses to connected devices. The lab demonstrates how network administrators can customize IP addressing schemes and ensure proper communication between devices in a local network.

Through hands-on configuration, this activity highlights the importance of DHCP in simplifying network management and maintaining organized IP address allocation.

---

## Technologies Used
- Cisco Packet Tracer
- Wireless Router (GUI Configuration)
- DHCP (Dynamic Host Configuration Protocol)
- Command Line Interface (ipconfig, ping)
- Ethernet Networking

---

## Objectives
- Connect multiple PCs to a wireless router
- Configure DHCP settings on a router
- Modify the IP address range for clients
- Enable clients to obtain IP addresses automatically
- Verify connectivity between network devices

---

## Lab 1: Configure DHCP on a Wireless Router

### Description
This lab involves setting up a small network with three PCs connected to a wireless router. The router is configured to assign IP addresses dynamically using DHCP, and the default network settings are modified to a custom IP range.

---

### Tools & Technologies
- Cisco Packet Tracer
- Wireless Router GUI
- Command Prompt (ipconfig, ping)

---

### Key Tasks Performed

#### Network Setup
- Added three PCs to the network topology
- Connected each PC to the wireless router using Ethernet cables
- Ensured all devices were physically connected and active

#### DHCP Observation
- Configured PC0 to obtain IP address via DHCP
- Identified default gateway address (192.168.0.1)
- Accessed router GUI through web browser
- Reviewed default DHCP settings and IP address range

#### Router IP Configuration
- Changed router IP address from 192.168.0.1 to 192.168.5.1
- Renewed IP configuration on PC to match new network
- Re-accessed router GUI using updated IP address

#### DHCP Range Configuration
- Modified DHCP starting address to 192.168.5.126
- Set maximum number of users to 75
- Renewed IP configuration to apply new settings
- Verified updated IP assignment using `ipconfig`

#### Client Configuration
- Enabled DHCP on PC1 and PC2
- Verified both devices received valid IP addresses within new range

#### Connectivity Testing
- Used `ping` to test connectivity to router and other PCs
- Confirmed successful communication between all devices

---

### Technical Insight
- DHCP automates IP address assignment, reducing manual configuration errors
- Changing the router IP requires clients to renew their IP configuration
- DHCP address pools must match the router’s network range
- Tools like `ipconfig` and `ping` are essential for verifying network configuration and connectivity
- Proper IP planning ensures efficient network management and scalability

---

### Results / Findings
- Successfully configured DHCP with a custom IP address range
- All PCs obtained valid IP addresses automatically
- Devices were able to communicate with each other and the router
- Network configuration changes were correctly applied and verified

---

### Skills Demonstrated
- DHCP configuration and management
- Router GUI configuration
- IP address planning and allocation
- Network troubleshooting using command-line tools
- Understanding of local network communication

---

## Key Skills Gained
- DHCP setup and customization
- IP addressing and subnet configuration
- Router management
- Network connectivity testing
- Troubleshooting network issues

---

## Reflection
This lab enhanced my understanding of how DHCP simplifies network configuration by automatically assigning IP addresses to devices. I learned how to modify the router’s IP address and adjust the DHCP range to suit network requirements.

The process of renewing IP configurations and verifying connectivity helped reinforce my understanding of how devices adapt to network changes. Additionally, using command-line tools like `ipconfig` and `ping` strengthened my troubleshooting skills.

---

## Conclusion
In conclusion, this module provided practical experience in configuring DHCP services within a network. I successfully set up a customized IP addressing scheme and ensured all devices could communicate effectively.

This lab strengthened my foundational networking skills, particularly in DHCP configuration, router management, and network troubleshooting, which are essential for real-world networking environments.
