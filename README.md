# Information Security Project – Network Scanning & Traffic Analysis

A hands-on project from my 2nd semester **Information Security** course focused on understanding network security fundamentals.  
The project demonstrates the use of **Nmap** for port scanning and vulnerability assessment, and **Wireshark** for real-time packet capture and analysis on a private local network.

---

## Overview

The project was designed to:
- Identify open/closed ports and running services using **Nmap**.
- Perform basic vulnerability scanning with **Nmap Scripting Engine (NSE)**.
- Capture and analyze network traffic using **Wireshark**.
- Apply IP and protocol-based filters for deeper traffic inspection.
- Understand encrypted request-response patterns and potential security risks.

---

## Tools Used
- **Nmap** – Port scanning, service/version detection, vulnerability scanning.
- **Wireshark** – Packet capture, filtering, and traffic analysis.
- **Windows 10** – Host system for scanning and monitoring.
- **Private Home Network** – Test environment for safe and ethical scanning.

---

## Steps Performed

1. **Port Scanning with Nmap**  
   - Identified open/closed ports on devices within the local network.  
   - Detected running services and versions.  
   - Conducted vulnerability scanning using NSE scripts.

2. **Packet Capture with Wireshark**  
   - Selected a specific Wi-Fi channel for focused packet capture.
   - Applied filters like:
     ```wireshark
     ip.addr == 192.168.1.103 && tcp
     ```
     to isolate traffic by IP and protocol.
   - Followed TCP streams to view encrypted request and response data.

3. **Traffic Analysis & Decryption**  
   - Analyzed captured packets for potential vulnerabilities.
   - Uploaded saved packet files to external tools for deeper decryption and insight.

---

## Key Learnings
- Practical understanding of **network scanning and vulnerability assessment**.
- Hands-on experience with **Wireshark filters and packet-level analysis**.
- Improved awareness of **network traffic behavior** and potential security risks.
- Reinforced safe and ethical use of cybersecurity tools.

---

## Screenshots

![Nmap Port Scan](/assets/screenshots/nmap-scan.png)  
*Identifying open and closed ports using Nmap.*

![Wireshark Traffic Analysis](/assets/screenshots/wireshark-analysis.png)  
*Filtering packets by IP and protocol in Wireshark.*

---

## Report
The detailed project report with all screenshots and findings is included in this repository:  
**[IS-Project-Report.pdf](IS-Project-Report.pdf)**

---

## Disclaimer
All scanning and analysis were performed within a **private home network** for academic purposes only.