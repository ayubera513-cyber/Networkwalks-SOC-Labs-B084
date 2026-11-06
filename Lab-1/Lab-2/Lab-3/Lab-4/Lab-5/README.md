# Lab 5: VoIP Signalling & SIP Analysis

## Summary
Inspected Voice over IP setup signaling to retrieve call session details.

## Key Findings
- SIP protocol used for call setup (`INVITE`, `180 Ringing`, `200 OK`).
- Extracted caller extension numbers and user identities from SIP `From:` headers.
- Identified audio payload codecs (e.g., G.711 PCMU/PCMA).
