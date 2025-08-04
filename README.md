# Task 1 – Scan Local Network for Open Ports

Objective :
Discover open ports on devices in local network to understand network exposure.

Tools Used
- Kali Linux
- Nmap

Steps Followed
1. Found local IP range: 192.168.111.0/24
2. Ran TCP SYN scan:

nmap -sS 192.168.111.0/24

3. Saved result:

nmap -sS 192.168.111.0/24 -oN scan_result.txt

Outcome
- Learned port scanning basics and exposure
- Understood how TCP SYN scan works

Files
- scan_result.txt (Nmap output)
- Screenshot(s): terminal running scan (if added)

Wireshark Capture
-Captured packets during Nmap scan are saved in portscan_capture.pcap.

Interview Questions Prepared
- What is an open port?
- How does Nmap perform TCP SYN scan?
- Risks of open ports, etc.

