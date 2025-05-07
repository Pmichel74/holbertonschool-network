# Network Basics - Part 1

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Networking_icon_-_noun_project_8536.svg/512px-Networking_icon_-_noun_project_8536.svg.png" alt="Network Icon" width="150" height="150">
</p>

## Table of Contents

- [Description](#description)
- [Files](#files)
  - [0-change_your_home_IP](#0-change_your_home_ip)
  - [1-show_attached_IPs](#1-show_attached_ips)
  - [2-port_listening_on_localhost](#2-port_listening_on_localhost)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Author](#author)

## Description

This project contains a series of Bash scripts to manipulate and analyze network parameters on a Linux machine. It is part of the Holberton School curriculum to understand networking basics.

## Files

### 0-change_your_home_IP

Bash script that configures an Ubuntu server with the following requirements:
- localhost resolves to 127.0.0.2
- facebook.com resolves to 8.8.8.8

```bash
sudo ./0-change_your_home_IP
```

### 1-show_attached_IPs

Bash script that displays all active IPv4 IPs on the machine.

```bash
./1-show_attached_IPs
```

### 2-port_listening_on_localhost

Bash script that listens on port 98 on localhost.

```bash
sudo ./2-port_listening_on_localhost
```

## Prerequisites

- Ubuntu Linux
- Root access (for some scripts)
- Standard Unix commands: ip, sed, netcat, etc.

## Installation

Clone this repository and make the scripts executable:

```bash
git clone https://github.com/yourusername/holbertonschool-network.git
cd holbertonschool-network/basics_1
chmod +x 0-change_your_home_IP 1-show_attached_IPs 2-port_listening_on_localhost
```

## Usage

Each script can be run individually. Some scripts require administrative privileges (sudo).

Example:

```bash
./1-show_attached_IPs
```

For the port listening script:

```bash
# Terminal 1
sudo ./2-port_listening_on_localhost

# Terminal 2
telnet localhost 98
```
