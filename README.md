# Task-1: Local Network Open Port Scan

## Objective
To identify open ports in my local network using Nmap.

## Command Used
```bash
sudo nmap -sS 192.168.80.128 /24

OBSERVATIONS

| IP Address     | Open Ports | Service | Risk Summary / Remark                     |
| -------------- | ---------- | ------- | ----------------------------------------- |
| 192.168.80.1   | —          | —       | No open ports detected                    |
| 192.168.80.2   | 53         | DNS     | DNS service running – responds on port 53 |
| 192.168.80.254 | —          | —       | No open ports detected                    |
| 192.168.80.128 | —          | —       | No open ports detected                    |

Conclusion
Only one device in the scanned subnet (192.168.80.2) exposed an open port (DNS on port 53). The minimal number of open services detected suggests a relatively secure network posture with limited external exposure.
