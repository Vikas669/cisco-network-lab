
# Cisco Multi-Router Network Simulation (Packet Tracer)

## Overview
This project demonstrates the design and simulation of a multi-router network using Cisco Packet Tracer. The topology consists of five routers connected in a linear WAN structure, where each router connects to a local LAN via a switch. Each LAN contains two PCs, and the final LAN also includes a server. Static routing is configured to enable communication across all networks.

---

## Topology Description
- 5 Cisco routers interconnected through WAN links
- Each router connected to a 2950T switch
- Each switch connected to two PCs
- Final LAN includes a server connected to the switch
- End-to-end connectivity verified across all LANs

---

## Network Addressing

### LAN Subnets
- LAN1: 192.168.1.0/24  
- LAN2: 192.168.2.0/24  
- LAN3: 192.168.3.0/24  
- LAN4: 192.168.4.0/24  
- LAN5: 192.168.5.0/24  

Switch management IP in each LAN:
- 192.168.1.1  
- 192.168.2.1  
- 192.168.3.1  
- 192.168.4.1  
- 192.168.5.1  

PCs assigned within respective subnets (e.g., .2, .3)

Server IP:
- 192.168.5.x subnet (LAN5)

---

### WAN Links Between Routers
- R1–R2: 12.1.1.0/30  
- R2–R3: 13.1.1.0/30  
- R3–R4: 14.1.1.0/30  
- R4–R5: 15.1.1.0/30  

---

## Configuration Highlights
- Static routing configured on all routers
- Proper default gateway assignment in each LAN
- IP addressing for all router interfaces
- Switch-to-router and PC-to-switch connectivity
- Server added in final LAN segment

---

## Verification
- Successful ping between PCs across different LANs
- End-to-end connectivity from LAN1 to LAN5
- Server reachable from all networks

---

## Tools Used
- Cisco Packet Tracer
- Cisco Routers (2811, 2911)
- Cisco Switch 2950T
- PCs and Server (End Devices)

---

## Files
- Multi-router topology (.pkt)
- Network topology screenshot

---

## Learning Outcome
- Multi-router WAN design
- Static routing configuration
- Subnet segmentation
- LAN/WAN integration
- Client-server communication across networks
