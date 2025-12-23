flowchart LR
    Internet((Internet))
    IAP[Identity-Aware Proxy]
    VPC[VPC Network]
    Mgmt[Management Subnet]
    Workload[Workload Subnet]
    Restricted[Restricted Subnet]
    Logs[Central Logging]

    Internet --> IAP
    IAP --> Mgmt
    Mgmt --> Workload
    Workload --> Restricted
    VPC --> Logs
