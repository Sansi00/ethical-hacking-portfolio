# Cybersecurity Lab 2: Domain Reconnaissance on HomeDepot.com

**Author:** Sansi Pokharel    

---

### Overview
This lab demonstrates basic reconnaissance techniques used in cybersecurity to gather open-source intelligence (OSINT) about a target domain — in this case, **HomeDepot.com**.  
The activities included DNS lookups, WHOIS queries, DomainTools analysis, and examination of search results and site structure.

---

### Key Commands Used
- `nslookup`
- `whois`
- Google Dorking (e.g., `filetype:pdf site:homedepot.com`)
- Viewing HTML source code of login pages
- Examining `robots.txt` file

---

### Observations
- WHOIS results lacked detailed admin data compared to DomainTools.
- Login pages used strong “no cache” headers to secure user data.
- Google Dorking attempts were blocked or redirected to the homepage.
- Verified company HQ: *2455 Paces Ferry Road, Atlanta, Georgia 30339*.

---

###  File Included
- [`lab2report`](lab2report.pdf): Full annotated report.

---

### Reflection
This exercise reinforced how publicly available information can reveal a lot about an organization’s infrastructure. Even simple queries like `nslookup` or `whois` can uncover IP ownership, DNS records, and administrative data that are critical in ethical hacking and security assessment.
