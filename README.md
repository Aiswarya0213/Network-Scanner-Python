# 🔍 Network Scanner Using Python

A simple and effective ARP-based network scanner built in Python using **Scapy**.  
This tool discovers active devices on your local network and displays their **IP Address**, **MAC Address**, and **Hostname**.



## 🚀 Features
✔️ Scans an entire subnet (CIDR supported)  
✔️ Detects active hosts using ARP packets  
✔️ Retrieves IP, MAC, and Hostname  
✔️ Multithreaded scanning for faster results  
✔️ Simple to use  



## 📌 How It Works
1. Takes a network input (example: `192.168.1.0/24`).  
2. Generates all possible host IPs in the subnet.  
3. Sends ARP requests to each address.  
4. Collects replies from active hosts.  
5. Prints a clean table of:
   - IP Address  
   - MAC Address  
   - Hostname  



## 🖥️ Demo Output
```
IP Address       MAC Address       Hostname

192.168.1.1   00:11:22:33:44:55   router.local
192.168.1.5   AA:BB:CC:DD:EE:FF   Unknown
```



## 📦 Installation

```
pip install scapy
```



## 📁 Project Structure
```
├── network_scanner.py     # Main script
├── README.md              # Documentation
```



## 🧠 Technologies Used

- Python

- Scapy

- Threading

- Socket for hostname lookup



## 🛠️ Future Enhancements

- Port scanning support

- Export to CSV/JSON

- GUI/Web dashboard

- Thread pool optimization

- OS fingerprinting



## ⚠️ Disclaimer

This scanner is intended only for educational and authorized use.
Do not scan networks without permission.
