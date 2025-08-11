# Task-5-Capture-and-Analyze-Network-Traffic-Using-Wireshark.
Capturing and Analyzing Network Traffic Using Wireshark.

Objective:  
Capture live network packets using Wireshark, identify basic protocols, and understand their role in communication.

Tools Used:  
- Wireshark (Windows 10)

Project Contents:  
- network_capture_task5.pcap – Packet capture file  
- Wireshark_Report_Task5.pdf – Short analysis report with screenshots  
- README.md – This file  

Steps Performed:  
1. Started Wireshark and selected the active Wi-Fi interface  
2. Generated network traffic by:  
   - Browsing multiple websites  
   - Running `ping google.com` from Command Prompt  
   - Performing a YouTube search  
3. Captured packets for approximately 1 minute  
4. Filtered packets using:  
   - dns – Domain Name System traffic  
   - icmp – Ping/Connectivity check  
   - tcp / tls – Web traffic and secure communication  
5. Saved capture as .pcap file and created a short report  

Protocols Identified:  

| Protocol | Purpose | Example from Capture |
|----------|---------|----------------------|
| DNS      | Resolves domain names to IP addresses | Query for 'google.com' → IP address reply |
| ICMP     | Tests connectivity between devices | 'ping google.com' echo request/reply |
| TCP/TLS  | Handles secure website communication (HTTPS) | Connection to 'youtube.com' over port 443 |

Screenshots in Report:  
- DNS traffic view  
- ICMP traffic view  
- TCP/TLS traffic view
- http traffic view

Outcome:  
- Captured live network packets using Wireshark  
- Successfully filtered and analyzed different protocols  
- Developed hands-on skills in packet analysis and protocol awareness  

Author:  
Mohommad Kaif Hattiwale
