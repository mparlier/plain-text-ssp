---
type: ssp
controls: Access Control
control: AC.L1-3.1.1
responsible-entities:
implementation-status: Not Implemented
---

# AC.L1-3.1.1

Goal: Identify all users and devices, and limit access to only those users and devices. Show evidence of this.

Tasks:

- Create authorized users list. Define authorized users in the Access Control policy.
- Integrate Atlassian tools with M365 SSO
- Integrate GovSlack with M365 SSO
- Convert hardware inventory to Hardware Baseline. Include In-Scope/Out-of-Scope column for CUI Access
- MFP and 3-D printers. Segregate on the network; disallow network traffic from printer network back to the production network. Traffic can go from production to printer, but not backwards.
- Create a General User and Privileged User account request process. Use Jira for this? PDF Form that gets signed? Must show paperwork. If environments are not integrated with SSO, replicate this process for each environment.

## Account Types

PDW has defined and restricted the following information system account types that support the organizational business functions.

**General Users:**

General users are granted access to the systems to perform their job functions but are not given permission/access to anything that requires elevation.

**Privileged Users:**

Privileged user accounts are used to access system components that require elevated privileges to access. Access is granted only after management and IT approval and required training has been provided. The access granted to these accounts will enforce least privilege, only granting access to those components that are required for the user to do the job specified.

**Service Accounts:**

Service Accounts are created to support software that require a separate user account to manage the software, such as starting and stopping the service. These accounts are not generally used by regular users, except for account of software maintenance when using this account is required.

**Group Accounts:**

Group and role membership must be approved by Senior Leadership or Delegate. Usage will be logged in the maintenance log and monitored during weekly audit reviews.

**Temporary or Emergency Accounts**

If a temporary or emergency account is needed, it will be created and set to expire automatically within three days. These accounts can fall into any of the above criteria, and the privileges assigned to these accounts will be based on the purpose of the account and the actions it must be able to perform.

**Guest Accounts**

Guest accounts are specifically those accounts created in Microsoft Azure Active Directory and are tied to external vendors or contractors who have provided the required documentation necessary for the purposes of granting access to PDW systems.

## Roles and Responsibilities

**Program Leadership Role Responsibilities:**

- Approve the account request which includes confirming a user's need-to-know (NTK) as well as Non-Disclosure Agreement (NDA) status
- Program leadership will also have to approve privilege access requests
- This group of individuals will also have to inform IT when the account is no longer needed (such as terminations, transfer to different role, etc.)
- Identify whether a user is a PDW employee or contractor
- Notify IT whenever an account should be created, locked, or disabled

**IT Role Responsibilities:**

- Verify management has approved and acknowledged the employee’s need-to-know (NTK)
- Validate the type of account requested (privileged or general)
- Review accounts annually to ensure all users with active accounts have a current briefing on file and their clearances are still active.
- Implement all required STIG baseline settings regarding account creation and management.
- Creates, enables, modifies, or disables accounts when directed by IA.
- No user accounts will be created or enabled without a ticket from Program Leadership.

Group and role membership must be approved by a member of the Leadership team and shall be granted only to the level of the need required. Principle of least privilege is followed.

## Account Authorization

PDW utilizes the Jira Service Desk ticketing system to approve access to information systems based on intended system usage and business functions (need-to-know). A Jira Service Desk ticket must be submitted by an account-holder's manager or sponsor prior to receiving an account on the PDW information system. Authorization to the PDW information system is only granted once the user has provided all required documentation. The ticket and associated required documentation will determine the user's access authorizations.

## Reference

NIST SP 800-53 Rev 5: AC-2, AC-3, AC-17
