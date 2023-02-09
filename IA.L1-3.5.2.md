---
type: ssp
controls: IA
control: IA.L1-3.5.2
tags: note
---

# IA.L1-3.5.2

Goal: Authenticate (or verify) the identities of users, processes, or devices, as a prerequisite to allowing access to organizational systems.

800-53 Controls: IA-2, IA-3, IA-5

Tasks:

- Utilize unique naming convention practices based on unique device identifiers.
- IA Policy. Define device naming convention based on unique device identifiers: either by Serial or by MAC address depending on device type.
- In the case of Windows, set device name upon Endpoint Management enrollment.
- macOS, Linux - Manual renaming might be necessary.
- Document offboarding procedures for revoking access to systems that include key fobs, user access tokens, user accounts, etc. 

User Impact:

## Reference

NIST SP 800-53 Rev 5: IA-2 IA-3, IA-5