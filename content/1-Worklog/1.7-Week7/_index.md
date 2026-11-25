---
title: "Week 7 Worklog"
date: 2026-10-26
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

> **Draft:** Proposed FCJ practice schedule, pending confirmation. Outcomes below are expected, not verified accomplishments.

### Week 7 Objectives:

- **Multi-tier architecture:** Consolidate networking, application and database services.
- **Resilience and operations:** Review load balancing, health checks, backups and monitoring.
- **Foundation recap:** Review all 16 modules and identify cleanup and remaining learning tasks.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon (26/10) | **Highly available web application: network**<br>• Prepare the sample application network with multiple Availability Zones, subnet layout and tier-specific security groups.<br>• Practice: plan public load balancer subnets and application/database subnets across two AZs.<br>• Validation: review CIDR allocation, route table associations and tier-to-tier security group rules. | 26/10/2026 |  | [Module 1 - 16: Highly available web application](https://000021.awsfcaj.com/) |
| Tue (27/10) | **Highly available web application: application and data**<br>• Review deployment of the sample web application on EC2, its RDS connection and application access permissions.<br>• Practice: review application configuration and database endpoint connectivity; keep application credentials out of source code.<br>• Validation: plan a sample application health check and a basic database read/write test. | 27/10/2026 |  | [Module 1 - 16: Highly available web application](https://000021.awsfcaj.com/) |
| Wed (28/10) | **Highly available web application: traffic distribution**<br>• Review target registration, Application Load Balancer health checks and Auto Scaling configuration for the web tier.<br>• Practice: review ALB listener, target group, health check path and Auto Scaling group settings.<br>• Validation: inspect how traffic is routed to healthy targets in multiple AZs. | 28/10/2026 |  | [Module 1 - 16: Highly available web application](https://000021.awsfcaj.com/) |
| Thu (29/10) | **Highly available web application: resilience**<br>• Plan checks for unhealthy instances and multi-AZ database resilience; review backup and restore procedures.<br>• Theory: distinguish availability, fault tolerance and disaster recovery.<br>• Validation: plan an unhealthy-target replacement scenario and review RDS Multi-AZ failover and backup/restore procedures. | 29/10/2026 |  | [Module 1 - 16: Highly available web application](https://000021.awsfcaj.com/) |
| Fri (30/10) | **Architecture review and cost management**<br>• Review the end-to-end request flow, permissions, monitoring and potential charges from the practice architecture.<br>• Review: map monitoring signals, role permissions and network access against the request flow.<br>• Cost: estimate the main billable components and inspect budget alerts and cleanup priorities. | 30/10/2026 |  | [Module 1 - 2: AWS Budgets](https://000007.awsfcaj.com/) <br> [Module 1 - 4: IAM access management](https://000002.awsfcaj.com/) <br> [Module 1 - 13: Amazon CloudWatch](https://000008.awsfcaj.com/) <br> [Module 1 - 16: Highly available web application](https://000021.awsfcaj.com/) |
| Sat (31/10) | **Explore AWS Services recap**<br>• Review all 16 workshop topics, document key concepts and remaining questions, and check for billable resources requiring cleanup.<br>• Consolidation: organize the 16 workshop topics into account/cost, IAM, networking, compute, storage, database, monitoring and resilience.<br>• Review: record remaining questions and check for resources that may continue to generate charges. | 31/10/2026 |  | [Module 1 - 16: Highly available web application](https://000021.awsfcaj.com/) <br> [Explore AWS Services](https://cloudjourney.awsfcaj.com/1-explore/) |

### Week 7 Achievements:

*Expected learning outcomes, pending confirmation.*

- **Multi-tier architecture:**
    - Explain network isolation, application connectivity and database placement.
    - Trace ALB routing and Auto Scaling target registration.
- **Resilience and operations:**
    - Identify health checks, unhealthy-target replacement and database failover.
    - Describe backup, restore, monitoring and permissions checks.
- **Foundation consolidation:**
    - Summarize all 16 Explore AWS Services workshops by service category.
    - Identify outstanding practice tasks, cost risks and resource cleanup priorities.
