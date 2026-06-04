<!--
╔══════════════════════════════════════════════════════════════╗
║             RAHUL SUNOURI — GITHUB PROFILE README            ║
╚══════════════════════════════════════════════════════════════╝
-->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=00FF41&center=true&vCenter=true&width=700&lines=Security+Analyst+%7C+Penetration+Tester+%7C+SOC+Practitioner;Web+App+Pentesting+%7C+Network+Forensics+%7C+Threat+Detection;Wireshark+%7C+Splunk+%7C+Burp+Suite+%7C+Metasploit;Turning+Attacker+Mindset+into+Defensive+Insight;Open+to+Entry-Level+Security+Analyst+Internship+2026)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul_Sunouri-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahul-sunouri)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-Ethrahul-111927?style=for-the-badge&logo=tryhackme&logoColor=red)](https://tryhackme.com/p/Ethrahul)
[![GitHub](https://img.shields.io/badge/GitHub-EthRahul-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EthRahul)

[![Resume](https://img.shields.io/badge/Resume-Download_PDF-FF6633?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/EthRahul/EthRahul/raw/main/Rahul-Sunouri-CV.pdf)
</div>

---

## 〔 01 〕 ABOUT ME

I'm a B.Tech CSE student from Uttarakhand, India, specialising in cybersecurity across both offensive and defensive domains. I don't just study theory — I build tools, document methodologies, and work through real labs to develop skills that translate directly to a SOC or pentesting role.

My approach: **understand how attacks work, then learn to detect and stop them.** That dual perspective — thinking like an attacker while operating like a defender — is what I bring to a security analyst role.

```
Role      →  Security Analyst / Penetration Tester (Entry Level)
Focus     →  Web App Pentesting · Network Security Monitoring · Threat Detection
OS        →  Kali Linux XFCE
Currently →  THM SOC Level 1 · Web App Pentesting (Remaining Modules)
Next      →  DevSecOps · AI Security (Advanced)
Contact   →  linkedin.com/in/rahul-sunouri
```

---

## 〔 02 〕 TECHNICAL ARSENAL

### ⚔️ Offensive Tooling
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-025590?style=for-the-badge&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-2B4A69?style=for-the-badge&logoColor=white)
![SQLMap](https://img.shields.io/badge/SQLMap-E34C26?style=for-the-badge&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-00B4D8?style=for-the-badge&logoColor=white)
![Gobuster](https://img.shields.io/badge/Gobuster-F2CA28?style=for-the-badge&logoColor=black)
![John the Ripper](https://img.shields.io/badge/John_the_Ripper-000000?style=for-the-badge&logoColor=white)
![Netcat](https://img.shields.io/badge/Netcat-4A4A4A?style=for-the-badge&logoColor=white)
![Msfvenom](https://img.shields.io/badge/Msfvenom-025590?style=for-the-badge&logoColor=white)

### 🛡️ Defensive / SOC Tooling
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![NetworkMiner](https://img.shields.io/badge/NetworkMiner-2C3E50?style=for-the-badge&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic_Stack-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Snort](https://img.shields.io/badge/Snort_IDS-E8002D?style=for-the-badge&logoColor=white)
![AbuseIPDB](https://img.shields.io/badge/AbuseIPDB-222222?style=for-the-badge&logoColor=white)

### 🖥️ Languages & Platforms
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)

---

## 〔 03 〕 PROJECTS

### 🔧 [SOC-Log-Analyzer](https://github.com/EthRahul/SOC-Log-Analyzer)
**`Python` `Regex` `AbuseIPDB API` `Threat Intelligence` `SIEM-Ready Output`**

An automated SOC tool that parses Linux `auth.log` files to detect SSH brute-force and credential-stuffing attacks, then enriches extracted IPs with live threat intelligence from AbuseIPDB.

| Feature | Detail |
|---|---|
| 🔍 Detection | Regex-based parsing of failed SSH logins & invalid user attempts |
| 🌐 Threat Intel | Live AbuseIPDB enrichment — abuse score, country, ISP, report count |
| 📊 Reporting | Markdown with 🔴🟡🟢 risk markers + SIEM-ingestible CSV output |
| 🔒 Security | API key managed via `.env` — no hardcoded secrets |
| 🧪 Test Mode | `--mock` flag for offline demo without API keys |
| ⚡ Resilience | Built-in rate-limit handling and configurable request delays |

```python
# Catches patterns like:
# Failed password for invalid user admin from 198.51.100.12 port 50430 ssh2
# Invalid user guest from 198.51.100.12 port 51200 ssh2
r"(?:Failed password for (?:invalid user )?\S+|Invalid user \S+) from (\d{1,3}(?:\.\d{1,3}){3})"
```

---

### 📓 [thm-journey](https://github.com/EthRahul/thm-journey)
**`Markdown` `Obsidian` `110+ Commits` `Notes + Writeups`**

A structured, version-controlled knowledge base documenting 80+ TryHackMe rooms across offensive and defensive paths — built for revision, not just completion.

**Notes Coverage:**

| Path | Topics |
|---|---|
| Cyber Security 101 ✅ | Linux, Networking, Crypto, Metasploit, OWASP Top 10, Burp Suite |
| Jr. Penetration Tester ✅ | Nmap, Web Hacking, Network Security, Privilege Escalation, Shells |
| Web App Pentesting 🔄 | Authentication, JWT, OAuth, Session Management, Upload Vulns |
| SOC Level 1 🔄 | EDR, SIEM, Splunk, Elastic, SOAR, Kill Chains, MITRE ATT&CK, Wireshark, NetworkMiner |
| AI Security ✅ | AI/ML Threat Landscape, Model & Data Security |
| Networking (NetworkChuck) ✅ | Networking fundamentals & protocols from scratch |

**Challenge Writeups:**

| Room | Path | Difficulty |
|---|---|---|
| Blue | Cyber Security 101 | Easy |
| Metasploit Introduction | Cyber Security 101 | Easy |
| Net Sec Challenge | Jr. Penetration Tester | Medium |
| Vulnerability Capstone | Jr. Penetration Tester | Medium |
| Linux PrivEsc Capstone | Jr. Penetration Tester | Medium |

[![View Repository](https://img.shields.io/badge/📓_thm--journey-View_on_GitHub-00FF41?style=for-the-badge&labelColor=0D1117&logo=github&logoColor=white)](https://github.com/EthRahul/thm-journey)

---

> 📌 *DevSecOps tooling and AI Security projects incoming.*

---

## 〔 04 〕 CORE COMPETENCIES

| Domain | Skills |
|---|---|
| 🌐 **Web App Security** | SQLi, XSS, SSRF, Command Injection, File Inclusion, JWT forgery, OAuth abuse, Auth bypass, Upload vulns |
| 🔓 **Pentesting** | Nmap scanning, service enumeration, exploitation via Metasploit, Linux/Windows PrivEsc |
| 🔑 **Auth Attacks** | Brute force (Hydra), session hijacking, MFA bypass, credential stuffing detection |
| 🛡️ **Network Forensics** | pcap analysis (Wireshark/NetworkMiner), MITM/ARP detection, DNS & ICMP tunneling detection, exfil detection |
| 📊 **SOC & Monitoring** | SIEM log analysis (Splunk/Elastic), EDR concepts, SOAR workflows, MITRE ATT&CK & Kill Chain frameworks |
| 🔍 **Threat Detection** | Network discovery detection, data exfiltration indicators, IOC identification |
| 🐍 **Security Tooling** | Built SOC-Log-Analyzer: automated brute-force detection + AbuseIPDB threat intel enrichment in Python |

---

## 〔 05 〕 LEARNING PATH

```
[✅]  Cyber Security 101                              March 2026
[✅]  Jr. Penetration Tester Path                     April 2026
[✅]  Web App Pentesting — Authentication Module       May 2026
[✅]  AI Security — AI/ML Threats & Model Security     May 2026
[✅]  Networking (NetworkChuck)                        May 2026
[🔄]  SOC Level 1 — Network Security Monitoring        In Progress
[🔄]  Web App Pentesting — Remaining Modules           In Progress
[⏳]  DevSecOps Path                                   Next
[⏳]  AI Security (Advanced)                           Next
```

---

## 〔 06 〕 CERTIFICATIONS

| | Certification | Issuer | Date |
|---|---|---|---|
| 🏆 | **Jr. Penetration Tester Path** | TryHackMe | April 2026 |
| 🏆 | **Cyber Security 101 Path** — 56 labs · 45+ hrs | TryHackMe | March 2026 |
| 📜 | **Ethical Hacking Essentials (EHE)** | EC-Council | 2025 |
| 📜 | **Google Cybersecurity Professional Certificate** | Google / Coursera | 2025 |

---

## 〔 07 〕 STATS

<div align="center">

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Ethrahul-red?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0D1117)](https://tryhackme.com/p/Ethrahul)

<br/>

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=EthRahul&theme=react-dark&hide_border=true&bg_color=0D1117&color=00FF41&line=00FF41&point=FF6633)

<br/>

**TryHackMe Profile**

<a href="https://tryhackme.com/p/Ethrahul">
  <img src="https://tryhackme-badges.s3.amazonaws.com/Ethrahul.png" alt="TryHackMe Badge" height="60"/>
</a>

</div>

---

<div align="center">

```
┌──────────────────────────────────────────────────────────────────┐
│  I document everything I learn — because a security professional  │
│  who can't explain their thinking is just guessing.               │
│                                                                   │
│  Open to entry-level Security Analyst / SOC Internship 2026.  ⚡  │
└──────────────────────────────────────────────────────────────────┘
```

[![Profile Views](https://komarev.com/ghpvc/?username=EthRahul&color=00FF41&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/EthRahul)

</div>
