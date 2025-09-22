# Nmap & Wireshark Assignment
Assignment submission for Nmap and Wireshark
This repository contains my Nmap and Wireshark assignment. It includes the TCP SYN scan results (myscan.nmap) and the corresponding packet capture (myscan.pcap), demonstrating the open ports and services detected on the network.

## Tools Used
- Nmap
- Wireshark

## Files Submitted
- `myscan.nmap` → Nmap scan results
- `myscan.pcap` → Wireshark packet capture

## Scan Details
- Scan type: TCP SYN scan
- Command used: nmap -sS 192.168.56.1/24

## Observations
- Open ports and services were detected on hosts within the network.
- Services include common ones like SSH (22/tcp) and HTTP (80/tcp).
- Potential security risks include exposed services that may be vulnerable to known exploits.
- Packet capture shows SYN requests sent to these hosts and the responses received.
