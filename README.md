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

## Example Commands Used
```bash
nmap -sn 192.168.1.0/24
nmap -sV 192.168.1.10
nmap -Pn 192.168.1.10
