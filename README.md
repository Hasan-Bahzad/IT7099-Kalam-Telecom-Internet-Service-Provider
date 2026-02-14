# IT7099-Kalam-Telecom-Internet-Service-Provider
This repository contains the full design, configuration, and documentation of a simulated MPLS service provider network built in EVE-NG.

The project includes customer sites, a service provider backbone (Kalam Telecom), and external connectivity to Batelco. It demonstrates MPLS, MPLS VPN, routing protocols, security controls.

---

## What is included in this repository 

### 1) Network Configurations
This section includes all device configuration used in the topology
- Full CLI configurations
- Device-specific configuration files
- Routing protocol configuration
- MPLS and MPLS L3VPN configuration
- Security controls (Access Control List, Route-Maps)
- Verification commands (show run, show ip route)
- Devices included:
   - Customer Sites
   - Kalam Telecom Sites (MPLS Backbone and internal network)
   - Batelco Site

### 2) EVE-NG Topology File
- Complete .unl lab file
- Ready-to-import EVE-NG topology

### 3) Network Design Documentation
- **Network Topology**— Visual map of the project. 
- IP Addressing Plan
- Network Design Documentation

### 4) Reports
Includes all the academic reports and documentation produced throughout the project:
- Thesis
- Project Charter
- Project Plan
- Demonstration PPT

![Netowrk Topology](Topology.png)

## Purpose

The goal of this project is to demonstrate real-world carrier-grade ISP routing with MPLS:
- Scalable routing protocols (OSPF, EIGRP, MP-BGP)
- Label Switching Technique (MPLS)
- Inter-AS MPLS VPN Network
- IP addressing

## How to Use This Repository 

**If you’re studying or reviewing this project:**
1. Open the **Network Topology** diagram to understand Infrastructure layout.
2. Import the EVE-NG .unl file into your EVE-NG environment.
3. Laod the provided device configuration.
4. Compare your own setup against the configs in the Repository.

## Recommended Tools

- **EVE-NG** for topology/simulation
- Cisco CLI (IOL)  
- Ping, traceroute, and **show/debug** commands for verification

## Author
Hasan Bahzad (202001980) a networking student at Bahrain Polytechnic
