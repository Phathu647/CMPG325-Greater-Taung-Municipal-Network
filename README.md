# CMPG 325-Greater Taung Local Municipality Network

## Project Overview

This repository contains my individual semester project for CMPG_325 Computer Networks at North-West University.

The project involves designing and simulating a computer network for the **Greater Taung Local Municipality Offices** using Cisco Packet Tracer.

**Project ID:** CMPG325-2026-102
**Client ID:** CLI-102
**Organisation:** Greater Taung Local Municipality Offices (Taung)
**Industry:** Municipal Services
**Assigned Addressing Block:** 172.30.70.0/23

## Project Requirements

The network is designed to:

* Provide appropriate connectivity for the municipal network.
* Allow internal users to communicate and access shared network resources.
* Support critical file, print and application services.
* Provide a server for network services.
* Provide guest Wi-Fi for visitors.
* Isolate guest users from internal municipal resources.
* Use VLANs to logically separate network traffic.
* Use appropriate IP addressing for the different network segments.
* Allow future network expansion.
* Provide routing between the different network sections.

## Assigned Networking Challenge

The assigned networking challenge is:

**Basic OSPF (Single-Area Dynamic Routing)**

OSPF is implemented to provide dynamic routing between the network sections.

## Client Change Request

**CR3: Guest Wi-Fi must be added for visitors and isolated from internal resources.**

The network includes a guest network using **VLAN 20** and a Wireless Access Point for guest connectivity. An ACL is applied to the guest VLAN to prevent guest users from accessing internal municipal network resources.

## Network Design

The network includes:

* R1 - Core Router
* R2 - Branch Router
* SW1 - Internal Switch
* SW2 - Access Switch
* Municipal-Server
* Admin-PC
* Finance-PC
* HR-PC
* Services-PC
* Wireless Access Point
* Guest-Client

The network uses:

* **VLAN 10 - INTERNAL**
* **VLAN 20 - GUEST**
* **OSPF single-area dynamic routing**
* **172.30.70.0/23** addressing block

## Milestone 1

Milestone 1 focused on the Client Design Review and included:

1. Client Requirements
2. Physical Topology
3. Logical Topology
4. IP Addressing Plan
5. Initial GitHub Repository

## Project Evidence

The repository contains evidence of the network design, configuration and testing. This includes:

- Network topology
- Cisco Packet Tracer implementation
- IP addressing information
- VLAN configuration
- Router and switch configuration
- OSPF configuration and verification
- Guest Wi-Fi configuration
- Guest network isolation
- Connectivity testing
- ACL verification
- Troubleshooting evidence

## Tools Used

* Cisco Packet Tracer
* draw.io
* GitHub

## Project Status

**Milestone 2 - Network Implementation and Testing**

The network has been implemented and configured in Cisco Packet Tracer. OSPF single-area dynamic routing has
