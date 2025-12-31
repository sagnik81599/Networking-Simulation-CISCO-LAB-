Computer Networking Using Cisco Packet Tracer Practical Implementation

<img width="762" height="472" alt="Lab1" src="https://github.com/user-attachments/assets/c9a6f379-9640-4556-976e-352f04603e0b" />

-----------------------------------------------------
⚙️ Tools & Technologies Used:
-

Cisco Packet Tracer

Networking Devices:

Hub

Switch

Router

Server

PCs

Networking Protocols:

FTP

SMTP

POP3 / IMAP

DHCP
📌 Overview

This repository contains a complete practical implementation of computer networking concepts using Cisco Packet Tracer.
The project demonstrates how network devices and server-based services work together to enable communication in a real-world network.

It is designed for:

Academic learning

Practical lab understanding

Viva & interview preparation

Concept revision for beginners
------------------------------------------------------

🧱 Network Devices Implemented
-
🔹 Hub

Operates at Physical Layer (OSI Layer 1)

Broadcasts data to all connected devices

No MAC address learning

Used to understand basic signal transmission

🔹 Switch

Operates at Data Link Layer (OSI Layer 2)

Maintains a MAC address table

Sends data only to the intended destination

Reduces network congestion

🔹 Router

Operates at Network Layer (OSI Layer 3)

Connects multiple networks

Uses IP addressing for packet forwarding

Enables inter-network communication
---------------------------------------------------------
🖥️ Server Services Configured
📁 FTP Server (File Transfer Protocol)

Used for file upload and download

Operates on TCP Port 21

Requires authentication (username & password)

Demonstrates centralized file sharing

📧 Email Server

Supports:

SMTP – Sending emails

POP3 / IMAP – Receiving emails

Simulates real-time email communication between users

Demonstrates client-server communication

🌐 DHCP Server

Automatically assigns:

IP Address

Subnet Mask

Default Gateway

Eliminates manual IP configuration

Improves network efficiency and scalability

steps to connect DHCP others Network
-
step 1:  Router> enable

step 2:  Router# configure terminal

step 3:  Interface(router port:Gig0/0/1)/ int Gig0/0/1

step 4:  Ip helper-address (DHCP server ip)

step 5:  No shutdown
