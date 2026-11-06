# Lab 4: FTP Brute-Force Detection

## Summary
Analyzed unencrypted FTP authentication streams to isolate brute-force traffic.

## Key Findings
- FTP Response `530` indicated failed login attempts.
- FTP Response `230` confirmed successful authentication.
- Extracted plain-text passwords directly from `PASS` commands.
