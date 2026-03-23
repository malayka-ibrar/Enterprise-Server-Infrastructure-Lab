# Enterprise Network Infrastructure & Server Lab 🌐

## 📌 Project Overview
A fully virtualized, multi-service enterprise network environment built to demonstrate advanced system administration and network hardening. This lab features five core services running on **Ubuntu Linux** within a **VirtualBox** environment, ensuring stable inter-service communication and security.

## 🛠️ Tech Stack & Tools
* [cite_start]**OS:** Ubuntu Linux (Server & Desktop) [cite: 12, 20]
* [cite_start]**Virtualization:** Oracle VM VirtualBox [cite: 12, 35]
* [cite_start]**Network Services:** Bind9 (DNS), isc-dhcp-server (DHCP), Apache2 (Web), vsftpd (FTP), Squid (Proxy) [cite: 13, 20]
* [cite_start]**Security:** UFW (Uncomplicated Firewall), Least-Privilege Access Control [cite: 21]

## 🚀 Key Features & Implementation
* [cite_start]**DNS Resolution (Bind9):** Configured authoritative and caching DNS; successfully resolved resolution failures using strategic Bind9 forwarding[cite: 21, 35].
* [cite_start]**Traffic Management (Squid):** Implemented a forward proxy for controlled internet access and traffic caching[cite: 13, 20].
* [cite_start]**Automation (DHCP):** Automated IP address management across the virtual subnet[cite: 13, 35].
* [cite_start]**Web Hosting (Apache):** Deployed a functional enterprise web server integrated with internal DNS[cite: 20, 35].
* [cite_start]**Security Hardening:** Applied least-privilege firewall rules and secure configuration parameters to minimize the attack surface[cite: 21, 35].

## 📁 Repository Structure
```text
├── configs/              # Sanitized configuration files (named.conf, squid.conf, etc.)
├── docs/                 # Detailed technical documentation and network diagrams
└── scripts/              # Bash scripts used for automated service deployment
