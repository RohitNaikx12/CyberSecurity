
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

## Google Hacking

Google Dorking involves crafting queries using operators to find:
- Files containing passwords
- Login portals
- Vulnerability data
- Error messages

![Google Dork Example](pdf_images/image_6_1.jpeg)

**Source**: [Exploit DB GHDB](https://www.exploit-db.com/google-hacking-database)

---

## Internet Research Services

Includes:
- People search
- Job listings
- Financial services
- Third-party data
- Dark web footprinting

---

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

![Whois Lookup Example](pdf_images/image_5_1.jpeg)

---

## IP Geolocation

Find location-based data:
- Region, country, city
- ISP, timezone, ZIP
- Latitude/longitude

![IP Geolocation Tool](pdf_images/image_4_1.jpeg)

### Tools:
- [IP2Location](https://www.ip2location.com)

---

## DNS Footprinting

Identify:
- DNS zone data
- DNS records (A, MX, CNAME, etc.)

![DNS Lookup Output](pdf_images/image_8_1.jpeg)

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

![Social Engineering Techniques](pdf_images/image_9_1.jpeg)

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
