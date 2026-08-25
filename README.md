<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff88,100:0d1117&height=120&section=header&text=&fontSize=0" width="100%"/>

</div>

<div align="center">

# 👾 RUSHIL VARADE

### `VAPT Engineer` · `Offensive Security` · `SOC Analyst`

<a href="mailto:rushilvarade@gmail.com"><img src="https://img.shields.io/badge/Gmail-rushilvarade%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/rushil-varade"><img src="https://img.shields.io/badge/LinkedIn-Rushil--Varade-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/RushilVarade1405"><img src="https://img.shields.io/badge/GitHub-RushilVarade1405-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=RushilVarade1405&color=00ff88&style=for-the-badge&label=PROFILE+VIEWS"/>

</div>

---

## 🧠 About Me

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
        "Penetration Testing",  "Red Teaming",
        "Digital Forensics",    "Cryptography",
        "SOC Operations",       "Cyber Laws & Compliance",
    ]

    pgp_key    = "2659 48C7 4798 E5AC E7B1  F18A BB7F 7ACE 13B1 743B"

    def mission(self):
        return "Break things ethically. Understand deeply. Secure everything."
```

---

## 💼 Experience

<div align="center">

| Role | Organization | Duration |
|---|---|---|
| 🛡️ **Infra-VAPT Intern** | Talakunchi Networks | Present · On-site |
| 🔎 **Cybersecurity Intern** | NullClass EdTech Private Limited | 06/2025 – 08/2025 · Remote |

</div>

---

## ⚔️ Offensive Toolkit

<div align="center">

| Domain | Tools & Tech |
|---|---|
| 🌐 **Web App Pentesting** | Burp Suite · SQLMap · Nikto · Gobuster · OWASP Top 10 |
| 🔍 **Recon & OSINT** | Nmap · Masscan · Maltego · OSINT Frameworks · Nessus |
| 🕸️ **Network Security** | Wireshark · TCP/UDP · DNS · DHCP · IDS/IPS · VPN · Firewall |
| 💥 **Exploitation** | Metasploit · OpenVAS · Privilege Escalation · Enumeration |
| 🐍 **Scripting & Dev** | Python · Bash · PowerShell · Java · SQL |
| 🖥️ **OS & Infra** | Kali Linux · Windows Server · macOS · Linux Internals |
| 🔬 **Forensics & Blue Team** | Digital Forensics · Splunk SIEM · Cyber Laws · Compliance |
| 🏁 **Labs & CTF** | VulnHub · TryHackMe · OWASP Labs · Advent of Cyber |

</div>

---

## 🔬 VulnHub Lab Write-ups

> **6/6 machines rooted — full pentest methodology:** `Enumeration → Exploitation → Privilege Escalation → Root`

<details>
<summary><b>🏚️ Aragog</b> — Click to expand</summary>

```
[*] Nmap scan          → discovered open ports & services
[*] Gobuster web enum  → found hidden WordPress directories
[*] Exploit            → PHP file inclusion vulnerability
[*] Priv-esc           → misconfigured cron job → ROOT ✓
```
</details>

<details>
<summary><b>💀 Nullbyte</b> — Click to expand</summary>

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
[*] Web directories    → misconfigured dirs revealed flags
[*] Telnet / SSH       → lateral movement & flag capture → ALL FLAGS ✓
```
</details>

<details>
<summary><b>🔧 Basic Pentesting 1</b> — Click to expand</summary>

```
[*] ProFTPD 1.3.3c     → Metasploit known CVE exploit
[*] Kernel priv-esc    → escalated to root via kernel vulnerability → ROOT ✓
```
</details>

<details>
<summary><b>🐮 Jangow: 1.0.1</b> — Click to expand</summary>

```
[*] Command Injection  → exploited web app input to gain shell
[*] CVE-2016-5195      → DirtyCow kernel exploit
[*] Priv-esc           → escalated to root via kernel CVE → ROOT ✓
```
</details>

<details>
<summary><b>🩹 DC-2</b> — Click to expand</summary>

```
[*] WordPress enum     → discovered valid credential set
[*] Credential reuse   → reused creds for SSH access
[*] sudo git GTFOBins  → abused sudo git rights → ROOT ✓
```
</details>

---

## 🚀 Featured Projects

### 🔒 Image Steganography Tool
> **Category:** Security · Cryptography

- LSB (Least Significant Bit) encoding engine that embeds hidden payloads inside **PNG/BMP** images
- **100% payload integrity** with zero perceptible quality loss to the naked eye
- Supports full pipeline: Encode → Decode → Secure Transmission
- Demonstrates covert-channel / DLP-bypass exfiltration techniques

`Python` `Pillow` `LSB Encoding` `Cryptography` `Steganography`

---

### 🤖 Secure Document Summarization Tool *(Major Project)*
> **Category:** AI · NLP · Security

- AI-powered document Q&A system using **Ollama LLM + RAG (Retrieval-Augmented Generation)** architecture
- Supports multi-format ingestion: **PDF · DOCX · TXT**
- **Fully local & offline** — zero data leaves the machine, enterprise-grade privacy
- Features: Summarization · Adaptive Q&A · Contextual learning from document interactions

`Python` `Ollama` `RAG` `NLP` `LangChain` `Local LLM`

---

### 🌐 Cybersecurity Portfolio Platform
> **Category:** Web · Frontend · Education

- Modern, responsive **React + Vite + Tailwind CSS** web application
- Modules covering: Pentesting tools · Cryptography · Cyber Laws · Educational resources
- **Live RSS cybersecurity news feed** integrated
- Fully cross-device responsive: mobile · tablet · desktop
- Live at [ryt-cyberhub.vercel.app](https://ryt-cyberhub.vercel.app)

`React` `Vite` `Tailwind CSS` `JavaScript` `RSS Feed`

---

## 🏅 Certifications & Training

```
✅  Certified Ethical Hacker (CEH)         — EC-Council
✅  Penetration Testing Specialization     — Encrytecl Cyberguard
✅  Cybersecurity Fundamentals             — Encrytecl Cyberguard
✅  Network Fundamentals                   — Encrytecl Cyberguard
✅  Network Security                       — Encrytecl Cyberguard
✅  Ethical Hacking from Scratch           — Udemy
```

---

## 🧪 TryHackMe & Achievements

| Achievement | Focus Area |
|---|---|
| **Advent of Cyber 2025** | 24/24 challenges completed — SQLi · XSS · IDOR · OWASP Top 10 · OpenVAS · Splunk SIEM |
| **Hacker Holidays** | 14-day gamified series — 1 room/day across web, network & priv-esc scenarios |
| **OpenVAS** | Vulnerability scanning, assessment, and reporting |
| **Splunk SIEM** | Log monitoring, alerting, and security event analysis |
| **Linux CLI** | Command-line, file system, process management |


## 📡 Current Status

```
msf6 > show status

[███████████████░░░░░]  75%  WORKING   — Infra-VAPT internship @ Talakunchi Networks
[████████████████████] 100%  CERTIFIED — CEH (EC-Council)
[████████░░░░░░░░░░░░]  40%  SOLVING   — VulnHub machines & CTF challenges
[░░░░░░░░░░░░░░░░░░░░]  00%  SLEEPING  — Not yet. Stay sharp.
```

---

## 🤝 Let's Connect

<div align="center">

| Contact | Details |
|---|---|
| 📧 Email | [rushilvarade@gmail.com](mailto:rushilvarade@gmail.com) |
| 📞 Phone | +91-9136011065 |
| 💼 LinkedIn | [linkedin.com/in/rushil-varade](https://linkedin.com/in/rushil-varade) |
| 🐱 GitHub | [github.com/RushilVarade1405](https://github.com/RushilVarade1405) |
| 📍 Location | Mulund, Mumbai, Maharashtra, India |
| 🔑 PGP Key | `2659 48C7 4798 E5AC E7B1 F18A BB7F 7ACE 13B1 743B` |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff88,100:0d1117&height=100&section=footer&text=Stay+Ethical.+Stay+Sharp.&fontSize=20&fontColor=00ff88&animation=fadeIn"/>

</div>
