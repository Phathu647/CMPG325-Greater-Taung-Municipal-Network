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

##Assigned Networking Challenge

The assigned networking challenge is:

**Basic OSPF (Single-Area Dynamic Routing)**

OSPF is implemented to provide dynamic routing between the network sections.

## Client Change Request

**CR3: Guest Wi-Fi must be added for visitors and isolated from internal resources.**

The network includes a guest network using **VLAN 20** to separate guest traffic from the internal municipal network.

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

Milestone 1 focuses on the Client Design Review and includes:

1. Client Requirements
2. Physical Topology
3. Logical Topology
4. IP Addressing Plan
5. Initial GitHub Repository

## Project Evidence

Project evidence will be added to this repository as the project progresses. This includes:

* Network topology diagrams
* Cisco Packet Tracer screenshots
* IP addressing information
* Router and switch configurations
* OSPF configuration and verification
* Connectivity testing
* Troubleshooting evidence
* Project documentation

## Tools Used

* Cisco Packet Tracer
* draw.io
* GitHub

## Project Status

**Milestone 1 - Client Design Review**

The initial network design, topology and IP addressing plan have been prepared. Further configuration, testing and evidence will be added as the project progresses.
