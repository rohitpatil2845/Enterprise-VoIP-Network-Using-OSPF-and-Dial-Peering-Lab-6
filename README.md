# Enterprise-VoIP-Network-Using-OSPF-and-Dial-Peering-Lab-6
## Overview

Designed and implemented a VoIP-enabled enterprise network in Cisco Packet Tracer for four departments: Finance, HR, Sales, and ICT.

The project combines data and voice communication using VLANs, Router-on-a-Stick, OSPF, DHCP, Cisco CME, and Dial Peering.

## Technologies Used

- VLAN & Voice VLAN
- Router-on-a-Stick (ROAS)
- DHCP
- OSPF
- Cisco CME
- Dial Peering
- SSH
- DNS, HTTP, DHCP, and Email Servers

## Network Design

| Department | Data VLAN | Network |
|------------|------------|----------|
| Finance | 10 | 192.168.100.0/27 |
| HR | 20 | 192.168.100.32/27 |
| Sales | 30 | 192.168.100.64/27 |
| ICT | 40 | 192.168.100.96/27 |
| Servers | 50 | 192.168.100.128/29 |

Voice VLAN: VLAN 100 (172.16.100.0/24)

## Tasks Performed

- Created Data and Voice VLANs
- Configured Router-on-a-Stick for inter-VLAN routing
- Configured DHCP for PCs and IP Phones
- Implemented OSPF routing between routers
- Configured Cisco CME for IP Telephony
- Assigned phone extensions for each department
- Configured Dial Peering for inter-department calls
- Enabled SSH remote access
- Connected DNS, HTTP, DHCP, and Email servers

## Verification Commands
show ip interface brief
show vlan brief
show ip route
show ip ospf neighbor
show ephone registered
show dial-peer voice summary

## Results

- Successful inter-VLAN communication
- OSPF routing working correctly
- IP Phones registered successfully
- Voice calls between departments working
- Servers accessible from all departments
- SSH remote login functioning properly

## Key Learnings

- Voice VLAN implementation
- Cisco CME configuration
- Dial Peering concepts
- OSPF routing
- Integration of voice and data networks
- Enterprise VoIP deployment basics
