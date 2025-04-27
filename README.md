# Reconnaissance and Vulnerability Scanning Practice

This project documents my hands-on practice in reconnaissance, information gathering, and vulnerability scanning using commonly used cybersecurity tools.

---

## 🛠️ Tools Used
- Kali Linux
- Nmap
- Gobuster
- Nikto

---

## 🧠 Activities Performed

### 1. Nmap Scanning

Performed service version detection, OS detection, and full port scanning on the target machine.

- **Command Used:**
  ```bash
      Nmap -p 23 -sV 192.168.233.133 > Nmap_scan.txt

2. Directory Enumeration using Gobuster
Performed directory brute-forcing to discover hidden paths and files on a web server.

Command Used:

bash
Copy
Edit
gobuster dir -u http://127.0.0.1/ -w /usr/share/wordlists/dirb/common.txt
Key Features:

dir: Directory brute-forcing mode

-u: Target URL

-w: Wordlist for discovering hidden directories

Output:
See the file ➔ gobuster_scan.txt

3. Web Vulnerability Scanning using Nikto
Scanned the web server for vulnerabilities, outdated software, and misconfigurations.

Command Used:

bash
Copy
Edit
nikto -h http://127.0.0.1
Key Features:

Detection of security misconfigurations

Identification of outdated server software

Finding default files, scripts, and directories

Output:
See the file ➔ nikto_report.txt

📸 Screenshots

Tool Used	Screenshot Example
Nmap Scan	
Gobuster Scan	
Nikto Scan	
📚 Skills Learned
Basic and Advanced Network Scanning

Port and Service Enumeration

Web Directory Brute-Forcing

Web Server Vulnerability Detection

Practical usage of Kali Linux security tools
