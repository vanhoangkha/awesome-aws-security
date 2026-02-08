# Awesome AWS Security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](Contribute.md)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-February%202026-blue.svg)](#)

A comprehensive, curated collection of AWS security resources including official documentation, books, video tutorials, hands-on labs, penetration testing tools, CTF challenges, and real-world case studies.

**Target Audience:** Security professionals, Cloud architects, DevSecOps engineers, Penetration testers

_Inspired by the [awesome](https://github.com/sindresorhus/awesome) list project._

![Awesome AWS Security](awesome-aws-security.png)

## Table of Contents
- [AWS Whitepapers](#aws-whitepapers)
- [Books](#books)
- [Videos](#videos)
- [Tutorials & Blogs](#tutorials--blogs)
- [Online Courses](#online-courses)
- [Security Tools](#security-tools)
- [Hands-on Labs & CTFs](#hands-on-labs--ctfs)
- [Security Bulletins](#security-bulletins)
- [Notable Breaches](#notable-breaches)
- [Infrastructure Vulnerabilities](#infrastructure-vulnerabilities)
- [Podcasts & Newsletters](#podcasts--newsletters)
- [Contributors](#contributors)

> [!NOTE]
> **Related Resources:**
> - [Cloud Security Learning Resources](https://github.com/vanhoangkha/awesome-cybersecurity-learning-resources/blob/main/awesome-cloud-security-learning-resources.md)
> - [AWS Security Study Plan](https://github.com/vanhoangkha/security-study-plan/blob/main/aws-security-study-plan.md)
> - [AWS Security Interview Questions](https://github.com/vanhoangkha/security-interview-questions/blob/main/aws-security-interview-questions.md)
> - [Cloud Security Roadmap](https://github.com/vanhoangkha/cybersecurity-roadmap/blob/master/cloud-security.md)

---

## 🆕 What's New (2025-2026)

> **AWS re:Invent 2025 & re:Inforce 2025 Highlights:**
> - [AWS Security Agent](https://aws.amazon.com/blogs/aws/new-aws-security-agent-secures-applications-proactively-from-design-to-deployment-preview/) - AI-powered SAST from design to deployment (Preview)
> - [AWS Security Hub v2](https://aws.amazon.com/blogs/security/streamline-security-response-at-scale-with-aws-security-hub-automation/) - ML-powered threat detection, automated correlation
> - [GuardDuty Extended Threat Detection](https://aws.amazon.com/about-aws/whats-new/2025/12/guardduty-extended-threat-detection-ec2-ecs/) - Multi-stage attack detection for EC2/ECS
> - [MFA Enforcement](https://aws.amazon.com/blogs/aws/aws-reinforce-roundup-2025-top-announcements/) - FIDO2 passkeys, up to 8 MFA devices per user
> - [IAM Access Analyzer Updates](https://aws.amazon.com/blogs/security/customize-the-scope-of-iam-access-analyzer-unused-access-analysis/) - Customizable unused access analysis

---

## AWS Whitepapers

Official AWS security whitepapers provide foundational knowledge for cloud security architecture. For the latest publications, visit the [AWS Security Learning Portal](https://aws.amazon.com/security/security-learning/).

> **Important:** Subscribe to the [AWS Security Bulletin](https://aws.amazon.com/security/security-bulletins/) for vulnerability notifications.

### Foundational
1. [AWS Overview](https://d1.awsstatic.com/whitepapers/aws-overview.pdf) - Essential reading for understanding AWS service landscape
2. [Introduction to AWS Security](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/introduction-aws-security.pdf)
3. [AWS Well-Architected Security Pillar](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/wellarchitected-security-pillar.pdf)
4. [AWS Well-Architected Framework](https://d1.awsstatic.com/whitepapers/architecture/AWS_Well-Architected_Framework.pdf)

### Compliance & Governance
5. [Introduction to Security By Design](https://d1.awsstatic.com/whitepapers/compliance/Intro_to_Security_by_Design.pdf)
6. [AWS Risk and Compliance](https://d0.awsstatic.com/whitepapers/compliance/AWS_Risk_and_Compliance_Whitepaper.pdf)
7. [AWS Security Checklist](https://d1.awsstatic.com/whitepapers/Security/AWS_Security_Checklist.pdf)
8. [AWS HIPAA Compliance](https://d0.awsstatic.com/whitepapers/compliance/AWS_HIPAA_Compliance_Whitepaper.pdf)
9. [AWS Cloud Adoption Framework](https://d1.awsstatic.com/whitepapers/aws_cloud_adoption_framework.pdf)
10. [AWS Auditing Security Checklist](https://d1.awsstatic.com/whitepapers/compliance/AWS_Auditing_Security_Checklist.pdf)
11. [AWS CIS Foundations Benchmark](https://d1.awsstatic.com/whitepapers/compliance/AWS_CIS_Foundations_Benchmark.pdf)
12. [NIST Cybersecurity Framework on AWS](https://d0.awsstatic.com/whitepapers/compliance/NIST_Cybersecurity_Framework_CSF.pdf)
13. [NIST 800-144: Security and Privacy in Public Cloud](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-144.pdf)

### Service-Specific Security
14. [AWS Security Incident Response](https://d1.awsstatic.com/whitepapers/aws_security_incident_response.pdf)
15. [AWS Lambda Security Overview](https://d1.awsstatic.com/whitepapers/Overview-AWS-Lambda-Security.pdf)
16. [AWS KMS Best Practices](https://d1.awsstatic.com/whitepapers/aws-kms-best-practices.pdf)
17. [Amazon EFS Encryption](https://d1.awsstatic.com/whitepapers/Security/amazon-efs-encrypted-filesystems.pdf)
18. [AWS CloudHSM Backup Security](https://d1.awsstatic.com/whitepapers/Security/security-of-aws-cloudhsm-backups.pdf)
19. [Security at the Edge](https://d1.awsstatic.com/whitepapers/Security/security-at-the-edge.pdf)
20. [AWS Fargate Security Overview](https://d1.awsstatic.com/whitepapers/AWS_Fargate_Security_Overview_Whitepaper.pdf)
21. [AWS Lambda Security Deep Dive](https://aws.amazon.com/lambda/security-overview-of-aws-lambda/)

### AI/ML Security (New 2024-2026)
22. [Amazon Bedrock Security and Privacy](https://aws.amazon.com/bedrock/security-privacy-responsible-ai/) - Guardrails, content filtering, PII redaction
23. [Build Responsible AI with Amazon Bedrock Guardrails](https://aws.amazon.com/blogs/machine-learning/build-responsible-ai-applications-with-amazon-bedrock-guardrails/)
24. [AWS Digital Sovereignty](https://aws.amazon.com/compliance/digital-sovereignty/) - Data residency and compliance

## Books

### Penetration Testing & Offensive Security
1. [Hands-On AWS Penetration Testing with Kali Linux](https://www.packtpub.com/en-co/product/hands-on-aws-penetration-testing-with-kali-linux-9781789136722) - Packt
2. [Hacking AWS](https://www.wiley.com/en-us/Hacking+AWS-p-9781394207299) - Wiley (2024)

### Security Architecture & Best Practices
3. [Mastering AWS Security](https://www.packtpub.com/en-co/product/mastering-aws-security-9781805121718) - Packt (2024)
4. [AWS Security Best Practices](https://www.packtpub.com/en-co/product/aws-security-best-practices-on-aws-9781789137637) - Packt
5. [AWS Security Cookbook](https://www.packtpub.com/product/aws-security-cookbook/9781838826253) - Packt
6. [AWS Security](https://www.manning.com/books/aws-security) - Manning (2024)
7. [Effective IAM for AWS](https://www.effectiveiam.com) - Comprehensive IAM guide

### Cloud Security Fundamentals
8. [Practical Cloud Security](https://www.oreilly.com/library/view/practical-cloud-security/9781492037507/) - O'Reilly
9. [Securing DevOps](https://www.manning.com/books/securing-devops) - Manning
10. [CSA Guide to Cloud Computing](https://www.oreilly.com/library/view/csa-guide-to/9780124201255/) - Syngress
11. [Cloud Security Automation](https://www.packtpub.com/en-co/product/cloud-security-automation-9781788622196) - Packt

### Serverless & Specialized
12. [Serverless Security](https://ServerlessSecurityBook.com) - Apress (AWS, Azure, GCP)
13. [AWS Lambda Security Best Practices](http://www.aliencoders.org/wp-content/uploads/2020/01/AWS-Lambda-Security-eBook-1.pdf) - Puresec (PDF)
14. [Amazon Bedrock in Action](https://www.manning.com/books/amazon-bedrock-in-action) - Manning

### Free Resources
15. [Practical Guide to Security in AWS](https://pages.awscloud.com/rs/112-TZM-766/images/Cloud%20Security%20Practical%20Guide%20to%20Security%20in%20the%20AWS%20Cloud.pdf) - SANS/AWS (PDF)

## Videos

### AWS Official & Conference Talks
1. [The Fundamentals of AWS Security](https://www.youtube.com/watch?v=-ObImxw1PmI) - AWS
2. [AWS Security by Design](https://www.youtube.com/watch?v=I1SwoKxB13c) - AWS
3. [Account Security with IAM](https://www.youtube.com/watch?v=9CKsX6MOPDQ) - AWS
4. [AWS re:Inforce Security Best Practices](https://www.youtube.com/watch?v=u6BCVkXkPnM) - AWS re:Inforce
5. [Security at Scale: Goldman Sachs on AWS](https://www.youtube.com/watch?v=5cnob8HIswY) - AWS re:Invent 2020
6. [Hands-On AWS Security Best Practices](https://www.youtube.com/watch?v=dabbsZ_sDX0) - AWS

### Learning Playlists
7. [AWS Cloud Security Playlist](https://www.youtube.com/watch?v=N4DdqAkeqD4&list=PLxzKY3wu0_FL4VDfuCohtikXTQNTvKQVX) - Comprehensive series
8. [flaws.cloud Challenge Solutions](https://www.youtube.com/watch?v=VDptLO9XYbU&list=PLRTsCutScZnzo3uV_79Dur73kqskfaTMS) - Walkthrough

### Service Deep Dives
9. [Introduction to AWS Security Hub](https://www.youtube.com/watch?v=o0NDi01YPXs)
10. [Cloud Security Architecture Workshop](https://www.youtube.com/watch?v=4TxvqZFMaoA) - RSA
11. [AWS Cloud Security](https://www.oreilly.com/library/view/aws-cloud-security/9780135174784/) - O'Reilly

## Tutorials & Blogs

### Official AWS Resources
1. [AWS Security Blog](https://aws.amazon.com/blogs/security/) - Official AWS security updates and best practices
2. [Strengthen S3 Security with Additional AWS Services](https://aws.amazon.com/blogs/security/strengthen-the-security-of-sensitive-data-stored-in-amazon-s3-by-using-additional-aws-services/)
3. [IMDSv2 Defense in Depth](https://aws.amazon.com/blogs/security/defense-in-depth-open-firewalls-reverse-proxies-ssrf-vulnerabilities-ec2-instance-metadata-service/)
4. [Managing KMS Permissions with Grants](https://aws.amazon.com/blogs/security/managing-permissions-with-grants-in-aws-key-management-service/)

### Penetration Testing & Exploitation
5. [AWS Penetration Testing Guide](https://www.hackthebox.com/blog/aws-pentesting-guide) - HackTheBox
6. [AWS IAM Exploitation](https://sra.io/blog/aws-iam-exploitation/) - SRA
7. [S3 Penetration Testing](https://rhinosecuritylabs.com/penetration-testing/penetration-testing-aws-storage/) - Rhino Security
8. [AWS IAM Privilege Escalation Methods](https://rhinosecuritylabs.com/aws/aws-privilege-escalation-methods-mitigation/) - Rhino Security
9. [IAM Privilege Escalation Attacks](https://payatu.com/blog/mayank.arora/iam_privilege_escalation_attack) - Payatu
10. [IAM Vulnerable Lab Repository](https://github.com/BishopFox/iam-vulnerable) - Bishop Fox

### Vulnerability Research
11. [AWS CloudFormation Vulnerability](https://orca.security/resources/blog/aws-cloudformation-vulnerability/) - Orca Security
12. [AWS Glue Vulnerability](https://orca.security/resources/blog/aws-glue-vulnerability/) - Orca Security
13. [CVE-2022-25165: AWS VPN Client Privilege Escalation](https://rhinosecuritylabs.com/aws/cve-2022-25165-aws-vpn-client/) - Rhino Security
14. [Weaponizing ECS Task Definitions](https://rhinosecuritylabs.com/aws/weaponizing-ecs-task-definitions-steal-credentials-running-containers/) - Rhino Security
15. [Exploring AWS EBS Snapshots](https://rhinosecuritylabs.com/aws/exploring-aws-ebs-snapshots/) - Rhino Security

### S3 Security Deep Dives
16. [S3 Access Controls Deep Dive](https://labs.detectify.com/2017/07/13/a-deep-dive-into-aws-s3-access-controls-taking-full-control-over-your-assets/) - Detectify
17. [S3 Security Design Flaws](https://www.upguard.com/blog/s3-security-is-flawed-by-design) - UpGuard
18. [Discovering Open Databases on AWS](https://infosecwriteups.com/how-i-discovered-thousands-of-open-databases-on-aws-764729aa7f32) - InfoSec Write-ups

### Attack Techniques
19. [Hacking Serverless Runtimes](https://www.blackhat.com/docs/us-17/wednesday/us-17-Krug-Hacking-Severless-Runtimes.pdf) - Black Hat 2017
20. [SSRF via HTML Injection in PDF on EC2](https://blog.appsecco.com/finding-ssrf-via-html-injection-inside-a-pdf-file-on-aws-ec2-214cc5ec5d90) - AppSecCo
21. [Chaining Vulnerabilities for Shell Access](https://blog.appsecco.com/getting-shell-and-data-access-in-aws-by-chaining-vulnerabilities-7630fa57c7ed) - AppSecCo
22. [Instance Metadata Exploitation](https://www.mcafee.com/blogs/enterprise/cloud-security/how-an-attacker-could-use-instance-metadata-to-breach-your-app-in-aws/) - McAfee

### Architecture & Best Practices
23. [AWS in Plain English](https://expeditedsecurity.com/aws-in-plain-english/) - Service overview
24. [AWS Security Primer](https://cloudonaut.io/aws-security-primer/) - Cloudonaut
25. [ConsoleMe: Central AWS Permissions Control](https://netflixtechblog.com/consoleme-a-central-control-plane-for-aws-permissions-and-access-fd09afdd60a8) - Netflix
26. [API Gateway Security](https://dzone.com/articles/the-role-of-api-gateways-in-api-security) - DZone
27. [51 Tips for AWS Security](https://www.mcafee.com/enterprise/en-us/assets/skyhigh/white-papers/wp-definitive-guide-to-aws-ebook.pdf) - McAfee (PDF)

### New 2024-2026 Resources
28. [AWS Security Best Practices 2025](https://squareops.com/knowledge/top-10-aws-security-best-practices-for-us-companies/) - SquareOps
29. [AWS CDK Security Vulnerability Analysis](https://toxigon.com/aws-security-issues-2024) - CDK account takeover risks
30. [Protect GenAI Apps Against Encoding Attacks](https://aws.amazon.com/blogs/security/protect-your-generative-ai-applications-against-encoding-attacks-with-amazon-bedrock-guardrails/) - AWS Security Blog
31. [AWS Security Incidents and Lessons Learned](https://www.cisin.com/coffee-break/aws-security-incidents-and-lessons-learned.html) - CISO insights
32. [State of Cloud Security 2025](https://prowler.com/blog/cloud-security-report-2025/) - Prowler Report

## Online Courses

### Certification Preparation
1. [AWS Certified Security Specialty](https://www.udemy.com/course/aws-certified-security-specialty/) - Udemy (Zeal Vora)
2. [AWS Certified Security Specialty](https://www.udemy.com/course/ultimate-aws-certified-security-specialty/) - Udemy (Stephane Maarek)
3. [AWS Certified Security Specialty](https://acloud.guru/learn/aws-certified-security-specialty) - A Cloud Guru
4. [AWS Certified Security Specialty](https://www.whizlabs.com/aws-certified-security-specialty/) - WhizLabs

### Foundational Courses
5. [AWS Fundamentals: Addressing Security Risk](https://www.coursera.org/learn/aws-fundamentals-addressing-security-risk) - Coursera
6. [Cloud Computing Security](https://www.coursera.org/learn/cloud-computing-security) - Coursera
7. [Getting Started with Cloud Security](https://www.edx.org/course/aws-getting-started-with-cloud-security) - edX
8. [AWS Security Learning Plan](https://explore.skillbuilder.aws/learn/public/learning_plan/view/91/security-learning-plan) - AWS Skill Builder (Free)

### Advanced & Specialized
9. [AWS Advanced Security](https://www.udemy.com/course/aws-advanced-security/) - Udemy
10. [AWS Security Path](https://www.appsecengineer.com/product/aws-security) - AppSecEngineer
11. [AWS for Architects: Advanced Security](https://www.linkedin.com/learning/aws-for-architects-advanced-security/) - LinkedIn Learning
12. [Practical Event Driven Security](https://acloud.guru/learn/practical-event-driven-security-with-aws) - A Cloud Guru
13. [AWS Security Learning Path](https://learn.acloud.guru/learning-path/aws-security) - A Cloud Guru

### Offensive Security & Penetration Testing
14. [Cloud Hacking](https://www.notsosecure.com/hacking-training/cloud-hacking/) - NotSoSecure
15. [Breaking and Pwning AWS and Azure](https://github.com/appsecco/breaking-and-pwning-apps-and-servers-aws-azure-training) - AppSecCo (Free)
16. [Cloud Security Bootcamp](https://www.cloudsecuritybootcamp.com) - Kaizenteq (Free monthly)
17. [EKS Security Masterclass](https://ekssecurity.kubernetesvillage.com/) - Free EKS Attack & Defense

### New 2024-2026 Courses
18. [Breaching AWS - Offensive AWS Security](https://cloudbreach.io/breachingaws/) - CloudBreach (OAWSP Certification)
19. [Certified Cloud Pentesting Expert - AWS](https://pentestingexams.com/product/certified-cloud-pentesting-expert/) - CCPenX-AWS
20. [Pentesting AWS with Pacu, CloudGoat & ChatGPT](https://cybr.com/courses/pentesting-aws-environments-with-pacu-cloudgoat-and-chatgpt/) - CYBR

### Cloud Security Certifications (2026)
21. [CCSP - Certified Cloud Security Professional](https://www.isc2.org/certifications/ccsp) - ISC2 (vendor-neutral, 5 years exp required)
22. [CCSK - Certificate of Cloud Security Knowledge](https://cloudsecurityalliance.org/education/ccsk/) - CSA (foundational)
23. [AWS Certified Security - Specialty](https://aws.amazon.com/certification/certified-security-specialty/) - AWS Official

---

## Security Tools

### 🆕 AWS re:Invent 2025 New Services
| Service | Description |
|---------|-------------|
| **AWS Security Agent** | AI-powered SAST, automated security reviews, context-aware pentesting (Preview) |
| **Security Hub v2** | ML threat detection, automated correlation, real-time risk analytics |
| **GuardDuty Extended** | Multi-stage attack detection for EC2, ECS, S3 |
| **IAM Access Analyzer** | Customizable unused access analysis, guided revocation |

### AWS Native Security Services
[AWS Security Products](https://aws.amazon.com/products/security/) - Official AWS security service portfolio:

| Service | Description |
|---------|-------------|
| **IAM** | Identity and access management for AWS resources |
| **IAM Identity Center** | Centralized SSO and identity management |
| **CloudWatch** | Monitoring, logging, and observability |
| **CloudTrail** | API activity logging for governance and compliance |
| **Inspector** | Automated vulnerability assessment (Classic ends May 2026) |
| **GuardDuty** | Intelligent threat detection with ML + Extended Threat Detection |
| **KMS** | Key management with FIPS 140-2 validated HSMs |
| **Shield** | DDoS protection for EC2, ELB, CloudFront, Route 53 |
| **Trusted Advisor** | Real-time best practice recommendations |
| **Config** | Resource configuration assessment and auditing |
| **Security Hub** | Centralized security posture management (v2 GA Dec 2025) |
| **WAF** | Web application firewall |
| **Macie** | ML-powered sensitive data discovery |
| **Detective** | Security investigation and analysis |
| **Bedrock Guardrails** | GenAI content filtering, PII redaction, hallucination detection |
| **Conformance Packs** | Pre-built Config rule collections ([GitHub](https://github.com/awslabs/aws-config-rules/tree/master/aws-config-conformance-packs)) |

### Security Auditing & Assessment
1. [Prowler v5](https://github.com/prowler-cloud/prowler) - Open cloud security platform for AWS, Azure, GCP, K8s, M365 (2025 update)
2. [ScoutSuite](https://github.com/nccgroup/ScoutSuite) - Multi-cloud security auditing
3. [CloudMapper](https://github.com/duo-labs/cloudmapper) - AWS environment analysis and visualization
4. [aws-lint-iam-policies](https://github.com/welldone-cloud/aws-lint-iam-policies) - IAM policy analysis
5. [Nubicustos](https://github.com/Su1ph3r/Nubicustos) - Orchestrates 20+ security tools with unified findings
6. [Steampipe](https://github.com/turbot/steampipe) - SQL-based cloud infrastructure querying
7. [AWS Security Assessment Solution](https://github.com/awslabs/aws-security-assessment-solution) - Official AWS Prowler-based assessment

### Penetration Testing
8. [Pacu](https://github.com/RhinoSecurityLabs/pacu) - AWS exploitation framework
9. [CloudFox](https://github.com/BishopFox/cloudfox) - Cloud penetration testing automation
10. [AWS PWN](https://github.com/dagrz/aws_pwn) - AWS penetration testing toolkit
11. [HackTricks Cloud - AWS](https://cloud.hacktricks.xyz/pentesting-cloud/aws-pentesting) - AWS pentesting methodology
12. [Hacking the Cloud](https://hackingthe.cloud/aws/general-knowledge/aws_organizations_defaults/) - Cloud attack techniques
13. [Stratus Red Team](https://github.com/DataDog/stratus-red-team) - Adversary emulation for cloud (Datadog)

### Secrets & Credential Management
14. [AWS Vault](https://github.com/99designs/aws-vault) - Secure credential storage for development
15. [truffleHog](https://github.com/dxa4481/truffleHog) - Git repository secrets scanner
16. [Gitleaks](https://github.com/zricethezav/gitleaks) - Git secrets auditing

### Infrastructure Security
17. [AWS Security Benchmark](https://github.com/awslabs/aws-security-benchmark) - CIS Foundation framework demos
18. [AWS Security Automation](https://github.com/awslabs/aws-security-automation) - DevSecOps and incident response scripts
19. [S3 Inspector](https://github.com/kromtech/s3-inspector) - S3 bucket permission checker
20. [s3dns](https://github.com/olizimmermann/s3dns) - Passive DNS-based S3 bucket discovery
21. [Zeus](https://github.com/DenizParlak/Zeus) - AWS auditing and hardening
22. [AWS Firewall Factory](https://github.com/globaldatanet/aws-firewall-factory) - Centralized WAF management via FMS

### Access Management
23. [ConsoleMe](https://github.com/Netflix/consoleme) - Central AWS permissions control plane (Netflix)
24. [Arsenal of AWS Security Tools](https://github.com/toniblyx/my-arsenal-of-aws-security-tools) - Comprehensive tool collection

### Cloud Compliance Tools (2025-2026)
25. [Qualys Cloud Security](https://blog.qualys.com/product-tech/2026/01/29/top-10-cloud-compliance-tools-for-enterprise-security-and-audit-readiness-in-2026) - Enterprise compliance
26. [k9 Security](https://www.k9security.io/) - AWS IAM security analysis

---

## Hands-on Labs & CTFs

### AWS Official Labs
1. [AWS Well-Architected Security Labs](https://wellarchitectedlabs.com/security/) - Official hands-on exercises
2. [AWS Security Workshops](https://awssecworkshops.com/) - Official security workshop collection
3. [AWS Workshop Portal](https://awsworkshop.io/) - General AWS hands-on workshops
4. [Cloud Quest: Security Role](https://explore.skillbuilder.aws/learn/course/external/view/elearning/7636/cloud-quest) - AWS Skill Builder
5. [AWS Jam Journey: Security](https://explore.skillbuilder.aws/learn/course/external/view/elearning/9284/aws-jam-journey-security) - AWS Skill Builder

### Vulnerable-by-Design Environments
6. [flaws.cloud](http://flaws.cloud/) - Classic AWS misconfiguration challenges
7. [flaws2.cloud](http://flaws2.cloud/) - Advanced AWS security concepts
8. [CloudGoat](https://github.com/RhinoSecurityLabs/cloudgoat) - Vulnerable AWS infrastructure deployment - Rhino Security
9. [OWASP ServerlessGoat](https://github.com/OWASP/Serverless-Goat) - Insecure Lambda application
10. [OWASP WrongSecrets](https://github.com/commjoen/wrongsecrets) - Secrets management anti-patterns
11. [CloudFoxable](https://cloudfoxable.bishopfox.com/) - Build your own vulnerable AWS playground - Bishop Fox

### Third-Party Platforms
12. [TryHackMe: Attacking and Defending AWS](https://resources.tryhackme.com/attacking-and-defending-aws)
13. [HackTheBox Black Sky Cloud Labs](https://www.hackthebox.com/business/professional-labs/cloud-labs-blacksky)
14. [Pentesting.cloud](https://pentesting.cloud/) - Free AWS security labs
15. [Breaking and Pwning AWS/Azure](https://github.com/appsecco/breaking-and-pwning-apps-and-servers-aws-azure-training) - AppSecCo training

### Threat Modeling
16. [ThreatModel for Amazon S3](https://github.com/trustoncloud/threatmodel-for-aws-s3) - S3 attack scenarios and mitigations
17. [AWS S3 CTF Challenges](https://n0j.github.io/2017/10/02/aws-s3-ctf.html) - S3-focused challenges
18. [AWS CTF Practical Scenarios](https://r00tz-ctf.awssecworkshops.com/) - Real-world scenario CTF

### New Labs 2024-2026
19. [Pwned Labs](https://pwnedlabs.io/) - Cloud pentesting walkthroughs and labs
20. [CloudBreach Labs](https://cloudbreach.io/) - Vulnerable AWS infrastructure for training
21. [Cloud Pentesting Checklist 2025](https://www.onlinehashcrack.com/guides/ethical-hacking/cloud-pentesting-checklist-2025-aws-azure.php) - Comprehensive checklist

## Security Bulletins

### Critical Vulnerabilities
1. [CVE-2020-8558](https://nvd.nist.gov/vuln/detail/CVE-2020-8558) - Container networking issue allowing adjacent host access to localhost services
2. [CVE-2020-8911](https://nvd.nist.gov/vuln/detail/CVE-2020-8911) - CBC padding oracle in AWS S3 Crypto SDK for Go
3. [CVE-2020-8912](https://nvd.nist.gov/vuln/detail/CVE-2020-8912) - In-band key negotiation issue in AWS S3 Crypto SDK for Go
4. [CVE-2018-15869](https://nvd.nist.gov/vuln/detail/CVE-2018-15869) - AMI validation bypass when --owners flag not specified

### AWS Security Advisories
5. [TLS 1.2 Minimum Requirement for FIPS Endpoints](https://aws.amazon.com/security/security-bulletins/AWS-2020-001/)
6. [Unencrypted MD5 Hash in S3 Crypto SDK Metadata](https://github.com/google/security-research/security/advisories/GHSA-76wf-9vgp-pj7w)
7. [Open Databases Discovery on AWS](https://infosecwriteups.com/how-i-discovered-thousands-of-open-databases-on-aws-764729aa7f32)

### 2024-2025 Security Issues
8. [AWS CDK Account Takeover Vulnerability (2024)](https://toxigon.com/aws-security-issues-2024) - Cloud Development Kit security flaw
9. [Massive AWS Credential Exposure (Aug 2024)](https://riskcognizance.com/blog/massive-aws-data-breach-exposes-millions-of-users-to-hackers-how-misconfigured-cloud-instances-are-putting-data-at-risk) - Misconfigured cloud instances

## Notable Breaches

Understanding past incidents helps prevent future security failures.

| Year | Incident | Root Cause | Reference |
|------|----------|------------|-----------|
| 2019 | Capital One | S3 misconfiguration, SSRF | [Analysis](https://rhinosecuritylabs.com/aws/capital-one-cloud_breach_s3-cloudgoat/) |
| 2019 | Imperva | Stolen AWS API keys | [Report](https://www.zdnet.com/article/imperva-blames-data-breach-on-stolen-aws-api-key/) |
| 2018 | Tesla | Exposed Kubernetes dashboard | [Article](https://www.businessinsider.in/finance/teslas-amazon-cloud-account-was-hacked-and-used-to-mine-cryptocurrency/articleshow/63003345.cms) |
| 2020 | Lion Air | S3 misconfiguration | [Report](https://www.darkreading.com/attacks-breaches/lion-air-the-latest-to-get-tripped-up-by-misconfigured-aws-s3-/d/d-id/1335864) |
| 2020 | 21 Buttons | S3 misconfiguration | [Report](https://www.vpnmentor.com/blog/report-21-buttons-breach/) |
| 2020 | Utah COVID Testing | S3 misconfiguration | [Report](https://www.comparitech.com/blog/information-security/utah-covid-test-center-leak/) |
| 2021 | US Municipalities | S3 misconfiguration | [Report](https://www.securitymagazine.com/articles/95704-us-municipalities-suffer-data-breach-due-to-misconfigured-amazon-s3-buckets) |
| 2024 | Angel One (Financial) | S3 misconfiguration - 440GB | [Report](https://redrobot.online/2025/05/23/financial-brokerage-exposes-440-gb-of-client-data-through-misconfigured-aws-bucket/) |
| 2025 | Cloud Storage Leaks | 10% of public buckets exposed | [Tenable Report](https://www.cybersecuritydive.com/news/cloud-security-amazon-google-microsoft-tenable-report/751047/) |
| 2025 | Docker Hub Crypto Mining | Compromised credentials | [Timeline](https://cybersecurityforme.com/amazon-data-breaches-timeline/) |

### Additional Resources
- [AWS Security Breaches 2017 Summary](https://www.sumologic.com/blog/aws-security-breaches-2017/)
- [200 Million Voter Data Leak](https://www.skyhighnetworks.com/cloud-security-blog/latest-voter-data-leak-is-a-lesson-in-aws-security/)
- [10 Worst Amazon S3 Breaches](https://businessinsights.bitdefender.com/worst-amazon-breaches)
- [AWS Data Breach Lessons for CISOs](https://www.blackfog.com/aws-data-breach/) - BlackFog Analysis

## Infrastructure Vulnerabilities

### CPU-Level Vulnerabilities

**Spectre and Meltdown (2018)**
- Impact: Affected Intel, AMD, and ARM CPUs; enabled unauthorized cross-process data access including VM isolation bypass
- Type: Side-channel attacks exploiting speculative execution
- Mitigation: AWS deployed KPTI, Retpoline patches, and microcode updates

**Zenbleed (2023)**
- Impact: AMD Zen 2 processors leaked encryption keys and passwords from CPU registers
- Type: Register file leak via speculative execution failure
- Mitigation: AWS applied microcode updates and software patches to affected EC2 instances

### 2024-2025 Statistics
- Average cost of cloud data breach: **$5.17 million** (IBM 2024)
- US enterprise average: **$9.36 million**
- 10% of public cloud storage buckets contain sensitive data (Tenable 2025)

---

## Podcasts & Newsletters

### Podcasts
1. [Cloud Security Podcast](https://www.cloudsecuritypodcast.tv/) - Weekly interviews with cloud security professionals
2. [AWS Podcast](https://aws.amazon.com/podcasts/aws-podcast/) - Official AWS podcast
3. [The Cloud Pod](https://www.thecloudpod.net/) - Weekly AWS, Azure & GCP news
4. [Screaming in the Cloud](https://www.lastweekinaws.com/podcast/screaming-in-the-cloud/) - Cloud industry interviews

### Newsletters
5. [Cloud Security Newsletter](https://www.cloudsecuritynewsletter.com/) - Weekly cloud security digest
6. [AWS Security Blog RSS](https://aws.amazon.com/blogs/security/feed/) - Official AWS security updates
7. [tl;dr sec Newsletter](https://tldrsec.com/) - Weekly security newsletter with cloud coverage
8. [Cloud Security Club](https://cloudsecurity.club/) - Prowler updates and cloud security insights
9. [Last Week in AWS](https://www.lastweekinaws.com/) - Weekly AWS news and analysis

### Blogs to Follow (2026)
10. [AWS Security Blog](https://aws.amazon.com/blogs/security/) - Official
11. [Chris Farris Blog](https://www.chrisfarris.com/) - AWS security insights
12. [Rhino Security Labs](https://rhinosecuritylabs.com/blog/) - Cloud pentesting research
13. [Orca Security Research](https://orca.security/resources/blog/) - Cloud vulnerability research

---

## Contributors

See [Contribute.md](Contribute.md) for contribution guidelines.

[View All Contributors](https://github.com/vanhoangkha/awesome-aws-security/graphs/contributors)

---

*Maintained by [vanhoangkha](https://github.com/vanhoangkha) | Last updated: February 2026*
