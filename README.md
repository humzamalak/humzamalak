# Humza Malak

**DevOps and Cloud Engineer: AWS, Kubernetes, HPC and secure data environments**

## Current work

Research computing at the London School of Economics (LSE):

- Running an 18-node GPU HPC cluster for research workloads.
- Building an AWS research platform.
- Delivering a Trusted Research Environment for NHS data.

## Featured projects

| Project | What it is |
| --- | --- |
| [Production-Ready EKS Cluster with GitOps](https://github.com/humzamalak/Production-Ready-EKS-Cluster-with-GitOps) | AWS EKS built with Terraform (VPC, EKS and IAM modules), Argo CD for GitOps and Vault HA with KMS auto-unseal. Minikube for local use. |
| [DevSecOps CI/CD Pipeline](https://github.com/humzamalak/DevSecOps-CI-CD-Pipeline-with-Security-Scanning) | CI/CD pipeline with security checks in each stage: Semgrep, Trivy, Checkov, Gitleaks, OPA, SBOM and Cosign. |
| [DevOps Bash Script Toolkit](https://github.com/humzamalak/DevOps-Bash-Script-Toolkit) | Ten standalone Bash scripts for infrastructure, CI/CD, Kubernetes, monitoring and backups. |
| [Portfolio](https://github.com/humzamalak/portfolio) | My site: static-first Next.js on Cloudflare Pages. |

## AWS projects

| Project | What it is |
| --- | --- |
| [Cloud misconfiguration detector](https://github.com/humzamalak/cloud-misconfig-detector) | CloudTrail, EventBridge and Lambda find risky changes (open SSH, public S3, admin IAM) within minutes and alert through SNS. Optional automatic fix. |
| [Serverless checkout fraud detector](https://github.com/humzamalak/serverless-checkout-fraud-detector) | API Gateway, Lambda and DynamoDB score a checkout with rules. Amazon Bedrock reviews only the unclear cases. |
| [Three-tier web app](https://github.com/humzamalak/three-tier-web-app-aws) | nginx, FastAPI and PostgreSQL on ECS Fargate and RDS behind an ALB. Docker Compose for local use. GitHub Actions deploys through OIDC. |
| [AWS cost scanner](https://github.com/humzamalak/aws-cost-scanner) | Weekly read-only Lambda: Cost Explorer summary and a list of idle resources, sent by e-mail and stored in S3. |
| [AWS troubleshooting lab](https://github.com/humzamalak/aws-troubleshooting-lab) | One Terraform variable breaks routing, a network ACL, a security group or IAM. A diagnose script and a root-cause write-up for each fault. |
| [Résumé site on S3 and CloudFront](https://github.com/humzamalak/resume-site-s3-cloudfront) | Static site in a private S3 bucket, served by CloudFront with Origin Access Control and security headers. |
| [WordPress on EC2](https://github.com/humzamalak/wordpress-ec2) | WordPress on Amazon Linux 2023, set up by hand first and then automated. Session Manager access only, daily snapshots. |
| [PDF summariser chatbot](https://github.com/humzamalak/pdf-summariser-chatbot) | Streamlit app: summarise a PDF with page citations and ask questions about it, with Amazon Bedrock. |

## Contact

- Website: [humzamalak.dev](https://humzamalak.dev)
- LinkedIn: [humza-m-64607514b](https://www.linkedin.com/in/humza-m-64607514b)
