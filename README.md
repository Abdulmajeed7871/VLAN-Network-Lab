## VLAN Network with Inter-VLAN Routing and Security

### Overview
This project demonstrates a network built in Cisco Packet Tracer using VLANs, inter-VLAN routing, DHCP, and access control lists (ACLs).



### Network Design

- VLAN 10 – Engineering (192.168.1.0/26)
- VLAN 20 – HR (192.168.1.64/26)
- VLAN 30 – Sales (192.168.1.128/26)

Each VLAN is assigned its own subnet and default gateway.



### Features Implemented

- VLAN configuration on switch
- Trunk link between switch and router
- Router-on-a-stick (subinterfaces)
- DHCP for automatic IP assignment
- ACL to restrict traffic between VLANs



### Security

An ACL was configured to block communication between selected VLANs.  
For example:

- HR cannot access Engineering  
- Engineering cannot access Sales  



### Testing

Connectivity was tested using ping between devices.

- Inter-VLAN routing works
- ACL rules successfully block restricted traffic



### Key Skills

- VLAN configuration
- Subnetting (/26)
- Inter-VLAN routing
- DHCP configuration
- ACL (network security)
- Cisco CLI
- Troubleshooting
