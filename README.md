
# Network Scanning & Enumeration Lab

## Overview
This project demonstrates reconnaissance techniques used during the
initial phase of a penetration test. The lab environment simulates
a vulnerable target machine (Metasploitable) and an attacker machine
(Kali Linux).

## Lab Environment

Attacker Machine:
Kali Linux

Target Machine:
Metasploitable

Network:
Host-only isolated lab network

## Tools Used

- Nmap(Network Mapper)
- Netcat
- FTP Client
- Web Browser

## Objectives

- Identify live hosts in the network
- Discover open ports
- Enumerate running services
- Identify potential vulnerabilities

## Methodology

1. Host discovery using Nmap
2. Port scanning
3. Service version detection
4. OS fingerprinting
5. Vulnerability scanning

## Results

The scan identified several vulnerable services including:

- FTP (vsftpd 2.3.4)
- Telnet
- Apache Web Server
- Samba

These services are known to contain exploitable vulnerabilities.

## Key Learning Outcomes

- Understanding reconnaissance methodology
- Service enumeration techniques
- Identifying attack surfaces
