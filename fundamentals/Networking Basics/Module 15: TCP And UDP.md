# Module 15: TCP And UDP

## Overview
This module introduces the **Transport Layer** protocols and explains how data is reliably or quickly delivered between applications. It highlights the differences between TCP and UDP, the role of port numbers, and how multiple conversations are tracked on a single device.

---

## Section 15.0: Introduction

Networked applications rely on transport protocols to manage the delivery of data. Real-time applications like video conferencing, streaming audio, and VoIP often use **UDP (User Datagram Protocol)**. UDP is a "best effort" protocol that does not acknowledge received packets, which may lead to minor data loss, such as dropped words in a call. 

Despite this, UDP is preferred for real-time applications because retransmitting lost data would introduce unacceptable delays.

### Key Concepts
- **UDP:** Low-overhead, connectionless protocol for real-time communication  
- **TCP:** Reliable protocol for accurate, ordered delivery  
- **Best-effort delivery:** No guarantee that packets arrive, but minimal delay  

### Technical Insight
UDP is faster than TCP because it does not wait for acknowledgments, making it ideal for streaming or interactive applications where speed is more important than perfect accuracy.

### What I Learned
I learned why different applications choose different transport protocols: UDP prioritizes speed, while TCP prioritizes reliability and accuracy.

---

## Section 15.1: TCP and UDP

The **Transport Layer** primarily relies on **TCP and UDP**:

- **UDP (User Datagram Protocol):**  
  - No sequencing, acknowledgments, or retransmissions  
  - Used for streaming, VoIP, and online gaming  
  - Minimizes delays but may result in lost or out-of-order data  

- **TCP (Transmission Control Protocol):**  
  - Provides reliability using sequence numbers and acknowledgments  
  - Automatically retransmits lost segments  
  - Uses a **window mechanism** to control data flow based on link reliability  
  - Suitable for applications requiring complete accuracy, like web browsing and financial transactions  

### Key Concepts
- **Connection-oriented vs connectionless:** TCP establishes a session; UDP does not  
- **Reliability:** TCP guarantees delivery; UDP does not  
- **Flow control:** TCP adapts sending rate to network conditions  

### Technical Insight
TCP’s mechanisms for reliability (reordering, retransmission, and flow control) add overhead, which is acceptable for critical applications but inefficient for real-time services.

### What I Learned
Understanding TCP and UDP helps me select the right protocol based on application requirements—whether prioritizing **speed** or **accuracy**.

---

## Section 15.2: Port Numbers

**Port numbers** identify and track multiple simultaneous conversations on a single host.  

- **Well-known ports (0–1023):** Standard services like HTTP (80), FTP (21), SMTP (25), DNS (53)  
- **Dynamic/source ports (>1024):** Randomly assigned to client requests for return traffic  
- **Socket:** Combination of IP address + port number  
- **Socket pair:** Source and destination sockets uniquely identify a communication session  

The **netstat** utility can display active connections, including:  
- Protocols in use  
- Local and foreign addresses with ports  
- Connection state  

### Key Concepts
- **Port:** Identifies specific applications on a host  
- **Socket:** Endpoint of a network connection  
- **Socket pair:** Complete identification of both ends of a communication  

### Technical Insight
Port numbers allow a single host to handle multiple services and sessions simultaneously, ensuring that data reaches the correct application.

### What I Learned
I now understand how multiple applications on one device can communicate concurrently without interfering with each other using port numbers and sockets.

---

## Practical Application

- Monitored network connections using **netstat**  
- Observed how TCP ensures reliable delivery for web traffic  
- Saw how UDP supports real-time streaming with minimal delay  
- Identified port numbers associated with active applications  

---

## Reflection

This module helped me distinguish **TCP and UDP** and understand why different applications require different transport protocols. I also learned how **port numbers and sockets** allow multiple simultaneous network communications on a single device.

---

## Conclusion

Module 15 provides a clear understanding of Transport Layer functionality, highlighting how TCP ensures reliable communication while UDP optimizes speed. Port numbers and socket pairs enable multiple applications to coexist on the same device without conflict. This knowledge is essential for designing, monitoring, and troubleshooting modern networked applications.
