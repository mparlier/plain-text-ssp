---
type: ssp
controls: AC
control: AC.L2-3.1.10
tags: note
---

# AC.L2-3.1.10

Goal: Use session lock with pattern-hiding displays to prevent access and viewing of data after a period of inactivity.

Tasks:

- Access Control Policy. Define period of inactivity after which the system initiates a session lock.
- STIGs. Enforce system locks on endpoint devices.
- Document procedures on how these are implemented (Endpoint Manager, Ansible)
- Configure inactivity timeouts for SaaS products that support it. For those that don't, document deviations from configuration standard.

User Impact:

- Users should expect that all endpoint devices will automatically lock the screen after 15 minutes of inactivity (screensaver).
- Users will not be able to access systems unless their device meets compliance requirements.

## Reference

NIST SP 800-53 Rev 5: AC-11, AC-11(1)