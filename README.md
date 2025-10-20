# Scan-Your-Local-Network-for-Open-Port

Steps:
Used Nmap to scan my device and find open TCP ports.
Command: sudo nmap -sS 192.168.29.24 -oN scan_report.txt

Most ports were closed, but I found two active services (upnp and afs3-fileserver)!

Opened Wireshark to capture live network traffic.
Applied some filters, clicked through protocols, and followed a TCP stream to see full conversations.


This assignment helped me get comfortable with scanning, finding open ports, and viewing real network packets.
I now understand how network services and traffic appear on both command line and graphical tools.
