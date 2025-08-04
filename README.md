# Scan-your-local-network-for-open-ports-
This Repo demonstrates how to perform a network reconnaissance using Nmap and analyze the results with Wireshark.

🔧 Tasks Performed
Installed Nmap and Wireshark on local system.

Identified the local IP range (192.168.1.0/24) for scanning.

Conducted a TCP SYN scan using Nmap to discover active hosts and open ports.

Found open ports on host 192.168.1.1:

21/tcp FTP

22/tcp SSH

53/tcp DNS

80/tcp HTTP

Captured network traffic with Wireshark and analyzed Nmap scan packets using filters.

Researched common vulnerabilities for detected services (e.g., FTP credential leakage, SSH brute-force risk, DNS amplification, HTTP XSS).

Summarized potential risks and mitigation strategies.

📊 Key Tools
Nmap: Network scanner for port and service detection.

Wireshark: Packet analyzer for inspecting scan traffic and identifying service responses.

📁 Output
Nmap scan results saved in text format.

Documented observations, possible vulnerabilities, and mitigation guidance.
