# Module 13: The ARP Process

## Overview
This module explains **IP and MAC addresses**, their roles in network communication, and how they work together to deliver data reliably across local and remote networks.

---

## Section 13.0: Introduction

IP and MAC addresses serve distinct purposes:

- **IP Address:** Logical locator indicating a device’s network position  
- **MAC Address:** Physical identifier unique to the hardware  
- IP addresses can change depending on the network, whereas MAC addresses remain constant  

### What I Learned
IP addresses allow devices to join networks and facilitate routing, while MAC addresses ensure that data reaches the correct physical hardware. Understanding both is essential for accurate network communication.

---

## Section 13.1: MAC and IP

### Addressing Schemes
- **MAC Addresses:** Used for NIC-to-NIC communication on the same local segment  
- **IP Addresses:** Enable end-to-end delivery across multiple networks  

### Communication Process
1. **Local Communication:** Destination MAC = target device’s MAC  
2. **Remote Communication:** Source host sends frame to the **default gateway’s MAC** to exit the network  
3. **Routing:** Routers de-encapsulate the IP packet, determine the path, and re-encapsulate with new Layer 2 MAC addresses for each hop  

### Address Resolution
- **ARP (IPv4):** Maps IP addresses to MAC addresses within a LAN  
- **ICMPv6 Neighbor Discovery (IPv6):** Performs a similar role for IPv6 networks  

### What I Learned
Understanding how logical and physical addresses interact is crucial for tracing traffic and diagnosing connectivity issues across networks.

---

## Section 13.2: Broadcast Containment

### Ethernet Broadcasts
- Identified by MAC addresses of all Fs in hexadecimal  
- Used when a message must reach all devices in a broadcast domain  
- Switches flood the broadcast to all ports; routers **do not forward broadcasts**, preventing network-wide traffic overload  

### ARP for Local Discovery
- Hosts broadcast ARP requests to find unknown MAC addresses  
- Matching device replies with its MAC, which is then stored in the ARP table  
- Enables efficient future point-to-point communication  

### What I Learned
Routers enforce broadcast containment, preserving network performance. ARP bridges logical IP addresses with physical MAC addresses, ensuring correct delivery of data within a LAN.

---

## Practical Application

- Observed IP and MAC addressing in home and lab networks  
- Used ARP tables to trace local traffic paths  
- Understood router behavior in controlling broadcast domains  

---

## Reflection

IP and MAC addresses work together to enable reliable, scalable communication. Recognizing their roles is essential for network troubleshooting and design.

---

## Conclusion

Module 13 reinforces the importance of IP and MAC addresses in networking. Logical addressing enables routing across networks, while physical addressing ensures data arrives at the correct device, forming the backbone of network communication.
