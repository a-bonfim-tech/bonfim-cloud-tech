flowchart TD
    Data[Data]
    Classify[Classification]
    Encrypt[Encryption]
    IAM[IAM Access]
    Backup[Backup]
    Audit[Audit Logs]

    Data --> Classify
    Classify --> Encrypt
    Encrypt --> IAM
    IAM --> Backup
    IAM --> Audit
