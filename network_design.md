# Bonfim Cloud Tech — GCP Network Design (Internal)

## Objective
Provide a secure, segmented and auditable cloud network
to support internal operations, demos and reference architectures.

## Projects Structure
- bct-core
- bct-security
- bct-sandbox

Each project is isolated for blast-radius reduction.

## VPC Design
Each project contains:
- One VPC per project
- No default network
- Explicit subnet definition

## Subnets
- management-subnet
- workload-subnet
- restricted-subnet

## Connectivity
- No public IPs by default
- Identity-aware access
- Controlled ingress via proxy / gateway
