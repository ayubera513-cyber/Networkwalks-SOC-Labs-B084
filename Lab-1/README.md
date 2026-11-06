# Lab 1: HTTP Traffic Analysis

## Summary
Analyzed HTTP authentication traffic to identify brute-force login attempts and extract credentials.

## Key Findings
- Filtered HTTP response codes (`401` for unauthorized, `200` for successful access).
- Decoded Base64 authentication strings from HTTP headers.
