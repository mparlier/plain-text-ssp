---
type: ssp
controls: CM
control: CM.L2-3.4.8
tags: note
---

# CM.L2-3.4.8

Goal: Apply deny-by-exception (blacklist) policy to prevent the use of unauthorized software or deny-all, permit-by-exception (whitelisting) policy to allow the execution of authorized software.

800-53 Controls: CM-7(4), CM-7(5)

Tasks:

- Enforce firewall configurations via Endpoint Management or other automation mechanism.
- Configure Microsoft Defender on all OS's to support application whitelisting/blacklisting.
- Correlate software baseline with application whitelisting policies.

User Impact:

## Reference

NIST SP 800-53 Rev 5: CM-7(4), CM-7(5)