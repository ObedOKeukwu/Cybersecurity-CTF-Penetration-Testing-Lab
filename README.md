# Cybersecurity CTF Penetration Testing Lab

## Project Overview

This repository documents instructor-authorized Capture the Flag (CTF) and penetration testing exercises conducted against intentionally vulnerable systems within a controlled laboratory environment. The objective was to perform reconnaissance, enumeration, vulnerability assessment, exploitation, privilege escalation, post-exploitation activities, and Active Directory enumeration while adhering to defined Rules of Engagement.

The project provides practical experience with industry-standard offensive security methodologies, tools, and post-exploitation techniques commonly used in penetration testing and security assessment engagements.

---

## Objectives

* Perform network reconnaissance and host discovery
* Conduct service and operating system enumeration
* Identify and validate security vulnerabilities
* Perform exploit research and exploitation
* Establish remote access sessions
* Conduct privilege escalation and post-exploitation activities
* Enumerate Active Directory environments
* Locate and validate flag artifacts
* Document findings and attack methodology

---

## Lab Environment

| Component         | Technology                                         |
| ----------------- | -------------------------------------------------- |
| Attacker          | Kali Linux                                         |
| Target 1          | Linux Server (192.168.202.147)                     |
| Target 2          | Windows XP (192.168.202.222)                       |
| Target 3          | Windows Server / Active Directory (192.168.202.35) |
| Exploitation      | Metasploit Framework                               |
| Enumeration       | Nmap, SMB Scripts, Hydra                           |
| Remote Access     | RDP, SSH                                           |
| Post Exploitation | Meterpreter                                        |

---

## Target 1: Linux Server (192.168.202.147)

### Reconnaissance

* Host discovery
* Service enumeration
* SSH fingerprinting

### Enumeration

* SSH enumeration
* Password testing using Hydra
* FTP service validation
* Searchsploit vulnerability research

### Result

* Service identification completed
* Vulnerability assessment completed
* No successful compromise achieved

---

## Target 2: Windows XP (192.168.202.222)

### Reconnaissance

* Full TCP port scanning
* Service fingerprinting
* SMB enumeration

### Vulnerability Assessment

* SMB vulnerability scanning
* Operating system discovery
* Exploit validation

### Exploitation

* Successful exploitation using Metasploit
* Meterpreter session established
* Native shell access obtained

### Privilege Escalation

* NT AUTHORITY\SYSTEM access achieved
* Process migration completed

### Post Exploitation

* System enumeration
* Sensitive file discovery
* Flag identification
* Credential artifact discovery

---

## Target 3: Active Directory Server (192.168.202.35)

### Remote Access

* RDP authentication
* Administrative access verification

### Active Directory Enumeration

* Domain enumeration
* User discovery
* Administrative account validation

### Post Exploitation

* Sensitive file discovery
* Password artifact analysis
* Administrative note discovery

---

## Tools Used

* Kali Linux
* Nmap
* Metasploit Framework
* Meterpreter
* Hydra
* Searchsploit
* FreeRDP
* SMB NSE Scripts
* Windows Command Prompt
* Active Directory Users and Computers

---

## Skills Demonstrated

* Network Reconnaissance
* Host Discovery
* Service Enumeration
* Vulnerability Assessment
* Exploit Research
* Penetration Testing
* Exploitation
* Privilege Escalation
* Active Directory Enumeration
* Windows Administration
* Linux Enumeration
* Credential Discovery
* Remote Access Validation
* Post Exploitation
* Security Documentation

---

## Repository Structure

```text
01-Network-Reconnaissance/
02-Enumeration/
03-Vulnerability-Research/
04-Exploitation/
05-Privilege-Escalation/
06-Remote-Access/
07-Active-Directory/
08-Post-Exploitation/
Reports/
Evidence/
```

---

## Disclaimer

All activities documented in this repository were conducted within an instructor-authorized educational laboratory environment using intentionally vulnerable systems. Testing was limited strictly to authorized targets and performed in accordance with ethical cybersecurity practices and the defined Rules of Engagement.

---

## Author

**Obed Okeukwu**

Cybersecurity Graduate | Security Analyst | Network Security Enthusiast
