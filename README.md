PRODIGY_CS_05 - Network Packet Analyzer

Description

The Network Packet Analyzer is a Python-based cybersecurity tool designed to capture and analyze network packets in real time. It provides detailed information about network traffic, including source and destination IP addresses, protocols, ports, and packet payloads. This project helps users understand how data travels across networks and is intended for educational and ethical learning purposes.

Features

- Capture live network packets
- Analyze TCP, UDP, and ICMP protocols
- Display source IP addresses
- Display destination IP addresses
- Show source and destination port numbers
- View packet payload data
- Start and stop packet capture
- Clear captured packet logs
- User-friendly graphical interface
- Educational and ethical use warning

How It Works

1. The user starts packet capturing by clicking the Start Capture button.
2. The application listens for network traffic on the system.
3. Each captured packet is analyzed using Scapy.
4. Important details such as protocol, source IP, destination IP, ports, and payload are extracted.
5. The analyzed information is displayed in the GUI.
6. The user can stop capturing packets using the Stop Capture button.
7. The Clear button removes all displayed packet logs.

Technologies Used

- Python 3
- Scapy
- Tkinter
- Threading
- Socket Programming

How to Run

 1.Install Required Package

 2.pip install scapy

 3.Run the Program

 4.python network_packet_analyzer.py

Example Output

Protocol : TCP

Source : 192.168.1.10:54231

Destination : 142.250.183.14:443

Payload : Example packet data
