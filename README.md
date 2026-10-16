# CMPG 325-Greater Taung Local Municipality Network

## Project Overview

This repository contains my individual semester project for CMPG 325 Computer Networks at North-West University.

The project involves designing, implementing, and testing a computer network for the **Greater Taung Local Municipality Offices** using Cisco Packet Tracer.

**Project ID:** CMPG325-2026-102  
**Client ID:** CLI-102  
**Organisation:** Greater Taung Local Municipality Offices (Taung)  
**Industry:** Municipal Services  
**Assigned Addressing Block:** 172.30.70.0/23

## Project Requirements

The network is designed to:

- Provide appropriate connectivity for the municipal network.
- Allow internal users to communicate and access shared network resources.
- Support critical file, print and application services.
- Provide a server for network services.
- Provide guest Wi-Fi for visitors.
- Isolate guest users from internal municipal resources.
- Use VLANs to logically separate network traffic.
- Use appropriate IP addressing for the different network segments.
- Allow future network expansion.
- Provide routing between the different network sections.

## Assigned Networking Challenge

The assigned networking challenge is:

**Basic OSPF (Single-Area Dynamic Routing)**

OSPF is implemented to provide dynamic routing between the network sections.

## Client Change Request

**CR3: Guest Wi-Fi must be added for visitors and isolated from internal resources.**

The network includes a guest network using **VLAN 20** and a Wireless Access Point for guest connectivity. An ACL is applied to the guest VLAN to prevent guest users from accessing internal municipal network resources.

## Network Design

The network includes:

- R1 - Core Router
- R2 - Branch Router
- SW1 - Internal Switch
- SW2 - Access Switch
- Municipal-Server
- Admin-PC
- Finance-PC
- HR-PC
- Services-PC
- Wireless Access Point
- Guest-Client

The network uses:

- **VLAN 10 - INTERNAL**
- **VLAN 20 - GUEST**
- **OSPF single-area dynamic routing**
- **172.30.70.0/23** addressing block

## Milestone 1 - Client Design Review

Milestone 1 focused on the client requirements and initial network design. This included identifying the client's networking needs, developing the physical and logical topologies, preparing the IP addressing plan, and establishing the initial GitHub repository for the project.

## Milestone 2 - Network Implementation and Testing

Milestone 2 focused on implementing the proposed network design in Cisco Packet Tracer. This involved configuring the routers and switches, implementing OSPF single-area dynamic routing, configuring VLAN 10 and VLAN 20, and setting up trunking to support communication between the network segments.

The guest Wi-Fi network was also implemented to meet client change request CR3. An ACL was configured on the guest VLAN to restrict guest access to internal municipal resources.

Connectivity and configuration tests were performed to verify the implementation. These included checking OSPF neighbour relationships and routing information, testing communication between internal devices, verifying VLAN and trunk configurations, and confirming that guest users could reach their gateway but could not access the tested internal devices after the ACL was applied. Troubleshooting was also carried out to resolve issues encountered during implementation.

## Milestone 3 - Final Technical Documentation and Presentation

Milestone 3 focused on documenting the completed network implementation and presenting the project work. This included preparing the final technical report, compiling evidence of the network configuration and testing, and recording a video presentation explaining the project.

The technical report documents the network design, IP addressing plan, implementation of OSPF, VLAN configuration, guest network isolation, testing results, troubleshooting, project outcomes, and possible future improvements.

The video presentation provides an overview of the project and demonstrates the implemented network and its main features.

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
- Final technical report
- Project presentation video

## Tools Used

- Cisco Packet Tracer
- draw.io
- GitHub

## Project Status

**Milestone 3 - Final Technical Documentation and Presentation completed.**

The network has been implemented and tested in Cisco Packet Tracer. The final technical report and video presentation document the project design, configuration, testing, and results.


