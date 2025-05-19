# Port Scanning Lab

This lab demonstrates scanning networks and analyzing traffic using tools like Nmap, Zenmap, Fping, and Hping3.

## 🔍 Objectives
- Conduct TCP/UDP scans, fast scans, and stealth scans
- Analyze responses using Wireshark and tcpdump
- Use Zenmap for graphical output
- Scan individual ports, ranges, and all 65535 ports

## 🧰 Tools Used
- Nmap, Zenmap
- Fping, Hping3
- Wireshark
- Windows & Kali VMs

## 📌 Key Techniques
- TCP SYN, Connect, FIN, ACK scans with response analysis
- Identified port status changes with firewall ON/OFF
- Used Wireshark filters (e.g., `tcp.port == 135`) to inspect 3-way handshake
- Hping3 used for crafting custom TCP packets

