# Office Network with NAT & Security
A final-year Computer Engineering project simulating a real-world enterprise environment.

## 🛠 Tech Stack
* **Software:** Cisco Packet Tracer / GNS3
* **Protocols:** NAT/PAT, DHCP, IEEE 802.1Q (VLANs), OSPF/Static Routing
* **Security:** ACLs, WPA2 Enterprise

## 📋 IP Addressing Plan
| VLAN | Department | Subnet | Gateway |
| :--- | :--- | :--- | :--- |
| 10 | Staff | 192.168.10.0/24 | 192.168.10.1 |
| 20 | Guest/Wi-Fi | 192.168.20.0/24 | 192.168.20.1 |
| 99 | Management | 192.168.99.0/24 | 192.168.99.1 |
