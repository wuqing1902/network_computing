# Module 11: Build A Small Cisco Network

## Overview
This module focuses on configuring **switches, routers, and hosts** in a new network location using Cisco IOS. It emphasizes secure device management, proper network connectivity, and professional configuration practices that go beyond basic home networking.

---

## Section 11.0: Introduction to Device Configuration

### Description
This section highlights the importance of properly configuring network devices to ensure secure management, connectivity between hosts and headquarters, and reliable internet access.

### Key Concepts
- Cisco IOS command-line interface (CLI)  
- Switch and router initial configuration  
- Security best practices for passwords and remote access  

### Technical Insight
Network devices must be configured correctly to prevent unauthorized access and ensure smooth communication. Proper use of hostnames, secure passwords, and encrypted credentials is essential. Switches require an SVI and default gateway for remote management, while routers need secured VTY lines and restricted transport protocols.

### What I Learned
Device configuration is not just about connectivity—it is also about **security, management, and maintainability**. Small errors in configuration can lead to inaccessible devices or network vulnerabilities.

---

## Section 11.1: Switch Configuration

### Description
This section explains the steps required to configure a switch for initial use and remote management.

### Key Concepts
- Assigning hostnames and banners  
- Securing console and VTY lines  
- Enabling SVI for VLAN 1  
- Assigning management IP addresses and default gateways  

### Technical Insight
Switches operate at Layer 2 but require an SVI and default gateway to be managed remotely. Using `interface vlan 1`, `ip address`, and `no shutdown` enables in-band management. Encrypting passwords and setting secure login credentials ensures unauthorized users cannot access the device.

### What I Learned
Even simple Layer 2 devices require careful planning for security and management. The default gateway is critical for remote access.

---

## Section 11.2: Router Configuration

### Description
This section focuses on configuring routers, which connect multiple networks and provide routing between locations.

### Key Concepts
- Hostname and banner configuration  
- Securing Privileged EXEC mode  
- Securing console and VTY lines  
- Transport input commands for SSH/Telnet  
- Encrypting passwords and saving configuration  

### Technical Insight
Routers must be carefully configured because they control network traffic. Restricting VTY lines to specific protocols, enabling SSH, and applying strong passwords prevent unauthorized remote access while maintaining connectivity across networks.

### What I Learned
Router configuration requires attention to both **connectivity and security**, as misconfiguration can affect multiple network segments.

---

## Section 11.3: Secure Remote Access

### Description
This section explains enabling secure remote access to devices via SSH.

### Key Concepts
- SSH vs Telnet  
- RSA key pair generation  
- Local user authentication with secret passwords  
- Enforcing SSH version 2  

### Technical Insight
SSH encrypts all communication, protecting usernames, passwords, and management commands. Generating RSA keys ensures secure encryption, and restricting VTY lines to SSH prevents insecure access.

### What I Learned
SSH is the industry standard for secure device management. Proper setup of RSA keys and authentication ensures administrative control remains protected.

---

## Section 11.4: Default Gateway Configuration

### Description
This section describes configuring default gateways for hosts and switches to enable communication beyond the local network.

### Key Concepts
- Host default gateway assignment  
- Switch default gateway for remote management  
- IPv4 manual configuration vs IPv6 auto-learned gateway  

### Technical Insight
A default gateway allows a host or switch to send packets to devices outside the local subnet. Without it, devices cannot reach remote networks or be managed from outside the local network.

### What I Learned
Default gateway configuration is fundamental to networking, enabling proper routing and remote administration.

---

## Practical Application

- Configured switches with hostnames, SVI, and secure management IP  
- Set up routers with secure VTY lines and encrypted passwords  
- Enabled SSH for secure remote device access  
- Assigned default gateways for host and switch communication  

---

## Reflection

This module reinforced that **network device configuration is both technical and security-critical**. Proper initial configuration, password management, and remote access controls are essential to maintain a secure and functional network environment.

---

## Conclusion

Overall, Module 11 provides the foundational skills to configure, secure, and manage network devices using Cisco IOS. Understanding these concepts is crucial for establishing **reliable connectivity, secure remote access, and maintainable networks**, especially in multi-location enterprise environments.
