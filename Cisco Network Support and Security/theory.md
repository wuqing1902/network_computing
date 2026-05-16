<!--
# Cybersecurity & Networking Learning Portfolio

## About Me

I am an aspiring cybersecurity and networking professional with hands-on experience in networking, troubleshooting, endpoint support, operating systems, and cybersecurity fundamentals. This portfolio documents my structured learning journey through practical modules, labs, and technical exercises focused on networking, security operations, access control, malware defense, wireless security, and enterprise troubleshooting.

Through these modules, I developed practical skills in:

- Network troubleshooting and diagnostics
- Endpoint connectivity analysis
- Linux, Windows, and macOS networking tools
- Cisco networking concepts and IOS commands
- Security fundamentals and layered defense
- Authentication and access control
- Malware protection and system hardening
- Firewall configuration and intrusion prevention
- Wireless security implementation
- Technical documentation and structured troubleshooting

---

# Table of Contents

- [Module 1: Network Support and Troubleshooting](#module-1-network-support-and-troubleshooting)
  - [Section 1.1: Diagnostics and Troubleshooting Methodologies](#section-11-diagnostics-and-troubleshooting-methodologies)
  - [Section 1.2: Network Documentation](#section-12-network-documentation)
  - [Section 1.3: Help Desks and Ticketing Systems](#section-13-help-desks-and-ticketing-systems)
  - [Section 1.4: Troubleshoot Endpoint Connectivity](#section-14-troubleshoot-endpoint-connectivity)
  - [Section 1.5: Troubleshoot a Network](#section-15-troubleshoot-a-network)
  - [Section 1.6: Troubleshoot Connectivity Remotely](#section-16-troubleshoot-connectivity-remotely)

- [Module 2: Cybersecurity Threats, Vulnerabilities, and Attacks](#module-2-cybersecurity-threats-vulnerabilities-and-attacks)
  - [Section 2.1: Common Threats](#section-21-common-threats)
  - [Section 2.2: Deception and Social Engineering](#section-22-deception-and-social-engineering)
  - [Section 2.3: Cyber Attacks and Malware](#section-23-cyber-attacks-and-malware)
  - [Section 2.4: Wireless and Mobile Security](#section-24-wireless-and-mobile-security)
  - [Section 2.5: Application Attacks](#section-25-application-attacks)

- [Module 3: Network Security](#module-3-network-security)
  - [Section 3.1: Security Foundations](#section-31-security-foundations)
  - [Section 3.2: Access Control](#section-32-access-control)
  - [Section 3.3: Defending Systems and Devices](#section-33-defending-systems-and-devices)
  - [Section 3.4: Antimalware Protection](#section-34-antimalware-protection)
  - [Section 3.5: Firewalls and Host-Based Intrusion Prevention](#section-35-firewalls-and-host-based-intrusion-prevention)
  - [Section 3.6: Secure Wireless Access](#section-36-secure-wireless-access)

---

-->


# Module 1: Network Support and Troubleshooting

## Section 1.1: Diagnostics and Troubleshooting Methodologies

Modern IT environments rely heavily on structured troubleshooting methodologies to quickly identify, isolate, and resolve technical issues. Troubleshooting is not simply trial and error — it is a systematic process involving information gathering, analysis, hypothesis testing, and documentation.

### Key Concepts

#### Seven-Step Troubleshooting Process

1. Define the problem
2. Gather information
3. Analyze information
4. Eliminate possible causes
5. Propose a hypothesis
6. Test the hypothesis
7. Solve and document the problem

#### Structured Troubleshooting Methods

- Bottom-Up Approach
- Top-Down Approach
- Divide-and-Conquer
- Follow-the-Path
- Substitution Method
- Comparison Method

#### Troubleshooting Models

- OSI Model troubleshooting
- TCP/IP troubleshooting
- Layer-focused fault isolation

### Real-World Applications

- Diagnosing enterprise network outages
- Troubleshooting unstable internet connections
- Isolating endpoint connectivity failures
- Identifying faulty network devices

### What I Learned

I learned that effective troubleshooting depends on structured thinking, documentation, and systematic analysis rather than guessing.

---

## Section 1.2: Network Documentation

Accurate documentation is critical for maintaining, troubleshooting, and scaling enterprise networks.

### Key Concepts

#### Network Types

- PAN
- LAN
- VLAN
- WLAN
- WMN
- CAN
- MAN
- WAN
- VPN

#### Physical vs Logical Topology

Physical topology documents:

- Device locations
- Cabling layouts
- Physical connections

Logical topology documents:

- IP addressing
- VLAN assignments
- Routing structures

#### Cloud Computing Models

- SaaS
- PaaS
- IaaS
- XaaS

#### Network Baselines

Examples include:

- Bandwidth usage
- Error rates
- Device utilization
- Traffic flow patterns

#### Cisco Discovery Protocol (CDP)

```bash
show cdp neighbors
show cdp neighbors detail
```

### Real-World Applications

- Enterprise network mapping
- Infrastructure inventories
- Network performance monitoring
- Troubleshooting and auditing

### What I Learned

I learned that documentation is essential for operational efficiency, scalability, and troubleshooting in enterprise environments.

---

## Section 1.3: Help Desks and Ticketing Systems

Help desks serve as the primary support channel between users and IT departments.

### Key Concepts

#### Security Policies

- User authentication
- Password requirements
- Acceptable use policies
- Remote access policies

#### Help Desk Responsibilities

- Receive support requests
- Create and manage tickets
- Troubleshoot incidents
- Escalate unresolved issues
- Document solutions

#### Communication Skills

- Active listening
- Clear communication
- Empathy
- Technical translation

### Real-World Applications

- Enterprise help desk operations
- IT service management
- Incident escalation workflows
- Technical support environments

### What I Learned

I learned that communication and documentation are just as important as technical skills in IT support environments.

---

## Section 1.4: Troubleshoot Endpoint Connectivity

This section focused on diagnosing connectivity issues across Windows, Linux, macOS, and mobile devices.

### Key Concepts

#### Windows Networking Commands

```bash
ipconfig
ipconfig /all
ping
tracert
```

#### Linux Networking Commands

```bash
ifconfig
ip address
ping
traceroute
nc
```

#### macOS Networking Commands

```bash
ifconfig
networksetup -listallnetworkservices
ping
traceroute
```

### Connectivity Testing Tools

#### Ping

Tests Layer 3 communication.

#### Traceroute / Tracert

Displays routing paths.

#### Ncat (nc)

```bash
nc -z -v www.google.com 443
```

### Real-World Applications

- Diagnosing DHCP issues
- Testing internet connectivity
- Verifying wireless access
- Identifying routing failures

### What I Learned

I learned how to diagnose endpoint connectivity issues using platform-specific networking tools and commands.

---

## Section 1.5: Troubleshoot a Network

Network devices provide valuable operational and troubleshooting information.

### Key Concepts

#### Cisco IOS Privilege Levels

- User EXEC Mode (`>`)
- Privileged EXEC Mode (`#`)

### Common Cisco IOS Commands

```bash
enable
show running-config
show interfaces
show ip interface brief
show cdp neighbors
```

#### Packet Capture and Protocol Analysis

Tools such as Wireshark help:

- Inspect packets
- Analyze protocols
- Investigate traffic behavior

#### Throughput Measurement

```bash
iperf3 -c speedtest.masnet.ec
```

### Real-World Applications

- Network monitoring
- Traffic analysis
- Performance testing
- Security investigations

### What I Learned

I learned how networking professionals use IOS commands and packet analysis tools to troubleshoot enterprise environments.

---

## Section 1.6: Troubleshoot Connectivity Remotely

Remote support technologies allow technicians to resolve issues without physical access.

### Key Concepts

#### Remote Access Tools

- Microsoft Remote Desktop
- Apple Remote Desktop
- TeamViewer
- Zoho Assist

#### Telnet vs SSH

##### Telnet

- Uses TCP port 23
- Sends data in plaintext

##### SSH

- Secure encrypted communication
- Industry standard for remote administration

### Security Best Practices

- Multi-factor authentication
- Restricted remote access
- Encrypted communication
- Access authorization

### Real-World Applications

- Remote IT support
- Secure server administration
- Hybrid workforce support

### What I Learned

I learned how secure remote administration improves operational efficiency while introducing important security considerations.

---

# Module 2: Cybersecurity Threats, Vulnerabilities, and Attacks

## Section 2.1: Common Threats

Organizations face constantly evolving cyber threats targeting devices, users, applications, and networks.

### Key Concepts

#### Threat Domains

- User domain
- Device domain
- LAN domain
- Cloud domain
- Application domain

#### Common Threats

- Malware infections
- Unauthorized access
- Vulnerable software
- Weak configurations
- Insider threats

### Real-World Applications

- Threat monitoring
- Vulnerability management
- Security awareness programs
- Enterprise risk assessments

### What I Learned

I learned how attackers target different organizational domains and why layered defense is critical.

---

## Section 2.2: Deception and Social Engineering

Social engineering attacks exploit human behavior rather than technical weaknesses.

### Key Concepts

#### Social Engineering Techniques

- Pretexting
- Identity fraud
- Tailgating
- Shoulder surfing
- Dumpster diving

#### Psychological Manipulation

Attackers exploit:

- Trust
- Fear
- Urgency
- Curiosity

### Real-World Applications

- Security awareness training
- Identity verification procedures
- Physical security controls

### What I Learned

I learned that users are often the weakest link in cybersecurity and that awareness training is essential.

---

## Section 2.3: Cyber Attacks and Malware

Cybercriminals use malware and advanced attacks to compromise systems and networks.

### Key Concepts

#### Malware Types

- Viruses
- Worms
- Trojan horses
- Rootkits
- Spyware
- Ransomware

#### Advanced Threats

- APTs
- Backdoors
- Algorithm attacks

### Real-World Applications

- Endpoint protection
- Threat detection
- Incident response
- Security monitoring

### What I Learned

I learned how malware spreads and how organizations detect and respond to cyber threats.

---

## Section 2.4: Wireless and Mobile Security

Wireless and mobile technologies introduce additional security risks.

### Key Concepts

#### Wireless Security Standards

- WEP
- WPA
- WPA2

#### Wireless Threats

- Rogue access points
- Packet sniffing
- Weak encryption
- Public Wi-Fi risks

### Real-World Applications

- Secure enterprise Wi-Fi
- Mobile workforce protection
- Wireless intrusion prevention

### What I Learned

I learned the importance of encryption, VPN usage, and secure wireless configurations.

---

## Section 2.5: Application Attacks

Applications and databases are common attack targets.

### Key Concepts

#### Cross-Site Scripting (XSS)

Attackers inject malicious scripts into web applications.

#### Injection Attacks

- SQL injection
- XML injection

### Real-World Applications

- Secure web development
- Input validation
- Database security

### What I Learned

I learned how insecure coding practices can expose organizations to serious security risks.

---

# Module 3: Network Security

## Section 3.1: Security Foundations

Network security protects systems, devices, and data against unauthorized access and cyber threats.

### Key Concepts

#### CIA Triad

- Confidentiality
- Integrity
- Availability

#### Data States

- Data at rest
- Data in transit
- Data in process

#### Security Safeguards

- Technology
- Policies and procedures
- User education

### Real-World Applications

- Enterprise security policies
- Data protection strategies
- Security awareness training

### What I Learned

I learned how layered security principles protect enterprise environments.

---

## Section 3.2: Access Control

Access control mechanisms regulate who can access systems and resources.

### Key Concepts

#### Authentication Factors

##### Something You Know

- Passwords
- PINs

##### Something You Have

- Smart cards
- Hardware tokens

##### Something You Are

- Fingerprints
- Facial recognition

#### Multi-Factor Authentication (MFA)

Combines multiple authentication methods for stronger security.

#### Role-Based Access Control (RBAC)

Permissions are assigned based on organizational roles.

### Real-World Applications

- Enterprise authentication systems
- Banking authentication
- Cloud identity management

### What I Learned

I learned how strong authentication and access control improve organizational security.

---

## Section 3.3: Defending Systems and Devices

Organizations use layered defenses to protect endpoints and enterprise systems.

### Key Concepts

#### Endpoint Security

- Workstations
- Laptops
- Servers
- Mobile devices

#### Defense-in-Depth

Examples include:

- Firewalls
- Antivirus software
- Encryption
- Monitoring systems

#### System Hardening

- Disable unnecessary services
- Remove unused software
- Apply security patches

### Real-World Applications

- Endpoint protection
- Vulnerability remediation
- Secure device deployment

### What I Learned

I learned how layered defenses reduce attack surfaces and improve endpoint security.

---

## Section 3.4: Antimalware Protection

Antimalware solutions help detect and prevent malicious software infections.

### Key Concepts

#### Malware Types

- Viruses
- Worms
- Trojans
- Ransomware
- Spyware

#### Detection Methods

##### Signature-Based Detection

Uses known malware signatures.

##### Heuristic Analysis

Detects suspicious behavior patterns.

##### Real-Time Protection

Continuously monitors systems for threats.

### Real-World Applications

- Antivirus deployment
- Endpoint monitoring
- Malware incident response

### What I Learned

I learned how antimalware technologies combine multiple detection methods to protect systems.

---

## Section 3.5: Firewalls and Host-Based Intrusion Prevention

Firewalls and intrusion prevention systems help secure networks and endpoints.

### Key Concepts

#### Firewall Types

- Packet-filtering firewalls
- Stateful firewalls
- Application-layer firewalls
- Next-generation firewalls

#### IDS vs IPS

##### IDS

Detects suspicious activity and generates alerts.

##### IPS

Detects and automatically blocks malicious traffic.

### Real-World Applications

- Perimeter defense
- Traffic filtering
- Threat monitoring
- Network segmentation

### What I Learned

I learned how firewalls and IPS technologies help prevent unauthorized access and malicious activity.

---

## Section 3.6: Secure Wireless Access

Wireless networks require strong encryption and secure configurations to prevent attacks.

### Key Concepts

#### Wireless Security Standards

- WEP
- WPA
- WPA2

#### Wireless Threats

- Rogue access points
- Evil twin attacks
- Packet sniffing
- Weak passwords

#### Secure Wireless Practices

- Use WPA2 encryption
- Change default credentials
- Implement guest network segmentation
- Use strong passphrases

#### VPN Security

VPNs encrypt data transmitted over public networks.

### Real-World Applications

- Enterprise Wi-Fi deployment
- Secure remote access
- Wireless network monitoring

### What I Learned

I learned how secure wireless configurations and encryption help protect users and enterprise networks.


<!--


---

# Technical Skills Developed

## Networking

- TCP/IP fundamentals
- Network troubleshooting
- Cisco IOS fundamentals
- VLAN concepts
- Wireless networking
- VPN fundamentals

## Cybersecurity

- Access control
- Endpoint protection
- Malware defense
- Firewall technologies
- Intrusion prevention
- Wireless security

## Operating Systems

- Windows networking tools
- Linux command-line networking
- macOS diagnostics

## Tools & Technologies

- Wireshark
- Cisco IOS CLI
- Ping / Traceroute
- Netcat / Ncat
- iPerf
- Remote Desktop tools

---

# Portfolio Goals

This portfolio demonstrates:

- Networking fundamentals
- Cybersecurity awareness
- Troubleshooting methodologies
- Technical documentation skills
- Structured analytical thinking
- Continuous learning and self-development

---

# Future Learning Objectives

Going forward, I plan to continue developing skills in:

- SOC operations
- SIEM monitoring
- Linux administration
- Cloud security
- Python scripting
- Threat detection
- Digital forensics
- Incident response

---

# Contact

Feel free to connect with me through GitHub and LinkedIn as I continue building projects and documenting my cybersecurity learning journey.
-->

