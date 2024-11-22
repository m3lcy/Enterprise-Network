# Enterprise-network
A repository containing the Cisco device configurations for an Enterprise level network.
This network was developed as a redundant branch office enterprise network based in NYC, with multiple failover paths, connecting to the central office network based in SJ through NAT to ensure continuous operation even in the event of a connection failure.
I designed this network with scalability and adaptability in mind, enabling seamless implementation of future modifications. My approach emphasizes adding versatility to networks, whether through integrating automation tools with foundational networking or making necessary adjustments as requirements evolve.

Topology
![image](https://github.com/user-attachments/assets/49cecf76-4037-4892-84eb-3b784890f3b4)


There is the Cisco IOS version and the Ansible automation version of the network configuration.
This network comprises of L2/L3 networking protocols which consists of:
- IP ROUTE 
- STP
- VTP
- VLAN
- TRUNKING
- SSH
- HSRP
- NAT
- OSPF
- RIP
- DHCP (DHCP can be done on the server, router or layer 3 switch, in this case I did it on the router)
- ACL

Prerequisites for running the Ansible playbook:
- Python installed
- Ansible installed
- Inventory file
- SSH Access to device


