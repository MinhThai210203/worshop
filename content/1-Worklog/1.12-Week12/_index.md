---
title: "Week 12 Work Log"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---
### Week 12 Objectives:

* Optimize EC2 instance sizing with CloudWatch Agent and AWS Compute Optimizer for cost efficiency.
* Master data encryption at rest with AWS KMS and implement comprehensive audit logging with CloudTrail.
* Query and analyze security logs using Amazon Athena for compliance and monitoring.
* ITCoach project: conduct comprehensive testing, optimize web performance, stabilize infrastructure, and complete production deployment.

### Tasks to be implemented this week:
| Day | Tasks | Start Date | Completion Date | Reference Documents |
| --- | --- | --- | --- | --- |
| Mon | - Study CloudWatch and CloudWatch Agent<br>- Learn about EC2 Right Sizing and cost optimization<br>- Create IAM Role for CloudWatch Agent<br>- Launch EC2 instance to test monitoring | 07/06/2026 | 07/06/2026 | <https://000032.awsstudygroup.com/> |
| Tue | - Install CloudWatch Agent on EC2 instance<br>- Configure memory and disk metrics collection<br>- Generate workload to collect data<br>- Verify metrics in CloudWatch console | 07/07/2026 | 07/07/2026 | <https://000033.awsstudygroup.com/> |
| Wed | **ITCoach Project:**<br>- Comprehensive functional and integration testing<br>- Test all user flows end-to-end<br>- Load testing with 100 concurrent users<br>- Security testing: WAF, authentication, SSL/TLS | 07/08/2026 | 07/08/2026 | Internal team |
| Thu | **ITCoach Project:**<br>- Improve UI/UX and fix bugs<br>- Performance optimization: lazy loading, reduce bundle size<br>- Full monitoring setup: Dashboard, alerts, X-Ray tracing | 07/09/2026 | 07/09/2026 | Internal team |
| Fri | **ITCoach Project:**<br>- Stabilize infrastructure and optimize costs<br>- Write documentation: deployment runbook, API docs, troubleshooting guide<br>- Complete project: deploy to production <https://itcoach24h.xyz> | 07/10/2026 | 07/10/2026 | Internal team |

### Week 12 Achievements:

**Mon-Tue: AWS Labs - CloudWatch/Compute Optimizer + KMS/CloudTrail**

* **CloudWatch & Compute Optimizer:** Deployed CloudWatch Agent to collect memory and disk metrics. Analyzed EC2 performance with Compute Optimizer, achieving 50% cost savings by downsizing from t3.large to t3.medium. Created real-time monitoring dashboards for comprehensive resource visibility.

* **KMS & CloudTrail:** Mastered data encryption with KMS, created custom keys with automatic rotation enabled. Implemented CloudTrail for audit logging, queried logs with Athena. Optimized KMS costs by reducing API calls by 99% using S3 Bucket Key optimization.

**Wed-Fri: ITCoach Project - Final Testing & Deployment**

* **Comprehensive Testing:** Conducted end-to-end functional testing of all user flows (registration → login → question selection → voice recording → AI evaluation → XP updates). Performed integration testing across 15+ AWS services. Load tested with 100 concurrent users achieving <250ms average response time. Security tested WAF protection, authentication flows, and HTTPS encryption.

* **Web Optimization:** Enhanced UI/UX with improved voice recording interface, dark mode, and interactive notifications. Optimized frontend performance with lazy loading and code splitting, reducing bundle size by 50% (3.2MB → 1.6MB). Improved page load times from 4.5s to 2.1s.

* **Infrastructure Stabilization:** Established comprehensive monitoring with CloudWatch dashboards, 15+ alerts for system health, and AWS X-Ray distributed tracing. Finalized cost optimization at ~$20-22/month including OpenAI API costs. Created complete technical documentation including deployment runbook and API documentation.

* **Project Completion:** Successfully deployed production system to `https://itcoach24h.xyz`. All 15 AWS services operating stably with dual WAF protection, full HTTPS encryption, and Cognito authentication. ITCoach platform ready to serve users as a fully functional AI-powered IT interview practice system on AWS Serverless architecture.

