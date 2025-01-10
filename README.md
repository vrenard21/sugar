flowchart LR
    A["Sugar Industry\nStrategies"] --> B["Commercial Determinants\nof Health (CDoH)"]
    B --> C["Targeted Marketing,\nPolitical Lobbying,\nPrice Manipulation,\nResearch Interference"]
    C --> D["Excessive Sugar\nConsumption"]

    subgraph SDOH [Social Determinants of Health]
    E["Economic Stability\n(e.g., poverty,\nfood insecurity)"]
    F["Neighborhood & Built\nEnvironment\n(e.g., food deserts,\nfood swamps)"]
    G["Education &\nHealth Literacy"]
    H["Social/Cultural\nContexts\n(e.g., chronic stress)"]
    end

    E --> D
    F --> D
    G --> D
    H --> D
    
    D --> I["Health Impacts:\nObesity, T2DM,\nCVDs, Cancer,\nImmune/Cognitive\nDysfunction"]
    D --> J["Social Inequities\nExacerbated"]

    A --> K["Environmental\nDegradation:\nDeforestation,\nPollution,\nBiodiversity Loss"]
    K --> L["Planetary Health\nThreats"]
    K --> M["Disproportionate\nHarm to Marginalized\nPopulations"]
    
    M --> J
    I --> J
