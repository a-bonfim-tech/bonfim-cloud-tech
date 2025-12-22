flowchart LR
    Request[Access Request]
    Auth[Authentication]
    Context[Context Validation]
    Policy[Authorization Policy]
    Resource[Protected Resource]

    Request --> Auth
    Auth --> Context
    Context --> Policy
    Policy --> Resource
