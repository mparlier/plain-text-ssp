---
type: control
control-family: Access Control
control: AC.L2-3.1.16
responsible-entities:
implementation-status:
---

# AC.L2-3.1.16

Goal: Authorize wireless access prior to allowing such connections.

Tasks:

- Access Control Policy. Only company-approved devices that contain verified security configuration settings are allowed to connect to the PDW information system. The policy will also include usage restrictions that must be followed for anyone who wants to use the wireless network. Authorization is required before devices are allowed to connect to the wireless network.
- PDW-Guest has been created for non-PDW devices and does not have access to the LAN.
- Create Hardware Baseline of approved network devices.

User Impact:

- If people have been connecting personal devices to pdw-ewlan, these will have to be removed from the system and connected to pdw-guest instead.

## Reference

NIST SP 800-53 Rev 5: AC-18