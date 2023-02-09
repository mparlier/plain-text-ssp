---
type: control
control-family: Access Control
control: AC.L2-3.1.14
responsible-entities:
implementation-status:
---

# AC.L2-3.1.14

Goal: Route remote access via managed access control points.

Tasks:

- Access Control Policy. Define access control points/networks allowed to access the information system.
- Implement ACLs based on organizationally defined access control points.
- Windows STIGs. Enable FIPS on all Windows devices.
- Ubuntu STIGs. Test FIPS on Ubuntu/product devices. If product not affected, enforce FIPS on all Ubuntu devices. Product development will need to take this configuration into account.

User Impact:

- Changes to product might need to be developed if it does not meet FIPS 140-2 compliance requirement.
- Access to systems may need to be limited to specific geographic locations. Personal VPNs will no longer be allowed.

## Reference

NIST SP 800-53 Rev 5: AC-17(3)
