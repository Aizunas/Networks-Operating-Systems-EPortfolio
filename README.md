# Networks-Operating-Systems-Portfolio
E-Portfolio for Networks &amp; Operating Systems. Contains weekly lab exercises, code snippetsband learning reflections.


Table of Contents

Week 1: No LAB

Week 2: Networks Fundamentals

Week 3: Application Layer in Networks

Week 4: Transport Layer in Networks Part 1

Week 5: Transport Layer Part 2

Week 6: Internet Layer

Week 7: Network Access Layer

--------------------------------------------------------------
Week 6: Internet Layer

Objectives
- Understand IP addressing, including classful and classless addressing (CIDR).
- Simulate DHCP operations using Python.
- Analyze and manipulate IP addresses programmatically.

Exercises (Week 6)

1. Working with IP Addresses
   
a. Classful Addressing
Objective: Understand and implement classful IP addressing.
What I Learned: IPv4 addresses are divided into classes (A, B, C, D, E) based on the first octet, which determines the network and host portions.

b. Classless Inter-Domain Routing (CIDR)
Objective: Implement CIDR-based IP addressing.
What I Learned: CIDR allows flexible allocation of IP addresses using a network prefix and subnet mask, improving efficiency and scalability.

c. IP Address Analysis
Objective: Analyze IP addresses to determine network details, broadcast addresses, and usable host ranges.
What I Learned: Using Python's ipaddress module, I can programmatically analyze IP addresses and subnetting.

2. Dynamic Host Configuration Protocol (DHCP)
   
a. DHCP Operation (DORA Process)
Objective: Simulate the DHCP DORA process (Discover, Offer, Request, Acknowledge).
What I Learned: DHCP automates IP address assignment and network configuration for devices on a network.

-----------------------------------------------------------------------------------------------------
Week 7: Network Access Layer

Objectives:
- Understand and implement error detection and correction techniques.
- Simulate network behaviors and analyze performance metrics.

Exercises (Week 7)

1. Error Detection & Correction

a. Single-Bit Parity Check
Objective: Implement a single-bit parity check for 8-bit data.
What I Learned: Single-bit parity checks are effective for detecting single-bit errors but cannot correct errors or detect multiple-bit errors.

b. 2D Parity Check
Objective: Perform a 2D parity check to detect and correct errors in a block of data.
What I Learned: 2D parity checks can detect multiple-bit errors and correct single-bit errors, making them more robust than single-bit parity checks.

c. Checksum Using One's Complement
Objective: Implement a checksum using one's complement for error detection.
What I Learned: One's complement checksums are widely used in networking protocols like TCP, UDP, and IP for efficient error detection.

2. Multiple Access Protocols (MAP)
Objective: Model and compare the performance of Pure ALOHA, Slotted ALOHA, and CSMA/CD.
What I Learned: Slotted ALOHA improves the efficiency of Pure ALOHA by dividing time into slots, and its efficiency can be visualized using simulations.




