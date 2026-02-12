# Analyzing Traffic Accident Severity in the U.S.

1. Overview 
This project analyzes U.S. traffic accident data to identify factors influencing accident severity. The study focuses on the correlation between road conditions, time, and infrastructure to mitigate large-scale traffic disruptions.

2. Business Understanding - Segmented Strategies for Regional Traffic Impacts
The goal of this project is to find the main factors that affect incident severity (Level 1–4) and cause traffic delays. By looking at time, road features, and weather data, we aim to create a better traffic management plan. Instead of using the same rules everywhere, this project helps set up a system that fits the specific needs and traffic patterns of different regions.

[Phase 1] Exploratory Analysis (Sample-based)

3. Data Understanding: Initial Inspection & Sampling  
3.1 Data Loading & Schema Verification Strategy   
3.2 Numerical & Target Distribution  
3.3 Severity-Segmented Analysis  

4. Data Preparation (Sample)  
4.1 Physical Outlier Cleaning  
4.2 DateTime Convert  
4.3 Missing Values  
4.4 Drop Redundant Columns  
4.5 Preview after data preparation  
  
5. Analysis (Sample-based EDA)  
5.1 Hourly Distribution by Severity  
5.2 Road Features (POI)  
5.3 Weather & Environmental Analysis  
5.4 Spatial Analysis (Top 10 States)  
5.5 Integrated Insight Dashboard (Final Summary)  
  
[Phase 2] Full-scale Modeling (Entire Dataset)  
  
6. Large-scale Data Preparation  
6.1 Chunk-based Loading  
6.2 Entire Data Cleaning  
6.3 Temporal Feature Extraction  
6.4 Categorical Encoding  

7. Data Enhancement & Selection  
7.1 Temporal & Infrastructure Severity Analysis  
7.2 Spatial Severity Profile  
7.3 Weather Factor Analysis  
7.4 Regional Weather Comparison (VA, CA, PA)  
7.5 Temperature Sensitivity Analysis by City (PA & VA)  
7.6 Time-Series Analysis: Cold-induced Severity 4 Spikes  
7.7 Heatmap for Top 20 Sensitive Cities  
7.8 Gold-Hour Analysis for Severity 2   
7.9 Severity 3 Environmental Analysis  
7.10 Seasonal Winter (Dec-Feb) Severity 4 Multi-Year Trend  
  
8. Evaluation  
8.1 Overview: Framework for Severity-Based Intervention  
8.2 Recommendation 1: Critical Impact Management (S4: Critical)  
=> Targeting regional S4 incidents reduces the risk of long-term traffic paralysis during winter weather.  
8.3 Recommendation 2: Infrastructure-Driven Mitigation (S3: Major)  
=> Structural improvements can downshift Major (S3) impacts to lower severity levels by reducing physical crash force.  
8.4 Recommendation 3: Operational Efficiency in Urban Hubs (S2: Moderate)  
=> Improving operational speed in S2-dominant cities shortens overall road recovery times.  
8.5 Tableau Dashboard Link  
  
9. Conclusion and Next Steps  
9.1 Project Summary  
This project performed a comprehensive analysis of 7.7 million traffic accident records to establish a data-driven safety management framework. By shifting the focus from simple accident counts to impact-based severity (Severity 1–4), the analysis identified that traffic risks are not uniform across the United States.  
The core finding of this project is the regional divergence of severity profiles. Some states face critical system-wide paralysis (S4) during specific weather events, while others struggle with infrastructure-related serious injuries (S3) or chronic urban congestion (S2). This divergence proves that a one-size-fits-all national policy is inefficient. Instead, safety resources—ranging from federal winter assets to local towing services—must be allocated based on the specific severity dominant in each region.  
By integrating weather triggers, infrastructure types, and geographic concentrations, this study provides a tiered response model (Federal, State, and Local). This approach ensures that interventions are precisely matched to the impact level of the accidents they aim to mitigate.  
9.2 Limitations and Future Work  
[Critical Limitations]  
Road Type Identification: While this study identified high-impact cities and states, it did not distinguish between Interstate Highways and Local Streets.  
Scope of Inference: The increase in S4 incidents suggests a need for better regional management, but without specific route data, a direct causal link to national logistics failure cannot be fully verified.  
[Next Steps]  
Granular Route Analysis: Future research should integrate 'Street' and 'Route' variables to determine if severity surges are concentrated on highways or urban arterials.  
Region-Specific Prototyping: Develop separate response manuals for GA (S3-focused) and Charlotte (S2-focused) to test the effectiveness of tailored interventions.  
System Integration: Connect the identified weather triggers with real-time APIs to transform this retrospective analysis into an active regional warning system.  
