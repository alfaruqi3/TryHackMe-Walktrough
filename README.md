# TryHackMe Walkthroughs

This repository contains my personal walkthroughs, notes, and methodologies for machines and rooms completed on TryHackMe.

The purpose of this repository is to document my learning journey in cybersecurity, improve my enumeration and exploitation skills, and maintain a knowledge base for future reference.

## Disclaimer

These walkthroughs are intended **for educational purposes only**. Please do not use the techniques described here against systems without proper authorization.

---

## Repository Structure

```bash
.
├── Easy/
│   ├── Room-Name/
│   │   ├── README.md
│   │   ├── screenshots/
│   │   └── notes.md
│
├── Medium/
│   ├── Room-Name/
│
├── Hard/
│   └── Room-Name/
│
└── Resources/
    ├── Cheatsheets/
    └── Useful-Commands.md
```

---

## Methodology

My typical approach when solving TryHackMe rooms includes:

### 1. Reconnaissance
- Host discovery
- Port scanning
- Service enumeration
- Web enumeration

Tools:
- Nmap
- Rustscan
- Gobuster
- FFUF
- WhatWeb
- Nikto

### 2. Enumeration
- SMB
- FTP
- SSH
- HTTP
- DNS
- SNMP

Tools:
- enum4linux-ng
- smbclient
- ldapsearch
- dig
- snmpwalk

### 3. Exploitation
- Manual exploitation
- Public exploits
- Metasploit (when applicable)

Tools:
- Burp Suite
- Metasploit
- Searchsploit

### 4. Privilege Escalation
Linux:
- LinPEAS
- GTFOBins
- Sudo abuse
- SUID binaries

Windows:
- WinPEAS
- PowerUp
- SeImpersonatePrivilege abuses

### 5. Post-Exploitation
- Credential harvesting
- Persistence analysis
- Flag collection
- Documentation

---

## Progress

| Difficulty | Completed |
|------------|-----------|
| Easy | 0 |
| Medium | 0 |
| Hard | 0 |

---

## Skills Practiced

- Network Enumeration
- Web Application Security
- Privilege Escalation
- Active Directory Basics
- Password Attacks
- Reverse Shells
- Linux Fundamentals
- Windows Fundamentals
- Vulnerability Assessment
- Basic Red Team Methodology

---

## Notes

Some rooms may contain:
- Alternative exploitation paths
- Additional enumeration techniques
- Personal observations and lessons learned

---

## Author

**Helmi Daimu Afkari Alfaruqi**

Cybersecurity Enthusiast | TryHackMe | Hack The Box | PicoCTF | Root-Me

---

## License

This repository is licensed under the MIT License.
