# External Databases

All databases are AWS managed services in private subnets.

## Components
- MySQL 8.4 (RDS)
- DocumentDB 5.0 (MongoDB-compatible)
- Redis 7.1 (ElastiCache)
- OpenSearch 2.15 (AWS managed)

## Security
- Private subnets only
- TLS/SSL enabled
- IAM-based access for OpenSearch
- Encryption at rest

## Important
- DocumentDB requires TLS with CA certificate
- OpenSearch uses IAM (not public access)
- Credentials in ~/.openedx-secrets/databases.env (NOT in git)
