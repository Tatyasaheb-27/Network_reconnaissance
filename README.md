# Network_reconnaissance

📌 Objective

tatyadjkskdgsnhcvasfv

The goal is to perform a network reconnaissance scan using Nmap to identify open ports and understand potential security risks in a local network.

⸻

🛠 Tools Used

 • Nmap – For scanning IP ranges and identifying open ports.
 
 • Wireshark (optional) – For analyzing packets captured during scanning.

⸻

🚀 Steps Performed
 1. Installed Nmap from the official site.
    
 2. Identified local IP range using:

ipconfig   # (Windows)  
ifconfig   # (Linux/Mac)

 3. Ran a TCP SYN Scan on my local network:

nmap -sS 192.168.1.0/24

 4. Recorded IP addresses and open ports found.
 5. (Optional) Used Wireshark to capture and analyze packets.
 6. Researched the services running on detected ports and noted potential risks.

⸻

📊 Sample Results
 • Example output of Nmap scan:

Nmap scan report for 192.168.1.1
PORT     STATE SERVICE
22/tcp   open  ssh
80/tcp   open  http
443/tcp  open  https


 • Risks identified:
 • Port 22 (SSH): If weak credentials are used, it may allow brute-force attacks.
 • Port 80 (HTTP): Unencrypted traffic can be intercepted.
 • Port 443 (HTTPS): Generally secure, but vulnerable if SSL/TLS is outdated.

⸻

🧩 Key Learnings
 • Gained hands-on experience with TCP SYN scanning.
 • Understood how open ports reveal network exposure.
 • Learned how attackers can use port scanning as reconnaissance.
 • Explored how Wireshark complements Nmap by providing packet-level insights.


⸻

✅ Interview Question Answers

Check Answers.md for detailed responses to the provided interview questions.

⸻

