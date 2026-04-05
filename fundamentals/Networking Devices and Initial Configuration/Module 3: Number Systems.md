# Module 3: Number Systems

## Overview
This module introduces the fundamental numbering systems used in networking, including binary, decimal, and hexadecimal. It explains how these systems are used to represent IP addresses and MAC addresses, and why understanding number conversion is essential for network configuration and troubleshooting.

---

## Section 3.0: Introduction to Numbering Systems

### Description
This section explains the importance of different numbering systems in networking, highlighting the difference between human-readable decimal and machine-level binary representation.

### Key Concepts
- Decimal (base 10)
- Binary (base 2)
- Hexadecimal (base 16)

### Technical Insight
Computers and network devices operate using binary (0s and 1s), while humans use decimal for convenience. Hexadecimal serves as a bridge between the two, providing a more compact and readable way to represent large binary values such as IPv6 and MAC addresses.

### What I Learned
Understanding multiple numbering systems is essential because networking relies on both machine-level processing (binary) and human-level configuration (decimal and hexadecimal).

---

## Section 3.1: Binary and IPv4 Addressing

### Description
This section explains how binary is used in IPv4 addressing and how binary values are converted into decimal format for human readability.

### Key Concepts
- 32-bit IPv4 address
- Octets (8 bits = 1 byte)
- Dotted decimal notation
- Binary ↔ Decimal conversion

### Technical Insight
An IPv4 address is made up of 32 binary bits divided into four octets. Each octet represents values based on powers of 2 (128, 64, 32, 16, 8, 4, 2, 1). Converting between binary and decimal requires understanding positional values, where each bit contributes to the total value when set to 1. This conversion is critical for interpreting and configuring IP addresses in real-world networks.

### What I Learned
Binary is the actual language of networking devices, while decimal is used for human interaction. Being able to convert between them is a fundamental networking skill.

---

## Section 3.2: Hexadecimal and IPv6 Addressing

### Description
This section introduces hexadecimal numbering and its use in representing IPv6 and MAC addresses.

### Key Concepts
- Hexadecimal (0–9, A–F)
- 4-bit grouping
- IPv6 structure (128-bit)
- Hextets (16-bit segments)
- Hex ↔ Decimal conversion

### Technical Insight
Hexadecimal simplifies large binary numbers by grouping bits into sets of four. This makes it ideal for representing long addresses such as IPv6 (128 bits) and MAC addresses (48 bits). Converting between decimal and hexadecimal often involves binary as an intermediate step, ensuring accurate representation and efficient computation.

### What I Learned
Hexadecimal makes complex binary values easier to read and manage, especially for modern addressing systems like IPv6.

---

## Practical Application

- Practiced converting binary values to decimal and vice versa
- Converted decimal numbers into binary using positional values
- Converted decimal values into hexadecimal using binary as an intermediate step
- Identified IPv4 and IPv6 address structures

---

## Reflection

This module strengthened my understanding of how data is represented in networking systems. Learning how to convert between binary, decimal, and hexadecimal helped me better understand how IP and MAC addresses function at a deeper level.

---

## Conclusion

Overall, this module provides essential knowledge of numbering systems used in networking. Mastering binary, decimal, and hexadecimal conversions is critical for working with IP addressing and network configuration. These foundational skills are necessary for advancing in networking and cybersecurity.
