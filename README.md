🏢 Small Office Network Simulation (Cisco Packet Tracer)
📘 Overview

This repository contains a small office network simulation built using Cisco Packet Tracer.
The project demonstrates how to design and configure a simple enterprise-style network with multiple departments connected through VLANs and a router-on-a-stick configuration.

🧩 Network Design

The simulated network includes:

Departments:

🟪 Admin/IT (VLAN 10 — 192.168.1.0/26)

🟦 Finance/HR (VLAN 20 — 192.168.1.64/26)

🟨 Customer Service/Reception (VLAN 30 — 192.168.1.128/26)

Devices: PCs, Laptops, Access Points, and Printers

Router: ISR 4331

Switch: 2960 Catalyst

Each department has its own VLAN to enhance network segmentation and security. Inter-VLAN routing is enabled through the router.

⚙️ Key Features

VLAN configuration and inter-VLAN routing

Wireless connectivity via access points

Department-based IP addressing

Printer and laptop integration

Logical topology layout for clarity

🧠 Concepts Demonstrated

VLANs and Subnetting

Router-on-a-stick configuration

Basic switch and router setup

Network segmentation and scalability

🖥️ How to Use

Open the .pkt file using Cisco Packet Tracer (version 8.0 or later recommended).

Explore device configurations by opening the CLI of the router or switch.

Modify IP addresses, add new VLANs, or connect more devices to practice network design.

📂 Files Included

small-office-network.pkt — Main network simulation file

screenshots/ — Images of the topology (for documentation)

👩‍💻 Author

Nourhan Ali
Student at Faculty of Computers and Artificial Intelligence, Cairo University
