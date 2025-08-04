# Rishita---Elevate-Labs

# 🔍 Task 1: Network Port Scanning using Nmap

## 📘 Overview

This task is part of the Cyber Security Internship Program and focuses on **network reconnaissance** by scanning a local network for open ports using **Nmap**. The objective is to understand how devices on a network expose services through open ports and how this can lead to potential security risks.

---

## 🎯 Objective

- Learn basic port scanning techniques using **Nmap**
- Discover devices connected to the local network
- Identify **open ports** and running **services**
- Analyze results and understand possible **security risks**
- Document findings and reflect on learnings

---

## 🛠 Tools & Technologies Used

| Tool        | Purpose                                      |
|-------------|----------------------------------------------|
| **Nmap**    | Port scanning and host discovery             |
| **Wireshark** _(Optional)_ | Packet capture and protocol analysis |
| **GitHub**  | Version control and task submission          |

---

## 🪜 Steps Followed

### 1. 🔧 Nmap Installation
- Installed Nmap from the official website: [https://nmap.org/download.html](https://nmap.org/download.html)
- Verified installation using:  
  ```bash
  nmap --version
2. 🌐 Found Local IP Range
Used the following command to find local IP:

ipconfig   # (on Windows)

ifconfig or ip a  # (on Linux/Mac)

Local IP range determined as: 192.168.1.0/24

3. 🚀 Performed TCP SYN Scan
Command used:

nmap -sS 192.168.1.3/24
This scanned all IPs in the subnet for open TCP ports using the stealth SYN scan method.

4. 📋 Recorded Results
Noted active devices and their open ports and services

Saved scan output in scan_result.txt

5. 🧠 Service & Risk Analysis
Researched services running on open ports (e.g., SSH, HTTP)

Identified which services could pose security risks (e.g., Telnet, FTP)

6. 🔍 (Optional) Packet Analysis with Wireshark
Captured packets while running the scan

Applied filters to inspect SYN packets and responses

