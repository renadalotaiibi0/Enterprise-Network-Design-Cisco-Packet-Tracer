
# Enterprise Network Design – Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the design and simulation of a multi-subnet enterprise network using Cisco Packet Tracer.

The network connects two departments through Cisco routers and switches, incorporating essential network services such as DHCP, DNS, Web, and Email.

The project focuses on IP addressing, subnetting, routing, network configuration, and connectivity testing.

## 🖥️ Network Topology

The network consists of two interconnected LANs, connected through a point-to-point router link.

![Network Topology](Screenshot%201448-05-30%20at%209.04.05%20PM.png)

## 🛠️ Technologies & Tools

- Cisco Packet Tracer
- TCP/IP Networking
- IPv4 Addressing
- Subnetting
- Routing and Switching
- DHCP (Dynamic Host Configuration Protocol)
- DNS (Domain Name System)
- HTTP (Web Services)
- Email Services
- Network Connectivity Testing

## 🌐 Network Architecture

### Department 1 – Main Network

- Network Address: 192.168.1.0/26
- Subnet Mask: 255.255.255.192
- Default Gateway: 192.168.1.1
- Devices: Router, Switch, Admin PC
- Servers: DHCP, DNS, Web, Email

### Department 2 – Remote Network

- Network Address: 192.168.3.0/25
- Subnet Mask: 255.255.255.128
- Default Gateway: 192.168.3.1
- Devices: Router, Switch, and three PCs

### Router-to-Router Connection

- Network Address: 192.168.2.0/30
- Subnet Mask: 255.255.255.252
- Router 1: 192.168.2.1
- Router 2: 192.168.2.2

## 🖧 Network Components

| Device | Quantity |
|---|---|
| Cisco 1841 Routers | 2 |
| Cisco 2960 Switches | 2 |
| DHCP Server | 1 |
| DNS Server | 1 |
| Web Server | 1 |
| Email Server | 1 |
| PCs | 4 |

## ✅ Network Testing

### DHCP Configuration

Madawi PC obtained its IPv4 configuration via DHCP.

Assigned Network Configuration:
- IP Address: 192.168.3.4
- Subnet Mask: 255.255.255.128
- Default Gateway: 192.168.3.1
- DNS Server: 192.168.1.3

![DHCP Test](Screenshot%201448-05-30%20at%209.04.00...png)

### Connectivity Test

Successful ping from Atheer PC to 192.168.1.1, with 0% packet loss.

Test Results:
- Packets Sent: 4
- Packets Received: 4
- Packets Lost: 0
- Packet Loss: 0%
- Status: Successful

![Ping Test](Screenshot%201448-05-30%20at%209.27.10%20PM.png)

## 🎯 Project Objectives

- Design a structured network connecting two departments.
- Configure IPv4 addressing and subnetting.
- Connect multiple LANs using Cisco routers.
- Configure essential network services.
- Implement automatic IPv4 configuration using DHCP.
- Verify network connectivity using ping tests.
- Practice network troubleshooting and configuration.

## 🚀 How to Run the Project

1. Install Cisco Packet Tracer.
2. Download the PROJECT-IT1340-1-25-26.pkt file.
3. Open the file using Cisco Packet Tracer.
4. Explore the network topology and device configurations.
5. Test connectivity using the PC Command Prompt.
6. Review the configured network services.

## 📚 Skills Demonstrated

Network Design • Cisco Packet Tracer • IPv4 • Subnetting • Routing • Switching • DHCP • DNS • Troubleshooting • Network Testing

---

**Academic Networking Project | Cisco Packet Tracer**
