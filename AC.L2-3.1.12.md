---
type: ssp
controls: AC
control: AC.L2-3.1.12
tags: note
---

# AC.L2-3.1.12

Goal: Monitor and control remote access sessions.

Related controls: AC.L2-3.1.14, AC.L2-3.1.13, AC.L2-3.1.15, IA.L2-3.5.3, MA.L2-3.7.5

Tasks:

- Access Control Policy. Define conditional access policies for remote access.
- Default Deny on all remote access on all systems.
- Enforce MFA Everywhere.
- Configure audit logging on all systems for user login events, both Success and Failure.

User Impact:

- None.

## Remote Access

Remote access is access to organizational information systems by users (or processes acting on behalf of users) communicating through external networks (e.g., the Internet). PDW requires that all remote access sessions be monitored. Remote access to PDW information systems are managed via VPN in the case of the local LAN and via SaaS login portals in the case of SaaS products.

## Remote Access Monitoring and Control

All connections to the PDW information system utilize FIPS 140-2 validated encryption modules. PDW defines remote access users as PDW employees authorized for this purpose depending on the environment. Users are required to meet program obligations. Remote access events and audit logs are reviewed weekly. Weekly auditing of network devices will be implemented.

## Reference

NIST SP 800-53 Rev 5: AC-17(1)