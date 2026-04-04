# Lab Module 13: The ARP Process

## Overview
This module focuses on understanding how data is transmitted across networks by examining both MAC (Layer 2) and IP (Layer 3) addressing. Using Packet Tracer simulation mode, the lab analyzes how Protocol Data Units (PDUs) travel between devices in both local and remote network communications.

The activity highlights how MAC and IP addresses behave differently depending on whether communication occurs within the same network or across different networks via a router.

---

## Technologies Used
- Cisco Packet Tracer
- Simulation Mode (PDU Analysis)
- Command Line Interface (ping)
- Ethernet & Wireless Networking
- IP Addressing & MAC Addressing

---

## Objectives
- Analyze PDU flow in local and remote network communication
- Identify MAC and IP address behavior during transmission
- Understand differences between Layer 2 and Layer 3 addressing
- Observe how routers handle packet forwarding
- Examine packet details using simulation tools

---

## Lab 1: Identify MAC and IP Addresses

### Description
This lab investigates how MAC and IP addresses are used during communication within a local network and across remote networks. By capturing and analyzing PDUs in simulation mode, the lab demonstrates how addressing changes at different stages of packet transmission.

---

### Tools & Technologies
- Cisco Packet Tracer
- Simulation Mode
- Command Prompt (ping)

---

### Key Tasks Performed

#### Local Network Communication
- Initiated ping from 172.16.31.3 to 172.16.31.2
- Captured PDUs using Simulation Mode
- Recorded source and destination MAC and IP addresses
- Observed packet flow across switch and destination host
- Analyzed echo-reply behavior where addresses are reversed

#### Remote Network Communication
- Initiated ping from 172.16.31.3 to 10.10.10.2
- Identified router as the default gateway
- Captured PDUs across multiple devices (switches, router, access point)
- Recorded addressing changes at each step of transmission
- Observed router modifying MAC addresses while forwarding packets

#### Packet Analysis
- Examined inbound and outbound PDU details
- Compared Layer 2 (MAC) and Layer 3 (IP) addressing
- Identified where MAC addresses change during routing
- Observed that IP addresses remain consistent end-to-end

---

### Technical Insight
- MAC addresses operate at Layer 2 and are used for local network communication
- IP addresses operate at Layer 3 and remain consistent from source to destination
- In local communication, devices communicate directly without a gateway
- In remote communication, packets are sent to the router (default gateway)
- Routers modify MAC addresses at each hop but do not change IP addresses
- Access points convert wired frames into wireless frames (802.11) without altering addressing
- Packet direction reversal occurs during echo-reply (ping response)

---

### Results / Findings
- Local communication does not require a default gateway
- Remote communication requires routing through a gateway device
- MAC addresses change at each network segment, especially at the router
- IP addresses remain unchanged throughout transmission
- Successful communication verified between devices across networks

---

### Skills Demonstrated
- Packet-level analysis using simulation tools
- Understanding of MAC vs IP addressing
- Network troubleshooting and observation
- Interpretation of OSI Layer behavior
- Analysis of routing and packet forwarding

---

## Key Skills Gained
- Deep understanding of Layer 2 and Layer 3 communication
- Packet flow analysis across networks
- Router behavior and gateway functionality
- Network simulation and troubleshooting
- Addressing concepts in real-world networking

---

## Reflection
This lab significantly improved my understanding of how data is transmitted across networks at different OSI layers. By observing PDUs in simulation mode, I was able to clearly see how MAC and IP addresses function differently.

One key takeaway is that MAC addresses change as packets move across network devices, especially routers, while IP addresses remain constant throughout the communication. This helped me better understand how routing works in real-world networks.

Additionally, analyzing both local and remote communication scenarios reinforced the importance of default gateways and how routers enable communication between different networks.

---

## Conclusion
In conclusion, this module provided valuable insights into how network communication operates at both Layer 2 and Layer 3. I successfully analyzed packet flow, identified addressing behavior, and understood the role of routers in forwarding traffic.

This lab strengthened my foundational networking knowledge and provided practical experience in packet analysis, which is essential for network administration and cybersecurity roles.
