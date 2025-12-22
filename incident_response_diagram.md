flowchart LR
    Detect[Detect]
    Analyze[Analyze]
    Contain[Contain]
    Eradicate[Eradicate]
    Recover[Recover]
    Review[Post-Incident Review]

    Detect --> Analyze
    Analyze --> Contain
    Contain --> Eradicate
    Eradicate --> Recover
    Recover --> Review
