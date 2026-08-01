# Infinity Core Enterprise Network

Enterprise network infrastructure designed and implemented using **Cisco Packet Tracer**.

---

## Project Overview

This project simulates a real enterprise network consisting of:

- Headquarters (HQ)
- Cairo Branch
- Alexandria Branch
- Data Center
- ISP Core Network

The network is designed to provide high availability, secure management, centralized services, and scalable routing.

---

## Network Topology

![Topology](screenshots/topology.png)

---

## Technologies Used

- Cisco Packet Tracer
- Multi-Area OSPF
- VLAN Segmentation
- Inter-VLAN Routing (SVIs)
- HSRP Redundancy
- EtherChannel
- VTP
- DHCP
- DHCP Relay
- DNS
- HTTP
- FTP
- Email Server
- SSH
- Port Security
- ACLs
- NTP

---

## Network Design

### Headquarters

| VLAN | Department | Network |
|------|------------|----------------|
|10|IT|10.0.0.0/15|
|20|HR|10.2.0.0/15|
|30|Finance|10.4.0.0/15|
|40|Sales|10.6.0.0/15|
|50|Management|10.8.0.0/15|

### Cairo Branch

| VLAN | Department | Network |
|------|------------|----------------|
|30|Finance|10.16.0.0/15|
|40|Sales|10.18.0.0/15|
|50|Management|10.20.0.0/15|

### Alexandria Branch

| VLAN | Department | Network |
|------|------------|----------------|
|30|Finance|10.32.0.0/15|
|40|Sales|10.34.0.0/15|
|50|Management|10.36.0.0/15|

### Data Center

| VLAN | Service | Network |
|------|---------|----------------|
|100|Servers|10.48.0.0/15|

---

## Features

- Multi-Area OSPF Routing
- HSRP Gateway Redundancy
- Layer 3 Switching
- VLAN Segmentation
- Inter-VLAN Routing
- EtherChannel
- VTP
- Centralized DHCP
- DNS Resolution
- Internal Web Server
- FTP Server
- Email Services
- Secure SSH Remote Access
- Port Security
- ACL-based Access Control
- NTP Time Synchronization

---

## Verification

### OSPF

![OSPF](screenshots/ospf-neighbors.png)

### HSRP

![HSRP](screenshots/hsrp-status.png)

### EtherChannel

![EtherChannel](screenshots/etherchannel-summary.png)

### Routing Table

![Routing](screenshots/routing-table.png)

### VLANs

![VLANs](screenshots/vlan-configuration.png)

### SSH

![SSH](screenshots/ssh-test.png)

### DHCP

![DHCP](screenshots/dhcp-test.png)

### Web Server

![Web](screenshots/web-server-test.png)

### FTP

![FTP](screenshots/ftp-test.png)

### ACL

![ACL](screenshots/management-acl.png)

---

## Skills Demonstrated

- Enterprise Network Design
- IP Address Planning
- Dynamic Routing (OSPF)
- First Hop Redundancy (HSRP)
- Layer 2 & Layer 3 Switching
- Network Security
- Network Services Deployment
- Troubleshooting

---

## Author

**Mohamed Amr**

Faculty of Computers and Artificial Intelligence, Cairo University

CCNA Certified

Interested in Cloud Computing, Networking, and Cybersecurity.
