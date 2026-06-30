# Multi-Site-Networking-lab
This enterprise networking lab demonstrates a number of useful Cisco networking concepts, including VLAN segmentation, inter-VLAN routing, OSPF dynamic routing, DHCP relay, centralized network services, SSH hardening, ACL implementation, and port security. This project uses Cisco Packet Tracer to mimic a secure multi-site enterprise network. Layer 2 and Layer 3 networking technologies, such as VLAN segmentation, inter-VLAN routing, dynamic routing using OSPF, centralized DHCP and DNS services, SSH hardening, Access Control Lists, and switch port security, are demonstrated in the environment.

Designing, configuring, securing, and verifying a production-style network that exhibits useful networking and troubleshooting abilities was the aim of this lab.
# Technologies Used
Cisco Packet Tracer  
Cisco ISR Routers  
Cisco Catalyst Layer 3 Switch  
Cisco Catalyst Layer 2 Switches  
OSPF Area 0  
VLANs  
Inter-VLAN Routing  
IP Helper  
DNS  
HTTP  
SSHs  
Access Control Lists  
Port Security  
Network Architecture  
VLANs

# VLAN	Department	Network
10	IT	192.168.10.0/24  
20	HR	192.168.20.0/24  
30	Servers	192.168.30.0/24  
99	Management	192.168.99.0/24  

# WAN
R1 ↔ R2  
10.0.0.0/30  

# Remote Site
172.16.1.0/24  
# Features Implemented
Multi-site enterprise topology  
VLAN segmentation  
Inter-VLAN routing  
OSPF dynamic routing  
DHCP relay using IP Helper  
Centralized DHCP server  
DNS server  
HTTP server  
SSH-only device management  
Port Security  
Extended ACLs  
Management VLAN  
WAN security ACL  
Switch hardening  

# Verification

The network was fully validated by confirming:  

Successful DHCP address assignment  
OSPF neighbor relationships  
Dynamic route learning  
Inter-VLAN connectivity  
Remote site connectivity  
DNS resolution  
HTTP access  
SSH remote management  
ACL enforcement  
Port Security functionality  
Skills Demonstrated  
Enterprise Network Design  
Cisco IOS Configuration  
Routing & Switching  
Network Security  
OSPF  
VLAN Design  
Network Troubleshooting  
Infrastructure Hardening  
DHCP & DNS Administration  
