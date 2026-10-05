<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff88,100:0d1117&height=120&section=header&text=&fontSize=0" width="100%"/>

# 👾 RUSHIL VARADE

### `VAPT Engineer` · `Offensive Security`

<a href="mailto:rushilvarade@gmail.com"><img src="https://img.shields.io/badge/Gmail-rushilvarade%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/rushil-varade"><img src="https://img.shields.io/badge/LinkedIn-Rushil--Varade-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/RushilVarade1405"><img src="https://img.shields.io/badge/GitHub-RushilVarade1405-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=RushilVarade1405&color=00ff88&style=for-the-badge&label=PROFILE+VIEWS"/>

</div>

---

## 🧠 About Me

Cybersecurity professional and 2025 Computer Science & Engineering graduate specializing in **Vulnerability Assessment and Penetration Testing (VAPT)**. Hands-on experience rooting **9+ VulnHub machines** and completing **24/24 challenges** in TryHackMe's Advent of Cyber 2025, with practical exposure to web application testing, network scanning, and exploitation using Nmap, Metasploit, Burp Suite, and SQLMap.

```python
class RushilVarade:

    name       = "Rushil Lakshmikant Varade"
    location   = "Mulund, Mumbai, Maharashtra, India"
    email      = "rushilvarade@gmail.com"
    phone      = "+91-9136011065"

    education  = "BE in CSE (IoT, Cybersecurity & Blockchain) — 2025"
    college    = "Smt. Indira Gandhi College of Engineering, Ghansoli"

    role       = "Infra-VAPT Intern @ Talakunchi Networks"
    primary_os = "Kali Linux"  # btw

    languages  = ["Python", "Bash", "PowerShell", "Java", "SQL"]

    interests  = [
        "Penetration Testing",
        "Red Teaming",
        "Digital Forensics",
        "Cryptography",
        "SOC Operations",
        "Cyber Laws & Compliance",
    ]

    pgp_key    = "2659 48C7 4798 E5AC E7B1 F18A BB7F 7ACE 13B1 743B"

    def mission(self):
        return "Break things ethically. Understand deeply. Secure everything."
```

---

## 💼 Experience

| Role | Organization | Duration |
|------|--------------|----------|
| 🛡️ Infra-VAPT Intern | Talakunchi Networks | Present · On-site |
| 🔎 Cybersecurity Intern | NullClass EdTech Private Limited | 06/2025 – 08/2025 · Remote |

- **Talakunchi Networks** — Contributing to infrastructure security assessments, vulnerability identification, and penetration testing activities.
- **NullClass EdTech** — Performed penetration testing, vulnerability research, exploitation, and technical reporting.

---

## ⚔️ Offensive Toolkit

| Domain | Tools & Tech |
|--------|--------------|
| 🌐 Web App Pentesting | Burp Suite · SQLMap · Nikto · Gobuster · OWASP Top 10 |
| 🔍 Recon & OSINT | Nmap · Masscan · Maltego · OSINT Frameworks · Nessus |
| 🕸️ Network Security | Wireshark · TCP/UDP · OSI Model · DNS · DHCP · IDS/IPS · VPN · Firewall |
| 💥 Exploitation | Metasploit · OpenVAS · Privilege Escalation · Enumeration |
| 🐍 Scripting & Dev | Python · Bash · PowerShell · SQL |
| 🖥️ OS & Infra | Kali Linux · Windows Server · macOS · Linux |
| 🔬 Forensics & Blue Team | Digital Forensics · Splunk SIEM · Cyber Laws · Compliance |
| 🏁 Labs & CTF | VulnHub · TryHackMe · OWASP Labs · Advent of Cyber |

---

## 🚀 Projects

| Project | Description |
|---------|-------------|
| 🖼️ **Image Steganography Tool** | LSB steganography tool for PNG/BMP payload embedding with 100% payload integrity across test images and zero measurable quality loss — demonstrates a DLP-bypass and covert-channel technique. |
| 📄 **Secure Document Summarization Tool** *(Major Project)* | AI-powered Q&A tool built on Ollama LLM and RAG architecture. Supports PDF, DOCX, and TXT with fully local processing and zero external data exposure. |
| 🌐 **Cybersecurity Portfolio Platform** | React + Vite + Tailwind CSS app with pentesting tool references, cryptography modules, cyber law resources, and a live RSS security news feed. [Live demo](https://ryt-cyberhub.vercel.app) |

---

## 🎓 Certifications

- **Certified Ethical Hacker (CEH)** — EC-Council
- **Penetration Testing Specialization** — Encrytecl Cyberguard
- **Ethical Hacking from Scratch** — Udemy
- **Network Fundamentals · Cybersecurity Fundamentals · Network Security** — Encrytecl Cyberguard

---

## 🏆 Achievements

- **TryHackMe — Advent of Cyber 2025:** Completed 24/24 daily challenges covering SQLi, XSS, IDOR, vulnerability scanning, and log analysis (OWASP Top 10, OpenVAS, Splunk SIEM).
- **TryHackMe — Hacker Holidays:** Completed a 14-day gamified series, rooting a room per day across web, network, and privilege-escalation scenarios.
- **VulnHub — 9 Machines Rooted:** Full methodology from enumeration to root (details below).

---

## 🔬 VulnHub Lab Write-ups

**9+ machines rooted** — full pentest methodology: Enumeration → Exploitation → Privilege Escalation → Root

<details>
<summary><b>🏚️ Aragog</b> — Click to expand</summary>

```
[*] Nmap scan          → discovered open ports & services
[*] Gobuster web enum  → found hidden WordPress directories
[*] Exploit            → PHP Local File Inclusion vulnerability
[*] Priv-esc           → misconfigured cron job → ROOT ✓
```

</details>

<details>
<summary><b>💀 NullByte</b> — Click to expand</summary>

```
[*] Steganography      → extracted hidden credentials from image
[*] SQL Injection      → database enumeration & data extraction
[*] Priv-esc           → local privilege escalation → ROOT ✓
```

</details>

<details>
<summary><b>🚀 RickdiculouslyEasy</b> — Click to expand</summary>

```
[*] Anonymous FTP      → flag extraction via open FTP access
[*] Web directories    → misconfigured directories revealed flags
[*] Telnet / SSH       → lateral movement & flag capture → ALL FLAGS ✓
```

</details>

<details>
<summary><b>🔧 Basic Pentesting 1</b> — Click to expand</summary>

```
[*] ProFTPD 1.3.3c     → exploited vulnerable ProFTPD service
[*] Metasploit         → leveraged known vulnerability
[*] Kernel priv-esc    → escalated to root via kernel vulnerability → ROOT ✓
```

</details>

<details>
<summary><b>🕵️ Basic Pentesting 2</b> — Click to expand</summary>

```
[*] Information Disc.  → discovered sensitive information
[*] Credentials        → identified weak SSH credentials
[*] SSH Access         → gained access using discovered credentials
[*] Sudo Abuse         → abused sudo permissions → ROOT ✓
```

</details>

<details>
<summary><b>🐮 Jangow: 1.0.1</b> — Click to expand</summary>

```
[*] Enumeration        → identified vulnerable web application
[*] Command Injection  → exploited web application input
[*] Initial Access     → obtained shell access
[*] CVE-2016-5195      → DirtyCow kernel exploit
[*] Priv-esc           → escalated privileges → ROOT ✓
```

</details>

<details>
<summary><b>🩹 DC-1</b> — Click to expand</summary>

```
[*] Enumeration        → identified Drupal-based application
[*] Exploitation       → Drupalgeddon 2
[*] Initial Access     → obtained system access
[*] Priv-esc           → SUID find abuse
[*] Result             → ROOT ✓
```

</details>

<details>
<summary><b>📝 DC-2</b> — Click to expand</summary>

```
[*] WordPress enum     → discovered valid credential set
[*] Credential reuse   → reused credentials for SSH access
[*] Sudo permissions   → identified sudo git access
[*] GTFOBins           → abused sudo git → ROOT ✓
```

</details>

<details>
<summary><b>🤖 Mr. Robot</b> — Click to expand</summary>

```
[*] WordPress enum     → identified WordPress application
[*] Exploitation       → WordPress Remote Code Execution
[*] Initial Access     → obtained shell access
[*] Priv-esc           → abused SUID nmap
[*] Result             → ROOT ✓
```

</details>

---

## 📊 VulnHub Achievement

<div align="center">

```
                VULNHUB PROGRESS

                      9+
               MACHINES ROOTED

    ┌───────────────────────────────┐
    │ ✓ Aragog                      │
    │ ✓ NullByte                    │
    │ ✓ RickdiculouslyEasy          │
    │ ✓ Basic Pentesting 1          │
    │ ✓ Basic Pentesting 2          │
    │ ✓ Jangow: 1.0.1               │
    │ ✓ DC-1                        │
    │ ✓ DC-2                        │
    │ ✓ Mr. Robot                   │
    └───────────────────────────────┘

            Enumeration
                  ↓
            Exploitation
                  ↓
        Privilege Escalation
                  ↓
                 ROOT
```

</div>
