# Module 8: The Internet Protocol

## Overview
This module focuses on understanding how devices communicate with web servers using IP addresses. Through a hands-on Packet Tracer lab, the activity demonstrates how packets are transmitted across a network and how connectivity is verified using basic networking tools.

The lab emphasizes the process of testing connectivity and accessing a web server directly via its IP address, reinforcing foundational concepts of network communication and client-server interaction.

---

## Technologies Used
- Cisco Packet Tracer
- Command Line Interface (ping)
- Web Browser (HTTP client)
- IP Addressing

---

## Objectives
- Understand how packets are sent across networks using IP addresses
- Verify connectivity between a client and a web server
- Use ping to test network reachability
- Access a web server using its IP address
- Understand basic client-server communication

---

## Lab 1: Connect to a Web Server

### Description
This lab demonstrates how a client device connects to a web server using its IP address. It involves verifying connectivity using ping and accessing the server through a web browser to observe how network communication occurs.

---

### Tools & Technologies
- Cisco Packet Tracer
- Command Prompt (ping)
- Web Browser

---

### Key Tasks Performed

#### Network Connectivity Testing
- Accessed Command Prompt on PC0
- Sent ICMP echo requests using `ping 172.33.100.50`
- Observed replies from the destination web server
- Noted packet statistics including sent, received, and lost packets

#### Web Server Access
- Opened Web Browser on PC0
- Entered the IP address `172.33.100.50`
- Successfully connected to the web server
- Loaded the webpage using direct IP-based access

---

### Technical Insight
- The `ping` command uses ICMP to test reachability between devices
- Successful replies indicate that the destination device is accessible
- Initial packet loss may occur due to ARP resolution processes
- Web browsers can access servers directly using IP addresses without DNS
- Client-server communication relies on IP addressing for routing data packets

---

### Results / Findings
- Successfully verified connectivity to the web server
- Observed minor packet loss during initial communication
- Confirmed that the client can access the web server via IP address
- Webpage loaded successfully, demonstrating proper communication

---

### Skills Demonstrated
- Network connectivity testing
- Use of command-line tools (ping)
- Understanding of ICMP protocol
- Client-server communication
- Basic troubleshooting of network connections

---

## Key Skills Gained
- IP-based communication understanding
- Network diagnostics using ping
- Web server access without DNS
- Packet transmission analysis

---

## Reflection
This lab helped me understand how devices communicate over a network using IP addresses. By using the ping command, I was able to verify connectivity and observe how packets are transmitted between a client and a server.

Accessing the web server directly through its IP address reinforced the concept that DNS is not always required for communication, as long as the IP address is known. I also learned that initial packet loss can occur due to processes such as ARP, which is a normal part of network communication.

---

## Conclusion
In conclusion, this module provided a clear understanding of how network communication works at a fundamental level. I successfully verified connectivity and accessed a web server using its IP address.

This lab strengthened my knowledge of packet transmission, ICMP usage, and client-server interaction, which are essential concepts in networking and troubleshooting.
