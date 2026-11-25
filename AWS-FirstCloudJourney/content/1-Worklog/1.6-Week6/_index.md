---
title: "Week 6 Worklog"
date: 2026-10-19
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

> **Draft:** Proposed FCJ practice schedule, pending confirmation. Outcomes below are expected, not verified accomplishments.

### Week 6 Objectives:

- **Monitoring:** Explore CloudWatch alarms and notifications.
- **Hybrid DNS:** Study Route 53 Resolver and forwarding between networks.
- **CLI and availability:** Practise role-based CLI access and study multi-AZ architectures.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon (19/10) | **CloudWatch alarms and notifications**<br>• Configure a sample metric alarm and notification target; review alarm states and remove test resources after verification.<br>• Practice: choose a metric, threshold and evaluation period; review notification delivery using an SNS topic if required.<br>• Validation: inspect OK, ALARM and INSUFFICIENT_DATA states and the alarm history. | 19/10/2026 |  | [Module 1 - 13: Amazon CloudWatch](https://000008.awsfcaj.com/) |
| Tue (20/10) | **Hybrid DNS preparation**<br>• Study how on-premises DNS integrates with VPC DNS; review the lab environment, DNS traffic and security requirements.<br>• Theory: distinguish public DNS from private VPC name resolution and hybrid DNS forwarding.<br>• Preparation: map the simulated local network, VPC, DNS servers and port 53 connectivity requirements. | 20/10/2026 |  | [Module 1 - 14: Route 53 hybrid DNS](https://000010.awsfcaj.com/) |
| Wed (21/10) | **Route 53 Resolver**<br>• Review inbound/outbound Resolver endpoints and forwarding rules; plan DNS resolution tests in both directions and resource cleanup.<br>• Practice: inspect the design of inbound/outbound Resolver endpoints and conditional forwarding rules.<br>• Validation: plan name-resolution checks from both environments and review hourly endpoint charges before cleanup. | 21/10/2026 |  | [Module 1 - 14: Route 53 hybrid DNS](https://000010.awsfcaj.com/) |
| Thu (22/10) | **AWS CLI on EC2**<br>• Review CLI installation on Windows/Linux EC2 and use instance role credentials; verify identity and Region.<br>• Practice: review AWS CLI installation for Windows and Ubuntu EC2; inspect the credential provider chain.<br>• Validation: use role-based credentials and compare identity/Region output with the console. | 22/10/2026 |  | [Module 1 - 15: AWS CLI on EC2](https://000011.awsfcaj.com/) |
| Fri (23/10) | **AWS CLI resource operations**<br>• Practise listing and filtering EC2 and S3 resources; compare CLI output with the console and review safe cleanup commands.<br>• Practice: use describe/list operations, filters and output formats to inspect EC2 and S3.<br>• Safety: verify the account and Region before any resource-changing command and identify unused resources. | 23/10/2026 |  | [Module 1 - 15: AWS CLI on EC2](https://000011.awsfcaj.com/) |
| Sat (24/10) | **Highly available application design**<br>• Study the multi-AZ web application architecture and map the VPC, compute, database, load balancing and storage components.<br>• Theory: trace a request from the load balancer to the application tier and database tier.<br>• Design: identify single points of failure, AZ redundancy and the role of health checks. | 24/10/2026 |  | [Module 1 - 16: Highly available web application](https://000021.awsfcaj.com/) |

### Week 6 Achievements:

*Expected learning outcomes, pending confirmation.*

- **Monitoring and alerting:**
    - Describe alarm thresholds, evaluation periods and notification delivery.
    - Interpret common CloudWatch alarm states.
- **Hybrid networking:**
    - Explain inbound and outbound Resolver endpoints and conditional forwarding.
    - Identify DNS connectivity and endpoint cost considerations.
- **CLI and architecture:**
    - Describe role-based CLI access and resource filtering.
    - Trace requests through a multi-AZ application architecture.
