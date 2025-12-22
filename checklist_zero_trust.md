# Zero Trust — Operational Checklist

Objective: eliminate implicit trust across the environment.

## Access Control
- [ ] Identity-based access only
- [ ] No network-based trust assumptions
- [ ] Explicit allow rules
- [ ] Default deny posture

## Applications
- [ ] App-level authorization
- [ ] No direct backend exposure
- [ ] Service-to-service auth required
- [ ] Access logged

## Network
- [ ] East-west traffic restricted
- [ ] Microsegmentation applied
- [ ] Identity-aware gateways used
- [ ] No admin access from internet

## Data
- [ ] Data access tied to identity
- [ ] Classification enforced
- [ ] Exposure continuously monitored

## Monitoring
- [ ] Telemetry centralized
- [ ] Anomaly detection enabled
- [ ] Alerts tested
- [ ] Incident playbook linked

Zero Trust is validated continuously, not once.
