---
type: moc
controls: Access Control
---

# Access Control

- [AC.L1-3.1.1](AC.L1-3.1.1.md)
- [AC.L1-3.1.2](AC.L1-3.1.2.md)
- [AC.L1-3.1.22](AC.L1-3.1.22.md)
- [AC.L2-3.1.3](AC.L2-3.1.3.md)
- [AC.L2-3.1.4](AC.L2-3.1.4.md)
- [AC.L2-3.1.5](AC.L2-3.1.5.md)
- [AC.L2-3.1.6](AC.L2-3.1.6.md)
- [AC.L2-3.1.7](AC.L2-3.1.7.md)
- [AC.L2-3.1.8](AC.L2-3.1.8.md)
- [AC.L2-3.1.9](AC.L2-3.1.9.md)
- [AC.L2-3.1.10](AC.L2-3.1.10.md)
- [AC.L2-3.1.11](AC.L2-3.1.11.md)
- [AC.L2-3.1.12](AC.L2-3.1.12.md)
- [AC.L2-3.1.13](AC.L2-3.1.13.md)
- [AC.L2-3.1.14](AC.L2-3.1.14.md)
- [AC.L2-3.1.15](AC.L2-3.1.15.md)
- [AC.L2-3.1.16](AC.L2-3.1.16.md)
- [AC.L2-3.1.17](AC.L2-3.1.17.md)
- [AC.L2-3.1.18](AC.L2-3.1.18.md)
- [AC.L2-3.1.19](AC.L2-3.1.19.md)
- [AC.L2-3.1.20](AC.L2-3.1.20.md)
- [AC.L2-3.1.21](AC.L2-3.1.21.md)

## Appendix A: Role Based Schemes

General User

| Role                             | Name                                                                                                        | Authorized privileges and Functions Performed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| General User                     | First initial followed by last name.                                                                        | No special authorization outside of what is provided by default by the OS and any special security configurations (per STIGs). General User accounts provide the users with the ability to create documents, run various applications, code development, etc. A general user will only have access to data or applications that do not require elevated privileges to access or run.                                                                                                                                                                                                                                                                                                                                                       |
| Server Administrator             | 'da' followed by username (domain administrator) or 'ms' followed by username (member server administrator) | There are two types of server administrator accounts. 'da' represents administrative accounts on the domain controllers. Member server accounts, ms, are administrative accounts that are all on Windows servers that are not domain controllers. These accounts have full administrative privileges, but they are restricted to the specific server they are associated with. In other words, da accounts will only have administrative access to the domain controllers, and ms accounts will only have administrative access to other Windows servers that are not domain controllers. This was configured per STIG guidance. The only groups authorized to have these accounts are members of the IA and system administrators’ group. |
| Workstation Administrator        | 'ws' followed by username                                                                                   | These users will have full administrative privileges on all Workstations on the domain. This group includes both IT and IA personnel. Functions include troubleshooting issues with teh system, configuring security settings, audit log assessments.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Built-in Administrator Account   | pdwlocal                                                                                                    | This account is the built-in administrator account that comes with the Windows OS. This account was and has been disabled per STIG guidance.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| "Back-up" Administrator Accounts | root and pdwadmin                                                                                           | The root account will only be used if a system cannot be accessed using a domain account, and it will be logged in the maintenance log any time it has to be utilized. Pdwadmin is a local administrator account for all Windows desktops and servers. It is not the built-in administrator account (which is disabled), but it is an account that was created to provide local administrative access if a system cannot communicate with the domain. The account is configured to lock after three unsuccessful login attempts. The password for the pdwadmin account will be managed by LAPs and accessible only to admins on the Domain Controller.                                                                                     |

## Appendix B: Key Personnel

| Key Personnel  | Role | Phone        | Email           |
| -------------- | ---- | ------------ | --------------- |
| Ryan Gury      | CEO  |              | rgury@pdw.ai    |
| James Slider   | COO  |              | jslider@pdw.ai  |
| Martin Parlier | ISSM | 256-937-2245 | mparlier@pdw.ai |
