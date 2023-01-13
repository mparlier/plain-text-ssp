---
type: ssp
controls: AC
control: AC.L2-3.1.17
tags: note
---

# AC.L2-3.1.17

Goal: Protect wireless access using authentication and encryption.

Tasks:

- Implement a "Use at your own risk" banner for pdw-guest WiFi.
- Implement user authentication for pdw-ewlan.
  * WPA2-PSK can be used, but this key must be changed routinely (Quarterly) or any time someone leaves the company.
  * WPA2 Enterprise can be used to authenticate each individual. Users unable to authenticate would be denied access.
- Implement guest user request process for pdw-guest (?). This might be necessary because it is logically separate, not physically. So technically, guests are accessing the information system but are not accessing CUI.

User Impact:

- If WPA2-PSK is used, the pre-shared key will be routinely updated to allow access.
- If WPA2 Enterprise is used, everyone will need to authenticate before wireless access is granted.
- pdw-guest authentication will change to authenticate each individual. (Maybe)

## Reference

NIST SP 800-53 Rev 5: AC-18(1)
