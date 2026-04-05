# Module 9: Transport Layer

## Overview
This module introduces the Transport Layer (OSI Layer 4), which enables logical communication between applications on different hosts. It bridges the application layer and lower network layers, ensuring data is delivered reliably and efficiently.

---

## Section 9.0: Introduction to the Transport Layer

### Description
The transport layer provides temporary sessions between hosts and ensures proper data delivery. Key protocols are **TCP** (reliable, connection-oriented) and **UDP** (fast, connectionless).

### Key Concepts
- Logical communication between applications  
- Segmentation and reassembly of data  
- Port numbers for service identification  
- Multiplexing for concurrent communications  

### Technical Insight
Applications rely on the transport layer to abstract network complexity. Choosing TCP or UDP depends on whether reliability or speed is more important.

### What I Learned
Understanding transport protocols is critical for designing, troubleshooting, and optimizing networked applications.

---

## Section 9.1: Transport Layer Responsibilities

### Description
The transport layer manages sessions, data segmentation, addressing, and multiplexing.

### Key Concepts
1. **Segmentation** – Divides data into manageable blocks  
2. **Headers** – Contain sequence numbers, ports, and other control information  
3. **Port Numbers** – Identify destination services (e.g., 80 for HTTP)  
4. **Multiplexing** – Supports multiple conversations over a single network link  

### Practical Insight
Transport layer ensures applications can communicate simultaneously without interfering with each other.

---

## Section 9.2: Transmission Control Protocol (TCP)

### Description
TCP provides reliable, connection-oriented communication. It guarantees data delivery, order, and integrity.

### Key Concepts
- Connection establishment via **three-way handshake** (SYN → SYN-ACK → ACK)  
- Session termination via **four-step handshake** (FIN/ACK exchange)  
- Flow control using **window size** and **Maximum Segment Size (MSS)**  
- Congestion avoidance by monitoring acknowledgments  

### TCP Header
- Adds 20 bytes of overhead per segment  
- Includes sequence numbers, acknowledgment numbers, control flags (SYN, ACK, FIN, RST, PSH, URG)  

### Applications Using TCP
- Web browsers, email, database applications  
- Scenarios where data integrity is critical  

### What I Learned
TCP manages reliability automatically, allowing applications to focus on functionality without worrying about data loss or ordering.

---

## Section 9.3: User Datagram Protocol (UDP)

### Description
UDP is a lightweight, connectionless protocol ideal for time-sensitive applications.

### Key Concepts
- Stateless, no session establishment  
- Minimal header (8 bytes)  
- Best-effort delivery without acknowledgments or flow control  

### Applications Using UDP
- Real-time multimedia (VoIP, live streaming)  
- Simple request-response protocols (DNS, DHCP)  
- Applications managing their own reliability (SNMP, TFTP)  

### What I Learned
UDP prioritizes speed over reliability, making it suitable for applications where occasional data loss is acceptable.

---

## Section 9.4: Port Numbers and Sockets

### Description
Port numbers enable multiple concurrent connections between hosts.

### Key Concepts
- **Socket** = IP address + port number  
- **Socket Pair** uniquely identifies a communication between two hosts  
- Both TCP and UDP use dynamic source ports and well-known destination ports  

### Practical Insight
Understanding sockets and ports is essential for managing multiple simultaneous network sessions.

---

## Section 9.5: TCP Session Management

### Description
TCP establishes and terminates reliable connections between hosts.

### Key Concepts
- **Three-way handshake** for session setup  
- **Four-step handshake** for session termination  
- Wireshark captures show **Initial Sequence Numbers (ISN)** for security and tracking  

### What I Learned
TCP ensures reliable, orderly communication, handling retransmissions, acknowledgments, and session control automatically.

---

## Section 9.6: TCP Reliability and Flow Control

### Description
TCP guarantees delivery, ordering, and flow regulation of data streams.

### Key Concepts
- Sequence numbers and acknowledgments manage ordering and reliability  
- Selective Acknowledgment (SACK) reduces unnecessary retransmissions  
- Window size and MSS optimize flow control  
- Congestion avoidance prevents network overload  

### Practical Insight
TCP’s mechanisms allow networks to recover gracefully from data loss and congestion without application-level intervention.

---

## Section 9.7: UDP Characteristics

### Description
UDP provides minimal overhead and high-speed communication without reliability guarantees.

### Key Concepts
- No session establishment or flow control  
- Out-of-order datagrams are delivered as received  
- Server processes use destination ports; clients select dynamic source ports  

### What I Learned
UDP is optimal for applications that prioritize speed and can handle some data loss, with reliability handled by the application itself if needed.

---

## Reflection
TCP and UDP illustrate the trade-off between reliability and performance. Understanding their differences and use cases is essential for network design, application deployment, and troubleshooting.

---

## Conclusion
Mastering transport layer protocols ensures applications communicate efficiently and reliably. TCP is suitable for critical, ordered data transfer, while UDP supports fast, low-overhead communication for time-sensitive applications.
