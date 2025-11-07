# Introduction to Computer Security: Windows Threat Analysis

A comprehensive research project on Windows computer security, focusing on 
common threats, attack vectors, and defense mechanisms with practical 
demonstrations.

## 📚 Project Overview

This research explores the cybersecurity landscape of Windows operating 
systems, examining various attack methodologies and malware types that 
specifically target Windows environments. The project includes both 
theoretical analysis and practical lab demonstrations.

## 🎯 Key Topics Covered

### Malware Analysis
- **Ransomware**: WannaCry, Ryuk, LockBit
- **Spyware**: Keyloggers, screen capture, data theft
- **Trojans**: Backdoor, banking, DDoS trojans
- **Rootkits**: Firmware, kernel, bootloader, user-mode

### Attack Vectors
- **DoS/DDoS Attacks**: SYN flood, UDP flood, HTTP flood, DNS flood
- **Man-in-the-Middle**: ARP poisoning, IP spoofing, packet sniffing
- **Phishing**: Real-world examples and attack process
- **Vulnerability Exploitation**: 
  - Macro exploits (CVE examples)
  - HTA exploits (CVE-2017-0199)
  - CHM exploits (CVE-2017-8570)
  - JS-Web exploits (XSS, Clickjacking)
  - WinRAR exploits (CVE-2018-20250)

### Malicious Code Anatomy
- Payloads (staged vs stageless)
- Shellcode
- C2 communication
- Persistence mechanisms
- Evasion techniques

### Defense Strategies
- Best security practices
- Windows 11 security features
- System hardening
- Network protection

## 🛠️ Lab Demonstrations

### Virtual Environment Setup
- VirtualBox configuration
- Windows 10/11 victim machines
- Kali Linux attack platform

### Practical Demonstrations
1. **Backdoor Creation**: Using NJRAT for remote access
2. **Macro Exploitation**: Metasploit payload generation and delivery
3. **Phishing Attack**: Social engineering demonstration using Blackeye

## 📖 Full Report

The complete research report (91 pages) is available in the 
[`report/`](./report) directory.

## ⚠️ Disclaimer

This research is for **educational purposes only**. All demonstrations 
were conducted in isolated virtual environments. The techniques described 
should only be used for legitimate security testing and research with 
proper authorization.

## 🎓 Academic Context

- **Institution**: National Engineering School of Tunis (ENIT)
- **Department**: Information and Communication Technologies
- **Project Type**: Final Year Project I
- **Date**: 2023-2024
- **Supervisor**: Mr. HAMMAMI Hamza

## 👥 Authors

- MIGHRI Manar
- CHERNI Oussema


## 📚 Key References

- NIST Cybersecurity Framework
- MITRE ATT&CK Framework
- Microsoft Security Documentation
- CVE Database

## 🤝 Contributing

This is an educational research project. If you find errors or have 
suggestions for improvements, feel free to open an issue.

## 📄 License

This project is licensed under the MIT License - see LICENSE file for 
details.

---

**Note**: All attack demonstrations were performed in controlled, 
isolated virtual environments for educational research purposes only.
