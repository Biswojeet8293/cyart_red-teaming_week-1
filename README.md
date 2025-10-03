# week-1

📋 Lab Overview
This repository documents a complete security assessment workflow using popular penetration testing tools against vulnerable targets like Metasploitable2. Each section builds upon the previous one to simulate real-world attack scenarios and defensive measures.

🛠️ Lab Environment Setup
Required Tools
Kali Linux (Attacker machine)

Metasploitable2 (Target VM)

Windows 10 VM (For post-exploitation)

VMware

Network Configuration

Attacker IP: 192.168.138.129 (Kali)

Target IP: 192.168.138.128 (Metasploitable2)

📊 Exercises
1. 🔍 Network Scanning with Nmap
Tools: Nmap
Objectives:

Service enumeration and version detection

Stealth vs. aggressive scan comparison

Network reconnaissance documentation

2. 🎯 Vulnerability Assessment with OpenVAS
Tools: OpenVAS
Objectives:

Comprehensive vulnerability scanning

CVSS-based risk prioritization

Exploit verification with Metasploit

3. 💥 Exploitation Practice
Tools: Metasploit Framework
Objectives:

Weaponize identified vulnerabilities

Gain initial access

Privilege escalation techniques

Example Exploits:

VSFTPD v2.3.4 Backdoor

Samba usermap_script

4. 🕵️ Post-Exploitation & Persistence
Tools: Mimikatz, Netcat, Scheduled Tasks
Objectives:

Credential dumping and analysis

Persistence mechanism establishment

Reverse shell deployment

5. 🦠 Malware Analysis
Tools: VirusTotal, Hybrid Analysis
Objectives:

Antivirus evasion testing

Sandbox behavior analysis

EICAR test file validation

6. 🔐 Password Security
Tools: KeePassXC, Hydra
Objectives:

Strong password generation and management

Password policy auditing

Weak password cracking demonstration
