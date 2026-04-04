# Module 16: Application Layer Services

## Overview
This module focuses on client-server interactions and common network services, including HTTP, DNS, FTP, Telnet, and SSH. Through multiple hands-on labs, it demonstrates how clients communicate with servers, how data is transferred, and how secure and insecure remote access methods function.

The activities emphasize real-world networking concepts such as web communication, file transfer, and remote device management.

---

## Technologies Used
- Cisco Packet Tracer
- DNS & HTTP Services
- FTP (File Transfer Protocol)
- Telnet & SSH
- Command Line Tools
- Simulation Mode (PDU Analysis)

---

## Objectives
- Understand client-server communication
- Analyze DNS and HTTP request processes
- Perform file transfers using FTP
- Compare Telnet and SSH remote access methods
- Observe network traffic using simulation tools

---

## Lab 1: The Client Interaction

### Description
This lab demonstrates how a client interacts with a server to request and retrieve a web page. It focuses on DNS resolution and HTTP communication using simulation mode.

---

### Tools & Technologies
- Cisco Packet Tracer
- Simulation Mode
- Web Browser

---

### Key Tasks Performed
- Enabled simulation mode and applied DNS/HTTP filters
- Requested a web page (www.example.com) from a PC
- Observed DNS resolution process
- Tracked HTTP request and response between client and server
- Analyzed PDU details across OSI layers

---

### Technical Insight
- DNS resolves domain names into IP addresses
- HTTP is used to request and deliver web content
- Communication involves multiple steps: DNS request, HTTP request, and server response
- Data may be delivered in segments and acknowledged by the client

---

### Results / Findings
- Successfully observed DNS and HTTP traffic flow
- Web page was retrieved after successful DNS resolution
- Multiple PDUs were exchanged during communication

---

### Skills Demonstrated
- Traffic analysis using simulation mode
- Understanding client-server interaction
- Protocol-level observation (DNS, HTTP)

---

## Lab 2: Observe Web Request

### Description
This lab focuses on observing HTTP traffic between a client and a web server, including DNS resolution and packet exchange.

---

### Tools & Technologies
- Cisco Packet Tracer
- Web Browser
- Simulation Mode

---

### Key Tasks Performed
- Verified connectivity using ping to domain name
- Accessed web server via URL (ciscolearn.web.com)
- Examined HTML code on the server
- Created complex PDU to simulate HTTP traffic
- Observed packet flow and TCP communication

---

### Technical Insight
- DNS resolves domain names to IP addresses before communication
- HTTP operates over TCP, requiring connection establishment and acknowledgements
- Web pages are generated from HTML files hosted on servers
- TCP increases reliability but adds overhead

---

### Results / Findings
- Successfully accessed web server via domain name
- Observed multiple packets exchanged due to TCP communication
- Verified relationship between HTML code and web page display

---

### Skills Demonstrated
- Web traffic analysis
- Understanding TCP/HTTP communication
- Basic web server functionality

---

## Lab 3: Use FTP Services

### Description
This lab demonstrates how to upload, download, and manage files using an FTP server.

---

### Tools & Technologies
- FTP Protocol
- Command Line Interface

---

### Key Tasks Performed
- Located local file (sampleFile.txt)
- Connected to FTP server using credentials
- Uploaded file using `put` command
- Renamed file on server
- Downloaded file using `get` command
- Deleted file using `delete` command

---

### Technical Insight
- FTP uses port 21 for control and port 20 for data transfer
- File transfers require authentication
- FTP allows file management operations (upload, download, rename, delete)
- FTP is not secure as it transmits data in plaintext

---

### Results / Findings
- Successfully uploaded and downloaded files
- Verified file operations on FTP server
- Demonstrated full FTP workflow

---

### Skills Demonstrated
- File transfer using FTP
- Command-line operations
- Remote file management

---

## Lab 4: Use Telnet and SSH

### Description
This lab compares Telnet and SSH for remote access to a network device, highlighting the importance of secure communication.

---

### Tools & Technologies
- Telnet
- SSH (Secure Shell)
- Command Line Interface

---

### Key Tasks Performed
- Verified IP configuration using `ipconfig`
- Tested connectivity using ping
- Attempted Telnet connection (unsuccessful)
- Established SSH connection using credentials
- Accessed router command-line interface

---

### Technical Insight
- Telnet is insecure and often disabled on modern devices
- SSH provides encrypted and secure remote access
- Successful SSH login provides administrative access to network devices
- Security best practices require using SSH instead of Telnet

---

### Results / Findings
- Telnet connection was denied due to security restrictions
- SSH connection was successful
- Router access achieved securely via SSH

---

### Skills Demonstrated
- Remote device access
- Understanding secure vs insecure protocols
- Network troubleshooting and verification

---

## Key Skills Gained
- Client-server communication analysis
- Web and DNS operation understanding
- File transfer using FTP
- Secure remote access using SSH
- Network protocol analysis

---

## Reflection
This module provided a comprehensive understanding of how different network services operate and interact. I learned how DNS and HTTP work together to deliver web content, and how protocols like FTP enable file transfer between systems.

Additionally, comparing Telnet and SSH highlighted the importance of security in network communications. Observing these services in action helped me better understand real-world networking scenarios.

---

## Conclusion
In conclusion, this module strengthened my knowledge of client-server communication and network services. I successfully analyzed web traffic, performed file transfers, and accessed network devices remotely.

These skills are essential for networking and cybersecurity roles, especially in understanding how services operate and how to secure them effectively.
