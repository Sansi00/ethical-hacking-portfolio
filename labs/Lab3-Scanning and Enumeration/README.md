# Lab 3 — Scanning and Enumeration

## Objective
Demonstrate host discovery and port-scanning techniques using `nmap`.

## Key switches explained
- `-sn` — Ping (host discovery) only; skip port scan.  
- `-Pn` — Skip host discovery (assume hosts are up), go straight to port scan.  
- `-sS` — TCP SYN scan (half-open): send SYN; reply SYN/ACK => open (Nmap sends RST to avoid completing handshake); reply RST => closed.

## Commands & examples
```bash
# Host discovery only (no port scan)
nmap -sn 192.168.1.0/24

# Skip ping/host discovery and do a port scan
nmap -Pn 192.168.1.10

# SYN scan (fast stealthy scan)
sudo nmap -sS 192.168.1.10

## Full Lab Report (PDF)

A compiled version of this lab with detailed commands, outputs, and analysis is available:

Download PDF: [Lab 3 Report (PDF)](lab3/lab3report.pdf)

> If the PDF doesn't render in your browser, right-click the link and choose "Save link as..." to download.

