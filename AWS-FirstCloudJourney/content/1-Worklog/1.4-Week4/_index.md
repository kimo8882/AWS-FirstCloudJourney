---
title: "Week 4 Worklog"
date: 2026-10-05
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

> **Draft:** Proposed FCJ practice schedule, pending confirmation. Outcomes below are expected, not verified accomplishments.

### Week 4 Objectives:

- **EC2 deployment:** Study instance provisioning and application connectivity.
- **Secure credentials:** Explore application IAM roles and CloudShell.
- **Static hosting:** Configure and evaluate S3 static website hosting and access controls.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon (05/10) | **EC2 instance setup**<br>• Select an AMI and instance type; launch a test instance with an appropriate key pair and security group.<br>• Theory: compare AMIs, instance types, EBS root volumes and key pairs.<br>• Practice: select a lab subnet, attach a restricted security group and inspect the instance status checks. | 05/10/2026 |  | [Module 1 - 6: EC2 application deployment](https://000004.awsfcaj.com/) |
| Tue (06/10) | **Deploy a sample application on EC2**<br>• Connect securely to the instance, install a web server, deploy a sample page and inspect its response.<br>• Practice: connect using a supported SSH or Systems Manager method, install a web server and place a simple index page.<br>• Validation: check the HTTP response, service status and security group rules if connectivity fails. | 06/10/2026 |  | [Module 1 - 6: EC2 application deployment](https://000004.awsfcaj.com/) |
| Wed (07/10) | **EC2 application IAM roles**<br>• Create an EC2 role with scoped permissions, attach its instance profile and test temporary credential access.<br>• Practice: assign an IAM role with a narrowly scoped S3 permission to the EC2 instance.<br>• Validation: inspect the caller identity and compare an authorized operation with an operation outside the policy scope. | 07/10/2026 |  | [Module 1 - 7: Application permissions with IAM roles](https://000048.awsfcaj.com/) |
| Thu (08/10) | **Browser-based AWS CLI**<br>• Review the Cloud9 workshop and use its updated CloudShell lab; practise basic shell commands and AWS CLI commands.<br>• Theory: review managed browser-based shell access and the distinction from a local CLI installation.<br>• Practice: run identity and resource-listing commands in CloudShell without embedding access keys in source code. | 08/10/2026 |  | [Module 1 - 8: CloudShell (updated Cloud9 workshop)](https://000049.awsfcaj.com/) <br> [AWS Cloud9 notice](https://aws.amazon.com/cloud9/getting-started/) |
| Fri (09/10) | **Amazon S3 static website**<br>• Create a lab bucket, upload sample HTML assets and explore static website hosting settings.<br>• Practice: create a uniquely named lab bucket, upload index and error documents, and inspect website hosting settings.<br>• Theory: compare object access through S3 API endpoints and static website endpoints. | 09/10/2026 |  | [Module 1 - 9: S3 static website](https://000057.awsfcaj.com/) |
| Sat (10/10) | **S3 access and website testing**<br>• Review bucket access, test the website endpoint with the lab configuration and clean up public test resources.<br>• Validation: review Block Public Access and the bucket policy before enabling any lab-only public access; test the endpoint.<br>• Cleanup: remove public test objects and bucket configuration when finished. | 10/10/2026 |  | [Module 1 - 9: S3 static website](https://000057.awsfcaj.com/) |

### Week 4 Achievements:

*Expected learning outcomes, pending confirmation.*

- **EC2 and application deployment:**
    - Explain AMI, instance type, storage and network choices.
    - Describe web server deployment and HTTP connectivity checks.
- **Secure application access:**
    - Explain temporary instance role credentials and permission validation.
    - Use CloudShell as a browser-based CLI option in the proposed lab.
- **Static hosting:**
    - Describe S3 website hosting and distinguish website and API endpoints.
    - Review public access safeguards and lab cleanup.
