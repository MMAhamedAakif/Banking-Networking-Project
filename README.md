# 🏦 Enterprise Networking Project #5 – Banking and Insurance

### Multi-Floor Enterprise Network Infrastructure | Cisco Packet Tracer

## 📌 Project Overview
<img width="2638" height="2114" alt="P8" src="https://github.com/user-attachments/assets/1d219c89-b1f2-48fb-bbf4-2574d3b048d5" />


This project focuses on designing and implementing a multi-floor enterprise network infrastructure for a Banking and Insurance organization using Cisco Packet Tracer.

The network is designed to connect different departments across four floors, providing secure departmental segmentation, centralized network services, reliable communication, and network redundancy.

The infrastructure includes interconnected routers, multilayer switches, access switches, wireless access points, network printers, end-user devices, and centralized servers.

## 🏢 Network Architecture

The enterprise network consists of four floors with 12 departmental VLANs.

### 🟦 First Floor – Management & Research

| VLAN ID | Department |
|---|---|
| VLAN 10 | Management |
| VLAN 20 | Research |
| VLAN 30 | Human Resource |

### 🟩 Second Floor – Business Operations

| VLAN ID | Department |
|---|---|
| VLAN 40 | Marketing |
| VLAN 50 | Accounting |
| VLAN 60 | Finance |

### 🟪 Third Floor – Customer & Logistics

| VLAN ID | Department |
|---|---|
| VLAN 70 | Logistics |
| VLAN 80 | Customer |
| VLAN 90 | Guest |

### 🟧 Fourth Floor – Administration & IT Infrastructure

| VLAN ID | Department |
|---|---|
| VLAN 100 | Admin |
| VLAN 110 | ICT |
| VLAN 120 | Server Room |

## 🌐 Network Topology

The network design includes:

- Four-floor enterprise network infrastructure.
- Multiple interconnected routers.
- Core and access switching infrastructure.
- Department-based VLAN segmentation.
- Redundant network connections.
- Dedicated centralized server room.
- Wired and wireless network connectivity.

## 🛠️ Technologies & Devices Used

### Networking Technologies
- Cisco Packet Tracer
- Virtual LAN (VLAN)
- Inter-VLAN Routing
- Trunking
- Layer 3 Switching
- Network Redundancy
- Router-to-Router Connectivity
- Network Troubleshooting

### Network Devices
- Cisco 2911 Routers
- Cisco 3560 Multilayer Switches
- Cisco 2960 Access Switches
- Wireless Access Points
- Desktop Computers
- Laptops
- Network Printers
- Servers

## ⚙️ Key Network Features

### 1. VLAN Segmentation
Implemented 12 VLANs to separate organizational departments across four floors, improving network organization and traffic management.

### 2. Inter-VLAN Routing
Designed Layer 3 network connectivity to enable communication between different departmental VLANs.

### 3. Network Redundancy
Designed multiple network connections between switching devices to provide alternative communication paths and improve network availability.

### 4. Router Interconnection
Connected multiple routers to establish communication between different sections of the enterprise network.

### 5. Centralized Server Infrastructure

Implemented a dedicated server room using VLAN 120, containing:

- **DHCP Server:** Automatic IP address allocation.
- **DNS Server:** Domain name resolution.
- **Mail Server:** Organizational email communication.
- **HTTPS Server:** Secure web services.

### 6. Wireless Connectivity
Integrated wireless access points to provide wireless connectivity for laptops and other wireless devices.

### 7. Network Resource Sharing
Included network printers and end-user devices to support departmental resource sharing.

## 🧪 Network Testing & Verification

The following commands and tests can be used to verify the network:

| Command / Test | Purpose |
|---|---|
| `show vlan brief` | Verify VLAN configuration |
| `show interfaces trunk` | Verify trunk connections |
| `show ip interface brief` | Check interface status |
| `show ip route` | Verify routing information |
| `show spanning-tree` | Examine STP operation |
| `ping` | Test network connectivity |
| DHCP Testing | Verify automatic IP allocation |
| DNS Testing | Verify domain name resolution |
| Link Failure Testing | Examine network redundancy |

## 🎯 Project Objectives & Learning Outcomes

- Designed a multi-floor banking and insurance network infrastructure.
- Implemented 12 departmental VLANs.
- Practiced Layer 2 and Layer 3 networking concepts.
- Designed redundant network connections.
- Configured router and switch interconnections.
- Integrated centralized network services.
- Practiced enterprise network architecture and troubleshooting.

## 📁 Project Files

| File | Description |
|---|---|
| `Banking-Insurance-Project-05.pkt` | Cisco Packet Tracer project |
| `topology.png` | Complete network topology |
| `README.md` | Project documentation |
| `Configurations/` | Device configuration files |
| `Screenshots/` | Network testing evidence |

## 💻 Software Used

**Cisco Packet Tracer**

## 👨‍💻 Project Category

Enterprise Networking | Banking & Insurance | Network Infrastructure Design

---

**Project #05 – Banking and Insurance**

*Designing a structured, scalable, and reliable enterprise network infrastructure.*
