# Network_reconnaissance

📌 Objective

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

eg - nmap -sS 192.168.0.0/24

 4. Recorded IP addresses and open ports found.
 5. (Optional) Used Wireshark to capture and analyze packets.
 6. Researched the services running on detected ports and noted potential risks.

⸻

📊 Sample Results
 • Example output of Nmap scan:

Nmap scan report for 192.168.0.15

PORT     STATE SERVICE
80/tcp   open  http


 • Risks identified:
 
 • Port 80 (HTTP): Unencrypted traffic can be intercepted.


⸻

🧩 Key Learnings
 • Gained hands-on experience with TCP SYN scanning.
 • Understood how open ports reveal network exposure.
 • Learned how attackers can use port scanning as reconnaissance.
 • Explored how Wireshark complements Nmap by providing packet-level insights.


⸻

