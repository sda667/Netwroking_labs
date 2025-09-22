# Networking Labs Portfolio

This repository collects networking lab projects.  
Each lab focuses on a core concept of computer networks, with experiments, analysis, and detailed reports.  

---

## Summary Table

| Lab | Topic | Reports |
|-----|-------|---------|
| [HTTP and TCP Basics](https://github.com/sda667/HTTP-TCP_basics) | HTTP over TCP/IP, handshake, retransmissions, congestion control | [Markdown Report](https://github.com/sda667/HTTP-TCP_basics/blob/main/HTTP_TCP_Basics.md) • [PDF Report](https://github.com/sda667/HTTP-TCP_basics/blob/main/HTTP_TCP_Basics.pdf) |
| [TCP Flow Control and Congestion](https://github.com/sda667/TCP_FlowControl-Congestion) | Flow control, congestion avoidance (slow start, AIMD), ARQ comparison | [Markdown Report](https://github.com/sda667/TCP_FlowControl-Congestion/blob/main/REPORT.md) • [PDF Report](https://github.com/sda667/TCP_FlowControl-Congestion/blob/main/report.pdf) |
| [Bridging and STP](https://github.com/sda667/Bridging-STP) | Ethernet switching, MAC learning, ARP, loop prevention with STP | [Markdown Report](https://github.com/sda667/Bridging-STP/blob/main/Bridging_and_spanning_tree_protocol.md) • [PDF Report](https://github.com/sda667/Bridging-STP/blob/main/Bridging_and_spanning_tree_protocol.pdf) |
| [RIP and OSPF](https://github.com/sda667/RIP-OSPF) | Distance-vector vs link-state routing, convergence speed, scalability | [Markdown Report](https://github.com/sda667/RIP-OSPF/blob/main/RIP___OSPF.md) • [PDF Report](https://github.com/sda667/RIP-OSPF/blob/main/RIP___OSPF.pdf) |
| [IP Addressing and Static Routing](https://github.com/sda667/IP_addressing) | Subnetting, static routes, forwarding behavior, TTL, checksum | [Markdown Report](https://github.com/sda667/IP_addressing/blob/main/IP_addressing.md) • [PDF Report](https://github.com/sda667/IP_addressing/blob/main/IP_addressing.pdf) |

---

## Skills Highlighted

**Skills:** Packet analysis (Wireshark), TCP flow and congestion control, Ethernet switching and STP, routing protocols (RIP, OSPF), IP addressing and subnetting, troubleshooting and convergence analysis.  

---

## Labs

### 1. [HTTP and TCP Basics](https://github.com/sda667/HTTP-TCP_basics)  
Explores how the **HTTP protocol** operates over the **TCP/IP stack**.  
The project analyzes the TCP three-way handshake, reliable delivery through acknowledgments and retransmissions, and congestion control behavior.  
Incorrect configurations (such as using HTTPS on port 80) are used to highlight protocol limitations.  

[Markdown Report](https://github.com/sda667/HTTP-TCP_basics/blob/main/HTTP_TCP_Basics.md) • [PDF Report](https://github.com/sda667/HTTP-TCP_basics/blob/main/HTTP_TCP_Basics.pdf)  

---

### 2. [TCP Flow Control and Congestion](https://github.com/sda667/TCP_FlowControl-Congestion)  
Investigates how **TCP manages throughput and network stability**.  
The analysis demonstrates the effects of flow control (receiver-limited speed) and congestion control (slow start, AIMD, retransmissions).  
The study also compares TCP’s integrated reliability mechanisms with ARQ protocols such as Go-Back-N and Selective Repeat.  

[Markdown Report](https://github.com/sda667/TCP_FlowControl-Congestion/blob/main/REPORT.md) • [PDF Report](https://github.com/sda667/TCP_FlowControl-Congestion/blob/main/report.pdf)  

---

### 3. [Bridging and Spanning Tree Protocol (STP)](https://github.com/sda667/Bridging-STP)  
Examines the behavior of **Ethernet switches** and the operation of the **Spanning Tree Protocol** in redundant topologies.  
The project covers frame forwarding, MAC address learning, ARP exchanges, and the election of a root bridge.  
Results show how STP prevents loops and converges after failures (30–50s), with a comparison to Rapid STP (RSTP) for faster recovery.  

[Markdown Report](https://github.com/sda667/Bridging-STP/blob/main/Bridging_and_spanning_tree_protocol.md) • [PDF Report](https://github.com/sda667/Bridging-STP/blob/main/Bridging_and_spanning_tree_protocol.pdf)  

---

### 4. [Routing Protocols: RIP and OSPF](https://github.com/sda667/RIP-OSPF)  
Compares two fundamental routing protocols: **RIP (distance-vector)** and **OSPF (link-state)**.  
The study evaluates convergence speed, scalability, and path selection.  
Findings show that RIP is simple but slow (minutes to converge) and limited by hop count, while OSPF propagates LSAs quickly (~10s), uses cost-based metrics, and scales efficiently.  

[Markdown Report](https://github.com/sda667/RIP-OSPF/blob/main/RIP___OSPF.md) • [PDF Report](https://github.com/sda667/RIP-OSPF/blob/main/RIP___OSPF.pdf)  

---

### 5. [IP Addressing and Static Routing](https://github.com/sda667/IP_addressing)  
Covers the fundamentals of **IP addressing** and **static routing** in a small network.  
The configuration includes subnetting across multiple hosts, connectivity validation with ping and traceroute, and router forwarding behavior.  
Key aspects include TTL decrement, checksum recomputation, and the longest prefix match rule for routing decisions.  

[Markdown Report](https://github.com/sda667/IP_addressing/blob/main/IP_addressing.md) • [PDF Report](https://github.com/sda667/IP_addressing/blob/main/IP_addressing.pdf)  

---

## Portfolio Overview
These labs demonstrate practical knowledge of networking concepts including transport protocols, congestion control, switching, routing, and IP addressing.  
Each project combines hands-on experiments with theoretical analysis, showcasing applied skills in network analysis and troubleshooting.  

---
