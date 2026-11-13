# Network Security Project

## Project Overview
This project involved improving the security of an existing company network using Cisco Packet Tracer. The network connected three locations: Dublin headquarters, a London data centre and a Beijing home office.

The aim was to protect network devices, control access and secure communication between the different locations.

## Tools and Technologies
- Cisco Packet Tracer
- Cisco routers and switches
- SSH Version 2
- AAA and RADIUS authentication
- Syslog and NTP
- OSPF authentication
- NAT and access control lists (ACLs)
- WPA2 wireless security

## What I Did
I configured and tested several security controls across the network.

### 1. Network Device Hardening
I secured router administration using encrypted passwords, administrator accounts, warning banners and automatic session timeouts.

### 2. Secure Remote Access
I configured SSH to allow encrypted remote management of network devices.

### 3. AAA Authentication
I configured centralized RADIUS authentication for the Dublin and London routers and tested administrator login.

### 4. Network Monitoring
I configured Syslog for central logging and NTP for time synchronization.

### 5. Network and Firewall Security
I configured OSPF authentication, switch port security, NAT and ACL-based firewall rules. The firewall rules separated the Sales and Purchasing networks.

### 6. Wireless Security
I configured WPA2 Personal with AES encryption for the Beijing wireless network.

## Testing and Results
I tested the security configurations to check whether they worked correctly.

- Traffic between the Sales and Purchasing networks was blocked in both directions.
- Permitted connections to the local gateway continued working.
- SSH and AAA authentication allowed authorized remote access to the London router.
- NAT translations and OSPF neighbour connectivity were verified.

## Skills Developed
- Network security configuration
- Cisco router and switch administration
- Firewall rules and network segmentation
- Authentication and access control
- Troubleshooting and security testing
- Technical documentation

## Project Evidence
The project report includes configuration screenshots, security testing results and explanations of the controls implemented.

Supporting evidence will be added after sensitive credentials have been removed.

[View My Network Security Report](Network_Security_Report.pdf)
