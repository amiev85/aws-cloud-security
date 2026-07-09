# aws-cloud-security
AWS cloud security labs - IAM, VPC, S3, GuardDuty, CloudTrail, Prowler, incident response

# AWS Cloud Security Labs

Practical cloud security labs covering AWS security fundamentals, posture assessment, and incident response.

## Labs Completed

### IAM Security
- Least privilege policy design
- Role vs user analysis
- Excessive permission identification and remediation
- Credential management best practices

### VPC & Network Security  
- VPC segmentation design
- Security group hardening
- Network ACL configuration
- Exposed administrative service identification

### S3 Security
- Public access identification and blocking
- Bucket policy analysis
- Encryption configuration (SSE-S3, SSE-KMS)
- Access logging setup

### Monitoring & Detection
- CloudTrail configuration for audit logging
- CloudWatch alerting for suspicious activity
- GuardDuty threat detection review
- Prowler posture assessment against CIS benchmarks

### Incident Response
- PICERL framework application
- MITRE ATT&CK mapping for cloud TTPs
- Containment and eradication playbooks
- Evidence collection in cloud environments

## Key Vulnerabilities Assessed

| Issue | Risk | Remediation |
|-------|------|-------------|
| Public S3 buckets | Critical | Block public access + bucket policy |
| Excessive IAM permissions | High | Least privilege + permission boundaries |
| Exposed admin services | High | VPC restriction + security groups |
| No CloudTrail logging | High | Enable multi-region CloudTrail |
| Unencrypted secrets | High | Secrets Manager + KMS rotation |

## Tools & Services

`AWS Console` · `Prowler` · `CloudTrail` · `CloudWatch` · `GuardDuty` · `IAM Access Analyzer`

## Frameworks

`CIS AWS Foundations` · `MITRE ATT&CK for Cloud` · `PICERL` · `AWS Well-Architected Security Pillar`
```
