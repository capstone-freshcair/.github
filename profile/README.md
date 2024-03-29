### Hi there! We are a MEDS capstone group working with the Impact of oil production on emission, health and employment in California 

California has an ambitious goal to achieve carbon neutrality by 2045, yet it persists in the production of oil and gas, driven by its historical legacy as a significant petroleum producer. Senate Bill (SB) 1137 is a key piece of legislation that aims to regulate oil and gas infrastructure and reduce emissions. A provision in the law mandates a 3,200 foot minimum distance for new oil and gas structures from sensitive areas such as residential areas, schools, and healthcare facilities. The law was signed, but the oil industry successfully lobbied to move it to a referendum vote in November 2024. Now, the fate of SB 1137 depends on public approval, but there is a lack of data-driven analysis of the impacts of the proposed rule to inform the vote. The 2035 Initiative and emLab established a framework that assesses the effects of supply-side measures such as excise taxes, setback policies, carbon taxes on oil drilling operations, climate, employment, and public health at setback distances of 1,000 feet, 2,500 feet, and 1 mile from existing oil wells (Deshmukh et al. 2023). This project will extend this existing research by updating the framework to analyze how environmental policies – including SB 1137’s proposed 3200 foot setback – affect vulnerable communities, focusing on equitable health benefit distribution and assessing job loss impacts in the clean energy transition. We plan to create a machine learning model, utilizing historical data from the Department of Conservation, to predict future oil well locations throughout California, and explore this policy design for effectively measuring and managing these predictions . Additionally, we will examine the subsequent health risks and emission effects on surrounding vulnerable communities, employing methods such as geospatial analysis, time series analysis, and predictive modeling. We will create interactive maps and graphics to provide clear and intuitive visual interpretations of our findings that will be accessible to the public. The outcomes of this study will offer valuable and visual support to the implementation and durability of SB 1137, encapsulating the multifaceted impacts, significance, and logistics of the setback policy.


### Repository file structure

This is the fundamental structure of our repository:
We have two primary structures: "model" and "data". The existing model comprises three different sections (extraction, health, labor), which will be simplified to sections, and we will select the necessary ones to remain in this repository in the future. The Shinydashboard will be updated in the Spring quarter.
We create processed and final data. At the end of the project, we will select only the necessary files and structure the processed and final data accordingly.

Forked repository: https://github.com/mariamkg00/meds-freshcair-capstone/tree/main

```
├── model/
│   ├── energy/
│   │   ├── data-processing-prep/     
│   │   └── extraction/
│   │       ├── extraction/
│   │       └── cost/
│   │       └── map/ 
│   ├── health/
│   │   ├── health/
│   │   └── map/ 
│   ├── labor/
│   ├── mechanism/                             # will be removed 
│   ├── pred-model/                            # will be removed 
│   └── scripts/STAT_tool box                  # will be removed 
├── .gitignore
├── README.md
└── data                                       # not share in public
```
