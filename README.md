# OpenEdX on AWS EKS

Production deployment of OpenEdX Teak using Tutor 21.0.0 on AWS EKS 1.35

## Stack
- Tutor 21.0.0 (OpenEdX Teak)
- EKS 1.35
- External Databases (RDS MySQL 8.4, DocumentDB 5.0, ElastiCache Redis 7.1, OpenSearch 2.15)
- Nginx Ingress Controller
- ArgoCD for GitOps
- CloudFront CDN + AWS WAF

## Credentials
All credentials stored in: ~/.openedx/credentials.sh (NOT in git)
