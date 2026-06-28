<h1 align="center">Michael Asante Anim</h1>

<h3 align="center">
Full-Stack Developer &nbsp;|&nbsp; Web Application Security &nbsp;|&nbsp; Penetration Testing &nbsp;|&nbsp; Building & Securing Systems
</h3>

<p align="center">
  <a href="https://tryhackme.com/p/Aerixis" target="_blank">
    <img src="https://tryhackme-badges.s3.amazonaws.com/Aerixis.png" alt="TryHackMe" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anim-michael-asante&label=Profile%20views&color=0e75b6&style=flat" />
</p>

---

## About Me

BSc Cybersecurity student at the **University of Mines and Technology (UMaT), Tarkwa, Ghana** — building at the intersection of secure full-stack development and offensive security.

- Building production-grade **Django web applications** with OWASP-first security design
- Systematically working through **PortSwigger Web Security Academy** — 22 labs completed across SQL Injection and Path Traversal, with professional write-ups published on GitHub
- Preparing for the **ISC2 CC exam** (July 2026) — all five domain courses completed
- Pursuing the **BSCP certification pathway** (eWPT → OSCP long-term)
- Running an active **VMware home lab** — Windows Server 2022 (DC), Windows 10, and Kali Linux attacker machine
- Enrolled in the **One Million Coders Ghana** program
- Personal brand: **0x1aerixis** — cybersecurity and development content on X and GitHub

**Email:** [animmichaelasante@gmail.com](mailto:animmichaelasante@gmail.com)

---

## Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Databases & Infrastructure**

![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Security & Pentesting**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-214478?style=for-the-badge&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![OWASP](https://img.shields.io/badge/OWASP-000000?style=for-the-badge&logo=owasp&logoColor=white)

---

## Projects

### SecureVault — Enterprise Role-Based Encrypted File Portal

A production-ready Django application built around the principle of least privilege and encryption-at-rest.

- AES-256 file encryption using Fernet with per-file unique keys
- PBKDF2-HMAC-SHA256 master key derivation (100,000 iterations)
- Role-based access control across 8 departments and 9 roles
- Full audit logging — every file access recorded with timestamp and IP
- On-the-fly decryption served directly to authorized users only

**Security Considerations:** Designed to mitigate Broken Access Control (OWASP A01), Cryptographic Failures (OWASP A02), and Insecure Design (OWASP A04).

![Python](https://img.shields.io/badge/Python-3.11+-blue?style=flat-square)
![Django](https://img.shields.io/badge/Django-4.2+-green?style=flat-square)
![AES-256](https://img.shields.io/badge/Encryption-AES--256-red?style=flat-square)

---

### Aerixis-ShopNow — Django E-Commerce Platform

A full-stack e-commerce application with a custom admin dashboard — built with security-conscious backend design.

- Product management, cart, and checkout flow
- Custom admin panel at `/panel/` with order and inventory controls
- CSRF protection, input validation, and session security applied throughout
- Clean responsive UI built with Tailwind CSS

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![Django](https://img.shields.io/badge/Django-4.2-092E20?style=flat&logo=django&logoColor=white)](https://djangoproject.com)
[![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=flat&logo=sqlite&logoColor=white)](https://sqlite.org)

---

## Cybersecurity

**PortSwigger Web Security Academy**
- 22 of 263 labs completed — SQL Injection (16 labs), Path Traversal (6 labs)
- Professional write-ups for every lab: CVSS v3.1 scoring, CWE mapping, OWASP classification, MITRE ATT&CK mapping, full attack chain, and remediation guidance
- Write-ups published at [`github.com/anim-michael-asante/portswigger-web-security-writeups`](https://github.com/anim-michael-asante/portswigger-web-security-writeups)
- Target: **BSCP certification** (eWPT → OSCP long-term pathway)

**ISC2 Certified in Cybersecurity (CC) — Exam Prep**
- All five domain courses completed: Security Principles, Incident Response/BC/DR, Access Controls, Network Security, Security Operations
- Exam target: July 2026

**Academic Lab Work**
- **CY375 (Network Security):** ARP spoofing attack and DAI mitigation lab — VMware home lab with Windows Server 2022, Windows 10, and Kali Linux
- **CY384 (Cybersecurity Lab II):** Structured vulnerability assessment of gra.gov.gh — confirmed CVE-2024-2876, CVE-2023-6528, and CVE-2026-3222 using WPScan and Nessus; produced formal proposal and group presentation

**CTF & Practice**
- NEST CTF (Nkonsonkon Bank scenario) — SSH brute-force, OSINT, and web application testing
- TryHackMe — Jr Penetration Tester path

**Home Lab Environment**
- VMware-based lab: Windows Server 2022 (Domain Controller), Windows 10 (client), Kali Linux (attacker)
- Active directory attacks, network traffic analysis, privilege escalation, and password cracking exercises (John the Ripper, Hashcat)

**Security in Development**
- Applying OWASP Top 10 principles directly in every project
- Mitigating CSRF, RBAC misconfigurations, injection vulnerabilities, and insecure cryptographic storage by design

**Community**
- Organized **CyberWatch Ghana** webinar at UMaT — produced associated group report
- UMaT Cybersecurity Club — organizational and leadership capacity

---

## Certifications

**ISC2**

| Certification | Date |
|---|---|
| ISC2 Candidate (Credly, exp. May 2027) | — |
| CC Domain 1: Security Principles | May 2026 |
| CC Domain 2: Incident Response, BC/DR | May 2026 |
| CC Domain 3: Access Controls Concepts | May 2026 |
| CC Domain 4: Network Security | May 28, 2026 |
| CC Domain 5: Security Operations | May 31, 2026 |

**Google / Coursera**

| Certification | Date |
|---|---|
| Foundations of Cybersecurity | May 28, 2026 |
| Accelerate Your Job Search with AI | May 28, 2026 |

**Cisco Networking Academy**

| Certification | Date |
|---|---|
| Introduction to Cybersecurity | Sep 27, 2024 |
| Networking Basics | Oct 17, 2024 |
| Python Essentials 1 | Oct 15, 2024 |
| Networking Devices and Initial Configuration | Nov 27, 2024 |
| JavaScript Essentials 1 | Dec 05, 2024 |
| JavaScript Essentials 2 | Jan 20, 2025 |
| Network Addressing and Basic Troubleshooting | Jan 15, 2025 |
| Python Essentials 2 | May 13, 2026 |

**Anthropic Academy**

| Certification |
|---|
| AI Capabilities and Limitations |
| Introduction to Agent Skills |
| AI Fluency: Framework & Foundations |
| AI Fluency for Educators |
| AI Fluency for Students |
| Certificate of Completion: Claude 101 |

**Other**

| Certification | Issuer |
|---|---|
| Python | Kaggle |
| Zero Trust Cyber Security Model (CPD Certified) | Alison |

---

## GitHub Stats

<p align="center">
  <img 
    src="https://github-readme-stats.vercel.app/api?username=anim-michael-asante&theme=dark&show_icons=true&hide_border=true&cache_seconds=1800" 
    alt=""
  />
  <br/>
  <img 
    src="https://streak-stats.demolab.com?user=anim-michael-asante&theme=dark&hide_border=true&cache_seconds=1800" 
    alt=""
  />
  <br/>
  <img 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=anim-michael-asante&theme=dark&layout=compact&hide_border=true&cache_seconds=1800" 
    alt=""
  />
</p>

---

## Connect

<p align="left">
  <a href="https://linkedin.com/in/michael-asante-anim" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="30"/>
  </a>
  <a href="https://tryhackme.com/p/Aerixis" target="_blank">
    <img src="https://img.shields.io/badge/TryHackMe-Profile-FF6A00?style=for-the-badge&logo=tryhackme&logoColor=white" height="30"/>
  </a>
  <a href="https://x.com/0x1aerixis" target="_blank">
    <img src="https://img.shields.io/badge/X-0x1aerixis-000000?style=for-the-badge&logo=x&logoColor=white" height="30"/>
  </a>
  <a href="mailto:animmichaelasante@gmail.com">
    <img src="https://img.shields.io/badge/Email-animmichaelasante@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="30"/>
  </a>
</p>

---

<p align="center">
  <sub>BSc Cybersecurity · University of Mines and Technology, Tarkwa · 0x1aerixis · Built by Grace.</sub>
</p>
