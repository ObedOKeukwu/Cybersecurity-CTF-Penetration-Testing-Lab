# Cybersecurity CTF Penetration Testing Lab

## Overview

This repository documents instructor-authorized Capture the Flag (CTF) and penetration testing exercises conducted in a controlled laboratory environment using intentionally vulnerable virtual machines. The objective was to demonstrate practical cybersecurity skills including reconnaissance, enumeration, vulnerability assessment, exploitation, privilege escalation, post-exploitation, and Active Directory enumeration.

All activities were performed within the defined Rules of Engagement and limited strictly to authorized lab systems.

---

## Objectives

This project demonstrates hands-on experience in:

* Network Reconnaissance
* Host Discovery
* Service Enumeration
* Vulnerability Assessment
* Exploit Research
* Penetration Testing
* Privilege Escalation
* Post-Exploitation
* Active Directory Enumeration
* Credential Discovery
* Remote Access Validation
* Security Documentation

---

# Lab Environment

| Component              | Technology                        |
| ---------------------- | --------------------------------- |
| Attacker System        | Kali Linux                        |
| Target Systems         | Windows XP, Windows Server, Linux |
| Exploitation Framework | Metasploit                        |
| Network Scanning       | Nmap                              |
| Password Testing       | Hydra                             |
| Remote Access          | RDP, SSH                          |
| Enumeration            | SMB, SSH, Active Directory        |
| Post Exploitation      | Meterpreter                       |

---

# Target 1 – Linux Server (192.168.202.147)

## Reconnaissance

* Host discovery
* TCP port scanning
* Service enumeration
* SSH fingerprinting

## Enumeration

* SSH enumeration
* Hydra authentication testing
* FTP service verification
* Searchsploit vulnerability research

## Results

* OpenSSH service identified
* Service enumeration completed
* Authentication testing performed
* No successful compromise achieved

---

# Target 2 – Windows XP (192.168.202.222)

## Reconnaissance

* Host discovery
* Full TCP port scanning
* Service fingerprinting
* SMB enumeration

## Vulnerability Assessment

* SMB vulnerability scanning
* Windows OS identification
* Exploit research

## Exploitation

* Successful exploitation using Metasploit
* Meterpreter session established
* Native shell access obtained

## Privilege Escalation

* NT AUTHORITY\SYSTEM access achieved
* Process migration performed
* Administrative access verified

## Post-Exploitation

* System enumeration
* File discovery
* Flag identification
* Credential artifact discovery

---

# Target 3 – Active Directory Server (192.168.202.35)

## Remote Access

* RDP authentication
* Administrative login

## Active Directory Enumeration

* Domain enumeration
* User discovery
* Administrative account verification

## Post-Exploitation

* Sensitive file discovery
* Password artifact analysis
* Administrative note discovery

---

# Tools Used

* Kali Linux
* Nmap
* Metasploit Framework
* Meterpreter
* Hydra
* FreeRDP
* SMB NSE Scripts
* Searchsploit
* Windows Command Prompt
* Active Directory Users and Computers

---

# Skills Demonstrated

* Network Reconnaissance
* Host Discovery
* Vulnerability Assessment
* Penetration Testing
* Exploit Research
* Exploitation
* Privilege Escalation
* Active Directory Enumeration
* Windows Administration
* Linux Enumeration
* Credential Discovery
* Remote Access Validation
* Post-Exploitation
* Security Documentation

---

# Repository Structure

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

# Disclaimer

All activities documented in this repository were conducted in a controlled, instructor-approved educational laboratory environment using intentionally vulnerable systems. Testing was limited strictly to authorized systems and performed in accordance with ethical cybersecurity practices and the Rules of Engagement.

```
```
