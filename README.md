# Secure Financial Multi-Branch Banking Hub 🏦🔐

This project simulates a secure banking network environment using Cisco Packet Tracer.  
The network consists of an HQ router, two branch routers, and a central bank router connected through static routing and secured VPN tunnels.

Each branch is divided into separate VLANs for ATMs and Tellers to improve security and traffic isolation.  
VLSM is used to allocate IP addresses efficiently without wasting address space.  
Local routers provide DHCP services for teller devices, while DNS is used to resolve the internal banking web server using a `.bank` domain.

The project also implements NAT to hide internal private IP addresses, ACLs to restrict unauthorized communication between VLANs, and ICMP tests to verify WAN connectivity and network reliability.

## Key Features

- Multi-branch banking network design
- VLAN segmentation for ATMs and Tellers
- VLSM-based IP addressing
- DHCP configuration for teller networks
- Internal DNS server with `.bank` domain
- Internal banking web server
- Static routing between 4 routers
- VPN tunnels for secure inter-branch communication
- NAT for hiding internal IP addresses
- ACLs for traffic filtering and security
- ICMP connectivity and stress testing
