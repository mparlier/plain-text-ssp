---
type: ssp
controls: IA
control: IA.L1-3.5.1
tags: note
---

# IA.L1-3.5.1

Goal: Identify information system users, processes acting on behalf of users, and devices.

800-53 Controls: IA-2, IA-3, IA-5

Tasks:

- Integrate all SaaS products with Azure AD.
- IA Policy. All service accounts must go through CCB and be assigned an owner.
- Force approval of devices before gaining access. Set up conditional access restrictions.

Default administrator accounts will be disabled on systems or, if left enabled such as the case of 'root' on Linux or the Global Admin account in M365, they will be used only in emergency situations. Audit logging will be configured to alert multiple management personnel upon their use.

User Impact:

## Reference

NIST SP 800-53 Rev 5: IA-2, IA-3, IA-5