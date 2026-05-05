# Lab Module 4: Build A Home Network

## Overview
This module focuses on fundamental home networking concepts through a hands-on Packet Tracer lab. The activity involves setting up a complete home network, including wired and wireless connectivity, router configuration, and internet access verification.

The lab simulates a real-world scenario where a home network is built from scratch, requiring proper cable connections, router configuration, and wireless security setup. It emphasizes practical skills in configuring networking devices and ensuring connectivity across multiple devices.

---

## Technologies Used
- Cisco Packet Tracer
- Wireless Router Configuration (GUI)
- DHCP (Dynamic Host Configuration Protocol)
- Ethernet & Coaxial Cabling
- Wireless Networking (Wi-Fi)

---

## Objectives
- Understand how to physically connect home networking devices
- Configure a wireless router using a web-based GUI
- Set up DHCP for automatic IP addressing
- Establish a secure wireless network (WPA2)
- Connect both wired and wireless devices to the network
- Verify internet connectivity across multiple devices

---

## Lab 1: Configure a Wireless Router and Clients

### Description
This lab simulates setting up a home network for a user by connecting devices, configuring a wireless router, enabling DHCP, and securing a wireless LAN. The network includes both wired and wireless devices connected through a central home router.

### Tools & Technologies
- Cisco Packet Tracer
- Home Wireless Router (GUI-based configuration)
- Coaxial and Ethernet cables
- Wireless client configuration

---

### Key Tasks Performed

#### Network Setup
- Connected coaxial cables from ISP to cable modem and TV via splitter
- Connected cable modem to wireless router (Internet port)
- Connected wired devices (Office PC & Bedroom PC) using Ethernet cables

#### Router Configuration
- Accessed router GUI via web browser using default gateway
- Enabled DHCP for automatic IP assignment
- Limited DHCP users to 10 devices
- Changed default admin password for security

#### Wireless Network Setup
- Enabled 2.4 GHz wireless network
- Configured SSID: **MyHome**
- Set wireless security to **WPA2 Personal**
- Configured passphrase authentication

#### Device Connectivity
- Connected laptop to wireless network using passphrase
- Configured PCs to obtain IP addresses via DHCP
- Verified all devices received valid IP addresses (192.x.x.x range)

#### Connectivity Testing
- Tested internet access using web browser on all devices
- Verified successful connection to external server (skillsforall.srv)

---

### Technical Insight
- A home wireless router acts as a central device providing routing, switching, and wireless access
- DHCP simplifies network management by automatically assigning IP addresses
- WPA2 Personal enhances wireless security by requiring authentication
- Default credentials on network devices pose security risks and must be changed
- Proper cabling (coaxial, Ethernet) is essential for network functionality

---

### Results / Findings
- Successfully established a fully functional home network
- All devices (wired and wireless) were able to connect to the internet
- DHCP correctly assigned IP addresses to all clients
- Wireless network was secured using WPA2 authentication
- Demonstrated seamless integration of wired and wireless networking

---

### Skills Demonstrated
- Network configuration and setup
- Router GUI configuration
- Wireless network security implementation
- DHCP configuration and management
- Troubleshooting connectivity issues
- Understanding of home network architecture

---

## Key Skills Gained
- Home network installation and setup
- Wireless router configuration
- Secure Wi-Fi implementation
- IP addressing and DHCP management
- Network troubleshooting

---

## Reflection
This lab provided practical experience in setting up a real-world home network environment. I learned how different components such as cable modems, routers, and end devices work together to provide internet access.

Configuring the router through a GUI helped me understand how network settings are managed in real-life scenarios, especially for home users. The process of setting up wireless security also highlighted the importance of protecting networks from unauthorized access.

Additionally, testing connectivity across multiple devices reinforced my understanding of how DHCP, IP addressing, and routing function within a network.

---

## Conclusion
In conclusion, this module strengthened my foundational knowledge of networking by focusing on practical implementation. I successfully configured both wired and wireless connections, secured the network, and verified full connectivity.

This lab provided essential skills for real-world networking scenarios, particularly in home and small office environments. It also built my confidence in handling network setup, configuration, and troubleshooting tasks.

<br><br><br>

---

<br><br><br>

# Lab Module 8: The Internet Protocol

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


<br><br><br>

---

<br><br><br>

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


<br><br><br>

---

<br><br><br>

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


<br><br><br>

---

<br><br><br>

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


<br><br><br>

---

<br><br><br>


# Lab Module 14: Routing Between Networks

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


<br><br><br>

---

<br><br><br>

# Lab Module 16: Application Layer Services

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


<br><br><br>

---

<br><br><br>


# Lab Module 17: Network Testing Utilities

## Overview
Module 17 focuses on identifying and correcting network misconfigurations using basic Windows networking commands. Students learn to verify IP settings, test connectivity, and diagnose DNS-related issues. These skills are essential for troubleshooting small office networks and ensuring proper internet access for all hosts.

---

## Tools & Technologies
- Cisco Packet Tracer
- Command Prompt (PC)
- ipconfig command
- ping command
- Web Browser

---

## Lab 1: Use the ipconfig Command

### Objectives
- Use `ipconfig /all` to identify incorrect IP configuration on a PC
- Correct misconfigured network settings

---

### Background / Scenario
A small business office has four PCs on a static IP network (192.168.1.0/24). One PC cannot access the internet or the internal web server (www.cisco.pka). The goal is to identify which PC is misconfigured and correct the settings.

---

### Key Tasks Performed
1. Accessed Command Prompt on all PCs
2. Ran `ipconfig /all` to view IP address, subnet mask, and default gateway
3. Identified PC2 as incorrectly configured (default gateway 192.168.1.1 but network portion was 192.168.10.X)
4. Corrected PC2’s IP configuration to 192.168.1.X to match the network

---

### Technical Insights
1. **Verify configurations:**
   - Observed PC2 had IP 192.168.10.X, while the default gateway was 192.168.1.1
   - **Insight:** Mismatch in the network portion prevents Layer 3 routing. Even if physical connectivity exists, the PC cannot communicate outside its perceived subnet

2. **Correct misconfiguration:**
   - Updated PC2 IP to 192.168.1.X to align with the subnet of the gateway and other PCs
   - **Insight:** Proper subnet alignment ensures Layer 3 connectivity to other hosts and the default gateway, allowing internet and intranet access

---

### Results / Findings
- PC2 was misconfigured
- Corrected IP configuration allowed the PC to communicate properly on the LAN and access the web server

---

### Skills Demonstrated
- Reading and interpreting IP configuration using `ipconfig`
- Identifying incorrect default gateway or subnet mismatch
- Correcting static IP misconfigurations

---

## Lab 2: Use the ping Command

### Objectives
- Use the `ping` command to identify network connectivity issues
- Compare DNS configurations to diagnose domain resolution problems

---

### Background / Scenario
After correcting IP misconfigurations, some PCs still cannot access www.cisco.pka. Ping tests are used to verify connectivity and determine if issues are due to DNS misconfiguration.

---

### Key Tasks Performed
1. Verified web connectivity using the PC Web Browser
   - PC2 was unable to access www.cisco.pka
2. Pinged the web server from PC2
   - Received: `Ping request could not find host www.cisco.pka`
3. Pinged the web server from correctly configured PCs
   - Received replies from IP: 192.15.2.10
4. Pinged the IP address of the web server from PC2
   - Successful reply → indicates DNS issue
5. Compared DNS server settings
   - Correct PCs: DNS = 192.15.2.5
   - PC2: DNS = 191.15.2.5 (incorrect)
6. Updated PC2’s DNS server configuration
7. Verified connectivity to www.cisco.pka in the browser

---

### Technical Insights & Steps
1. **Verify connectivity at application layer:**
   - Attempted to access the web server using a browser → failed
   - **Insight:** Failure could be due to DNS (name resolution) or connectivity (Layer 3/4)

2. **Ping the web server using domain name:**
   - PC2 → `ping www.cisco.pka`
   - Result: `Ping request could not find host www.cisco.pka`
   - **Insight:** ICMP test confirms the PC cannot resolve the domain → DNS problem

3. **Ping the web server using IP address:**
   - PC2 → `ping 192.15.2.10`
   - Successful reply → indicates **network connectivity is intact**
   - **Insight:** Confirms Layer 3/4 connectivity works; problem is DNS (Layer 7)

4. **Compare DNS configurations:**
   - Correct PCs: DNS = 192.15.2.5
   - PC2: DNS = 191.15.2.5
   - **Insight:** Incorrect DNS server causes domain name resolution to fail even if IP connectivity is correct

5. **Correct DNS setting on PC2 and verify:**
   - Updated DNS to 192.15.2.5
   - Browser now successfully reaches `www.cisco.pka`
   - **Insight:** Proper DNS configuration ensures resolution of domain names to IP addresses

---

### Results / Findings
- Misconfigured DNS prevented domain name resolution
- Ping to IP address confirmed network connectivity was intact
- Correcting the DNS resolved the web access issue

---

### Skills Demonstrated
- Testing network connectivity using ping
- Diagnosing DNS-related issues
- Making necessary network configuration changes to restore access

---

## Reflection
These labs highlighted the importance of **systematic troubleshooting**. By using `ipconfig` to verify IP settings and `ping` to test connectivity, I was able to identify both subnet and DNS misconfigurations. This reinforces that even simple tools are extremely powerful for network troubleshooting in small office environments.

---

## Conclusion
Module 17 strengthened my skills in **network diagnostics**. I learned to:
- Verify IP, subnet, and gateway configurations
- Test connectivity to web servers
- Diagnose and fix DNS issues
- Restore network functionality for misconfigured hosts

These skills are foundational for network administration and troubleshooting in any enterprise or small office network.

