# Lab 1 — VirtualBox VM Setup & Connectivity Verification
Date:2025-08-31  
Author: Sansi Pokharel  
Course: Ethical Hacking  

---

## Objective
Set up a secure virtual lab environment using Oracle VirtualBox with Kali Linux and Metasploitable 3 targets.  
Verify inter-VM connectivity using ICMP (ping).

---

## Tools & Environment
| Tool / System | Purpose |
|----------------|----------|
| **VirtualBox 7.0.x** | Virtualization platform |
| **Kali Linux 2025.2** | Attacker machine |
| **Metasploitable 3 (Windows Server 2008)** | Target #1 |
| **Metasploitable 3 (Ubuntu 14.04)** | Target #2 |
| **Network Mode:** | Bridged + Host-Only Adapter |

---

## Steps & Commands

### 1️⃣ Confirm VMs are installed  
Take a screenshot of the VirtualBox Manager showing all three VMs.  
Save it as `screenshots/vbox_overview.png`.

### 2️⃣ Ping Windows target from Kali
```bash
ping -c 6 10.0.2.5 | tee logs/ping_windows.txt
