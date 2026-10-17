\# Cisco Packet Tracer – Multi-Router Network



\## Project Overview



This project was developed using Cisco Packet Tracer as part of my networking studies at the University of Limerick.



The project demonstrates the configuration and testing of a network containing multiple routers, switches, PCs, and a web server.



The objective was to establish communication between different networks and verify connectivity using networking tools.



\## Technologies Used



\- Cisco Packet Tracer 8.2.2

\- Cisco 2811 Routers

\- Cisco 2950-24 Switches

\- IPv4 Addressing and Subnetting

\- Network Routing

\- ICMP (Ping)

\- HTTP Web Server



\## Network Topology



The simulated network consists of:



\- 3 Cisco routers

\- 5 Cisco switches

\- 6 PCs

\- 1 web server

\- Multiple interconnected networks



The routers connect different subnets, allowing devices to communicate across the network.



\## Network Configuration



The following device configurations were verified during testing:



| Device | IP Address | Subnet Mask | Default Gateway |

|---|---|---|---|

| PC1 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |

| PC4 | 10.1.1.10 | 255.255.255.0 | 10.1.1.1 |

| PC0 | 10.1.2.10 | 255.255.255.0 | 10.1.2.1 |

| Web Server | 24.35.47.91 | 255.255.255.0 | 24.35.47.1 |



\## Connectivity Testing



Network connectivity was tested using the Command Prompt within Cisco Packet Tracer.



The following tests were successful:



\- PC1 successfully communicated with its default gateway.

\- PC1 successfully communicated with PC4 across Router1 and Router2.

\- PC1 successfully communicated with PC0 across three routers.

\- PC1 successfully communicated with the web server on another network.

\- The web server's default webpage was successfully accessed through PC1's web browser using HTTP.



Some initial ping attempts experienced a timeout, but subsequent replies confirmed successful communication.



\## Web Server Testing



The network includes a web server configured with the IP address `24.35.47.91`.



The website was successfully accessed from PC1 using:



`http://24.35.47.91`



This demonstrated that HTTP traffic could travel across the routed network.



\## Skills Demonstrated



\- Understanding of network topologies

\- IPv4 addressing and subnetting

\- Router and switch connectivity

\- Inter-network communication

\- Network connectivity testing

\- Basic network troubleshooting

\- Web server connectivity



\## Project File



`LabAssessment.pkt`



The project can be opened using Cisco Packet Tracer to inspect the network topology, device configurations, and connectivity.



\## Project Context



This project forms part of my practical networking experience while studying BSc Cybersecurity and IT Forensics at the University of Limerick.



It demonstrates foundational networking knowledge relevant to IT infrastructure, network administration, and cybersecurity.

## Network Topology



The network consists of three routers, five switches, six PCs, and one web server.



!\[Cisco Packet Tracer Network Topology](Screenshots/network-topology.png)

