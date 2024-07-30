# PRODIGY_CS_05
Packet Sniffer

A Python-based packet sniffer using Scapy to capture, analyze, and save network packets. This tool is useful for network monitoring, debugging, and educational purposes.

Features

Capture Packets: Sniffs packets from a selected network interface. Protocol Analysis: Analyzes IP, TCP, UDP, and ICMP packets. Packet Storage: Saves captured packets to a .pcap file. User Interface: Command-line interface to select network interfaces and control the sniffer. Requirements

Python 3.x Scapy Keyboard Installation

Clone the Repository

cd packet-sniffer Install Dependencies

pip install scapy keyboard Usage

Run the Packet Sniffer

python networkanalyser.py Select a Network Interface

The script will list all available network interfaces. Enter the index of the interface you want to sniff on. Start Sniffing

The sniffer will start capturing packets on the selected interface. Press Esc to stop sniffing. Captured Packets

The captured packets will be saved to captured_packets.pcap in the current directory
