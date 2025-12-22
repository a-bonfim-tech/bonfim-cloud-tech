flowchart TD
    Human[Human Identity]
    Workload[Workload Identity]
    External[External Partner]
    IdP[Central IdP]
    RBAC[RBAC / Policies]
    Resources[Cloud Resources]

    Human --> IdP
    Workload --> IdP
    External --> IdP
    IdP --> RBAC
    RBAC --> Resources
