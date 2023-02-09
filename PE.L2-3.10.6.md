---
type: ssp
controls: PE
control: PE.L2-3.10.6
tags: note
---

# PE.L2-3.10.6

Goal: Enforce safeguarding measures for CUI at alternate work sites.

Tasks:

- Enroll all devices in MDM solution.
- Enforce full disk encryption on all devices
- Configure VPN to disallow split tunneling
- Configure VPN with MFA solution

- Do all alternative sites where CUI data is stored or processed meet the same physical security requirements as the main site?

The answer to this question will definitely be "no". We cannot feasibly enforce the same physical security requirements for employees working at home that we do for the office. Therefore, the primary focus for protecting CUI at alternate work sites that include WFH situations will be to lock down the employee's laptop. The laptop will be configured in accordance with STIG and SRG requirements and disallow the use of portable storage devices.

## Reference

NIST SP 800-53 Rev 5: PE-3, PE-17