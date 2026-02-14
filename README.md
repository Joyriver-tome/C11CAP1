# Analyzing Traffic Accident Severity in the U.S.

1. Overview 
This project analyzes U.S. traffic accident data to identify factors influencing accident severity. The study focuses on the correlation between road conditions, time, and infrastructure to mitigate large-scale traffic disruptions.
  
2. Business Understanding - Segmented Strategies for Regional Traffic Impacts
The goal of this project is to find the main factors that affect incident severity (Level 1–4) and cause traffic delays. By looking at time, road features, and weather data, we aim to create a better traffic management plan. Instead of using the same rules everywhere, this project helps set up a system that fits the specific needs and traffic patterns of different regions.
  
[Phase 1] Exploratory Analysis (Sample-based)  
  
4. Data Understanding: Initial Inspection & Sampling  
3.1 Data Loading & Schema Verification Strategy  
3.2 Numerical & Target Distribution  
3.3 Severity-Segmented Analysis  
  
5. Data Preparation (Sample)  
4.1 Physical Outlier Cleaning  
4.2 DateTime Convert  
4.3 Missing Values  
4.4 Drop Redundant Columns  
4.5 Preview after data preparation  
  
6. Analysis (Sample-based EDA)  
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
7.11 Strategic Analysis of S4 Hotspots in VA & PA  
  
8. Evaluation    
8.1 Overview: Framework for Severity-Based Intervention  
8.2 Recommendation 1: Operational Efficiency in Urban Hubs (S2: Moderate)  
8.3 Recommendation 2: Infrastructure-Driven Mitigation & Escalation Control (S3: Major)  
8.4 Recommendation 3: Dynamic Risk Management (S4: Critical)   
8.5 Tableau Dashboard Link  
  
9. Conclusion and Next Steps    
9.1 Project Summary  
* This project analyzed 7.7 million accident records to create a data-driven safety management framework. The results show that accidents have different impacts, so our response must be different for each level. Traffic risk is a process where lower severity incidents can lead to higher severity outcomes if they are not managed early.  
* First, each region has different severity profiles. In cities like Charlotte, Severity 2 (S2) incidents are the most common and cause frequent urban delays. In Georgia, Severity 3 (S3) incidents occur at a higher rate due to road features like junctions. In Virginia, Severity 4 (S4) incidents are a major threat because weather conditions can shut down the road network. We must focus on these specific regional data instead of using one general policy.  
* Second, the study found a connection between Severity 3 (S3) and Severity 4 (S4). S3 accidents often act as a tipping point. If an S3 accident is not cleared quickly, the congestion spreads and can turn into an S4 total shutdown. By managing S3 incidents effectively, we can prevent them from becoming S4 disasters.  
* Finally, this study changes how we allocate resources. We now look at Risk Velocity, which shows where S4 risk is growing the fastest. This gives leaders a plan to use patrols for S2 delays, improve infrastructure in S3 areas, and pre-deploy equipment for S4 risks.  
* The goal of this study is to change traffic management. We want to move from a system that reacts to accidents to a system that stops them from spreading.
  
9.2 Limitations and Future Work  
* Critical Limitations  
- Road Type Specificity: The current study does not distinguish between Interstate Highways and Local Streets. Since traffic flow behaves differently on these roads, a more detailed analysis is required.  
- Spatial Analysis (GIS): Statistical tables alone cannot show the exact location of risk. Future work must integrate GIS (Geographic Information Systems) to visualize hotspots and understand how infrastructure density affects accident severity.  
* Next Steps
- Analyze the S3-S4 Link: We will focus on the causal link between Severity 3 (Major) and Severity 4 (Critical). We need to measure how often and how fast an S3 incident turns into a full road closure (S4).
- Speed vs. Structure: By understanding this link, we can decide the best strategy. We will determine if we simply need to increase "Response Speed" (clearing scenes faster) or if we need a "Structural Change" (improving road design and adding detours) to stop risk from escalating.  
- Define the Golden Hour: We plan to identify the "Golden Hour"—the specific time window available to intervene at an S3 stage before the entire regional network reaches a point of no return (S4).


