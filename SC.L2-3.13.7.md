---
type: ssp
controls: SC
control: SC.L2-3.13.7
tags: note
---

# SC.L2-3.13.7

Goal: Prevent remote devices from simultaneously establishing non-remote connections with the information system and communicating via some other connection to resources in external networks(i.e., split tunneling).

Tasks:

-  Configure Fortinet VPN to disallow split tunneling
-  Document - None of our SaaS solutions require VPN. Document their exception and how devices are configured per STIG guidelines with conditional access enforcing those configurations. This is a compensating security implementation.

## Reference

NIST SP 800-53 Rev 5: SC-7(7)