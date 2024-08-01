# Simple Intrusion Detection System (IDS)

A basic IDS that monitors network traffic for potential intrusions by detecting packets on common malicious ports and logging suspicious activity.

## Features
- Real-time network traffic monitoring
- Detection of common malicious ports
- Logging of potential intrusions

## Requirements
- Python 3.x
- Scapy library

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/D-MW/Simple-Intrusion-Detection-System.git
   cd Simple-Intrusion-Detection-System

Install the required library:
sh
Copy code
pip install scapy
Usage
Ensure you have the necessary permissions to sniff network traffic. On Unix-based systems, you might need to run the script with sudo.

Run the script:

sh
Copy code
sudo python simple_ids.py
The script will start sniffing on the specified network interface and log any potential intrusions to intrusion_log.txt.

Configuration
You can change the network interface by modifying the network_interface variable in the script.
Add or remove ports from the malicious_ports list as needed.
