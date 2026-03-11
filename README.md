
## Project Title: Multi-VLAN Campus Network with Inter-VLAN Routing
Overview
This project demonstrates the implementation of a scalable Local Area Network (LAN) using Cisco Packet Tracer. It features two Layer 3 switches (Cisco 3650) supporting multiple departments via VLAN segmentation and high-speed trunking.

Core Features
VLAN Segmentation: Created VLAN 10 (Sales) and VLAN 20 (Marketing) to logically isolate broadcast domains.

802.1Q Trunking: Configured a trunk link on GigabitEthernet1/0/24 between Switch0 and Switch1 to carry multi-VLAN traffic.

Inter-VLAN Routing: Enabled the Layer 3 routing engine (ip routing) and Switched Virtual Interfaces (SVIs) to allow communication between subnets.

Layer 3 Switching: Utilized Cisco 3650 multilayer switches for hardware-based routing, reducing latency compared to "Router-on-a-Stick" configurations.

| Department | VLAN ID | Subnet | Gateway (SVI) |
| Sales | 10 | 192.168.10.0/24 | 192.168.10.1 |
| Marketing | 20 | 192.168.20.0/24 | 192.168.20.1 |
