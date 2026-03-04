# Smart-Enterprise-Multi-Area-Network-Design
This project represents a complete enterprise-level network simulation designed using Cisco Packet Tracer.
The network simulates a multi-department organization with:

Multi-area OSPF routing

VLAN segmentation

Centralized services (DNS, DHCP, HTTP, Email, FTP)

Firewall security

Inter-department connectivity

Hierarchical network architecture

The objective of this project is to demonstrate real-world enterprise network design principles including scalability, redundancy, and segmentation.

🏗️ Network Architecture

The topology is divided into multiple colored zones representing different departments and OSPF areas.

🔹 Core Features

🧭 OSPF Multi-Area Routing

🖧 VLAN Segmentation

🌐 Centralized Server Farm

🔐 ASA Firewall Implementation

📡 Inter-VLAN Routing

📬 Email + DNS + HTTP + FTP Services

🖥️ Wired & Wireless Clients

🖨️ Printer & IoT Devices Simulation

🗺️ Network Topology

<img width="1636" height="731" alt="image" src="https://github.com/user-attachments/assets/1813192b-73ab-4f7c-a1de-3dbe2cf8aa1f" />



🌍 OSPF Design

Area 0 → Core Backbone

Area 1 → Department A

Area 2 → Department B

Area 3 → Server Zone

Area 4 → Remote Branch

The backbone area ensures stable routing and optimal path selection between departments.

🖥️ Server Infrastructure

Located in the Server Farm zone:

DNS Server

DHCP Server

HTTP Server

FTP Server

Email Server

All internal networks can resolve domain names and access centralized services.

🔐 Security Implementation

ASA Firewall configured between internal network and external zone

Network segmentation using VLANs

Access control between departments

NAT configuration for external communication

📊 IP Addressing Scheme

The network uses structured subnetting:

192.178.x.0/24 per department

Dedicated subnet for servers

Separate WAN subnets for router interconnections

🎯 Project Objectives

Apply enterprise-level routing protocols

Implement secure network segmentation

Simulate real-world organizational infrastructure

Demonstrate scalable and modular network design

🛠️ Technologies Used

Cisco Packet Tracer

OSPF Routing Protocol

VLAN Configuration

ASA Firewall

DHCP / DNS / HTTP / FTP Services

🚀 How to Run

Download the .pkt file

Open using Cisco Packet Tracer (version X or later)

Wait for routing convergence

Test:

Ping between departments

DNS resolution

HTTP access

Email sending

FTP file transfer

📌 Future Improvements

Implement Network Automation using Python

Add SNMP Monitoring

Add VPN between branches

Convert simulation to GNS3 for advanced configuration

👨‍💻 Author

 Name:Ebrahem Elgharib Mohamed amer
 Network Engineering Student
 Aspiring MSc Candidate in Computer Networks
