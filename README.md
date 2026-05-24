# SOC Analyst Home Lab - Project 1

## Objective
Build a functional cybersecurity home lab using virtual machines to simulate 
a real SOC environment for threat detection and security monitoring practice.

## Lab Architecture

| VM | OS | IP Address | Role |
|---|---|---|---|
| Kali Linux | Debian 64-bit | 192.168.56.101 | Analyst / Attack Machine |
| Ubuntu Server | Ubuntu 64-bit | 192.168.56.106 | Log Server / SIEM Host |
| Windows 10 | Windows 64-bit | 192.168.56.109 | Target / Monitored Machine |

## Network Configuration
- **Network Type:** Host-Only Adapter (VirtualBox)
- **Subnet:** 192.168.56.0/24
- **All VMs communicate with each other successfully**

## Tools Used
- VirtualBox (Hypervisor)
- Kali Linux
- Ubuntu Server 24.04 LTS
- Windows 10 Enterprise

## Proof of Connectivity
All three machines successfully ping each other with 0% packet loss.

![Lab Screenshot](screenshots/lab_running.png)

## What I Learned
- Configuring virtual networks in VirtualBox
- Host-Only networking between multiple VMs
- Windows Firewall ICMP rule configuration
- Linux networking commands (ip a, ip route, ping)
- Documenting a technical lab environment

## Next Project
Project 2: SIEM Setup and Log Analysis using Secur
