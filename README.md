# Secure-Enterprise-Network-Simulation
Secure Enterprise Network Simulation (Cisco Packet Tracer)
📌 Overview

This project simulates a secure small enterprise branch office network using Cisco Packet Tracer. The scenario is based on a mid-sized financial services company expanding across Africa and Europe, requiring a segmented and secure internal network for its departments.

The network is designed with multiple VLANs, controlled inter-VLAN communication, Access Control Lists (ACLs), and secure remote management using SSH. The goal is to demonstrate practical skills in network design, segmentation, routing, and security enforcement.

# Objectives

Design a segmented enterprise network using VLANs

Implement inter-VLAN routing using Router-on-a-Stick (ROAS) or a Layer 3 switch

Apply Access Control Lists (ACLs) to enforce security policies

Configure secure remote access using SSH

Document configurations, security decisions, and network behavior

# Network Departments (VLANs)

The branch office consists of three core departments:

Admin VLAN – Human Resources and Finance

Sales VLAN – Customer engagement and business growth

IT VLAN – Technical operations and system management

Each department is assigned its own VLAN and subnet to ensure logical separation and improved security.

# Network Design & VLAN Segmentation

Created three VLANs: Admin, Sales, and IT

Assigned end devices to their respective VLANs

Configured IP addressing and subnetting per department

Ensured that devices communicate only within their VLAN by default

# Inter-VLAN Routing

Implemented Router-on-a-Stick (ROAS) or Layer 3 switching

Configured sub-interfaces for each VLAN

Enabled controlled communication between VLANs

Applied routing policies to limit unnecessary access

# Access Control Lists (ACLs)

Traffic restrictions were enforced using standard and extended ACLs based on the principle of least privilege:

Admin VLAN can access Sales VLAN for reporting purposes but not IT VLAN

Sales VLAN cannot access Admin VLAN but can access IT VLAN for system support

IT VLAN has unrestricted access to all VLANs for administrative tasks

Each ACL rule is documented with a security justification explaining its purpose and impact.

# Secure Remote Access

Configured SSH on routers and switches for encrypted remote management

Disabled insecure protocols such as Telnet

Restricted device access to authorized users only

 # Deliverables

This project includes:

Network topology diagram showing devices, VLANs, and links

Cisco IOS configuration commands for:

VLAN creation

Inter-VLAN routing

ACL implementation

SSH configuration

Security justification report explaining ACL logic and access control decisions

Step-by-step documentation with screenshots

Analysis of security risks caused by misconfiguration

# Tools and Technologies

Cisco Packet Tracer

Cisco IOS (Router & Switch CLI)

VLANs and Subnetting

Router-on-a-Stick / Layer 3 Switching

Access Control Lists (ACLs)

Secure Shell (SSH)

 # Security Focus

This lab demonstrates:

Network segmentation as a security control

Enforcement of least privilege using ACLs

Protection of sensitive departments (HR, Finance, IT)

Secure device management through encrypted protocols

Risks of improper VLAN and ACL configurations

# Intended Audience

Networking students

Cybersecurity learners

IT support and system administration trainees

Network security beginners

Academic and training institutions

# Learning Outcomes

By completing this project, users will be able to:

Design a VLAN-based enterprise network

Configure inter-VLAN routing

Apply ACLs to restrict network traffic

Secure network devices using SSH

Understand the impact of network misconfigurations

Interpret security policies at the network layer

Ethical Use

This project is intended strictly for educational and defensive networking practice.
Do not apply these configurations to production systems without authorization and proper testing.
