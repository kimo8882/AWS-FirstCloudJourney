---
title: "Week 3 Worklog"
date: 2026-09-28
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

> **Draft:** Proposed FCJ practice schedule, pending confirmation. Outcomes below are expected, not verified accomplishments.

### Week 3 Objectives:

- **Account governance:** Review MFA, budget notifications and support workflows.
- **IAM authorization:** Study identity and role policies and validate least privilege.
- **Network architecture:** Design VPC subnets, routes and access controls.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon (28/09) | **Account security and billing**<br>• Review root MFA and account access; configure a sample cost budget with email alerts and review the support request workflow.<br>• Theory: distinguish root and IAM access, actual versus forecasted spend, and the purpose of support plans.<br>• Practice: review MFA; set a sample budget threshold and notification recipient; inspect billing and support pages. | 28/09/2026 |  | [Module 1 - 1: AWS account creation](https://000001.awsfcaj.com/) <br> [Module 1 - 2: AWS Budgets](https://000007.awsfcaj.com/) <br> [Module 1 - 3: AWS Support](https://000009.awsfcaj.com/) |
| Tue (29/09) | **IAM identities and permissions**<br>• Create lab IAM identities and a group; compare managed and custom policies and apply least privilege.<br>• Theory: compare identity-based policies and role-based temporary access.<br>• Practice: configure a limited lab identity, assign a policy and review its effective permissions. | 29/09/2026 |  | [Module 1 - 4: IAM access management](https://000002.awsfcaj.com/) |
| Wed (30/09) | **IAM policy testing**<br>• Review policy statements and role trust relationships; test permitted and denied operations in a lab context.<br>• Practice: inspect Effect, Action, Resource and Condition in a policy; compare a role trust policy with its permissions policy.<br>• Validation: use IAM policy simulation or a test identity to compare allowed and denied requests. | 30/09/2026 |  | [Module 1 - 4: IAM access management](https://000002.awsfcaj.com/) |
| Thu (01/10) | **VPC architecture**<br>• Design a VPC CIDR and non-overlapping public/private subnets across Availability Zones.<br>• Theory: distinguish CIDR blocks, Regions and Availability Zones.<br>• Practice: sketch a two-AZ VPC and allocate separate public and private subnet ranges without overlap. | 01/10/2026 |  | [Module 1 - 5: VPC networking](https://000003.awsfcaj.com/) |
| Fri (02/10) | **VPC routing and connectivity**<br>• Configure route tables and an Internet Gateway; review private subnet egress and DNS settings.<br>• Practice: associate subnet route tables, add an internet route for the public subnet and inspect private subnet routes.<br>• Validation: check route targets, DNS resolution settings and potential NAT Gateway charges. | 02/10/2026 |  | [Module 1 - 5: VPC networking](https://000003.awsfcaj.com/) |
| Sat (03/10) | **Network security and verification**<br>• Review security groups and network ACLs; check connectivity and remove unused lab networking resources.<br>• Theory: compare stateful security groups and stateless network ACLs.<br>• Validation: review inbound/outbound rules and identify unnecessary network resources to remove after the lab. | 03/10/2026 |  | [Module 1 - 5: VPC networking](https://000003.awsfcaj.com/) |

### Week 3 Achievements:

*Expected learning outcomes, pending confirmation.*

- **Account governance:**
    - Describe MFA, budget thresholds and alert delivery.
    - Identify the appropriate AWS Support workflow.
- **IAM security:**
    - Differentiate identity policies and role trust policies.
    - Explain how to verify least-privilege access using permitted and denied operations.
- **VPC networking:**
    - Design non-overlapping subnet ranges and explain route table associations.
    - Compare security groups and network ACLs, and identify network cleanup steps.
