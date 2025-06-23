# CyberSecurityInternship-Task-1

# 🔐 Cybersecurity Internship – Task 1 Report

## 📌 Task Title:
**Scanning Local Network for Open Ports using Nmap**

---

## 🧠 Objective:
The objective of this task was to perform **network reconnaissance** on the local network to discover open ports and identify potentially exposed services. This enhances understanding of how attackers can probe for vulnerabilities in a networked environment.

---

## 🛠️ Tools & Technologies Used:
- [Nmap](https://nmap.org/) – For network scanning and port discovery
- [Wireshark](https://www.wireshark.org/) *(optional)* – For packet-level traffic inspection
- Terminal (Linux Environment)
- GitHub – For task submission and documentation

---

## 📡 My Local IP Range:
```bash
192.168.1.0/24
```

##📡Nmap Command Used:

nmap -sS 192.168.1.0/24 -oN scan.txt
