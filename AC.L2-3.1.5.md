---
type: control
control-family: Access Control
control: AC.L2-3.1.5
responsible-entities:
implementation-status:
---

# AC.L2-3.1.5

Goal: Employ the principle of least privilege, including for specific security functions and privileged accounts.

Tasks:

- Access Control Policy.
- Create Privileged Account list (access matrix?) for each environment (365, Atlassian, etc.).
- Set up just in time administration (JITA) for Windows laptops.
- Environment audits. Make sure groups are assigned to specific roles where possible. Audit those privileged groups/roles. Make sure general users cannot access privileged functions and security information.

## Least Privilege

PDW utilizes the PUA process to implement the concept of least privilege allowing only authorized access for users (and processes acting on behalf of users) which are necessary to accomplish assigned tasks in accordance with mission and business functions.

### Explicit Authorization and Privileged Accounts

PDW utilizes the `<INSERT ACCOUNT AUTHORIZATION PROCESS` process for user account creation which designates the role assigned to the user. PDW requires the Privileged User Agreement (PUA) to be submitted for all administrator accounts. Privileged accounts are restricted to the absolute minimum number to manage the system. All privileged accounts must be approved by Program Management, a privileged user briefing must be obtained, and privileged access will only be given to the extent required by the function that needs to be performed.

Privileged user accounts will be reviewed annually. In the event a review identifies incorrect privileges 

## Reference

NIST SP 800-53 Rev 5: AC-6, AC-6(1), AC-6(5)