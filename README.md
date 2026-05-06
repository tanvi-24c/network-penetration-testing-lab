# 🔐 Network Penetration Testing & Exploitation using Kali Linux

## 📌 Objective

To perform network penetration testing in a controlled lab environment to identify, analyze, and exploit vulnerabilities in a target system.

---

## 🛠️ Tools Used

* Kali Linux
* Nmap
* Metasploit Framework
* Wireshark

---

## 🧪 Lab Setup

| Component        | Details                         |
| ---------------- | ------------------------------- |
| Attacker Machine | Kali Linux                      |
| Target Machine   | Metasploitable2 (Vulnerable VM) |
| Network          | Virtual Lab Environment         |

---

## 🔍 Methodology

### 1️⃣ Reconnaissance (Scanning)

Performed network scanning to identify live hosts, open ports, and running services.

### 2️⃣ Enumeration

Gathered detailed information about services and identified potential vulnerabilities.

### 3️⃣ Exploitation

Used Metasploit Framework to exploit identified vulnerabilities and gain access to the system.

### 4️⃣ Post Exploitation

Verified system access and analyzed compromised system behavior.

---

## 🔄 Attack Flow

Kali Linux → Nmap Scan → Vulnerability Identification → Exploitation (Metasploit) → System Access

---

## ⚡ Commands Used

```
nmap -sV <target-ip>
msfconsole
search exploit
use exploit/...
set RHOST <target-ip>
exploit
```

---

## 🧨 Vulnerabilities Identified

* vsftpd backdoor vulnerability
* Open ports exposing critical services
* Weak authentication mechanisms

---

## 📊 Results

* Discovered open ports (21, 80, 443)
* Identified vulnerable services
* Successfully exploited target system
* Gained unauthorized access using Metasploit
* Demonstrated real-world attack scenario

---

## 📸 Screenshots

### 🔹 Nmap Scan

Performed scanning to identify open ports and services
![Nmap Scan](nmap.png)

### 🔹 Exploitation using Metasploit

Successfully gained access to the target system
![Metasploit](metasploit.png)

### 🔹 Wireshark Analysis

Captured and analyzed network traffic
![Wireshark](wireshark.png)

---

## 🔐 Security Recommendations

* Close unused ports
* Update and patch vulnerable services
* Implement firewall rules
* Use Intrusion Detection Systems (IDS)
* Enforce strong authentication mechanisms

---

## 📌 Conclusion

This project demonstrates practical implementation of penetration testing techniques including reconnaissance, enumeration, exploitation, and post-exploitation using Kali Linux tools. It highlights real-world vulnerabilities and emphasizes the importance of securing network systems.

---

## ⚠️ Disclaimer

This project was conducted in a controlled lab environment for educational purposes only. Unauthorized testing on real systems is illegal.

---

## 📄 Full Report

[Click here to view detailed report](Report.md or https://docs.google.com/document/d/1ihAsTqPQAUYJOuwdr8tCRWkjxEnYX3mb9-o8Ip52oFA/edit?usp=sharing)

