# Design and Implementation of a Secure Healthcare Information Network System

This repository contains the **Design and Implementation of a Secure Healthcare Information Network System** for a multi-floor healthcare organization. The project ensures **secure, scalable, and efficient networking** to support medical services, communication, and data handling.

---

## Project Overview

The healthcare company operates across three floors, handling medical tests and digitizing services for over **2,120 users**. The network architecture integrates **cloud computing**, **wireless networks**, **VoIP systems**, and robust **firewall configurations**, ensuring secure access and reliable communication across departments.

---

## ⚙Technologies and Tools Implemented

The project incorporates the following technologies and tools:

- **Hierarchical Network Design**
- **VLANs** and **Inter-VLAN Routing** (Switch Virtual Interface + Router-on-a-Stick)
- **DHCP Server** configuration for dynamic IP assignments
- **SSH** with Access Control Lists (ACLs) for secure management
- **OSPF** routing protocol
- **HSRP (Hot Standby Router Protocol)** for failover and redundancy
- **Firewall Basic Levels and Zone Configurations**
- **Firewall NAT Configurations**
- **Firewall Default Route Configurations**
- **Firewall Inspection Policies**
- **Standard and Extended ACLs** for traffic control
- **VoIP Configurations** on Cisco Voice Gateway routers
- **Wireless LAN Controller (WLC)** and **Lightweight Access Points** for wireless networking
- **Wireless Network** deployment for staff and guests
- **EtherChannel** using the **LACP method**
- **STP PortFast** and **BPDUguard** for switch security
- **Static IPv4 Addressing** and **Subnetting**
- **Host Configurations** for devices like PCs, IP phones, and servers

---

## Network Components and Structure

### **Floor-Wise Department Setup**
1. **35th Floor**  
   - **Pharmacy & Medical Labs**: ~200 users  
   - **Reception & Guest Area**: ~1,000 users  

2. **36th Floor**  
   - **Doctors & Consultancy**: ~200 users  
   - **Procurement, HR, Finance**: ~300 users  

3. **37th Floor**  
   - **Internal Auditors & Corporate**: ~120 users  
   - **IT Department**: ~300 users (including Network Security, Cloud Engineers, etc.)  

### **IP Address Ranges**
- **WLAN**: 10.10.0.0/16  
- **LAN**: 192.168.0.0/20  
- **Voice**: 172.16.0.0/20  
- **DMZ**: 10.20.20.0/26  
- **Public**: 197.200.100.0  

---

## Security Measures

- **Firewall Configurations**:  
  - NAT for internal to external communication  
  - Zone-Based Firewall Security Policies  
  - Default Routes and Inspection Policies  

- **Access Control**:  
  - Standard & Extended ACLs  
  - SSH Configurations for secure device management  

- **Switch-Level Security**:  
  - **STP PortFast** and **BPDUguard** to prevent broadcast storms  
  - EtherChannel using **LACP** for redundancy  

---

## Testing and Validation

- **Device Communication**: Inter-department VLAN communication  
- **Network Redundancy**: HSRP failover testing  
- **Firewall Policies**: Validating access control and inspection rules  
- **VoIP Services**: Functional testing of IP phones  
- **Wireless Network**: Seamless WLC and LAP connectivity  

