 

# **Bicycle Theft Analysis in Toronto (2014-2020)**

## **Project Overview**

Bicycle theft is a persistent issue in Toronto, affecting daily life and challenging law enforcement. This project analyzes reported bicycle thefts from 2014 to 2020, offering insights into patterns and potential solutions.

**Project plan**
We aim to determine the predominant factors and key associative rules that contribute to bicycle thefts in Toronto. Additionally, we seek to identify which factors increase the likelihood of bike recovery post-theft. 

**Hypotheses for Analysis**
The following attributes may have a significant impact on both the likelihood of a bicycle being stolen and the chances of its recovery:
Bike Characteristics: Color, cost, and make/model of the bicycle.
Environmental Factors: Location where the bike is parked/locked.
Temporal Factors: Time of the day and day of the week and season of the year when the bike is most frequently parked.

To achieve our objectives, we will leverage the Cross-Industry Standard Process for Data Mining (CRISP-DM) framework. The analysis will be conducted using RapidMiner, a robust tool for data processing and mining.

## **Contents**

1. **Business Understanding**  
   This section explains the problem of bike theft in Toronto and how the analysis can help law enforcement and urban planners address the issue.

2. **Data Understanding**  
   Provides an overview of the dataset used, including key variables and initial observations.

3. **Data Preparation**  
- Attributes Dropped: Removed irrelevant fields like IDs and redundant date details.
- Bike Details: Categorized models, types, and colors into simplified values.
- Report Time Gap: Classified the time between incident and report into categories (e.g., 'same day', 'half day').
- Location Clustering: Used premises type and clustered coordinates into regions.
- Seasonal & Hourly Analysis: Grouped data by seasons and time periods.
- Clustering & Binarization: Applied k-Means clustering and converted nominal data (e.g., Status, Season) to numeric for analysis.

4. **Modeling**  
   - **k-Nearest Neighbors (kNN)**: Used to find patterns and similarities in theft cases.
   - **Outlier Detection**: Identifies unusual or rare theft cases.
   - **Clustering**: Groups similar theft incidents to uncover trends (e.g., high-risk areas).
   - **Classification (Decision Tree)**: Predicts the likelihood of theft in various scenarios.
   - **Association Rule Mining**: Explores relationships between factors like time, location, and bike type.

5. **Discussion of Results**  
Bikes stolen outside during work hours are most likely to be recovered.
Summer and weekday recoveries are common.
Bike model is a key predictor for recovery, while color has little impact.

This report is designed for:
- **Urban Planners**: To create bike-friendly infrastructure with a focus on security.
- **Policy Makers**: To develop effective policies that reduce bike theft.
 
