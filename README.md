# Packet Sniffer

## Objective

This is a basic Network Sniffer/Scanner where it will detect the devices on your network and prints the local IP address along the MAC address

### Skills Learned

- Networking Fundamentals: Understanding of network protocols (TCP/IP, UDP, HTTP, etc.), IP addressing, and subnetting.
- Socket Programming: Skills in creating and managing network connections, sending, and receiving data.
- Port Scanning Techniques: Knowledge of different methods for scanning open ports and services on a network.
- Packet Analysis: Ability to capture and analyze network packets, possibly using tools like Wireshark.
- Security Best Practices: Understanding of ethical considerations and security measures to avoid misuse.
- Development of critical thinking and problem-solving skills in cybersecurity.


1. Sniff_Tool.py
_________________

I have used argparse and scapy to make this basic network scanner.

[Syntax : python &lt;file_name&gt; -ip &lt;ip_address&gt;/&lt;subnet&gt;]

[NOTE : Use it with root/administrative priviledges]

One needs to have argparse and scapy installed.

They can be installed with :

   pip install argparse

   pip install scapy
   
   
   
   OUTPUT : 
   
   {'ip': '192.168.1.1', ' mac': '7c:a9:6b:07:6e:14'}
   
   {'ip': '192.168.1.3', ' mac': '88:11:96:ff:79:a0'}
   
   {'ip': '192.168.1.10', ' mac': '68:db:f5:84:80:7f'}
   
   {'ip': '192.168.1.4', ' mac': 'd4:f5:47:17:b0:a6'}
   
   {'ip': '192.168.1.14', ' mac': 'a4:c3:f0:4f:a5:06'}
   
   {'ip': '192.168.1.2', ' mac': '6c:56:97:b0:fe:b3'}
   
   {'ip': '192.168.1.26', ' mac': '28:6c:07:8c:96:f5'}

   

2. Sniff_Tool2.py
__________________

I have used sys and scapy to build this basic network scanner.

Call it from the command line using root/admin privileges

[Syntax : python &lt;file_name&gt; &lt;ip_address&gt;/&lt;subnet&gt;]

[Note : Put the ip address of your default gateway(router) to get all the client's ip address.]
Scapy can be installed with : 
  
   pip install scapy

