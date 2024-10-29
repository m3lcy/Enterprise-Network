# Enterprise-network
A repository containing the Cisco device configurations for an Enterprise level network.
This network was developed as a redundant branch office enterprise network based in NYC, with multiple failover paths, connecting to the main office network based in SJ through NAT to ensure continuous operation even in the event of a connection failure.
There is the Cisco IOS version and the Ansible automation version of the network configuration.
This network comprises of L2/L3 networking protocols which consists of:
- IP ROUTE 
- STP
- VTP
- VLAN
- TRUNKING
- HSRP
- NAT
- OSPF
- RIP
- DHCP
- ACL

Prerequisites for running the Ansible playbook:
- Python installed
- Ansible installed
- Inventory file
- SSH Access to device
