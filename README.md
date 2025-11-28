🖧 Dual-Enterprise Network Infrastructure
Advanced Cisco Configuration Project

This project showcases the design, configuration, and deployment of a dual-enterprise network using advanced Cisco routing, switching, and security mechanisms. The goal is to simulate a realistic multi-site enterprise topology with redundancy, scalability, and security at every layer.

🖼️ Network Topology – Full Views
🔹 Global Topology Overview

🔹 Enterprise A – Topology

🔹 Enterprise B – Topology

🔹 Mid Network / Interconnection Area

🧩 Core Switch & Routing Configuration Views
🔹 Enterprise A – Core Switches

EA Core 1
![EA CORE 1](./EA CORE 1.jpg)

EA Core 2
![EA Core 2](./Core EA 2.jpg)

🔹 Enterprise B – Core Switches

EB Core 1
![EB Core 1](./Core EB CORE 1.jpg)

EB Core 2
![EB Core 2](./Core EB 2.jpg)

🖥️ DHCP Server Configuration
🔹 Enterprise A DHCP

![EA DHCP](./EA DHCP.jpg)

🔹 Enterprise B DHCP

![EB DHCP](./EB DHCP.jpg)

🚀 Project Overview

This lab implements a full Core–Distribution–Access architecture across two interconnected enterprises.
Each enterprise uses VLAN segmentation, HSRP gateway redundancy, OSPF multi-area routing, DHCP services, and Layer 2 security.

The interconnection between both enterprises uses secure OSPF authentication and controlled routing.

🔧 Technologies Implemented
Layer 2 Switching

VLAN segmentation (Sales, HR, IT, Management, Guest)

VTP for centralized VLAN propagation

DTP for dynamic trunk negotiation

PVST+ (Per-VLAN Spanning Tree)

EtherChannel (LACP/PAgP)

Port Security on access ports

STP security (BPDU Guard, PortFast, Root Guard)

Routing & Redundancy

Inter-VLAN routing (SVIs)

OSPF Multi-Area

Static routes for backup paths

HSRP gateway redundancy

OSPF MD5 authentication

Network Services

Centralized DHCP pools

DHCP Snooping

SSH for secure device management

AAA for access control

📂 Repository Contents
Dual-Enterprise Network Infrastructure  Advanced Cisco Configuration Project.pkt   → Main topology file
FullView.jpg                                                               → Global full topology
EA.jpg                                                                     → Enterprise A topology
EB.jpg                                                                     → Enterprise B topology
Mid.jpg                                                                    → Interconnection area
Core EA CORE 1.jpg / Core EA 2.jpg                                         → EA core switch configs
Core EB CORE 1.jpg / Core EB 2.jpg                                         → EB core switch configs
EA DHCP.jpg / EB DHCP.jpg                                                  → DHCP server configuration
README.md                                                                  → Project documentation

▶️ How to Use This Project

Download the .pkt file from this repository

Open it in Cisco Packet Tracer

Verify:

OSPF area adjacency

HSRP failover

DHCP IP allocation

Port Security behavior

SSH & AAA authentication

Explore configuration logic using the included screenshots

🔮 Future Enhancements

Add BGP between enterprises

Introduce IPSec VPN

Implement Syslog, SNMP, and NetFlow monitoring

Add IPv6 across both enterprises

👨‍💻 Author

Adib
IT Specialist – Systems & Networks
Passionate about enterprise network design, Cisco technologies, and infrastructure engineering.
