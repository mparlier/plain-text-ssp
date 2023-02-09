---
type: control
control-family: Access Control
control: AC.L2-3.1.6
responsible-entities:
implementation-status:
---

# AC.L2-3.1.6

Goal: Use non-privileged accounts or roles when accessing non-security functions.

Tasks:

- Implement Privileged User Access Request.
- Privileged Users will have secondary accounts created for privileged functions.
- Access Control Policy. "Non-security functions must only be accessed with the use of non-privileged accounts." Something to that effect.

User Impact:

- Users will have to sign a PUA if they want privileged accounts in each environment (Atlassian, SharePoint, etc.)
- Users will have to use a secondary account to execute privileged functions. Example:
  * 'mparlier' = standard non-privileged account
  * 'gamparlier' = Global Admin in M365

## Reference

NIST SP 800-53 Rev 5: AC-6(2)