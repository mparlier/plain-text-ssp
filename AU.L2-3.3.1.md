---
type: ssp
controls: AU
control: AU.L2-3.3.1
tags: note
---

# AU.L2-3.3.1

800-53 Controls: AU-2, AU-3, AU-3(1), AU-6, AU-11, AU-12

Goal: Create and retain system audit logs and records to the extent needed to enable the monitoring, analysis, investigation, and reporting of unlawful or unauthorized system activity.

Tasks:

- Audit and Accountability Policy. Specify event types to be monitored. Define audit log content required. Define audit log retention.
- Procedures. Configure Azure Sentinel to receive defined audit records and content from all endpoints and SaaS products within the Information System.
- STIGs. Windows/macOS/Ubuntu systems.

User Impact:

An event is any observable occurrence in an information system. Audit events are those events which are significant and relevant to the security of information systems and the environments in which those systems operate to meet specific and ongoing audit needs.

PDW requires the below audit events to be configured and tracked. Audit events are reviewed/updated yearly or upon changes to situational awareness of threats or vulnerabilities.

| Event                                                                                                                                                                    | Investigation Support |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------- |
| Success and unsuccessful attempts to access, modify, or delete privileges, security objects, security levels, or categories of information (e.g., classification levels) | Unauthorized Access   |
| Successful and unsuccessful logon attempts                                                                                                                               | Unauthorized Access   |
| Privileged activities or other system level access                                                                                                                       | Unauthorized Access   |

## Reference

NIST SP 800-53 Rev 5: AU-2, AU-3, AU-3(1), AU-6, AU-11, AU-12