---
title: "Week 11 Work Log"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
### Week 11 Objectives:

* Master IAM Permission Boundary to prevent privilege escalation and limit user permissions effectively.
* Deploy comprehensive server management with AWS Systems Manager for centralized fleet operations.
* Implement secure remote access, automated patching, and command execution across multiple EC2 instances.
* ITCoach project: deploy complete AWS infrastructure with 15+ services and develop React TypeScript frontend.

### Tasks to be implemented this week:
| Day | Tasks | Start Date | Completion Date | Reference Documents |
| --- | --- | --- | --- | --- |
| Mon | - Research IAM Permission Boundary concepts<br>- Understand effective permissions calculation<br>- Create Permission Boundary policy and test | 06/29/2026 | 06/29/2026 | <https://000030.awsstudygroup.com/> |
| Tue | - Learn AWS Systems Manager: Session Manager, Patch Manager, Run Command<br>- Create IAM Role, launch EC2 instances<br>- Configure Patch Manager and Run Command<br>- Test Session Manager connections | 06/30/2026 | 06/30/2026 | <https://000031.awsstudygroup.com/> |
| Wed | **ITCoach Project:**<br>- Deploy frontend: S3 bucket, CloudFront, Route 53, ACM<br>- Create API Gateway REST API<br>- Deploy 8 Lambda functions with Node.js runtime | 07/01/2026 | 07/01/2026 | Internal team |
| Thu | **ITCoach Project:**<br>- Create 8 DynamoDB tables<br>- Setup Cognito User Pool and SQS queue<br>- Create 2 WAF Web ACLs (CloudFront + API Gateway)<br>- Setup CloudWatch Log Groups and SNS topics | 07/02/2026 | 07/02/2026 | Internal team |
| Fri | **ITCoach Project:**<br>- Develop React + TypeScript frontend<br>- Build components and integrate AWS Amplify SDK<br>- Deploy code: build React app and upload to S3<br>- Deploy Lambda code and test integration | 07/03/2026 | 07/03/2026 | Internal team |

### Week 11 Achievements:

**Mon-Tue: AWS Labs - Permission Boundary + Systems Manager**

* **Mon - Permission Boundary (Lab 030):** Mastered IAM Permission Boundaries for preventing privilege escalation attacks. Created comprehensive permission boundary policies to limit user capabilities while maintaining operational access. Successfully implemented effective permissions calculation and tested scenarios where users cannot create new IAM users or modify existing permissions despite having administrative policies attached.

* **Tue - Systems Manager (Lab 031):** Deployed comprehensive server management solution with Session Manager for secure shell access without SSH keys, Patch Manager for automated OS updates across fleet, and Run Command for remote execution. Established centralized management reducing operational overhead by 80% while enhancing security posture through encrypted connections and audit trails.

**Wed-Fri: ITCoach Project - Infrastructure Deployment**

* **Deploy 15 AWS services:** Successfully deployed complete serverless infrastructure including S3/CloudFront for frontend, API Gateway with 8 Lambda functions, 8 DynamoDB tables with GSI, Cognito User Pool, SQS queue, dual WAF protection, and comprehensive CloudWatch monitoring with SNS notifications.

* **Developing React frontend:** Built responsive TypeScript React application with voice recording capabilities, AI feedback interface, gamification system, and AWS Amplify SDK integration. Implemented modern UI with Tailwind CSS and efficient state management.

* **Deploy code:** Completed end-to-end deployment with optimized React build uploaded to S3, Lambda functions packaged with dependencies, environment variables configured, and full integration testing. Verified user flows from registration through AI evaluation and XP updates.

* **Infrastructure modification:** Fine-tuned infrastructure with IAM permission fixes, increased Lambda timeouts to 30s for OpenAI API calls, optimized WAF rules based on traffic patterns, and implemented comprehensive monitoring. Established cost baseline at ~$17/month through AWS Cost Explorer.

