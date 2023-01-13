---
type: control
control-family: Access Control
control: AC.L2-3.1.7
responsible-entities:
implementation-status:
---

# AC.L2-3.1.7

Goal: Prevent non-privileged users from executing privileged functions and capture the execution of such functions in audit logs. Related control - AC.L1-3.1.2.

Tasks:

- Access Control Policy. Define privileged functions and non-privileged users.
- Implement Acceptable Use [banners](../banners.md) on all systems.
- Implement audit logging on all systems to show privileged function executions as well as who granted privileged access.
- Write procedures on how audit logging is implemented and reviewed.
- Continuous monitoring policy and procedures.
- STIGs - automatic lockouts on account login failures.

User Impact:

- On systems that support this, users must accept the login banner before accessing the system.

## Privilege Function Audit

Use of privileged functions are audited during weekly audits. This also includes reviewing maintenance logs for local administrator logins. In addition, any action that can be taken on the system that would result in a user potentially gaining privileged access is monitored via the audit logs. Group Policy and DAC settings prohibit unauthorized escalation of user privileges or unauthorized circumventing of security safeguards.

## Reference

NIST SP 800-53 Rev 5: AC-6(9), AC-6(10)