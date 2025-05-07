# holbertonschool-network

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/network-card.png" alt="Network Icon" width="96" height="96"/>
</p>

---

## 📚 Table of Contents
- [about](#about)
- [features](#features)
- [getting-started](#getting-started)
- [scripts](#scripts)
- [useful-ports](#useful-ports)
- [resources](#resources)
- [author](#author)

---

## 📝 About

This repository contains Bash scripts and resources for learning the basics of computer networking, focusing on TCP/UDP ports, sockets, and network utilities. It is part of the Holberton School curriculum.

---

## ✨ Features
- Display listening TCP/UDP ports and associated programs
- Check if a host is on the network
- Learn about common network ports
- Practice with real-world networking commands

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/holbertonschool-network.git
   cd holbertonschool-network/basics_0
   ```
2. **Make scripts executable:**
   ```bash
   chmod +x 4-TCP_and_UDP_ports 5-is_the_host_on_the_network
   ```
3. **Run a script:**
   ```bash
   sudo ./4-TCP_and_UDP_ports
   ./5-is_the_host_on_the_network 8.8.8.8
   ```

---

## 🖥️ Scripts

Here is the list of scripts in this folder, each with a direct link and a short description:

- [0-OSI_model](./0-OSI_model): Displays the number corresponding to the OSI (Open Systems Interconnection) model.
- [1-types_of_network](./1-types_of_network): Displays the type of network (LAN, WAN, etc.) based on the input.
- [2-MAC_and_IP_address](./2-MAC_and_IP_address): Shows the difference between a MAC address and an IP address.
- [3-UDP_and_TCP](./3-UDP_and_TCP): Shows the difference between UDP and TCP.
- [4-TCP_and_UDP_ports](./4-TCP_and_UDP_ports): Displays all listening TCP/UDP ports with the PID and associated program name.
- [5-is_the_host_on_the_network](./5-is_the_host_on_the_network): Checks if a host is reachable via ping (5 packets).

---

## 🔑 Useful Ports
- **22**: SSH
- **80**: HTTP
- **443**: HTTPS

---

## 📚 Resources
- [IANA Service Name and Transport Protocol Port Number Registry](https://www.iana.org/assignments/service-names-port-numbers/service-names-port-numbers.xhtml)
- [Linux netstat command](https://linux.die.net/man/8/netstat)
- [Holberton School](https://www.holbertonschool.com/)

---


<p align="center">
  <img src="https://img.shields.io/badge/holbertonschool-networking-blue" alt="Holberton Networking"/>
</p>