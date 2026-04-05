# Module 4: Ethernet Switching

## Overview
This module introduces Ethernet as the foundational technology for wired networks, operating at the Physical and Data Link layers of the OSI model. It explains how Ethernet standards define data transmission, how MAC addressing works, and how switches use these concepts to efficiently forward data within a network.

---

## Section 4.0: Introduction to Ethernet

### Description
This section introduces Ethernet as the core technology behind wired networking and explains its role in defining how data is formatted and transmitted.

### Key Concepts
- Ethernet fundamentals
- OSI Layer 1 and Layer 2
- Data formatting and transmission

### Technical Insight
Ethernet operates across both the Physical and Data Link layers, meaning it not only defines how signals are transmitted but also how data is structured into frames. Understanding Ethernet is essential for evaluating and upgrading network infrastructure, especially in environments requiring reliable communication for services like VoIP and e-commerce.

### What I Learned
Ethernet is the backbone of wired networks, and understanding its operation is essential for building and managing modern network systems.

---

## Section 4.1: Ethernet Standards and Communication

### Description
This section explains the development of Ethernet as a standard, how it evolved over time, and how devices communicate using MAC addresses.

### Key Concepts
- IEEE 802.3 standards
- Ethernet evolution (10 Mbps → 100+ Gbps)
- Frame delivery using MAC addresses
- Vendor interoperability

### Technical Insight
Ethernet became the global standard for wired LANs by enabling interoperability between devices from different vendors. Communication relies on MAC addresses, where each frame includes source and destination addresses. Switches forward frames to all devices in a segment, but only the intended recipient processes the frame based on the destination MAC address.

### What I Learned
Standardization is critical in networking. Ethernet ensures compatibility and reliable communication across different devices and systems.

---

## Section 4.2: Ethernet Operation and Frame Structure

### Description
This section covers how Ethernet operates at the Data Link layer, including encapsulation, sublayers, and frame structure.

### Key Concepts
- Ethernet encapsulation
- LLC and MAC sublayers
- Frame structure (Preamble, MAC addresses, Data, FCS)
- CSMA/CD and full-duplex communication

### Technical Insight
The Data Link layer is divided into LLC (software interface) and MAC (hardware-level operations). The MAC sublayer handles framing, addressing, and error detection using FCS. Modern Ethernet networks use switches and full-duplex communication, eliminating collisions and improving efficiency compared to older CSMA/CD-based systems. Frame size limits (64–1518 bytes) ensure proper transmission and error handling.

### What I Learned
Ethernet frames are carefully structured to ensure accurate and efficient data transmission, with modern improvements eliminating many legacy limitations.

---

## Section 4.3: MAC Addressing and Communication Types

### Description
This section explains MAC addressing, its hexadecimal representation, and different communication methods within a network.

### Key Concepts
- 48-bit MAC address (hexadecimal)
- Unicast, Broadcast, Multicast
- ARP and Neighbor Discovery

### Technical Insight
MAC addresses are represented in hexadecimal to simplify long binary values. Unicast communication is one-to-one, broadcast sends data to all devices in a network, and multicast targets specific groups. Protocols like ARP (IPv4) and Neighbor Discovery (IPv6) map IP addresses to MAC addresses, enabling proper frame delivery within a LAN.

### What I Learned
Different communication types serve different purposes, and MAC addressing is essential for delivering data correctly within a local network.

---

## Section 4.4: Switch Operations

### Description
This section explains how switches operate at Layer 2 to forward frames efficiently using MAC address tables.

### Key Concepts
- MAC address table
- Learning and forwarding
- Flooding and filtering
- Default gateway communication

### Technical Insight
Switches learn MAC addresses by examining incoming frames and associating them with specific ports. When forwarding, switches send frames only to the correct port if the destination is known, reducing unnecessary traffic. Unknown, broadcast, and multicast frames are flooded. When communicating with remote networks, frames are sent to the default gateway’s MAC address, allowing routers to handle inter-network communication.

### What I Learned
Switches play a critical role in optimizing network performance by intelligently forwarding traffic and reducing congestion.

---

## Practical Application

- Identified Ethernet frame structure and key fields
- Understood how MAC addresses are used in real network communication
- Observed how switches learn and forward frames
- Related ARP and default gateway concepts to real-world networking scenarios

---

## Reflection

This module provided a comprehensive understanding of how Ethernet operates at the Data Link layer. It connected concepts such as frame structure, MAC addressing, and switch operations, showing how data is efficiently transmitted within a network.

---

## Conclusion

Overall, this module establishes a strong foundation in Ethernet and Layer 2 networking. Understanding how frames are structured, how MAC addresses function, and how switches forward data is essential for network design and troubleshooting. These concepts are critical for progressing in networking and cybersecurity.
