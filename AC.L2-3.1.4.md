---
type: control
control-family: Access Control
control: AC.L2-3.1.4
responsible-entities:
implementation-status:
---

# AC.L2-3.1.4

Goal: Separate the duties of individuals to reduce the risk of malevolent activity without collusion.

Tasks:

- Access Control Policy, section AC.L2-3.1.4, "Separation of Duties".
- Contract with either MSP or MSSP; ISSM will take over either Sysadmin or Auditing role based on decision. Alternative: Hire Sysadmin.

## Separation of Duties

Separation of duties addresses the potential for abuse of authorized privileges and helps to reduce the risk of malevolent activity without collusion. Separation of duties includes, for example: (i) dividing mission functions and information system support functions among different individuals and/or roles; (ii) conducting information system support functions with different individuals (e.g., system management, programming, configuration management, quality assurance and testing, and network security); and (iii) ensuring security personnel administering access control functions do not also administer audit functions.

PDW has defined the below duties that require separation:

### Add/Delete Roles

PDW utilizes the `<INSERT ACCOUNT AUTHORIZATION PROCEDURE>` for user account creation, which designates the role assigned to the user. PDW requires the Privileged User Agreement (PUA) to be submitted for all administrator accounts. Separation of duties are determined via roles and implemented either through assigned attributes for a role or through group membership. Users are assigned to these roles based on their job function with IA and Management approval. This requirement is for both general users and administrators.

### Separation of System Administrators and ISSO Functions

## Reference

NIST SP 800-53 Rev 5: AC-5