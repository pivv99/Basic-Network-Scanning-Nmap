# Basic Network Scanning and Port Discovery using Nmap

## Objective
The objective of this lab was to practice basic network reconnaissance and host discovery using Nmap in a controlled lab environment.

## Tools Used
- Kali Linux
- Nmap

## Scope
The scan was performed in a safe practice environment for educational purposes only.

## Activities Performed
- Performed host discovery to identify active systems on the network
- Conducted basic port scanning to identify open ports
- Reviewed service exposure and common network services
- Interpreted scan results to understand possible attack surfaces


Key Findings
Identified active hosts within the network range
Detected open ports such as:
22 (SSH)
80 (HTTP)
443 (HTTPS)
Observed how exposed services may increase attack surface if not properly secured
Skills Demonstrated
Network reconnaissance
Host discovery
Port scanning
Service enumeration
Basic attack surface analysis
Learning Outcome


## Example Commands Used
```bash
nmap -sn 192.168.1.0/24
nmap -sV 192.168.1.10
nmap -Pn 192.168.1.10
