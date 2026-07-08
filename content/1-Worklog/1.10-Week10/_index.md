---
title: "Week 10 Worklog"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Week 10 Objectives:

* Implement AWS WAF to protect web applications from common attacks (SQL injection, XSS, DDoS).
* Master comprehensive resource tagging strategy and Resource Groups for efficient resource organization.
* Deploy tag-based IAM policies (ABAC) to control access based on resource tags for enhanced governance.
* ITCoach project: finalize system design, complete detailed database schema, and define API endpoints.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Mon | - Research AWS WAF and OWASP Top 10 vulnerabilities<br>- Create Web ACL, configure managed rules and rate-based rules<br>- Create custom rules: SQL injection, XSS protection | 06/22/2026 | 06/22/2026 | <https://000026.awsstudygroup.com/> |
| Tue | - Enable WAF logging and analyze logs<br>- Research resource tagging strategies<br>- Tag resources and create Resource Groups<br>- Implement IAM tag-based access control (ABAC) | 06/23/2026 | 06/23/2026 | <https://000026.awsstudygroup.com/><br><https://000027.awsstudygroup.com/><br><https://000028.awsstudygroup.com/> |
| Wed | **ITCoach Project:**<br>- Review feedback from last week and adjust architecture<br>- Add SQS for async AI processing<br>- Finalize database schema for 8 DynamoDB tables | 06/24/2026 | 06/24/2026 | Internal team |
| Thu | **ITCoach Project:**<br>- Detail design API endpoints with schema<br>- Design GSI for query patterns<br>- Create infrastructure checklist: 15+ AWS services | 06/25/2026 | 06/25/2026 | Internal team |
| Fri | **ITCoach Project:**<br>- Estimate costs: ~$12-20/month AWS + $1-5 OpenAI<br>- Complete design documentation<br>- Update architecture diagram final version | 06/26/2026 | 06/26/2026 | Internal team |

### Week 10 Achievements:

**Mon-Tue: AWS Labs - WAF + Resource Tagging**

* **Mon - AWS WAF (Lab 026):** Mastered WAF architecture and OWASP Top 10 vulnerabilities protection. Successfully deployed Web ACL with managed rules for SQL injection and XSS prevention. Configured rate-based rules for DDoS mitigation and custom rules for specific threats. Enabled comprehensive logging and monitoring through CloudWatch for security analysis.

* **Tue - Resource Tagging (Lab 027+028):** Implemented enterprise-level tagging strategy with standardized taxonomy (Environment, CostCenter, Project, Owner). Created automated tagging policies via console and CLI operations. Deployed Resource Groups for efficient resource management and implemented tag-based IAM access control (ABAC) for enhanced security governance.

**Wed-Fri: ITCoach Project - Design Finalization**

* **Design Completion:** Finalized system architecture incorporating all feedback from previous reviews. Enhanced the design with additional security layers and optimized data flow patterns. Created comprehensive technical documentation ready for implementation phase.

* **Detailed Database Schema:** Completed database design with 8 DynamoDB tables including primary keys, sort keys, and Global Secondary Indexes. Defined data relationships, access patterns, and query optimization strategies. Established data modeling best practices for scalability.

* **API Endpoints Specification:** Documented 25+ REST API endpoints across 7 functional groups (Authentication, Questions, Sessions, Answers, Quiz, Gamification, Results). Defined complete request/response schemas, error handling, and authentication requirements for each endpoint.

* **Infrastructure Checklist:** Created comprehensive deployment checklist covering 15+ AWS services including frontend (S3, CloudFront, Route 53), backend (API Gateway, Lambda, DynamoDB), security (WAF, Cognito), and monitoring (CloudWatch, SNS). Established cost estimates and operational procedures.
