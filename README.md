# NETWORKWALKS-LIYA-B084-WK2-PM1-CYBERSECURIT-LAB-SETUP
# Penetration Testing Project – Footprinting & Network Scanning
Name= Liya Mekbib

## Project Overview
This project was completed as part of the Cybersecurity & Ethical Hacking Program at Networkwalks.

The project focuses on two important penetration-testing phases:
- Phase 1: Reconnaissance and Footprinting
- Phase 2: Scanning and Network Discovery

The objective was to gather publicly available information about a permitted target domain and identify active devices on my own local network.

## Tools Used

Kali Linux 
WHOIS 
WhatWeb 
Nslookup 
Curl
Wafw00f
DNSRecon 
Zenmap 
Windows CMD 

## Activities Performed

### 1. Footprinting & Reconnaissance
Target: `networkwalks.com`

Performed:
- WHOIS
- <img width="1280" height="800" alt="WHOIS Results" src="https://github.com/user-attachments/assets/381d1487-a9a8-408e-80d1-39a4c585aad6" />

- WhatWeb
- <img width="1280" height="800" alt="whatweb Results" src="https://github.com/user-attachments/assets/f0215861-d715-4328-a5a1-972e45412657" />

- Nslookup
- <img width="1280" height="800" alt="nslookup Results" src="https://github.com/user-attachments/assets/ee854753-ff6e-4633-8fab-489fc5535af6" />

- Curl
- <img width="1280" height="800" alt="curl -I Results" src="https://github.com/user-attachments/assets/451c3559-8651-4ecf-9f03-23639dd9a629" />

- Wafw00f
- <img width="1280" height="800" alt="wafw00f Results" src="https://github.com/user-attachments/assets/d745ff36-03df-4e52-a6f3-3a9d88d6cb1b" />

- DNSRecon
<img width="1280" height="800" alt="dnsrecon Results" src="https://github.com/user-attachments/assets/46195ff3-906f-41d3-bd21-1cadac208ce6" />

### 2. Network Scanning
Target: Own local network (`192.168.1.0/24`)
<img width="1920" height="1080" alt="Screenshot 2026-11-12 215919" src="https://github.com/user-attachments/assets/e215ad1a-7aec-4c1f-a3b7-6d0da1d3c254" />


Performed:
- Identified local IP and subnet using `ipconfig`
- Conducted network discovery using Zenmap
- Identified 6 live hosts
- Collected available MAC address and vendor information
- Generated network topology evidence

## Key Findings
- Identified WordPress 7.1.4 and WordPress Download Manager 3.3.76.
- Identified the web server IP address: `192.232.216.135`.
- Detected ModSecurity (SpiderLabs) WAF.
- Enumerated DNS records.
- Discovered 6 live devices on the local network.

## Learning Outcomes
- Understanding reconnaissance techniques.
- Using Kali Linux tools for footprinting.
- Performing DNS enumeration.
- Identifying web technologies.
- Discovering live network hosts.
- Analyzing and documenting security observations.

