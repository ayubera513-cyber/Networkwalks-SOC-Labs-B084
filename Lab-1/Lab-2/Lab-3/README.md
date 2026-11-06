# Lab 3: Network Reconnaissance & Port Scanning

## Summary
Identified port scanning patterns targeting internal network hosts.

## Key Findings
- High volume of TCP SYN packets detected across sequential ports within short timeframes.
- Identified attacker source IP and responsive open ports using `tcp.flags.syn == 1`.
