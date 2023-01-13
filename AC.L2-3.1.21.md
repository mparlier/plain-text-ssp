---
type: ssp
controls: AC
control: AC.L2-3.1.21
tags: note
---

# AC.L2-3.1.21

Goal: Limit use of portable storage devices on external systems.

Tasks:

- Access Control Policy. Define portable storage units (see control guidance).
- Hardware baseline - identify approved portal storage units.
- Assign portal storage devices to individual users.

User Impact:

- USB devices will have to be owned by PDW and be able to employ encryption.
- If a USB device cannot be encrypted by an OS such as a USB drive used for OS installations, if that device also stores CUI, it must use a FIPS-validated hardware encryption method. Example of this would be [Apricorn](https://apricorn.com/aegis-secure-key-3) drives.

## Reference

NIST SP 800-53 Rev 5: AC-20(2)