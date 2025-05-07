# Holberton School Networking Projects 🌐

<p align="center">
  <img src="https://img.icons8.com/fluency/240/000000/network.png" alt="Network Icon" width="180" height="180"/>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Bash-4.4+-blue.svg?style=for-the-badge&logo=gnu-bash" alt="Bash"/>
  <img src="https://img.shields.io/badge/Linux-Ubuntu_20.04-orange.svg?style=for-the-badge&logo=ubuntu" alt="Ubuntu"/>
  <img src="https://img.shields.io/badge/Networking-TCP/IP-green.svg?style=for-the-badge&logo=cisco" alt="Networking"/>
</div>

---

## 📚 Table of Contents
- [🔎 About](#-about)
- [🚀 Projects](#-projects)
  - [🔹 Basics 0: OSI Model & TCP/UDP](#-basics-0-osi-model--tcpudp)
  - [🔹 Basics 1: IP Configuration & Networking Tools](#-basics-1-ip-configuration--networking-tools)
- [⚙️ Technologies](#️-technologies)
- [📦 Installation](#-installation)
- [📋 Requirements](#-requirements)
- [📖 Resources](#-resources)
- [👨‍💻 Author](#-author)

---

## 🔎 About

This repository contains Bash scripts and resources for learning computer networking fundamentals as part of the Holberton School curriculum. The projects focus on understanding and implementing networking concepts through practical exercises, from the OSI model to advanced network configuration tasks.

Each script is designed to demonstrate specific networking principles and tools, providing hands-on experience with essential networking commands and configurations in a Linux environment.

---

## 🚀 Projects

### 🔹 Basics 0: OSI Model & TCP/UDP

<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6119/6119533.png" alt="OSI Model" width="70"/>
</p>

This project covers fundamental networking concepts including:
- The OSI model and its 7 layers (Physical, Data Link, Network, Transport, Session, Presentation, Application)
- Types of networks (LAN, WAN, Internet, MAN)
- MAC and IP addressing schemes
- TCP/UDP protocols and their differences
- Network ports and services mapping

**Key scripts:**
- `4-TCP_and_UDP_ports.sh` - Display active listening ports with PID and program name
- `5-is_the_host_on_the_network` - Ping an IP address to check network connectivity 
- Port classification and understanding common service port numbers

[Go to Basics 0 →](./basics_0/)

### 🔹 Basics 1: IP Configuration & Networking Tools

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/ip-address.png" alt="IP Configuration" width="70"/>
</p>

This project focuses on more advanced networking tools and operations:
- IP address configuration and manipulation techniques
- Network interface management and configuration
- Port listening and network connectivity troubleshooting
- Host resolution configuration

**Key scripts:**
- `0-change_your_home_IP` - Configure custom host resolutions (localhost to 127.0.0.2, facebook.com to 8.8.8.8)
- `1-show_attached_IPs` - Display all active IPv4 IPs on the machine
- `2-port_listening_on_localhost` - Set up a port listener on localhost port 98

[Go to Basics 1 →](./basics_1/)

---

## ⚙️ Technologies

<div align="center">
  <img src="https://img.icons8.com/color/48/000000/bash.png" title="Bash" alt="Bash" width="40" height="40"/>
  <img src="https://img.icons8.com/color/48/000000/linux--v1.png" title="Linux" alt="Linux" width="40" height="40"/>
  <img src="https://img.icons8.com/color/48/000000/dns.png" title="DNS" alt="DNS" width="40" height="40"/>
  <img src="https://img.icons8.com/color/48/000000/tcp-ip.png" title="TCP/IP" alt="TCP/IP" width="40" height="40"/>
</div>

- **Bash Scripting**: All tasks are implemented using Bash shell scripts
- **Linux Networking Tools**: utilizes netstat, ip, ifconfig, ping, netcat, etc.
- **TCP/IP Protocol Suite**: Hands-on work with core internet protocols
- **System Configuration**: Editing system files like /etc/hosts for network settings

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/holbertonschool-network.git
   cd holbertonschool-network
   ```

2. **Make scripts executable:**
   ```bash
   chmod +x basics_0/* basics_1/*
   ```

3. **Navigate to a specific project:**
   ```bash
   cd basics_0  # or basics_1
   ```

4. **Run a script:**
   ```bash
   ./script_name  # Some scripts might require sudo privileges
   ```

---

## 📋 Requirements

- **Operating System**: Ubuntu Linux 20.04 LTS
- **Permissions**: Root/sudo privileges for system configuration scripts
- **Shell**: Bash shell
- **Packages**: Standard networking tools:
  - net-tools (for netstat)
  - iputils-ping (for ping)
  - iproute2 (for ip command)
  - netcat (for nc command)

---

## 📖 Resources

<div align="center">
  <img src="https://img.icons8.com/color/48/000000/study.png" alt="Learning Resources" width="40"/>
</div>

- [IANA Port Registry](https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml) - Official port number assignments
- [Linux Networking Commands](https://www.tecmint.com/linux-networking-commands/) - Essential commands for network administration
- [Introduction to Computer Networks](https://www.geeksforgeeks.org/basics-computer-networking/) - Fundamentals of networking
- [OSI Model Explained](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/) - Detailed explanation of the 7-layer model
- [TCP vs UDP](https://www.diffen.com/difference/TCP_vs_UDP) - Comparative analysis of transport protocols
- [IPv4 Addressing](https://www.subnet-calculator.com/subnet.php) - Guide to IPv4 addressing and subnetting

---

## 👨‍💻 Author

<div align="center">
  <img src="https://img.icons8.com/color/48/000000/user-male-circle--v1.png" width="40"/>
  <p><b>Your Patrick MICHEL</b></p>
  <a href="https://github.com/PMichel74">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/patrick-michel">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</div>

---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F-at%20Holberton%20School-blue" alt="Made with Love at Holberton School"/>
</p>

<p align="center">
  <i>Copyright © 2025 Holberton School. All rights reserved.</i>
</p>