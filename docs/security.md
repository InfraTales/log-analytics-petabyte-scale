# Security Overview

Security posture of **Petabyte Log Analytics**.

## Data Protection

- **Encryption at rest**: KMS for OpenSearch and S3
- **Encryption in transit**: TLS 1.2+
- **Access control**: Fine-grained OpenSearch security
- **PII handling**: Log scrubbing pipelines

## Access Controls

- **IAM integration**: OpenSearch SAML/OIDC
- **Role-based access**: Per-index permissions
- **Audit logging**: All queries logged
- **VPC deployment**: No public access

## Compliance

- SOC 2 audit logging
- GDPR data retention
- HIPAA log protection
- PCI-DSS log requirements

> See `SECURITY.md` for detailed configurations.
