# Cloud Security Baseline — Operational Checklist

Objective: establish a minimum secure cloud posture.

## Identity & Access
- [ ] Central IdP configured
- [ ] MFA enforced for all human users
- [ ] No shared accounts
- [ ] Least privilege roles applied
- [ ] Privileged access time-bound

## Network
- [ ] Flat networks eliminated
- [ ] Segmentation implemented (prod/stage/dev)
- [ ] Ingress restricted to approved entry points
- [ ] Egress controls defined
- [ ] Firewall rules documented and reviewed

## Storage & Data
- [ ] Data classification defined
- [ ] Encryption at rest enabled
- [ ] Encryption in transit enforced
- [ ] Public access disabled by default
- [ ] Backup and versioning enabled

## Logging & Monitoring
- [ ] Centralized logging enabled
- [ ] Access logs retained
- [ ] Alerts for critical events configured
- [ ] Log retention aligned with governance

## Governance
- [ ] Ownership defined per system
- [ ] Policies documented
- [ ] Changes tracked
- [ ] Periodic reviews scheduled

Baseline complete when all items are checked.
