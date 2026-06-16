# 🔴 VAPT Lab Portfolio

A hands-on Vulnerability Assessment and Penetration Testing lab built on VirtualBox.
All testing conducted in an isolated environment for educational purposes.

## 🖥️ Lab Environment

| Machine | Role | IP |
|---------|------|----|
| Kali Linux | Attacker | 192.168.56.102 |
| Metasploitable 2 | Target | 192.168.56.101 |

## 📋 Machines Completed

| # | Machine | Difficulty | Vulnerabilities | Report |
|---|---------|------------|-----------------|--------|
| 1 | Metasploitable 2 | Easy | 6 Critical/High | [View](01-Metasploitable/report/) |
| 2 | Mr. Robot | Medium | Coming soon | — |

## ⚔️ Attacks Demonstrated

- vsftpd 2.3.4 Backdoor RCE (CVE-2011-2523)
- Samba Usermap Script RCE (CVE-2007-2447)
- MySQL Unauthenticated Root Access
- UnrealIRCd Backdoor RCE (CVE-2010-2075)
- distccd RCE + SUID Privilege Escalation (CVE-2004-2687)
- DVWA — SQLi, XSS, File Upload RCE

## 🛠️ Tools Used

Nmap | Metasploit | Nikto | Gobuster | Netcat | Enum4linux | Searchsploit

## 📊 Skills Demonstrated

- Network reconnaissance and service enumeration
- Exploitation of known CVEs
- Linux privilege escalation techniques
- Professional VAPT report writing
- CVSS scoring and MITRE ATT&CK mapping

## ⚠️ Disclaimer
All testing was performed in an isolated lab environment.
No real systems were harmed.
