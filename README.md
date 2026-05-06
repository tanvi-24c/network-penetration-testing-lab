# 🔐 Network Penetration Testing & Exploitation Lab using Kali Linux

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
nmap -sV 192.168.1.5
msfconsole
search exploit
use exploit/...
set RHOST <target-ip>
exploit
```

---

## 🧨 Vulnerabilities Identified


- vsftpd 2.3.4 backdoor vulnerability
- Open ports exposing critical services
- Weak authentication mechanisms
---

## 📊 Results

* Discovered open ports (21, 80, 443)
* Identified vulnerable services
* Successfully exploited target system
* Gained unauthorized access using Metasploit
* Demonstrated real-world attack scenario
- Demonstrated how attackers can gain unauthorized system access
---

## 📸 Screenshots

### 🔹 Nmap Scan

Performed service version detection to identify open ports and running services 
![Nmap Scan](nmap.png)
![Nmap Scan](nmap2.png)
![Nmap Scan](nmap3.png)
### 🔹 Exploitation using Metasploit

Successfully gained access to the target system
![Metasploit](metasploit.png)

### 🔹 Wireshark Analysis

Captured and analyzed network traffic
![Wireshark](wireshark.png)
![Wireshark](wireshark2.png)
![Wireshark](wireshark(1).pcapng)

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

[Click here to view detailed report](Report.md )

