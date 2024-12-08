# Automated High-Availability Deployment Infrastructure
A repository containing the Cisco device configurations for an Enterprise Wide Area Network (WAN).
This network was developed as a redundant branch office in NYC, with multiple failover paths, connecting to the central office network based in SJ through NAT to ensure continuous operation even in the event of a connection failure.
I designed this network with scalability, redundancy and reliability in mind, enabling seamless implementation of future modifications. 

This network will undergo regular updates to accommodate continuous improvements and evolving requirements, ensuring its capabilities remain adaptable and limitless.

Figure 3.11: Main Topology

![image](https://github.com/user-attachments/assets/29e34b99-1105-413d-b282-71f13fa60433)


Figure 3.12: VLAN Segmentation - High Performance Computing VLANs

![image](https://github.com/user-attachments/assets/f2408ec4-0ca7-4c90-9eff-c22db12c8574)



Figure 3.13: VLAN Segmentation - General Access VLANs

![image](https://github.com/user-attachments/assets/6fe4f79a-0f5d-4777-b47a-89dee45562ee)




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


