 Network Reconnaissance with Nmap

## Project Overview
This project demonstrates a basic network reconnaissance task using Nmap on a Kali Linux environment. The goal was to perform a TCP SYN scan on my local network, identify active hosts and open ports, and understand the potential security implications of the exposed services.

## Tools Used
* *Nmap:* For network scanning.
* *Kali Linux:* The operating system used.
* *Wireshark (Optional):* For analyzing packet captures.

## Steps Performed
1.  *Identified Local IP Range:* Used the ip a command to find my network range (192.168.1.0/24).
2.  *Performed a TCP SYN Scan:* Ran nmap -sS 192.168.1.0/24 to scan the network.
3.  *Analyzed Open Ports:* Researched the services running on the discovered open ports.
4.  *Identified Security Risks:* Documented potential risks associated with the open ports.

## Files in this Repository
* scan_results.txt: The raw output from the Nmap scan.
* nmap-scan-output.png: A screenshot of the Nmap terminal output.
* wireshark-capture.png: (If applicable) A screenshot of the packet capture in Wireshark.

## Findings
(Add your specific findings here, e.g., "I found SSH (port 22) and HTTP (port 80) open on my router...")
