# Network Fundamentals — TryHackMe

**Platform:** TryHackMe  
**Path:** Pre-Security  
**Difficulty:** Easy  
**Category:** Networking  
**Status:** Completed  
**Date:** April 2026  

---

## Objective
Introduction to core networking concepts including the OSI model,
TCP/IP protocols, and how data travels across networks.

---

## Key Concepts Learned

### OSI Model
- Layer 1 Physical — cables, hardware
- Layer 2 Data Link — MAC addresses, switches
- Layer 3 Network — IP addresses, routers
- Layer 4 Transport — TCP/UDP, ports
- Layer 5 Session — connections between devices
- Layer 6 Presentation — encryption, formatting
- Layer 7 Application — HTTP, FTP, DNS

### TCP vs UDP
- TCP — reliable, connection-oriented, three-way handshake
- UDP — fast, connectionless, no guarantee of delivery

### Key Protocols
- HTTP/HTTPS — web traffic (ports 80/443)
- DNS — domain name resolution (port 53)
- SSH — secure remote access (port 22)
- FTP — file transfer (port 21)

---

## Tools Used
- None (theoretical room)

---

## Key Learnings
- Understanding how data travels through network layers
- Difference between TCP and UDP and when each is used
- How DNS resolves domain names to IP addresses
- Importance of ports in network communication

---

## How This Applies to Security
- Knowing which ports are commonly open helps during reconnaissance
- Understanding TCP handshake is essential for port scanning with Nmap
- DNS knowledge is critical for OSINT and network mapping

---
*Write-up by Juan Esteban Umana Machado — linkedin.com/in/juanesumaa11*