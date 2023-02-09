---
type: control
control-family: Access Control
control: AC.L2-3.1.13
responsible-entities:
implementation-status:
---

# AC.L2-3.1.13

Goal: Employ cryptographic mechanisms to protect the confidentiality of remote access sessions.

Tasks:

- Access Control Policy. Define cryptographic mechanisms for remote access. CMMC requires FIPS-validated cryptography, not just FIPS-compliant algorithms.
- Configure Wireless Access to meet FIPS-validated cryptography.
- Document all FIPS validated modules used in remote access.

User Impact:

- None.

## Remote Access Encryption

All remote connections to PDW systems are required to use FIPS 140-2 validated encryption methods when possible. If certain systems cannot use encryption methods, then they will be properly documented. FIPS will be enabled on all endpoint devices. If FIPS must be disabled on an endpoint device for troubleshooting or maintenance, those devices will be identified in the Configuration Baseline.

## Reference

NIST SP 800-53 Rev 5: AC-17(2)