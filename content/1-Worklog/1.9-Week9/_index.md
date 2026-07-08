---
title: "Week 9 Worklog"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
### Week 9 Objectives:

* Deploy complete CI/CD pipeline with AWS CodePipeline, CodeBuild, and CodeDeploy for automated software delivery.
* Configure Git integration with AWS CodeCommit and automated deployment workflows.
* Implement hybrid storage solution with AWS Storage Gateway for seamless on-premises to cloud integration.
* Initiate ITCoach project: conceptualize AI-powered interview platform and design system architecture.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon | - Research AWS CI/CD services ecosystem<br>- Prepare infrastructure: VPC, Security Groups, S3 bucket<br>- Create IAM roles for CI/CD services<br>- Install and configure CodeDeploy Agent on EC2 | 06/15/2026 | 06/15/2026 | <https://000023.awsstudygroup.com/> |
| Tue | - Create AWS CodeCommit repository and configure Git credentials<br>- Create CodeBuild, CodeDeploy, CodePipeline<br>- Test CI/CD pipeline end-to-end<br>- Learn AWS Storage Gateway and deploy File Gateway | 06/16/2026 | 06/16/2026 | <https://000023.awsstudygroup.com/><br><https://000024.awsstudygroup.com/> |
| Wed | **ITCoach Project:**<br>- Brainstorm IT interview practice platform idea<br>- Analyze problem and solution<br>- Draw AWS Serverless architecture diagram<br>- Design preliminary database schema (8 DynamoDB tables) | 06/17/2026 | 06/17/2026 | Internal team |
| Thu | **ITCoach Project:**<br>- Detail design of 8 DynamoDB tables with partition/sort keys<br>- Define API endpoints and request/response schema<br>- Prepare architecture presentation slides | 06/18/2026 | 06/18/2026 | Internal team |
| Fri | **ITCoach Project:**<br>- Present idea and design to team<br>- Receive feedback from mentor on architecture<br>- Document improvement suggestions | 06/19/2026 | 06/19/2026 | Internal team |
### Week 9 Achievements:

**Mon-Tue: AWS Labs - CI/CD Pipeline + Storage Gateway**

* **Mon - CI/CD Pipeline (Lab 023):** Master AWS CodePipeline, CodeBuild, CodeDeploy, and CodeCommit. Set up the necessary infrastructure, including VPCs, security groups, and S3 buckets. Create IAM roles for CI/CD services and install the CodeDeploy agent on EC2 instances. Complete a three-stage CI/CD pipeline featuring automated deployment upon source code commits.

* **Tue - Storage Gateway (Lab 024):** Researched Storage Gateway types and successfully deployed a File Gateway. Created and configured SMB/NFS file shares, connecting on-premises systems with automatic synchronization to S3. Implemented a hybrid storage solution for seamless on-premises integration.

**Wed-Fri: ITCoach Project - Ideation & Architecture Design**

* **Ideation:** Developed AI-powered IT interview practice platform addressing the gap in practical interview experience for IT students. Conducted competitive analysis against existing platforms and identified key differentiators: detailed AI voice evaluation and gamification elements.

* **Architectural design:** Designed comprehensive AWS Serverless architecture including React frontend with CloudFront CDN, API Gateway with 8 Lambda functions, DynamoDB for data persistence, Cognito for authentication, and dual WAF protection for enhanced security.

* **Database schema:** Created preliminary design for 8 DynamoDB tables (Users, Questions, Sessions, Answers, Quiz, Gamification, Results, Feedback) with appropriate partition/sort keys and planned data access patterns for optimal performance.

* **Group presentation:** Successfully presented system architecture and design concepts to team. Received valuable feedback from mentor and documented improvement suggestions for iterative refinement in subsequent development phases.
