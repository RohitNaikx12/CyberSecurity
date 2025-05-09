
# Footprinting & Reconnaissance

## Reconnaissance Methodology

Reconnaissance (or footprinting) is the first phase in ethical hacking where attackers gather information about a target. The aim is to get a "blueprint" of the target’s security profile, including its network, systems, and personnel. 

There are two primary types:

### Passive Footprinting

Gathering information without directly interacting with the target.
- OSINT
- Search engines
- Social networking sites
- Partner intelligence

### Active Footprinting

Direct interaction with the target.
- DNS interrogation
- Social engineering
- Port scanning
- User enumeration

## Information Obtained in Footprinting

### Organization Information
- Employee and branch details
- Partner information
- Legal and technological details
- Publicly available documents

### Network Information
- Domain/subdomain data
- IP addresses
- DNS records
- Firewalls and network blocks

### System Information
- Web server OS
- Email addresses
- Server locations

---

## Footprinting Threats

- **Social Engineering**: Convincing employees to give up sensitive info.
- **System and Network Attacks**: Exploiting discovered vulnerabilities.
- **Information Leakage**
- **Privacy Loss**
- **Corporate Espionage**
- **Business Loss**

---
![Screenshot 2025-05-08 110750](https://github.com/user-attachments/assets/3100d0cc-0a9e-4628-963e-6c9799d586e8)

## Google Hacking

Google Dorking involves crafting queries using operators to find:
- Files containing passwords
- Login portals
- Vulnerability data
- Error messages

**Source**: [Exploit DB GHDB](https://www.exploit-db.com/google-hacking-database)
![Screenshot 2025-05-08 111846](https://github.com/user-attachments/assets/54ce0ffe-6df0-4eec-a556-8ae8eadcb085)

Categories:
- Sensitive Directories
- Error Messages
- Vulnerable Servers
- Juicy Info, etc.

---

## Internet Research Services

Includes:
- People search
- Job listings
- Financial services
- Third-party data
- Dark web footprinting

---
![Screenshot 2025-05-08 113643](https://github.com/user-attachments/assets/ee3c2486-beed-49a3-aaa9-343d9d46e687)

## Archive.org Footprinting

Use [https://archive.org](https://archive.org) to:
- View archived versions of websites
- Access removed or old content
- Identify past vulnerabilities

---

## Social Networking Sites

Platforms like Facebook, LinkedIn, and Twitter can reveal:
- Personal/professional details
- Emails, phone numbers, education
- Real-time updates and connections

---

## Whois Footprinting

Gather:
- Domain registration details
- Name servers
- Admin contact info

### Tools:
- ARIN database
- Whois lookup tools
![Screenshot 2025-05-08 115236](https://github.com/user-attachments/assets/853aa762-1722-42f0-8df9-8b57752cd59d)

---

## IP Geolocation

Find location-based data:
- Region, country, city
- ISP, timezone, ZIP
- Latitude/longitude

### Tools:
- [IP2Location](https://www.ip2location.com)

---

## DNS Footprinting

Identify:
- DNS zone data
- DNS records (A, MX, CNAME, etc.)
![Screenshot 2025-05-08 115656](https://github.com/user-attachments/assets/d958a0c1-66c1-4a0b-b2e5-f5fe6ef6c26f)

Tools: DNS interrogation tools and reverse DNS lookups

---

## Network & Email Footprinting

### Network Range
Using traceroute and regional databases (like ARIN):
- Identify subnet and live hosts
- Internal IP discovery

### Email Footprinting
- Extract data from headers
- Trace email origin and servers

---

## Social Engineering Techniques

- **Eavesdropping**: Intercepting communication
- **Shoulder Surfing**: Observing password entries
- **Dumpster Diving**: Searching trash for sensitive info
- **Impersonation**: Pretending to be an insider or employee

---

## Footprinting Countermeasures

- Restrict social media access
- Limit information on websites
- Use pseudonyms in public forums
- Educate employees
- Enforce information security policies
- Implement multi-factor authentication
- Use split DNS architecture
- Prevent zone transfers to unauthorized servers

---


---
