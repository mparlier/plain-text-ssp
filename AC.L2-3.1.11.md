---
type: ssp
controls: AC
control: AC.L2-3.1.11
tags: note
---

# AC.L2-3.1.11

Goal: Terminate (automatically) a user session after a defined condition.

Tasks:

- Access Control Policy. Define conditions requiring a user session termination.
  * User logoff
  * System shutdown
  * Session inactivity (network devices)
  * Suspicious activity? Able to accomplish this with ATP?
- Patch Management Policy. Automatic scheduled system restarts to occur during patch cycles.

User Impact:

- Users can no longer expect to stay logged into some applications at all times. Impact should mostly be towards privileged users; general user impact will be low.

## Session Termination

This section addresses the termination of user-initiated logical sessions, not network sessions. A logical session (for local, network, and remote access) is initiated whenever a user (or process acting on behalf of a user) accesses an organizational information system. Such user sessions can be terminated (and thus terminate user access) without terminating network sessions. Session termination terminates all processes associated with a user's logical session except those processes that are specifically created by the user (i.e., session owner) to continue after the session is terminated.

PDW has defined the following conditions or trigger events requiring session disconnect to be employed by the information system when automatically terminating a user session: 

- User logoff
- System shutdown

In some cases, it is necessary to configure automatic session termination due to user inactivity. These cases include accessing network/web applications that are used to execute privileged functions to the system (i.e., switches and firewall). User sessions are automatically terminated if a session is inactive for 15 minutes.

## Reference

NIST SP 800-53 Rev 5: AC-12