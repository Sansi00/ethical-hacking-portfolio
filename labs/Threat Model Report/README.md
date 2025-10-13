# 🛡️ Threat Model Report – Personal Computer

**Author:** Sansi Pokharel  
**Date:** 09/21/2025  

---

## 🧭 Objective
The objective of this lab is to develop a threat model for my personal computer and identify ways to enhance its overall security.  
This documentation includes an introduction to threat modeling, identification of assets, threats, and actors, risk assessment, and mitigation strategies.

---

## 🔍 Introduction to Threat Modeling

Threat modeling is a **systematic process** of identifying threats, vulnerabilities, and risks associated with a system, and then designing measures to mitigate or manage them.  
It plays a crucial role in maintaining the **CIA triad** — Confidentiality, Integrity, and Availability.

**Five Key Elements of Threat Modeling:**
1. **Findings (Threats):** Potential vulnerabilities or malicious actions.  
2. **Kill Chain:** Steps an attacker takes to exploit a system.  
3. **Single Asset Value:** Worth of one specific data element.  
4. **Organizational Asset Value:** The importance of the system within its environment.  
5. **Estimated Risk:** Likelihood and impact of potential threats.

---

## 💻 Identifying Assets

**System Overview:**
- **Device:** Razer Blade (2019 Model)  
- **Processor:** Intel i5  
- **Operating System:** Windows 11  

**Personal Assets Stored:**
- **Documents:** Assignments, resumes, IDs, financial records, certifications  
- **Professional Data:** Work files, code repositories, confidential communications  
- **Credentials:** Saved passwords, autofill data, browsing history  
- **Personal Media:** Photos, videos, personal messages revealing location/contacts  
- **System Information:** Installed applications, network configurations, logs  

Each asset has varying sensitivity and requires **tailored protection** based on its confidentiality level.

---

## 🧠 Identifying Threat Actors

Threat actors are entities capable of exploiting vulnerabilities.  
For my system, the primary threat actors include:

- **Cybercriminals:** Seek financial or credential data for profit  
- **Malware Authors:** Deploy ransomware/spyware for extortion or surveillance  
- **Insiders/Acquaintances:** Individuals with physical access who might steal/tamper with data  
- **Hacktivists:** Unlikely but possible ideological targeting  
- **Opportunistic Attackers:** Exploit general vulnerabilities like phishing or weak passwords  

**Common Motives:**
- Financial gain  
- Revenge or personal grievance  
- Data theft/resale  
- Defamation or social harm  
- Unauthorized access or curiosity  

---

## ⚔️ Identifying Attack Vectors

Attack vectors are the **pathways** used by threat actors to compromise a system.

| **Attack Vector** | **Description** |
|--------------------|-----------------|
| Phishing Emails | Fake messages prompting clicks or credential entry |
| Malicious Downloads | Compromised software or attachments |
| Unsecured Networks | Using public Wi-Fi without encryption |
| Outdated Software | Exploitable known vulnerabilities |
| Weak or Reused Passwords | Enables brute-force or credential stuffing |
| Physical Theft | Device stolen or tampered with |
| Browser Exploits | Drive-by downloads or session hijacking |
| Poor Configuration | Misconfigured firewalls, unpatched antivirus |

---

## ⚖️ Risk Assessment

| **Threat** | **Likelihood** | **Impact** | **Overall Risk** |
|-------------|----------------|-------------|------------------|
| Phishing Attack | High | Medium | High |
| Malware Infection | Medium | High | High |
| Data Theft (Physical) | Medium | High | Medium-High |
| Password Compromise | High | High | Critical |
| Outdated Software Exploit | Medium | Medium | Medium |
| Ransomware | Low | Critical | Medium |
| Social Engineering | High | Medium | High |

---

## 🧩 Mitigation Strategies

### 🛠️ Technical Controls
- Enable **Multi-Factor Authentication (MFA)** on all major accounts  
- Use a **VPN** when on public or shared networks  
- Encrypt sensitive files and use a **Password Manager**  
- Keep **OS and antivirus** software up to date  
- Enable **Windows Defender Firewall** and review rules regularly  
- Perform **routine backups** to encrypted drives or cloud  
- Use **BitLocker** for full-disk encryption  

### 🧍 Behavioral Controls
- Avoid untrusted or pirated software downloads  
- Verify links and attachments before clicking  
- Don’t reuse passwords or share credentials  
- Stay alert for social engineering and scams  
- Keep up with the latest security patches and awareness

---

## 💡 Recommendations
To strengthen long-term resilience:
- Conduct **monthly vulnerability scans**  
- Review system permissions and remove unnecessary software  
- Use **threat intelligence tools** (e.g., VirusTotal) to analyze suspicious files  
- Enable **2FA** on all cloud platforms (Google Drive, OneDrive, etc.)  
- Educate others sharing your network on basic cybersecurity hygiene  

---

## 🧾 Summary & Conclusion

This exercise revealed how much **valuable data** my personal laptop holds and how easily it could be compromised without proper security habits.  
From school projects to personal credentials, every piece of data carries potential risk.

Security isn’t just about tools — it’s about **consistent habits**.  
Simple actions like keeping software updated, avoiding suspicious links, and using MFA can dramatically reduce threats.  
I also learned that risks evolve, meaning **security is an ongoing process**, not a one-time fix.

In conclusion, I now see my laptop not merely as a device, but as a **digital extension of my identity**.  
The goal isn’t to be “unhackable,” but to be **resilient** — to make attacks costly, recovery quick, and damage minimal.

---

✅ *End of Report*
