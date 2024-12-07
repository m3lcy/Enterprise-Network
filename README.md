# Automated High-Availability Deployment Infrastructure
A repository containing the Cisco device configurations for an Enterprise Wide Area Network (WAN).
This network was developed as a redundant branch office in NYC, with multiple failover paths, connecting to the central office network based in SJ through NAT to ensure continuous operation even in the event of a connection failure.
I designed this network with scalability, redundancy and reliability in mind, enabling seamless implementation of future modifications. My approach emphasizes adding versatility to networks, whether through integrating automation tools with foundational networking or making necessary adjustments as requirements evolve.

This network will undergo regular updates to accommodate continuous improvements and evolving requirements, ensuring its capabilities remain adaptable and limitless.

Figure 3.11: Main Topology

![image](https://github.com/user-attachments/assets/e9140b4a-3b1c-4658-8e4c-6000ed93a904)


Figure 3.12: VLAN Segmentation - High Performance Computing VLANs

![image](https://github.com/user-attachments/assets/4677ca6d-7053-42f2-946f-7ca98d3e470e)


Figure 3.13: VLAN Segmentation - General Access VLANs

![image](https://github.com/user-attachments/assets/db1d544d-d8be-4df7-81c5-bc31c7718a82)



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
- DHCP (DHCP can be done on the router or L3 Switch and server, in this case I did it on the router)
- ACL
- QOS

Prerequisites for running the Ansible playbook:
- Python installed
- Ansible installed
- Inventory file
- SSH Access to device


