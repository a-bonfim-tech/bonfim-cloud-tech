# IAM — Operational Checklist

Objective: control access through identity-first security.

## Identity Lifecycle
- [ ] Joiner process defined
- [ ] Mover process defined
- [ ] Leaver process enforced
- [ ] Access revoked on exit

## Authentication
- [ ] MFA mandatory
- [ ] Strong password policy
- [ ] No legacy authentication
- [ ] Break-glass accounts controlled

## Authorization
- [ ] RBAC implemented
- [ ] Least privilege enforced
- [ ] Environment separation applied
- [ ] Privileged roles documented

## Service Accounts
- [ ] One service account per workload
- [ ] No key-based auth when avoidable
- [ ] Permissions scoped
- [ ] Rotation and review scheduled

## Audit & Review
- [ ] IAM changes logged
- [ ] Periodic access reviews
- [ ] Evidence retained
- [ ] Policy versions tracked

IAM maturity requires continuous review.
