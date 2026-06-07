# Capture-and-Analyze-Network-Traffic-Using-Wireshark
Capture live network traffic using Wireshark and analyze TCP, DNS, HTTPS/TLS protocols.
## Objective
The objective of this task is to capture live network traffic using Wireshark, analyze different network protocols, and understand how data travels across a network. This task helps develop packet analysis and network troubleshooting skills.

## Tools Used
- Wireshark
- Windows Operating System
- Internet Connection

## Task Description
In this task, I used Wireshark to capture live network packets generated while browsing websites and sending network requests. The captured packets were analyzed to identify different protocols and understand their functions.

## Steps Performed

### 1. Installed Wireshark
Downloaded and installed Wireshark from the official website.

### 2. Started Packet Capture
Opened Wireshark and selected the active network interface (Wi-Fi/Ethernet).

### 3. Generated Network Traffic
Performed the following actions:
- Browsed multiple websites
- Opened online services
- Sent ping requests using Command Prompt

### 4. Stopped Packet Capture
Captured traffic for approximately one minute and stopped the capture.

### 5. Applied Filters
Used Wireshark filters to analyze specific protocols:
- TCP
- UDP
- DNS
- HTTP/HTTPS

### 6. Identified Network Protocols
Observed and analyzed various network protocols present in the captured traffic.

### 7. Exported Capture File
Saved the packet capture as a `.pcap` file for future analysis.

## Protocols Identified

### TCP (Transmission Control Protocol)
- Connection-oriented protocol
- Ensures reliable delivery of data
- Used for web browsing, email, and file transfers

### DNS (Domain Name System)
- Converts domain names into IP addresses
- Helps devices locate websites on the internet

### HTTP/HTTPS
- Used for communication between web browsers and web servers
- HTTPS provides encrypted communication

### UDP (User Datagram Protocol)
- Faster but less reliable than TCP
- Commonly used for streaming, gaming, and VoIP

## Sample Packet Analysis

### DNS Query Packet
- Source: Local Device
- Destination: DNS Server
- Purpose: Resolve website domain name into an IP address

### TCP Packet
- Source: Client
- Destination: Web Server
- Purpose: Establish a reliable connection

### HTTPS Packet
- Source: Browser
- Destination: Secure Web Server
- Purpose: Encrypted web communication

## Findings

- Successfully captured live network traffic.
- Identified multiple protocols including TCP, UDP, DNS, and HTTPS.
- Observed packet exchange between client and server.
- Learned how protocol filtering helps analyze network activity efficiently.
- Understood the role of packet analysis in network troubleshooting and cybersecurity.