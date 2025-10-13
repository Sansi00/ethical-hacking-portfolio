Threat Model Report – Personal Computer  

By: Sansi Pokharel 
Date: 09/21/2025 

The objective of this lab is to develop a threat model for my personal computer and see how I can enhance the security of the system. In this lab, you will see the documentation for the following:  

Introduction to Threat Modelling:  

 

Threat modelling is a systematic process of identifying the threats, vulnerabilities, and risk associated with your system and designing ways to mitigate or tackle them. It is important in computer security because you assess various components, interactions, and attack vectors to understand what potential vulnerabilities could be putting your system as a target.  

 

The process helps ensure that the three pillars of cybersecurity Confidentiality, Integrity, and Availability (CIA) are maintained. 

 

There are five elements of threat modelling: 

Findings (Threats): Possible malicious actions or vulnerabilities. 

Kill Chain: Steps an attacker follows to exploit the system. 

Single Asset Value: Worth of one specific system or data element. 

Organizational Asset Value: Overall, the importance of the system within the user’s environment. 

Estimated Risk: Likelihood and impact of potential attacks. 

 

Identifying Assets:  

System Overview: 

Hardware: Razer Blade (2019 model) 

Processor: Intel i5 

Operating System: Windows 11 

Personal Assets Stored: 

Documents: College assignments, resumes, identification, financial records, and certifications. 

Professional Data: Work-related files, code repositories, and confidential communications. 

Credentials: Saved passwords, browsing history, autofill data. 

Personal Media: Photos, videos, and personal communications revealing location and contacts. 

System Information: Installed applications, network configurations, OS logs, and metadata. 

Each of these assets carries different levels of confidentiality and sensitivity, 		requiring tailored protection. 

Identifying Threat Actors:  

Threat actors represent individuals or entities that may exploit system weaknesses. 	For my personal setup, the likely threat actors are: 

Cybercriminals: Seeking financial data or credentials for profit. 

Malware Authors: Distributing ransomware or spyware for extortion or surveillance. 

Insiders/Acquaintances: People with physical access who could tamper with or steal data. 

Hacktivists: Less likely but could target ideological beliefs or public accounts. 

Opportunistic Attackers: Using phishing or general malware targeting common vulnerabilities. 

Common Attack Motives: 

Financial gain 

Revenge or personal grievance 

Data theft and resale 

Defamation or social harm 

Unauthorized access or curiosity 

 

 

 

Identifying Attack Vectors:  

 

Attack vectors mean what methods/vulnerabilities could be used to attack a system. Since my threat actors are distinct, my attack vectors would look something like this:  

Attack vectors are the pathways used by threat actors to exploit vulnerabilities. For my system, these include: 

Phishing Emails: Fake messages prompting clicks or credential entry. 

Malicious Downloads: Compromised software or attachments. 

Unsecured Networks: Using public Wi-Fi without encryption. 

Outdated Software: Allowing known exploits to be used. 

Weak Passwords or Reuse: Enabling brute-force or credential stuffing. 

Physical Theft: Unattended devices can be stolen or tampered with. 

Browser Exploits: Drive-by downloads or session hijacking. 

Poor Configuration: Misconfigured firewalls or lack of antivirus updates. 

 

Risk Assessment:		 

Threat 

Likelihood 

Impact 

Overall Risk 

Phishing attack 

High 

Medium 

High 

Malware infection 

Medium 

High 

High 

Data theft (physical) 

Medium 

High 

Medium-High 

Password compromise 

High 

High 

Critical 

Outdated software exploit 

Medium 

Medium 

Medium 

Ransomware 

Low 

Critical 

Medium 

Social engineering 

High 

Medium 

High 

 

Mitigation Strategies:  

To reduce these risks, I implement both technical and behavioral controls: 

Technical Controls 

Enable Multi-Factor Authentication (MFA) on all key accounts. 

Use VPN when connecting to public networks. 

Encrypt sensitive files and use strong, unique passwords managed via a Password Manager. 

Keep the OS and antivirus software regularly updated. 

Enable Windows Defender Firewall and review its rules. 

Regularly back up critical data to an encrypted external drive or cloud. 

Use BitLocker for full-disk encryption. 

Behavioral Controls 

Avoid downloading software from untrusted sources. 

Verify email links and attachments before clicking. 

Do not reuse passwords or share credentials. 

Be cautious of social engineering attempts. 

Maintain awareness of new security updates and patches. 

 

Recommendations 

To further improve long-term resilience: 

Conduct monthly security scans and vulnerability checks. 

Review system permissions and remove unnecessary applications. 

Use threat intelligence feeds or tools (e.g., VirusTotal) to check suspicious files. 

Implement secure cloud practices like enabling 2FA on Google Drive or OneDrive. 

Educate others who may use the same network about cybersecurity hygiene. 

 

 

Summary and Conclusion  

 

Going through this threat modeling process made me realize how much personal and professional information is stored on my laptop and how easily it could be compromised if I’m not careful. From my assignments and work projects to my passwords, photos, and even my location history, everything has some level of value that could be targeted by attackers. 

 

What stood out the most is that security isn’t just about having antivirus software or a strong password; it’s about habits. Small things like avoiding suspicious links, keeping software updated, or using MFA consistently make a huge difference. I also learned that risks change over time, so keeping my system safe means staying aware and adapting as new threats appear. 

 

In the end, this lab helped me see my personal computer not just as a device I use every day, but as something that needs to be protected with intention. The goal isn’t to be completely “unhackable,” but to make it hard enough for attackers that they move on, and to make sure that if something does happen, I can recover quickly with minimal loss. 

 

 

 

 
