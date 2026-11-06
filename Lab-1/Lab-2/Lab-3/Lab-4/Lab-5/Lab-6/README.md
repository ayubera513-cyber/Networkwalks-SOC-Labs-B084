# Lab 6: VoIP Call Replay & Security Remediation

## Summary
Reconstructed unencrypted RTP voice streams to recover sensitive audio data and evaluated security controls.

## Key Findings
- Utilized Wireshark Telephony (`Telephony > VoIP Calls > Play Streams`) to reconstruct RTP streams.
- Replayed call audio to identify call answerer and invoice payment digits.
- Recommended implementing **SRTP** (Secure Real-time Transport Protocol) to encrypt voice traffic and protect against eavesdropping.
