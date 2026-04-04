# Module 14: Routing Between Networks
# Lab Module 14: Networking Basics

## Overview
This module focuses on improving network efficiency through routing and building a functional Local Area Network (LAN). The labs demonstrate how network segmentation reduces unnecessary traffic and how to design, configure, and verify a small office network.

Through hands-on activities, this module highlights the importance of subnetting, routing, and proper network setup in real-world environments.

---

## Technologies Used
- Cisco Packet Tracer
- Routing & Subnetting
- DHCP (Dynamic Host Configuration Protocol)
- Command Line Tools (ping, ipconfig, tracert)
- Ethernet Networking

---

## Objectives
- Analyze traffic flow in both unrouted and routed networks
- Understand the benefits of subnetting and routing
- Build and configure a small office LAN
- Assign IP addresses dynamically and statically
- Verify network connectivity and troubleshoot issues

---

## Lab 1: Observe Traffic Flow in a Routed Network

### Description
This lab demonstrates how network performance improves when a large LAN is divided into multiple subnetworks. It compares traffic flow in an unrouted network versus a routed network using simulation mode.

---

### Tools & Technologies
- Cisco Packet Tracer
- Simulation Mode
- Command Prompt (ping, arp)

---

### Key Tasks Performed

#### Unrouted Network Analysis
- Cleared ARP cache on host devices
- Initiated ping between hosts in the same network
- Observed ARP broadcast traffic across all devices
- Identified broadcast MAC address (FFFF.FFFF.FFFF)
- Analyzed impact of ARP broadcasts on network performance

#### Network Reconfiguration
- Modified physical connections to connect switches directly to router
- Assigned separate IPv4 networks to departments:
  - Finance: 192.168.2.0/24
  - Sales: 192.168.3.0/24
- Renewed IP addresses using DHCP

#### Routed Network Analysis
- Repeated ping tests between hosts
- Observed ARP broadcasts limited to specific subnet
- Analyzed improved traffic efficiency

---

### Technical Insight
- ARP broadcasts are sent to all devices within the same subnet
- Large single networks increase unnecessary broadcast traffic
- Subnetting divides networks into smaller, manageable segments
- Routers limit broadcast domains, improving performance
- Routing enables communication between different subnetworks

---

### Results / Findings
- Unrouted network generated excessive broadcast traffic
- Routed network reduced unnecessary traffic significantly
- ARP requests were limited to relevant subnet only
- Network efficiency improved with segmentation

---

### Skills Demonstrated
- Network traffic analysis
- Understanding broadcast domains
- Subnetting and routing concepts
- Packet-level observation using simulation

---

## Lab 2: Create a LAN

### Description
This lab involves building a small office LAN by connecting devices, configuring IP addressing, and verifying connectivity. It simulates setting up a new branch office network.

---

### Tools & Technologies
- Cisco Packet Tracer
- Command Prompt (ipconfig, tracert)
- DHCP and Static IP Configuration
- Ethernet Cabling

---

### Key Tasks Performed

#### Network Setup
- Powered on all devices
- Connected router, switch, PCs, and printer using Ethernet cables
- Verified physical connectivity through link lights

#### IP Address Configuration
- Configured Admin and Manager PCs to obtain IP addresses via DHCP
- Assigned static IP address to printer (192.168.1.100)
- Verified consistent subnet mask and default gateway

#### Connectivity Testing
- Used ping to verify communication between PCs and printer
- Tested internet access using web browser
- Identified DNS-related issues when accessing via URL

#### Network Diagnostics
- Used `ipconfig` and `ipconfig /all` to view configuration details
- Used `tracert` to trace route to external server
- Identified routers along the path

---

### Technical Insight
- DHCP simplifies IP address management for end devices
- Static IP addresses are important for devices like printers
- DNS is required to resolve domain names into IP addresses
- tracert helps identify routing paths and intermediate devices
- Proper physical and logical configuration ensures network functionality

---

### Results / Findings
- Successfully built and configured a functional LAN
- All devices communicated within the network
- Internet connectivity was verified using IP address
- DNS issues identified when URL resolution failed
- Network diagnostics tools provided detailed configuration insights

---

### Skills Demonstrated
- LAN setup and configuration
- DHCP and static IP management
- Network troubleshooting
- Use of networking diagnostic tools
- Understanding of DNS and routing behavior

---

## Key Skills Gained
- Network segmentation and routing
- LAN design and implementation
- IP addressing and DHCP configuration
- Network troubleshooting techniques
- Use of command-line networking tools

---

## Reflection
This module helped me understand the importance of network design in improving performance and efficiency. By comparing unrouted and routed networks, I learned how subnetting reduces unnecessary traffic and optimizes communication.

Building a LAN from scratch also gave me practical experience in connecting devices, configuring IP addressing, and verifying connectivity. I also gained insight into common issues such as DNS misconfiguration and how to troubleshoot them.

---

## Conclusion
In conclusion, this module provided both theoretical and practical knowledge of network design and implementation. I successfully analyzed traffic flow, implemented routing, and built a functional LAN.

These skills are essential for real-world networking environments, particularly in designing scalable and efficient networks for organizations.
