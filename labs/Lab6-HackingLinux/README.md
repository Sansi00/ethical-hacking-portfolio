# Lab 06 — Hacking LINUX

**Compiled lab report (PDF):** [Lab 06 — Hacking LINUX (PDF)] (lab6report.pdf)

---

## Objective
Demonstrate host discovery, service/port scanning, exploit enumeration and execution using Metasploit, and forensic observation of configuration files on a Linux target. This README summarizes the work and points to the compiled PDF that contains all screenshots and full raw outputs.

---

## Summary of work performed
1. **Host discovery & port scanning (Nmap)**  
   - Performed network/host discovery and targeted port scans to identify open services on the Linux target.  
   - The Nmap scan output and a screenshot are included in the PDF.

2. **Exploit enumeration (Metasploit search)**  
   - Searched the Metasploit Framework for modules relevant to discovered services and versions.  
   - Metasploit search results are captured in the PDF.

3. **Exploit preparation & validation (`show options`)**  
   - Selected a module and reviewed its required options (`show options`) to confirm parameters (RHOST, RPORT, payload, etc.).  
   - Screenshot of `show options` is included in the PDF.

4. **Exploit execution and post‑exploit evidence**  
   - Executed the exploit and captured console output showing exploit progress and success.  
   - Proof of a successful session / completed exploit is included in the PDF.

5. **Forensic evidence (`config.inc.php`)**  
   - Located `config.inc.php` on the target and captured the file contents showing credential exposure.  
   - The version in the repo/PDF has credentials **redacted**. See Security Note below.

---

## Key commands used
> Exact terminal output and all screenshots are bundled inside the linked PDF (`lab6/lab6report.pdf`). The following are representative commands used during the lab.

### Nmap (examples)
```bash
# Host discovery on the subnet (ping only)
nmap -sn 192.168.56.0/24

# Targeted SYN scan for common ports (example)
sudo nmap -sS -p 1-65535 -T4 -A 192.168.56.101

# Service/version scan
nmap -sV -p 22,80,139,445,3306 192.168.56.101

