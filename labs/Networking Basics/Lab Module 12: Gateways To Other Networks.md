# Lab Module 12: Gateways To Other Networks

## Overview
This module focuses on Network Address Translation (NAT) and how it enables communication between private internal networks and external public networks. Through a hands-on Packet Tracer lab, the activity demonstrates how a wireless router translates private IP addresses into a public IP address for internet communication.

The lab highlights the role of NAT in allowing multiple devices within a local network to share a single public IP address while maintaining proper data routing.

---

## Technologies Used
- Cisco Packet Tracer
- Wireless Router (GUI Configuration)
- DHCP (Dynamic Host Configuration Protocol)
- NAT (Network Address Translation)
- Command Line Interface (ipconfig)
- Simulation Mode (Packet Analysis)

---

## Objectives
- Examine NAT configuration on a wireless router
- Configure multiple PCs to obtain IP addresses via DHCP
- Identify differences between public and private IP addresses
- Analyze network traffic and NAT translation
- Observe packet flow using simulation tools

---

## Lab 1: Examine NAT on a Wireless Router

### Description
This lab explores how NAT operates within a wireless router by connecting multiple devices, assigning IP addresses through DHCP, and analyzing how traffic is translated when communicating with external networks.

---

### Tools & Technologies
- Cisco Packet Tracer
- Wireless Router GUI
- Command Prompt (ipconfig)
- Simulation Mode (PDU analysis)

---

### Key Tasks Performed

#### External Network Configuration
- Connected a PC to the wireless router
- Enabled DHCP to obtain IP configuration
- Accessed router GUI via default gateway
- Identified ISP-assigned IP address (209.165.200.227)
- Determined that the ISP address is a public IP

#### Internal Network Configuration
- Examined local network settings on router
- Identified DHCP range (192.168.1.100 – 192.168.1.149)
- Confirmed that internal addresses are private IPs

#### Network Expansion
- Added three additional PCs to the network
- Connected all devices to the router using Ethernet cables
- Configured all PCs to obtain IP addresses via DHCP
- Verified IP configurations using `ipconfig /all`

#### NAT Traffic Simulation
- Switched to Simulation Mode in Packet Tracer
- Created a Complex PDU using HTTP protocol
- Configured periodic traffic between PC and web server
- Observed packet flow across the network

#### Packet Analysis
- Inspected inbound and outbound PDU details
- Compared source and destination IP addresses
- Observed changes in source IP due to NAT translation
- Analyzed how private IPs are translated to public IP

---

### Technical Insight
- NAT allows multiple devices in a private network to share a single public IP address
- Private IP addresses cannot be routed over the internet without translation
- The router replaces the source private IP with its public IP when sending traffic externally
- DHCP dynamically assigns private IP addresses within the local network
- Simulation tools help visualize packet flow and protocol behavior

---

### Results / Findings
- Successfully identified public and private IP address ranges
- All PCs received valid private IP addresses via DHCP
- Observed NAT translating private IP addresses into a public IP
- Verified proper communication between internal devices and external server
- Packet analysis confirmed changes in source IP during transmission

---

### Skills Demonstrated
- Understanding NAT functionality
- Network configuration and setup
- IP address classification (public vs private)
- Packet analysis using simulation tools
- Troubleshooting and verifying network communication

---

## Key Skills Gained
- NAT configuration and analysis
- Network traffic monitoring
- IP addressing concepts
- DHCP-based network setup
- Packet-level troubleshooting

---

## Reflection
This lab helped me understand how NAT enables communication between private networks and the internet. I learned that devices within a local network use private IP addresses, which must be translated into a public IP address for external communication.

By using simulation mode, I was able to visually observe how packets travel across the network and how the router modifies the source IP address during transmission. This provided a clearer understanding of how NAT operates in real-world networking environments.

---

## Conclusion
In conclusion, this module provided valuable insight into how NAT functions within a network. I successfully configured multiple devices, analyzed IP address assignments, and observed NAT translation in action.

This lab strengthened my understanding of how internal networks communicate with external systems, which is a fundamental concept in networking and cybersecurity.
