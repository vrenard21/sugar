flowchart LR

    A([Sugar Industry<br>Strategies]) --> B([Commercial Determinants<br>of Health (CDoH)])
    B --> C([Targeted Marketing,<br>Political Lobbying,<br>Price Manipulation,<br>Research Interference])
    C --> D([Excessive Sugar Consumption])

    subgraph SDOH [Social Determinants of Health]
    E([Economic Stability<br>(e.g., poverty, food insecurity)]) 
    F([Neighborhood and<br>Built Environment<br>(e.g., food deserts,<br>food swamps)])
    G([Education and<br>Health Literacy])
    H([Social/Cultural<br>Contexts<br>(e.g., chronic stress, <br> cultural norms)])
    end

    E --> D
    F --> D
    G --> D
    H --> D
    
    D --> I([Health Impacts:<br>Obesity, T2DM,<br>CVDs, Cancer,<br>Immune/Cognitive<br>Dysfunction])
    D --> J([Social Inequities<br>Exacerbated])

    A --> K([Environmental<br>Degradation:<br>Deforestation,<br>Water/Air Pollution,<br>Biodiversity Loss])
    K --> L([Planetary Health<br>Threats])
    K --> M([Disproportionate<br>Harm to Marginalized<br>Populations])
    
    M --> J
    I --> J
