# Phase 1: Network Reconnaissance
**Target:** zero.webappsecurity.com
**Tools:** Nmap 7.98

## Scan Results:
Completed a service enumeration scan (`-sV -Pn`). The following ports were identified:

| Port | State | Service | Version |
| :--- | :--- | :--- | :--- |
| 21/tcp | open | ftp? | - |
| 1720/tcp | open | tcpwrapped | - |
| 8010/tcp | open | tcpwrapped | - |

## Summary & Analysis:
The reconnaissance phase identified an open FTP port (21). This is a critical finding as FTP can be susceptible to anonymous login or brute-force attacks if not properly secured. The high-number ports (1720, 8010) are "tcpwrapped," suggesting they might be protected by a firewall or a specific security configuration.