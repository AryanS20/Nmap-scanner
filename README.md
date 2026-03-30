# Nmap-scanner
This project is a simple cybersecurity tool built using Python. It automates basic network scanning tasks like checking if a host is active, viewing devices in the local network, and scanning open ports using Nmap.

The project includes three main scripts:

ping_scanner.py → checks if a system is reachable
arp_scanner.py → shows devices connected to the network
nmap_scanner.py → scans ports and services using Nmap

The main idea of this project is to understand how network scanning works and how we can control system tools using Python.

How to install Nmap

Nmap is required for the nmap_scanner.py script.

For Windows:
Go to https://nmap.org/download.html and download the installer. Follow the setup instructions.

For Linux:
Run this command in terminal:
sudo apt install nmap

For Mac:
If you have Homebrew installed, run:
brew install nmap

To check if installation worked, run:
nmap --version

How to run each program

Make sure Python 3 is installed.

To run the scripts, open terminal in the project folder and use:

python ping_scanner.py
python arp_scanner.py
python nmap_scanner.py

If python does not work, try:
python3 filename.py

Example usage

Ping Scanner:
Run the script and choose whether to scan a single host or a small network range.

Example:
Enter hostname or IP: google.com

Output will show if the host is reachable and response time.

ARP Scanner:
Run the script and it will automatically display IP and MAC addresses of devices in the network.

Example output:
192.168.1.1 AA:BB:CC:DD:EE

Nmap Scanner:
Run the script and enter a target IP or range. Then choose the type of scan.

Example:
Enter target IP: 192.168.1.1
Choose option: 2 (Port Scan)

Output will show open ports and services.
