---
title: "Week 5 Worklog"
date: 2026-10-12
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

> **Draft:** Proposed FCJ practice schedule, pending confirmation. Outcomes below are expected, not verified accomplishments.

### Week 5 Objectives:

- **Database services:** Explore private RDS connectivity, backup and resilience.
- **Elastic compute:** Compare Lightsail and EC2; study scaling and load balancing.
- **Observability:** Review CloudWatch monitoring signals and costs.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon (12/10) | **RDS networking and database setup**<br>• Prepare a DB subnet group and security group; review database engine, instance class and private access settings.<br>• Theory: compare managed RDS with self-managed database installation on EC2.<br>• Practice: select a database engine, private subnet group and security group allowing access only from the lab application. | 12/10/2026 |  | [Module 1 - 10: RDS database](https://000005.awsfcaj.com/) |
| Tue (13/10) | **RDS connectivity and backups**<br>• Test database connectivity from the application environment, practise basic queries and review snapshots and Multi-AZ options.<br>• Practice: inspect the database endpoint and port, connect from the application environment and run a simple query.<br>• Validation: review backup retention, manual snapshots and Multi-AZ deployment trade-offs. | 13/10/2026 |  | [Module 1 - 10: RDS database](https://000005.awsfcaj.com/) |
| Wed (14/10) | **Amazon Lightsail**<br>• Explore bundled compute pricing; plan a small web deployment, review firewall rules and compare Lightsail with EC2.<br>• Theory: compare bundled Lightsail plans with EC2's configurable infrastructure.<br>• Practice: review a sample instance blueprint, networking/firewall settings, public IP and expected monthly costs. | 14/10/2026 |  | [Module 1 - 11: Amazon Lightsail](https://000045.awsfcaj.com/) |
| Thu (15/10) | **EC2 Auto Scaling setup**<br>• Prepare a launch template and target group; review desired, minimum and maximum capacity for an Auto Scaling group.<br>• Practice: define an EC2 launch template and configure an Auto Scaling group across two Availability Zones.<br>• Review: connect the group to a target group and inspect minimum, desired and maximum capacity. | 15/10/2026 |  | [Module 1 - 12: EC2 Auto Scaling](https://000006.awsfcaj.com/) |
| Fri (16/10) | **Scaling and load balancing**<br>• Review target tracking policies and load balancer health checks; plan a controlled scaling test and inspect instance replacement.<br>• Theory: distinguish target tracking from manual scaling and understand health check replacement.<br>• Validation: plan a small controlled workload, inspect target health and review scaling activity history. | 16/10/2026 |  | [Module 1 - 12: EC2 Auto Scaling](https://000006.awsfcaj.com/) |
| Sat (17/10) | **CloudWatch monitoring**<br>• Explore EC2 metrics and log groups; prepare a dashboard and identify metrics useful for monitoring application health.<br>• Theory: distinguish CloudWatch metrics, logs and dashboards.<br>• Practice: identify CPUUtilization, network metrics and application log signals; review log retention and dashboard costs. | 17/10/2026 |  | [Module 1 - 13: Amazon CloudWatch](https://000008.awsfcaj.com/) |

### Week 5 Achievements:

*Expected learning outcomes, pending confirmation.*

- **Managed databases:**
    - Explain RDS subnet and security requirements.
    - Describe endpoint connectivity, snapshots and Multi-AZ options.
- **Compute cost and elasticity:**
    - Compare Lightsail bundled pricing with EC2.
    - Explain launch templates, scaling capacity and target health checks.
- **Observability:**
    - Distinguish CloudWatch metrics, logs and dashboards.
    - Identify application monitoring signals and cost considerations.
