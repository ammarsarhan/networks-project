# Enterprise Network Design - OSPF, BGP & SDN

## Overview
A medium-scale enterprise network implemented in **Cisco Packet Tracer** integrating OSPF multi-area routing, BGP external connectivity, and SDN-based centralized control.

## Problem Statement
Traditional flat networks suffer from poor scalability and high routing overhead. This project addresses these challenges through hierarchical routing (OSPF), policy-based inter-domain routing (BGP), and centralized SDN control.

## Technologies
- **OSPF Multi-Area** - Hierarchical internal routing with Area 0 backbone
- **BGP** - External connectivity to ISP network
- **SDN/OpenFlow** - Centralized network control segment
- **Cisco Packet Tracer** - Network simulation platform

## Requirements Met
✅ Multiple OSPF areas including backbone (Area 0)  
✅ OSPF multi-area routing for internal communication  
✅ BGP implementation for ISP connectivity  
✅ SDN-controlled segment with OpenFlow switches  
✅ End-to-end connectivity verification  
✅ Link and node failure handling  

## Files
- `Final Project.pkt` - Main Packet Tracer file
- Device configuration exports
- Testing and verification results

## Testing
- Connectivity verification using ping/traceroute
- OSPF area communication tests
- BGP route advertisement validation
- Failure scenario simulations (link/node failures)
- SDN flow table verification

---
*Academic project - Designed purely in Cisco Packet Tracer*