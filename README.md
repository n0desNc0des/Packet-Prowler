# PacketProwler

PacketProwler is a Python script using Scapy to capture and analyze HTTP requests, filtering specific properties and extracting useful information.

## Prerequisites

- Python 3
- Install required third-party module:
pip install scapy_http

## Usage

1. Clone the repository:
2. https://github.com/n0desNc0des/Packet-Prowler.git
 cd PacketSniffer
Run the packet sniffer with the specified interface:

python packet_sniffer.py -i <interface>
Replace <interface> with the name of your network interface (e.g., eth0, wlan0).

##Features
Captures HTTP requests on ports 80 and 443.
Filters HTTP properties and extracts URLs visited.
Identifies potential username and password information.

Example
python packet_sniffer.py -i wlan0

Disclaimer
This tool is intended for educational and ethical use only. Ensure compliance with legal regulations and obtain proper authorization before using it in any environment.
