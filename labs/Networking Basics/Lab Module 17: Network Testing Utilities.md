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
