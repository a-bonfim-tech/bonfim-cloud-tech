# Storage Strategy — Reference Architecture

Storage is treated as a security domain, not a utility.
All data is classified, encrypted, monitored and recoverable by design.

## Core Principles
- Data classification first
- Encryption everywhere
- Least-access storage
- Default deny for public exposure
- Backup and recovery are mandatory

## Data Classification
All data is classified before storage:
- Public: non-sensitive, approved for exposure
- Internal: business data, restricted access
- Confidential: sensitive data, strict access controls
- Restricted: regulated or high-risk data

Classification determines:
- Access policies
- Encryption requirements
- Logging level
- Retention period

## Encryption
- Encryption at rest for all storage
- Encryption in transit for all access
- Customer-managed keys where applicable
- Key rotation enforced

No unencrypted storage is allowed.

## Access Control
- Storage access is identity-based (IAM)
- No anonymous or shared access
- Service accounts have scoped permissions
- Human access is reviewed periodically

Public access is disabled by default.

## Storage Types and Usage
- Object storage: documents, backups, logs
- Block storage: workloads requiring low latency
- File storage: legacy or shared access needs

Each storage type follows the same security baseline.

## Backup and Resilience
- Automated backups enabled
- Versioning for critical data
- Cross-region backup where applicable
- Regular restore testing

Backups are protected with separate access policies.

## Logging and Monitoring
- Access logs enabled for all storage
- Alerts on:
  - Public exposure
  - Permission changes
  - Unusual access patterns
- Logs retained for audit and forensics

## Governance Controls
- Storage ownership is defined
- Data retention policies enforced
- Periodic exposure scans
- Compliance alignment (LGPD-ready)

## Security Outcomes
This storage strategy prevents:
- Accidental public exposure
- Data loss
- Unauthorized access
- Compliance violations

Storage without governance is considered a risk.
