---
type: control
control-family: Access Control
control: AC.L2-3.1.15
responsible-entities:
implementation-status:
---

# AC.L2-3.1.15

Goal: Authorize remote execution of privileged commands and remote access to security-relevant information.

Tasks:

- Access Control Policy. Define who can remotely execute privileged commands, which privileged commands they can execute, and who is allowed access to security relevant information such as audit log configuration settings. Because of our use case, this will likely be defined as "This role may execute all privileged command remotely" and see if that will fly.

User Impact:

- Privileged users
- General users - none.


IT needs the ability to execute privileged commands from remote sessions due to the nature and layout of the information system across multiple environments. All execution of privileged commands and access to security-relevant information is performed by members granted the role of System Administrator or Auditor.

## Reference

NIST SP 800-53 Rev 5: AC-17(4)